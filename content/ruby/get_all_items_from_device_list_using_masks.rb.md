---
title: "get_all_items_from_device_list_using_masks.rb"
description: "get_all_items_from_device_list_using_masks.rb"
date: "2017-11-23"
classes: 
    - "SoftLayer_Network_Application_Delivery_Controller"
    - "SoftLayer_Virtual_Guest"
    - "SoftLayer_Search"
    - "SoftLayer_Hardware"
    - "SoftLayer_Network_Vlan_Firewall"
tags:
    - "search"
---


```
# Get all items from Device list using an object mask
#
# Important manual pages:
# see http://sldn.softlayer.com/reference/services/SoftLayer_Search/advancedSearch
#
# license <http://sldn.softlayer.com/article/License>
# author SoftLayer Technologies, Inc. <sldn@softlayer.com>

require 'rubygems'
require 'softlayer_api'

# Your SoftLayer API username.
SL_API_USERNAME = 'set me'

# Your SoftLayer API key.
SL_API_KEY = 'set me'

# Softlayer API public endpoint
API_PUBLIC_ENDPOINT = 'https://api.softlayer.com/xmlrpc/v3.1/'

softlayer_client = SoftLayer::Client.new(username: SL_API_USERNAME,
                                         api_key: SL_API_KEY,
                                         endpoint_url: API_PUBLIC_ENDPOINT)

search_service = softlayer_client.service_named('SoftLayer_Search')

# Create an object mask to get more information than by default
mask = 'mask[resource(SoftLayer_Hardware)'\
    '[ id, fullyQualifiedDomainName,datacenter],'\
    'resource(SoftLayer_Virtual_Guest)'\
    '[ id, fullyQualifiedDomainName,datacenter],'\
    'resource(SoftLayer_Network_Application_Delivery_Controller)'\
    '[ id, name,datacenter.longName],'\
    'resource(SoftLayer_Network_Vlan_Firewall)'\
    '[ id, fullyQualifiedDomainName,datacenter.longName]]'

# The items with the following Device types should be displayed
# using the below filter:
# Bare Metal Server, Virtual Server, Firewall, Gateway Member, Netscaler,KVM/IP
filter_data = '_objectType:SoftLayer_Hardware,'\
    'SoftLayer_Virtual_Guest,SoftLayer_Network_Vlan_Firewall,'\
    'SoftLayer_Network_Application_Delivery_Controller '

begin
  # Display all items with specif properties included in the mask.
  result = search_service.object_mask(mask).advancedSearch(filter_data)
  puts 'Process finished successfully'
  p result
rescue StandardError => e
  raise e
end

```
