---
title: "SoftLayer_Network_Subnet"
description: "Every SoftLayer ip address is associated with a subnet which is defined in the SoftLayer_Network_Subnet service. SoftLay... "
date: "2018-02-12"
layout: "service"
tags:
    - "service"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Subnet"
---
# SoftLayer_Network_Subnet
<div id='service-datatype'>
    <ul id='sldn-reference-tabs'>
    <li id='service'> <a href='/reference/services/SoftLayer_Network_Subnet' >Service</a></li>    <li id='datatype'> <a href='/reference/datatypes/SoftLayer_Network_Subnet' >Datatype</a></li>
    </ul>
</div>

## Description
Every SoftLayer ip address is associated with a subnet which is defined in the SoftLayer_Network_Subnet service. SoftLayer subnets define a group of ip addresses and are assigned to a SoftLayer_Network_Vlan.  The SoftLayer_Network_Subnet service gives you information about your subnet such as your network address, broadcast address, the subnet gateway address, and the total number of IP addresses within the subnet. Use the data returned by these methods with other API services to get more detailed information about your services. 

Along with VLANs, subnets are an integral part of the SoftLayer network. Each server ordered by SoftLayer comes with at least one public and one private subnet, with more available for order in the customer portal. Subnets exist in the SoftLayer network as either interfaces on a VLAN or as route destination from an IP address or VLAN. 

SoftLayer customers can order and manage subnets through the customer portal. If you need to cancel a subnet please open a sales ticket in our customer portal and our account management staff will assist you. 

### External Links


* [Subnetwork at Wikipedia](http://en.wikipedia.org/wiki/Subnetwork)


* [RFC950:Internet Standard Subnetting Procedure at ietf.org](http://tools.ietf.org/html/rfc950)




### seeAlso

* [SoftLayer_Network_Vlan](/reference/services/SoftLayer_Network_Vlan )


* [SoftLayer_Network_IpAddress](/reference/datatypes/SoftLayer_Network_IpAddress )


        
<div id="properties" class="content">
    <h2>Methods</h2>
    <div class="view-filters">
        <div class="clearfix">
            <div class="search-input-box">
                <input placeholder="Datatype Filter" onkeyup="titleSearch(inputId='edit-combine', divId='method-div', elementClass='method-row')" 
                    type="text" id="edit-combine" value="" size="30" maxlength="128" class="form-text">
            </div>
        </div>
    </div>
    <div id="method-div">
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/allowAccessToNetworkStorage'> allowAccessToNetworkStorage</a> </span>
            <div class='views-field-body'>Allow access to a SoftLayer_Network_Storage volume from this device. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/allowAccessToNetworkStorageList'> allowAccessToNetworkStorageList</a> </span>
            <div class='views-field-body'>Allow access to multiple SoftLayer_Network_Storage volumes from this device. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/createReverseDomainRecords'> createReverseDomainRecords</a> </span>
            <div class='views-field-body'>Create the default PTR records for this subnet</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/createSubnetRouteUpdateTransaction'> createSubnetRouteUpdateTransaction</a> </span>
            <div class='views-field-body'>create a new transaction to modify a subnet route.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/createSwipTransaction'> createSwipTransaction</a> </span>
            <div class='views-field-body'>create a SWIP transaction for a subnet</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/editNote'> editNote</a> </span>
            <div class='views-field-body'>Edit the note for this subnet.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/findAllSubnetsAndActiveSwipTransactionStatus'> findAllSubnetsAndActiveSwipTransactionStatus</a> </span>
            <div class='views-field-body'>Retrieve a list of subnets along with their SWIP transaction statuses.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getAccount'> getAccount</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getActiveRegistration'> getActiveRegistration</a> </span>
            <div class='views-field-body'>Retrieve if present, the active registration for this subnet.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getActiveSwipTransaction'> getActiveSwipTransaction</a> </span>
            <div class='views-field-body'>Retrieve all the swip transactions associated with a subnet that are still active.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getActiveTransaction'> getActiveTransaction</a> </span>
            <div class='views-field-body'>Retrieve the billing item for a subnet.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getAddressSpace'> getAddressSpace</a> </span>
            <div class='views-field-body'>Retrieve identifier which distinguishes what classification of addresses the subnet represents.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getAllowedHost'> getAllowedHost</a> </span>
            <div class='views-field-body'>Retrieve the SoftLayer_Network_Storage_Allowed_Host information to connect this Subnet to Network Storage supporting access control lists.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getAllowedNetworkStorage'> getAllowedNetworkStorage</a> </span>
            <div class='views-field-body'>Retrieve the SoftLayer_Network_Storage objects that this SoftLayer_Hardware has access to.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getAllowedNetworkStorageReplicas'> getAllowedNetworkStorageReplicas</a> </span>
            <div class='views-field-body'>Retrieve the SoftLayer_Network_Storage objects whose Replica that this SoftLayer_Hardware has access to.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getAttachedNetworkStorages'> getAttachedNetworkStorages</a> </span>
            <div class='views-field-body'>Return a list of SoftLayer_Network_Storage volumes authorized to this device. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getAvailableNetworkStorages'> getAvailableNetworkStorages</a> </span>
            <div class='views-field-body'>Return a list of SoftLayer_Network_Storage volumes that can be authorized to this device. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getBillingItem'> getBillingItem</a> </span>
            <div class='views-field-body'>Retrieve the billing item for a subnet.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getBoundDescendants'> getBoundDescendants</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getBoundRouterFlag'> getBoundRouterFlag</a> </span>
            <div class='views-field-body'>Retrieve whether or not this subnet is associated with a router. Subnets that are not associated with a router cannot be routed.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getBoundRouters'> getBoundRouters</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getChildren'> getChildren</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getDatacenter'> getDatacenter</a> </span>
            <div class='views-field-body'>Retrieve the data center this subnet may be routed within.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getDescendants'> getDescendants</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getDisplayLabel'> getDisplayLabel</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getEndPointIpAddress'> getEndPointIpAddress</a> </span>
            <div class='views-field-body'>Retrieve a static routed ip address</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getGlobalIpRecord'> getGlobalIpRecord</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getHardware'> getHardware</a> </span>
            <div class='views-field-body'>Retrieve the hardware using IP addresses on this subnet.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getIpAddresses'> getIpAddresses</a> </span>
            <div class='views-field-body'>Retrieve all the ip addresses associated with a subnet.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getNetworkComponentFirewall'> getNetworkComponentFirewall</a> </span>
            <div class='views-field-body'>Retrieve the upstream network component firewall.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getNetworkProtectionAddresses'> getNetworkProtectionAddresses</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getNetworkTunnelContexts'> getNetworkTunnelContexts</a> </span>
            <div class='views-field-body'>Retrieve iPSec network tunnels that have access to a private subnet.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getNetworkVlan'> getNetworkVlan</a> </span>
            <div class='views-field-body'>Retrieve the VLAN object that a subnet is associated with.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getObject'> getObject</a> </span>
            <div class='views-field-body'>Retrieve a SoftLayer_Network_Subnet record.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getPodName'> getPodName</a> </span>
            <div class='views-field-body'>Retrieve the pod in which this subnet resides.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getProtectedIpAddresses'> getProtectedIpAddresses</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getRegionalInternetRegistry'> getRegionalInternetRegistry</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getRegistrations'> getRegistrations</a> </span>
            <div class='views-field-body'>Retrieve all registrations that have been created for this subnet.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getReverseDomain'> getReverseDomain</a> </span>
            <div class='views-field-body'>Retrieve the reverse DNS domain associated with this subnet.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getReverseDomainRecords'> getReverseDomainRecords</a> </span>
            <div class='views-field-body'>Retrieve all reverse DNS records associated with a subnet.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getRoleKeyName'> getRoleKeyName</a> </span>
            <div class='views-field-body'>Retrieve an identifier of the role the subnet is within. Roles dictate how a subnet may be used.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getRoleName'> getRoleName</a> </span>
            <div class='views-field-body'>Retrieve the name of the role the subnet is within. Roles dictate how a subnet may be used.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getRoutableEndpointIpAddresses'> getRoutableEndpointIpAddresses</a> </span>
            <div class='views-field-body'>Retrieve valid routable endpoint addresses for a subnet.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getRoutingTypeKeyName'> getRoutingTypeKeyName</a> </span>
            <div class='views-field-body'>Retrieve the identifier for the type of route then subnet is currently configured for.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getRoutingTypeName'> getRoutingTypeName</a> </span>
            <div class='views-field-body'>Retrieve the name for the type of route then subnet is currently configured for.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getSubnetForIpAddress'> getSubnetForIpAddress</a> </span>
            <div class='views-field-body'>Retrieve an IP addresses's associated subnet.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getSwipTransaction'> getSwipTransaction</a> </span>
            <div class='views-field-body'>Retrieve all the swip transactions associated with a subnet.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getUnboundDescendants'> getUnboundDescendants</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getUtilizedIpAddressCount'> getUtilizedIpAddressCount</a> </span>
            <div class='views-field-body'>Retrieve provides the total number of utilized IP addresses on this subnet. The primary consumer of IP addresses are compute resources, which can consume more than one address. This value is only supported for primary subnet types.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/getVirtualGuests'> getVirtualGuests</a> </span>
            <div class='views-field-body'>Retrieve the Virtual Servers using IP addresses on this subnet.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Network_Subnet/removeAccessToNetworkStorageList'> removeAccessToNetworkStorageList</a> </span>
            <div class='views-field-body'>Remove access to multiple SoftLayer_Network_Storage volumes from this device. </div>
        </div>
        </div>
</div>

