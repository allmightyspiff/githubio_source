---
title: "SoftLayer_Network_Subnet"
description: "The SoftLayer_Network_Subnet data type contains general information relating to a single SoftLayer subnet. Personal info... "
layout: "datatype"
tags:
    - "datatype"
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
The SoftLayer_Network_Subnet data type contains general information relating to a single SoftLayer subnet. Personal information in this type such as names, addresses, and phone numbers are assigned to the account only and not to users belonging to the account. 

### External Links


* [Subnetwork at Wikipedia](http://en.wikipedia.org/wiki/Subnetwork)


* [RFC950:Internet Standard Subnetting Procedure at ietf.org](http://tools.ietf.org/html/rfc950)


* [Classless Inter-Domain Routing at Wikipedia](http://en.wikipedia.org/wiki/Classless_Inter-Domain_Routing)



### associatedMethods

*  [SoftLayer_Network_Subnet::findAllSubnetsAndActiveSwipTransactionStatus](/reference/services/SoftLayer_Network_Subnet/findAllSubnetsAndActiveSwipTransactionStatus )
*  [SoftLayer_Network_Subnet::getObject](/reference/services/SoftLayer_Network_Subnet/getObject )
*  [SoftLayer_Network_Subnet::getSubnetForIpAddress](/reference/services/SoftLayer_Network_Subnet/getSubnetForIpAddress )
*  [SoftLayer_Network_Subnet_Swip_Transaction::getSubnet](/reference/services/SoftLayer_Network_Subnet_Swip_Transaction/getSubnet )
*  [SoftLayer_Network_Vlan::getSubnets](/reference/services/SoftLayer_Network_Vlan/getSubnets )
*  [SoftLayer_Network_Vlan::getSecondarySubnets](/reference/services/SoftLayer_Network_Vlan/getSecondarySubnets )





<!-- Service Filer BEGIN -->
<div class="view-filters">
        <div class="clearfix">
            <div class="search-input-box">
                <input placeholder="Method Filter" onkeyup="titleSearch(inputId='prop-input', divId='properties', elementClass='prop-row')" 
                    type="text" id="prop-input" value="" size="30" maxlength="128" class="form-text">
            </div>
        </div>
</div>
<!-- Service Filer END -->

<div id="properties" class="content">
    <div id="localProperties" class="prop-content" >
        <h2>Local</h2>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#broadcastAddress" name=broadcastAddress>broadcastAddress</a>
            </span>
            <div class='views-field-body'>The last IP address in a subnet is the subnet's broadcast address. This is an IP address that will broadcast network requests to the entire subnet and may not be assigned to a network interface.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#cidr" name=cidr>cidr</a>
            </span>
            <div class='views-field-body'>A subnet's Classless Inter-Domain Routing prefix. This is a number between 0 and 32 signifying the number of bits in a subnet's netmask. These bits separate a subnet's network address from it's host addresses. It performs the same function as the ''netmask'' property, but is represented as an integer.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#gateway" name=gateway>gateway</a>
            </span>
            <div class='views-field-body'>A subnet's gateway address. This is an IP address that belongs to the router on the subnet and may not be assigned to a network interface.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#id" name=id>id</a>
            </span>
            <div class='views-field-body'>A subnet's internal identifier. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#isCustomerOwned" name=isCustomerOwned>isCustomerOwned</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#isCustomerRoutable" name=isCustomerRoutable>isCustomerRoutable</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#modifyDate" name=modifyDate>modifyDate</a>
            </span>
            <div class='views-field-body'>The last time this subnet was last modified </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>dateTime</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#netmask" name=netmask>netmask</a>
            </span>
            <div class='views-field-body'>A bitmask in dotted-quad format that is used to separate a subnet's network address from it's host addresses. This performs the same function as the ''cidr'' property, but is expressed in a string format.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkIdentifier" name=networkIdentifier>networkIdentifier</a>
            </span>
            <div class='views-field-body'>A subnet's network identifier. This is the first IP address of a subnet and may not be assigned to a network interface.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkVlanId" name=networkVlanId>networkVlanId</a>
            </span>
            <div class='views-field-body'>A subnet's associated VLAN's internal identifier. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#note" name=note>note</a>
            </span>
            <div class='views-field-body'>This is the note field.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#sortOrder" name=sortOrder>sortOrder</a>
            </span>
            <div class='views-field-body'>A subnet can be one of several types. PRIMARY, ADDITIONAL_PRIMARY, SECONDARY, ROUTED_TO_VLAN, SECONDARY_ON_VLAN, and STATIC_IP_ROUTED. The type determines the order in which many subnets are sorted in the SoftLayer customer portal. This groups subnets of similar type together.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#subnetType" name=subnetType>subnetType</a>
            </span>
            <div class='views-field-body'>A subnet can be one of several types. PRIMARY, ADDITIONAL_PRIMARY, SECONDARY, ROUTED_TO_VLAN, SECONDARY_ON_VLAN, STORAGE_NETWORK, and STATIC_IP_ROUTED. A "PRIMARY" subnet is the primary network bound to a VLAN within the softlayer network. An "ADDITIONAL_PRIMARY" subnet is bound to a network VLAN to augment the pool of available primary IP addresses that may be assigned to a server. A "SECONDARY" subnet is any of the secondary subnet's bound to a VLAN interface. A "ROUTED_TO_VLAN" subnet is a portable subnet that can be routed to any server on a vlan. A "SECONDARY_ON_VLAN" subnet also doesn't exist as a VLAN interface, but is routed directly to a VLAN instead of a single IP address by SoftLayer's routers.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#totalIpAddresses" name=totalIpAddresses>totalIpAddresses</a>
            </span>
            <div class='views-field-body'>The number of IP addresses contained within this subnet. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#usableIpAddressCount" name=usableIpAddressCount>usableIpAddressCount</a>
            </span>
            <div class='views-field-body'>The number of IP addresses that can be addressed within this subnet. For IPv4 subnets with a CIDR value of at most 30, a discount of 3 is taken from the total number of IP addresses for the subnet's unusable network, gateway and broadcast IP addresses. For IPv6 subnets with a CIDR value of at most 126, a discount of 2 is taken for the subnet's network and gateway IP addresses.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#version" name=version>version</a>
            </span>
            <div class='views-field-body'>This is the Internet Protocol version. Current values may be either 4 or 6.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
            </div>
        <div id="relationalProperties"  class="prop-content" >
        <h2>Relational</h2>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#account" name=account>account</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account'>SoftLayer_Account </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeRegistration" name=activeRegistration>activeRegistration</a>
            </span>
            <div class='views-field-body'>If present, the active registration for this subnet. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet_Registration'>SoftLayer_Network_Subnet_Registration </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeSwipTransaction" name=activeSwipTransaction>activeSwipTransaction</a>
            </span>
            <div class='views-field-body'>All the swip transactions associated with a subnet that are still active. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet_Swip_Transaction'>SoftLayer_Network_Subnet_Swip_Transaction </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeTransaction" name=activeTransaction>activeTransaction</a>
            </span>
            <div class='views-field-body'>The billing item for a subnet. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Provisioning_Version1_Transaction'>SoftLayer_Provisioning_Version1_Transaction </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#addressSpace" name=addressSpace>addressSpace</a>
            </span>
            <div class='views-field-body'>Identifier which distinguishes what classification of addresses the subnet represents. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedHost" name=allowedHost>allowedHost</a>
            </span>
            <div class='views-field-body'>The SoftLayer_Network_Storage_Allowed_Host information to connect this Subnet to Network Storage supporting access control lists. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage_Allowed_Host'>SoftLayer_Network_Storage_Allowed_Host </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedNetworkStorage" name=allowedNetworkStorage>allowedNetworkStorage</a>
            </span>
            <div class='views-field-body'>The SoftLayer_Network_Storage objects that this SoftLayer_Hardware has access to. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedNetworkStorageReplicas" name=allowedNetworkStorageReplicas>allowedNetworkStorageReplicas</a>
            </span>
            <div class='views-field-body'>The SoftLayer_Network_Storage objects whose Replica that this SoftLayer_Hardware has access to. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#billingItem" name=billingItem>billingItem</a>
            </span>
            <div class='views-field-body'>The billing item for a subnet. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item'>SoftLayer_Billing_Item </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#boundDescendants" name=boundDescendants>boundDescendants</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet'>SoftLayer_Network_Subnet[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#boundRouterFlag" name=boundRouterFlag>boundRouterFlag</a>
            </span>
            <div class='views-field-body'>Whether or not this subnet is associated with a router. Subnets that are not associated with a router cannot be routed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#boundRouters" name=boundRouters>boundRouters</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#children" name=children>children</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet'>SoftLayer_Network_Subnet[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#datacenter" name=datacenter>datacenter</a>
            </span>
            <div class='views-field-body'>The data center this subnet may be routed within. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Location_Datacenter'>SoftLayer_Location_Datacenter </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#descendants" name=descendants>descendants</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet'>SoftLayer_Network_Subnet[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#displayLabel" name=displayLabel>displayLabel</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#endPointIpAddress" name=endPointIpAddress>endPointIpAddress</a>
            </span>
            <div class='views-field-body'>A static routed ip address </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet_IpAddress'>SoftLayer_Network_Subnet_IpAddress </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#globalIpRecord" name=globalIpRecord>globalIpRecord</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet_IpAddress_Global'>SoftLayer_Network_Subnet_IpAddress_Global </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardware" name=hardware>hardware</a>
            </span>
            <div class='views-field-body'>The hardware using IP addresses on this subnet. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#ipAddresses" name=ipAddresses>ipAddresses</a>
            </span>
            <div class='views-field-body'>All the ip addresses associated with a subnet. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet_IpAddress'>SoftLayer_Network_Subnet_IpAddress[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkComponentFirewall" name=networkComponentFirewall>networkComponentFirewall</a>
            </span>
            <div class='views-field-body'>The upstream network component firewall. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Component_Firewall'>SoftLayer_Network_Component_Firewall </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkProtectionAddresses" name=networkProtectionAddresses>networkProtectionAddresses</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Protection_Address'>SoftLayer_Network_Protection_Address[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkTunnelContexts" name=networkTunnelContexts>networkTunnelContexts</a>
            </span>
            <div class='views-field-body'>IPSec network tunnels that have access to a private subnet. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Tunnel_Module_Context'>SoftLayer_Network_Tunnel_Module_Context[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkVlan" name=networkVlan>networkVlan</a>
            </span>
            <div class='views-field-body'>The VLAN object that a subnet is associated with. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Vlan'>SoftLayer_Network_Vlan </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#podName" name=podName>podName</a>
            </span>
            <div class='views-field-body'>The pod in which this subnet resides. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#protectedIpAddresses" name=protectedIpAddresses>protectedIpAddresses</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet_IpAddress'>SoftLayer_Network_Subnet_IpAddress[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#regionalInternetRegistry" name=regionalInternetRegistry>regionalInternetRegistry</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Regional_Internet_Registry'>SoftLayer_Network_Regional_Internet_Registry </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#registrations" name=registrations>registrations</a>
            </span>
            <div class='views-field-body'>All registrations that have been created for this subnet. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet_Registration'>SoftLayer_Network_Subnet_Registration[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#reverseDomain" name=reverseDomain>reverseDomain</a>
            </span>
            <div class='views-field-body'>The reverse DNS domain associated with this subnet. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Dns_Domain'>SoftLayer_Dns_Domain </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#roleKeyName" name=roleKeyName>roleKeyName</a>
            </span>
            <div class='views-field-body'>An identifier of the role the subnet is within. Roles dictate how a subnet may be used. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#roleName" name=roleName>roleName</a>
            </span>
            <div class='views-field-body'>The name of the role the subnet is within. Roles dictate how a subnet may be used. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#routingTypeKeyName" name=routingTypeKeyName>routingTypeKeyName</a>
            </span>
            <div class='views-field-body'>The identifier for the type of route then subnet is currently configured for. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#routingTypeName" name=routingTypeName>routingTypeName</a>
            </span>
            <div class='views-field-body'>The name for the type of route then subnet is currently configured for. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#swipTransaction" name=swipTransaction>swipTransaction</a>
            </span>
            <div class='views-field-body'>All the swip transactions associated with a subnet. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet_Swip_Transaction'>SoftLayer_Network_Subnet_Swip_Transaction[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#unboundDescendants" name=unboundDescendants>unboundDescendants</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet'>SoftLayer_Network_Subnet[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#utilizedIpAddressCount" name=utilizedIpAddressCount>utilizedIpAddressCount</a>
            </span>
            <div class='views-field-body'>Provides the total number of utilized IP addresses on this subnet. The primary consumer of IP addresses are compute resources, which can consume more than one address. This value is only supported for primary subnet types. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsigned integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuests" name=virtualGuests>virtualGuests</a>
            </span>
            <div class='views-field-body'>The Virtual Servers using IP addresses on this subnet. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <h2>Count</h2>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedNetworkStorageCount" name=allowedNetworkStorageCount>allowedNetworkStorageCount</a>
            </span>
            <div class='views-field-body'>A count of the SoftLayer_Network_Storage objects that this SoftLayer_Hardware has access to. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedNetworkStorageReplicaCount" name=allowedNetworkStorageReplicaCount>allowedNetworkStorageReplicaCount</a>
            </span>
            <div class='views-field-body'>A count of the SoftLayer_Network_Storage objects whose Replica that this SoftLayer_Hardware has access to. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#boundDescendantCount" name=boundDescendantCount>boundDescendantCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#boundRouterCount" name=boundRouterCount>boundRouterCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#childrenCount" name=childrenCount>childrenCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#descendantCount" name=descendantCount>descendantCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareCount" name=hardwareCount>hardwareCount</a>
            </span>
            <div class='views-field-body'>A count of the hardware using IP addresses on this subnet. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#ipAddressCount" name=ipAddressCount>ipAddressCount</a>
            </span>
            <div class='views-field-body'>A count of all the ip addresses associated with a subnet. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkProtectionAddressCount" name=networkProtectionAddressCount>networkProtectionAddressCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkTunnelContextCount" name=networkTunnelContextCount>networkTunnelContextCount</a>
            </span>
            <div class='views-field-body'>A count of iPSec network tunnels that have access to a private subnet. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#protectedIpAddressCount" name=protectedIpAddressCount>protectedIpAddressCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#registrationCount" name=registrationCount>registrationCount</a>
            </span>
            <div class='views-field-body'>A count of all registrations that have been created for this subnet. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#swipTransactionCount" name=swipTransactionCount>swipTransactionCount</a>
            </span>
            <div class='views-field-body'>A count of all the swip transactions associated with a subnet. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#unboundDescendantCount" name=unboundDescendantCount>unboundDescendantCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestCount" name=virtualGuestCount>virtualGuestCount</a>
            </span>
            <div class='views-field-body'>A count of the Virtual Servers using IP addresses on this subnet. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
            </div>
</div>


