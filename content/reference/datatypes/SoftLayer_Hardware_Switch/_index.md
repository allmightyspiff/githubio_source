---
title: "SoftLayer_Hardware_Switch"
description: "The SoftLayer_Hardware_Switch object extends the base functionality of the SoftLayer_Hardware service."
layout: "datatype"
tags:
    - "datatype"
    - "sldn"
    - "Hardware"
classes:
    - "SoftLayer_Hardware_Switch"
---

# SoftLayer_Hardware_Switch
<div id='service-datatype'>
    <ul id='sldn-reference-tabs'>
        <li id='datatype'> <a href='/reference/datatypes/SoftLayer_Hardware_Switch' >Datatype</a></li>
    </ul>
</div>

## Description 
The SoftLayer_Hardware_Switch object extends the base functionality of the SoftLayer_Hardware service. 

### External Links


* [Network switch at Wikipedia](http://en.wikipedia.org/wiki/Network_switch)






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
                <a href="#accountId" name=accountId>accountId</a>
            </span>
            <div class='views-field-body'>A hardware's associated [[SoftLayer_Account|account]] id. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#bareMetalInstanceFlag" name=bareMetalInstanceFlag>bareMetalInstanceFlag</a>
            </span>
            <div class='views-field-body'>When true, this flag specifies that a hardware is Bare Metal Server. Bare Metal Servers are physical bare metal servers that are billed with the same options as Virtual Servers, with monthly and hourly rates.  Bare Metal instances are ordered based on processor core count and ram amount.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#domain" name=domain>domain</a>
            </span>
            <div class='views-field-body'>A piece of hardware's local network domain name. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#fullyQualifiedDomainName" name=fullyQualifiedDomainName>fullyQualifiedDomainName</a>
            </span>
            <div class='views-field-body'>A name reflecting the hostname and domain of the hardware. This is created from the combined values of the hardware's hostname and domain name automatically, and thus should not be edited directly.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareStatusId" name=hardwareStatusId>hardwareStatusId</a>
            </span>
            <div class='views-field-body'>A number reflecting the state of a hardware </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hostname" name=hostname>hostname</a>
            </span>
            <div class='views-field-body'>A hardware's hostname </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#id" name=id>id</a>
            </span>
            <div class='views-field-body'>A hardware's internal identification number </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#manufacturerSerialNumber" name=manufacturerSerialNumber>manufacturerSerialNumber</a>
            </span>
            <div class='views-field-body'>A hardware's serial number that is supplied by the manufacturer. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#notes" name=notes>notes</a>
            </span>
            <div class='views-field-body'>A small note about a piece of hardware to use at your discretion. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#postInstallScriptUri" name=postInstallScriptUri>postInstallScriptUri</a>
            </span>
            <div class='views-field-body'>URI of the script to be downloaded and executed after installation is complete. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#provisionDate" name=provisionDate>provisionDate</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>dateTime</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#serialNumber" name=serialNumber>serialNumber</a>
            </span>
            <div class='views-field-body'>A hardware's serial number that is supplied by SoftLayer. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#serviceProviderId" name=serviceProviderId>serviceProviderId</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#serviceProviderResourceId" name=serviceProviderResourceId>serviceProviderResourceId</a>
            </span>
            <div class='views-field-body'>A hardware's internal identification number at its service provider </div>
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
            <div class='views-field-body'>The account associated with a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account'>SoftLayer_Account </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeComponents" name=activeComponents>activeComponents</a>
            </span>
            <div class='views-field-body'>A piece of hardware's active physical components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Component'>SoftLayer_Hardware_Component[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeNetworkMonitorIncident" name=activeNetworkMonitorIncident>activeNetworkMonitorIncident</a>
            </span>
            <div class='views-field-body'>A piece of hardware's active network monitoring incidents. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Monitor_Version1_Incident'>SoftLayer_Network_Monitor_Version1_Incident[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allPowerComponents" name=allPowerComponents>allPowerComponents</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Power_Component'>SoftLayer_Hardware_Power_Component[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedHost" name=allowedHost>allowedHost</a>
            </span>
            <div class='views-field-body'>The SoftLayer_Network_Storage_Allowed_Host information to connect this server to Network Storage volumes that require access control lists. </div>
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
                <a href="#antivirusSpywareSoftwareComponent" name=antivirusSpywareSoftwareComponent>antivirusSpywareSoftwareComponent</a>
            </span>
            <div class='views-field-body'>Information regarding an antivirus/spyware software component object. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Software_Component'>SoftLayer_Software_Component </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#attributes" name=attributes>attributes</a>
            </span>
            <div class='views-field-body'>Information regarding a piece of hardware's specific attributes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Attribute'>SoftLayer_Hardware_Attribute[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#averageDailyPublicBandwidthUsage" name=averageDailyPublicBandwidthUsage>averageDailyPublicBandwidthUsage</a>
            </span>
            <div class='views-field-body'>The average daily public bandwidth usage for the current billing cycle. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>float</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#backendNetworkComponents" name=backendNetworkComponents>backendNetworkComponents</a>
            </span>
            <div class='views-field-body'>A piece of hardware's back-end or private network components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Component'>SoftLayer_Network_Component[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#backendRouters" name=backendRouters>backendRouters</a>
            </span>
            <div class='views-field-body'>A hardware's backend or private router. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#bandwidthAllocation" name=bandwidthAllocation>bandwidthAllocation</a>
            </span>
            <div class='views-field-body'>A hardware's allotted bandwidth (measured in GB). </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#bandwidthAllotmentDetail" name=bandwidthAllotmentDetail>bandwidthAllotmentDetail</a>
            </span>
            <div class='views-field-body'>A hardware's allotted detail record. Allotment details link bandwidth allocation with allotments. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Bandwidth_Version1_Allotment_Detail'>SoftLayer_Network_Bandwidth_Version1_Allotment_Detail </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#benchmarkCertifications" name=benchmarkCertifications>benchmarkCertifications</a>
            </span>
            <div class='views-field-body'>Information regarding a piece of hardware's benchmark certifications. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Benchmark_Certification'>SoftLayer_Hardware_Benchmark_Certification[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#billingItem" name=billingItem>billingItem</a>
            </span>
            <div class='views-field-body'>Information regarding the billing item for a server. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item_Hardware'>SoftLayer_Billing_Item_Hardware </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#billingItemFlag" name=billingItemFlag>billingItemFlag</a>
            </span>
            <div class='views-field-body'>A flag indicating that a billing item exists. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#blockCancelBecauseDisconnectedFlag" name=blockCancelBecauseDisconnectedFlag>blockCancelBecauseDisconnectedFlag</a>
            </span>
            <div class='views-field-body'>Determines whether the hardware is ineligible for cancellation because it is disconnected. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#businessContinuanceInsuranceFlag" name=businessContinuanceInsuranceFlag>businessContinuanceInsuranceFlag</a>
            </span>
            <div class='views-field-body'>Status indicating whether or not a piece of hardware has business continuance insurance. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#childrenHardware" name=childrenHardware>childrenHardware</a>
            </span>
            <div class='views-field-body'>Child hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#components" name=components>components</a>
            </span>
            <div class='views-field-body'>A piece of hardware's components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Component'>SoftLayer_Hardware_Component[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#continuousDataProtectionSoftwareComponent" name=continuousDataProtectionSoftwareComponent>continuousDataProtectionSoftwareComponent</a>
            </span>
            <div class='views-field-body'>A continuous data protection/server backup software component object. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Software_Component'>SoftLayer_Software_Component </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#currentBillableBandwidthUsage" name=currentBillableBandwidthUsage>currentBillableBandwidthUsage</a>
            </span>
            <div class='views-field-body'>The current billable public outbound bandwidth for this hardware for the current billing cycle. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#datacenter" name=datacenter>datacenter</a>
            </span>
            <div class='views-field-body'>Information regarding the datacenter in which a piece of hardware resides. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Location'>SoftLayer_Location </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#datacenterName" name=datacenterName>datacenterName</a>
            </span>
            <div class='views-field-body'>The name of the datacenter in which a piece of hardware resides. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#daysInSparePool" name=daysInSparePool>daysInSparePool</a>
            </span>
            <div class='views-field-body'>Number of day(s) a server have been in spare pool. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#downlinkHardware" name=downlinkHardware>downlinkHardware</a>
            </span>
            <div class='views-field-body'>All hardware that has uplink network connections to a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#downlinkNetworkHardware" name=downlinkNetworkHardware>downlinkNetworkHardware</a>
            </span>
            <div class='views-field-body'>All hardware that has uplink network connections to a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#downlinkServers" name=downlinkServers>downlinkServers</a>
            </span>
            <div class='views-field-body'>Information regarding all servers attached to a piece of network hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#downlinkVirtualGuests" name=downlinkVirtualGuests>downlinkVirtualGuests</a>
            </span>
            <div class='views-field-body'>Information regarding all virtual guests attached to a piece of network hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#downstreamHardwareBindings" name=downstreamHardwareBindings>downstreamHardwareBindings</a>
            </span>
            <div class='views-field-body'>All hardware downstream from a network device. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Component_Uplink_Hardware'>SoftLayer_Network_Component_Uplink_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#downstreamNetworkHardware" name=downstreamNetworkHardware>downstreamNetworkHardware</a>
            </span>
            <div class='views-field-body'>All network hardware downstream from the selected piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#downstreamNetworkHardwareWithIncidents" name=downstreamNetworkHardwareWithIncidents>downstreamNetworkHardwareWithIncidents</a>
            </span>
            <div class='views-field-body'>All network hardware with monitoring warnings or errors that are downstream from the selected piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#downstreamServers" name=downstreamServers>downstreamServers</a>
            </span>
            <div class='views-field-body'>Information regarding all servers attached downstream to a piece of network hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#downstreamVirtualGuests" name=downstreamVirtualGuests>downstreamVirtualGuests</a>
            </span>
            <div class='views-field-body'>Information regarding all virtual guests attached to a piece of network hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#driveControllers" name=driveControllers>driveControllers</a>
            </span>
            <div class='views-field-body'>The drive controllers contained within a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Component'>SoftLayer_Hardware_Component[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#evaultNetworkStorage" name=evaultNetworkStorage>evaultNetworkStorage</a>
            </span>
            <div class='views-field-body'>Information regarding a piece of hardware's associated EVault network storage service account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#firewallServiceComponent" name=firewallServiceComponent>firewallServiceComponent</a>
            </span>
            <div class='views-field-body'>Information regarding a piece of hardware's firewall services. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Component_Firewall'>SoftLayer_Network_Component_Firewall </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#fixedConfigurationPreset" name=fixedConfigurationPreset>fixedConfigurationPreset</a>
            </span>
            <div class='views-field-body'>Defines the fixed components in a fixed configuration bare metal server. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Product_Package_Preset'>SoftLayer_Product_Package_Preset </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#frontendNetworkComponents" name=frontendNetworkComponents>frontendNetworkComponents</a>
            </span>
            <div class='views-field-body'>A piece of hardware's front-end or public network components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Component'>SoftLayer_Network_Component[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#frontendRouters" name=frontendRouters>frontendRouters</a>
            </span>
            <div class='views-field-body'>A hardware's frontend or public router. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#globalIdentifier" name=globalIdentifier>globalIdentifier</a>
            </span>
            <div class='views-field-body'>A hardware's universally unique identifier. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardDrives" name=hardDrives>hardDrives</a>
            </span>
            <div class='views-field-body'>The hard drives contained within a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Component'>SoftLayer_Hardware_Component[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareChassis" name=hardwareChassis>hardwareChassis</a>
            </span>
            <div class='views-field-body'>The chassis that a piece of hardware is housed in. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Chassis'>SoftLayer_Hardware_Chassis </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareFunction" name=hardwareFunction>hardwareFunction</a>
            </span>
            <div class='views-field-body'>A hardware's function. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Function'>SoftLayer_Hardware_Function </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareFunctionDescription" name=hardwareFunctionDescription>hardwareFunctionDescription</a>
            </span>
            <div class='views-field-body'>A hardware's function. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareStatus" name=hardwareStatus>hardwareStatus</a>
            </span>
            <div class='views-field-body'>A hardware's status. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Status'>SoftLayer_Hardware_Status </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hasTrustedPlatformModuleBillingItemFlag" name=hasTrustedPlatformModuleBillingItemFlag>hasTrustedPlatformModuleBillingItemFlag</a>
            </span>
            <div class='views-field-body'>Determine in hardware object has TPM enabled. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hostIpsSoftwareComponent" name=hostIpsSoftwareComponent>hostIpsSoftwareComponent</a>
            </span>
            <div class='views-field-body'>Information regarding a host IPS software component object. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Software_Component'>SoftLayer_Software_Component </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hourlyBillingFlag" name=hourlyBillingFlag>hourlyBillingFlag</a>
            </span>
            <div class='views-field-body'>A server's hourly billing status. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#inboundBandwidthUsage" name=inboundBandwidthUsage>inboundBandwidthUsage</a>
            </span>
            <div class='views-field-body'>The sum of all the inbound network traffic data for the last 30 days. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#inboundPublicBandwidthUsage" name=inboundPublicBandwidthUsage>inboundPublicBandwidthUsage</a>
            </span>
            <div class='views-field-body'>The total public inbound bandwidth for this hardware for the current billing cycle. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lastTransaction" name=lastTransaction>lastTransaction</a>
            </span>
            <div class='views-field-body'>Information regarding the last transaction a server performed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Provisioning_Version1_Transaction'>SoftLayer_Provisioning_Version1_Transaction </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#latestNetworkMonitorIncident" name=latestNetworkMonitorIncident>latestNetworkMonitorIncident</a>
            </span>
            <div class='views-field-body'>A piece of hardware's latest network monitoring incident. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Monitor_Version1_Incident'>SoftLayer_Network_Monitor_Version1_Incident </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#location" name=location>location</a>
            </span>
            <div class='views-field-body'>Where a piece of hardware is located within SoftLayer's location hierarchy. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Location'>SoftLayer_Location </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#locationPathString" name=locationPathString>locationPathString</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lockboxNetworkStorage" name=lockboxNetworkStorage>lockboxNetworkStorage</a>
            </span>
            <div class='views-field-body'>Information regarding a lockbox account associated with a server. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#managedResourceFlag" name=managedResourceFlag>managedResourceFlag</a>
            </span>
            <div class='views-field-body'>A flag indicating that the hardware is a managed resource. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#memory" name=memory>memory</a>
            </span>
            <div class='views-field-body'>Information regarding a piece of hardware's memory. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Component'>SoftLayer_Hardware_Component[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#memoryCapacity" name=memoryCapacity>memoryCapacity</a>
            </span>
            <div class='views-field-body'>The amount of memory a piece of hardware has, measured in gigabytes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsigned integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#metricTrackingObject" name=metricTrackingObject>metricTrackingObject</a>
            </span>
            <div class='views-field-body'>A piece of hardware's metric tracking object. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Metric_Tracking_Object_HardwareServer'>SoftLayer_Metric_Tracking_Object_HardwareServer </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#modules" name=modules>modules</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Component'>SoftLayer_Hardware_Component[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#monitoringAgents" name=monitoringAgents>monitoringAgents</a>
            </span>
            <div class='views-field-body'>Information regarding the monitoring agents associated with a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Monitoring_Agent'>SoftLayer_Monitoring_Agent[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#monitoringRobot" name=monitoringRobot>monitoringRobot</a>
            </span>
            <div class='views-field-body'>Information regarding the hardware's monitoring robot. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Monitoring_Robot'>SoftLayer_Monitoring_Robot </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#monitoringServiceComponent" name=monitoringServiceComponent>monitoringServiceComponent</a>
            </span>
            <div class='views-field-body'>Information regarding a piece of hardware's network monitoring services. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Monitor_Version1_Query_Host_Stratum'>SoftLayer_Network_Monitor_Version1_Query_Host_Stratum </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#monitoringServiceEligibilityFlag" name=monitoringServiceEligibilityFlag>monitoringServiceEligibilityFlag</a>
            </span>
            <div class='views-field-body'>The monitoring service flag eligibility status for a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#monitoringServiceFlag" name=monitoringServiceFlag>monitoringServiceFlag</a>
            </span>
            <div class='views-field-body'>The service flag status for a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#motherboard" name=motherboard>motherboard</a>
            </span>
            <div class='views-field-body'>Information regarding a piece of hardware's motherboard. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Component'>SoftLayer_Hardware_Component </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkCards" name=networkCards>networkCards</a>
            </span>
            <div class='views-field-body'>Information regarding a piece of hardware's network cards. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Component'>SoftLayer_Hardware_Component[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkComponents" name=networkComponents>networkComponents</a>
            </span>
            <div class='views-field-body'>Returns a hardware's network components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Component'>SoftLayer_Network_Component[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkGatewayMember" name=networkGatewayMember>networkGatewayMember</a>
            </span>
            <div class='views-field-body'>The gateway member if this device is part of a network gateway. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Gateway_Member'>SoftLayer_Network_Gateway_Member </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkGatewayMemberFlag" name=networkGatewayMemberFlag>networkGatewayMemberFlag</a>
            </span>
            <div class='views-field-body'>Whether or not this device is part of a network gateway. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMonitorAttachedDownHardware" name=networkMonitorAttachedDownHardware>networkMonitorAttachedDownHardware</a>
            </span>
            <div class='views-field-body'>All servers with failed monitoring that are attached downstream to a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMonitorAttachedDownVirtualGuests" name=networkMonitorAttachedDownVirtualGuests>networkMonitorAttachedDownVirtualGuests</a>
            </span>
            <div class='views-field-body'>Virtual guests that are attached downstream to a hardware that have failed monitoring </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMonitorIncidents" name=networkMonitorIncidents>networkMonitorIncidents</a>
            </span>
            <div class='views-field-body'>The status of all of a piece of hardware's network monitoring incidents. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Monitor_Version1_Incident'>SoftLayer_Network_Monitor_Version1_Incident[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMonitors" name=networkMonitors>networkMonitors</a>
            </span>
            <div class='views-field-body'>Information regarding a piece of hardware's network monitors. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Monitor_Version1_Query_Host'>SoftLayer_Network_Monitor_Version1_Query_Host[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkStatus" name=networkStatus>networkStatus</a>
            </span>
            <div class='views-field-body'>The value of a hardware's network status attribute. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkStatusAttribute" name=networkStatusAttribute>networkStatusAttribute</a>
            </span>
            <div class='views-field-body'>The hardware's related network status attribute. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Attribute'>SoftLayer_Hardware_Attribute </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkStorage" name=networkStorage>networkStorage</a>
            </span>
            <div class='views-field-body'>Information regarding a piece of hardware's associated network storage service account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkVlans" name=networkVlans>networkVlans</a>
            </span>
            <div class='views-field-body'>The network virtual LANs (VLANs) associated with a piece of hardware's network components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Vlan'>SoftLayer_Network_Vlan[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#nextBillingCycleBandwidthAllocation" name=nextBillingCycleBandwidthAllocation>nextBillingCycleBandwidthAllocation</a>
            </span>
            <div class='views-field-body'>A hardware's allotted bandwidth for the next billing cycle (measured in GB). </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#notesHistory" name=notesHistory>notesHistory</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Note'>SoftLayer_Hardware_Note[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#nvRamCapacity" name=nvRamCapacity>nvRamCapacity</a>
            </span>
            <div class='views-field-body'>The amount of non-volatile memory a piece of hardware has, measured in gigabytes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsigned integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#nvRamComponentModels" name=nvRamComponentModels>nvRamComponentModels</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Component_Model'>SoftLayer_Hardware_Component_Model[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#operatingSystem" name=operatingSystem>operatingSystem</a>
            </span>
            <div class='views-field-body'>Information regarding a piece of hardware's operating system. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Software_Component_OperatingSystem'>SoftLayer_Software_Component_OperatingSystem </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#operatingSystemReferenceCode" name=operatingSystemReferenceCode>operatingSystemReferenceCode</a>
            </span>
            <div class='views-field-body'>A hardware's operating system software description. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#outboundBandwidthUsage" name=outboundBandwidthUsage>outboundBandwidthUsage</a>
            </span>
            <div class='views-field-body'>The sum of all the outbound network traffic data for the last 30 days. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#outboundPublicBandwidthUsage" name=outboundPublicBandwidthUsage>outboundPublicBandwidthUsage</a>
            </span>
            <div class='views-field-body'>The total public outbound bandwidth for this hardware for the current billing cycle. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#parentBay" name=parentBay>parentBay</a>
            </span>
            <div class='views-field-body'>Blade Bay </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Blade'>SoftLayer_Hardware_Blade </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#parentHardware" name=parentHardware>parentHardware</a>
            </span>
            <div class='views-field-body'>Parent Hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#pointOfPresenceLocation" name=pointOfPresenceLocation>pointOfPresenceLocation</a>
            </span>
            <div class='views-field-body'>Information regarding the Point of Presence (PoP) location in which a piece of hardware resides. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Location'>SoftLayer_Location </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#powerComponents" name=powerComponents>powerComponents</a>
            </span>
            <div class='views-field-body'>The power components for a hardware object. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Power_Component'>SoftLayer_Hardware_Power_Component[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#powerSupply" name=powerSupply>powerSupply</a>
            </span>
            <div class='views-field-body'>Information regarding a piece of hardware's power supply. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Component'>SoftLayer_Hardware_Component[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#primaryBackendNetworkComponent" name=primaryBackendNetworkComponent>primaryBackendNetworkComponent</a>
            </span>
            <div class='views-field-body'>Information regarding the hardware's primary back-end network component. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Component'>SoftLayer_Network_Component </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#primaryIpAddress" name=primaryIpAddress>primaryIpAddress</a>
            </span>
            <div class='views-field-body'>The administrative ip address of the switch. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#primaryNetworkComponent" name=primaryNetworkComponent>primaryNetworkComponent</a>
            </span>
            <div class='views-field-body'>Information regarding the hardware's primary public network component. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Component'>SoftLayer_Network_Component </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#privateNetworkOnlyFlag" name=privateNetworkOnlyFlag>privateNetworkOnlyFlag</a>
            </span>
            <div class='views-field-body'>Whether the hardware only has access to the private network. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#processorCoreAmount" name=processorCoreAmount>processorCoreAmount</a>
            </span>
            <div class='views-field-body'>The total number of processor cores, summed from all processors that are attached to a piece of hardware </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsigned integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#processorPhysicalCoreAmount" name=processorPhysicalCoreAmount>processorPhysicalCoreAmount</a>
            </span>
            <div class='views-field-body'>The total number of physical processor cores, summed from all processors that are attached to a piece of hardware </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsigned integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#processors" name=processors>processors</a>
            </span>
            <div class='views-field-body'>Information regarding a piece of hardware's processors. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Component'>SoftLayer_Hardware_Component[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#rack" name=rack>rack</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Location'>SoftLayer_Location </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#raidControllers" name=raidControllers>raidControllers</a>
            </span>
            <div class='views-field-body'>The RAID controllers contained within a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Component'>SoftLayer_Hardware_Component[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#recentEvents" name=recentEvents>recentEvents</a>
            </span>
            <div class='views-field-body'>Recent events that impact this hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Notification_Occurrence_Event'>SoftLayer_Notification_Occurrence_Event[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#remoteManagementAccounts" name=remoteManagementAccounts>remoteManagementAccounts</a>
            </span>
            <div class='views-field-body'>User credentials to issue commands and/or interact with the server's remote management card. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Component_RemoteManagement_User'>SoftLayer_Hardware_Component_RemoteManagement_User[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#remoteManagementComponent" name=remoteManagementComponent>remoteManagementComponent</a>
            </span>
            <div class='views-field-body'>A hardware's associated remote management component. This is normally IPMI. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Component'>SoftLayer_Network_Component </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#resourceConfigurations" name=resourceConfigurations>resourceConfigurations</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Resource_Configuration'>SoftLayer_Hardware_Resource_Configuration[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#resourceGroupMemberReferences" name=resourceGroupMemberReferences>resourceGroupMemberReferences</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Resource_Group_Member'>SoftLayer_Resource_Group_Member[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#resourceGroupRoles" name=resourceGroupRoles>resourceGroupRoles</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Resource_Group_Role'>SoftLayer_Resource_Group_Role[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#resourceGroups" name=resourceGroups>resourceGroups</a>
            </span>
            <div class='views-field-body'>The resource groups in which this hardware is a member. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Resource_Group'>SoftLayer_Resource_Group[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#routers" name=routers>routers</a>
            </span>
            <div class='views-field-body'>A hardware's routers. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#scaleAssets" name=scaleAssets>scaleAssets</a>
            </span>
            <div class='views-field-body'>Collection of scale assets this hardware corresponds to. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Scale_Asset'>SoftLayer_Scale_Asset[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#securityScanRequests" name=securityScanRequests>securityScanRequests</a>
            </span>
            <div class='views-field-body'>Information regarding a piece of hardware's vulnerability scan requests. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Security_Scanner_Request'>SoftLayer_Network_Security_Scanner_Request[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#serverRoom" name=serverRoom>serverRoom</a>
            </span>
            <div class='views-field-body'>Information regarding the server room in which the hardware is located. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Location'>SoftLayer_Location </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#serviceProvider" name=serviceProvider>serviceProvider</a>
            </span>
            <div class='views-field-body'>Information regarding the piece of hardware's service provider. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Service_Provider'>SoftLayer_Service_Provider </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#softwareComponents" name=softwareComponents>softwareComponents</a>
            </span>
            <div class='views-field-body'>Information regarding a piece of hardware's installed software. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Software_Component'>SoftLayer_Software_Component[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#sparePoolBillingItem" name=sparePoolBillingItem>sparePoolBillingItem</a>
            </span>
            <div class='views-field-body'>Information regarding the billing item for a spare pool server. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item_Hardware'>SoftLayer_Billing_Item_Hardware </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#sshKeys" name=sshKeys>sshKeys</a>
            </span>
            <div class='views-field-body'>SSH keys to be installed on the server during provisioning or an OS reload. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Security_Ssh_Key'>SoftLayer_Security_Ssh_Key[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#storageNetworkComponents" name=storageNetworkComponents>storageNetworkComponents</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Component'>SoftLayer_Network_Component[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#tagReferences" name=tagReferences>tagReferences</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Tag_Reference'>SoftLayer_Tag_Reference[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#topLevelLocation" name=topLevelLocation>topLevelLocation</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Location'>SoftLayer_Location </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#upgradeRequest" name=upgradeRequest>upgradeRequest</a>
            </span>
            <div class='views-field-body'>An account's associated upgrade request object, if any. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Product_Upgrade_Request'>SoftLayer_Product_Upgrade_Request </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#uplinkHardware" name=uplinkHardware>uplinkHardware</a>
            </span>
            <div class='views-field-body'>The network device connected to a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#uplinkNetworkComponents" name=uplinkNetworkComponents>uplinkNetworkComponents</a>
            </span>
            <div class='views-field-body'>Information regarding the network component that is one level higher than a piece of hardware on the network infrastructure. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Component'>SoftLayer_Network_Component[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#userData" name=userData>userData</a>
            </span>
            <div class='views-field-body'>An array containing a single string of custom user data for a hardware order. Max size is 16 kb. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Attribute'>SoftLayer_Hardware_Attribute[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualChassis" name=virtualChassis>virtualChassis</a>
            </span>
            <div class='views-field-body'>Information regarding the virtual chassis for a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Group'>SoftLayer_Hardware_Group </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualChassisSiblings" name=virtualChassisSiblings>virtualChassisSiblings</a>
            </span>
            <div class='views-field-body'>Information regarding the virtual chassis siblings for a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualHost" name=virtualHost>virtualHost</a>
            </span>
            <div class='views-field-body'>A piece of hardware's virtual host record. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Host'>SoftLayer_Virtual_Host </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualLicenses" name=virtualLicenses>virtualLicenses</a>
            </span>
            <div class='views-field-body'>Information regarding a piece of hardware's virtual software licenses. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Software_VirtualLicense'>SoftLayer_Software_VirtualLicense[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualRack" name=virtualRack>virtualRack</a>
            </span>
            <div class='views-field-body'>Information regarding the bandwidth allotment to which a piece of hardware belongs. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Bandwidth_Version1_Allotment'>SoftLayer_Network_Bandwidth_Version1_Allotment </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualRackId" name=virtualRackId>virtualRackId</a>
            </span>
            <div class='views-field-body'>The name of the bandwidth allotment belonging to a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualRackName" name=virtualRackName>virtualRackName</a>
            </span>
            <div class='views-field-body'>The name of the bandwidth allotment belonging to a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualizationPlatform" name=virtualizationPlatform>virtualizationPlatform</a>
            </span>
            <div class='views-field-body'>A piece of hardware's virtualization platform software. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Software_Component'>SoftLayer_Software_Component </a></p>
            </div>
        </div>
                <h2>Count</h2>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeComponentCount" name=activeComponentCount>activeComponentCount</a>
            </span>
            <div class='views-field-body'>A count of a piece of hardware's active physical components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeNetworkMonitorIncidentCount" name=activeNetworkMonitorIncidentCount>activeNetworkMonitorIncidentCount</a>
            </span>
            <div class='views-field-body'>A count of a piece of hardware's active network monitoring incidents. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allPowerComponentCount" name=allPowerComponentCount>allPowerComponentCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
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
                <a href="#attributeCount" name=attributeCount>attributeCount</a>
            </span>
            <div class='views-field-body'>A count of information regarding a piece of hardware's specific attributes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#backendNetworkComponentCount" name=backendNetworkComponentCount>backendNetworkComponentCount</a>
            </span>
            <div class='views-field-body'>A count of a piece of hardware's back-end or private network components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#backendRouterCount" name=backendRouterCount>backendRouterCount</a>
            </span>
            <div class='views-field-body'>A count of a hardware's backend or private router. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#benchmarkCertificationCount" name=benchmarkCertificationCount>benchmarkCertificationCount</a>
            </span>
            <div class='views-field-body'>A count of information regarding a piece of hardware's benchmark certifications. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#childrenHardwareCount" name=childrenHardwareCount>childrenHardwareCount</a>
            </span>
            <div class='views-field-body'>A count of child hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#componentCount" name=componentCount>componentCount</a>
            </span>
            <div class='views-field-body'>A count of a piece of hardware's components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#downlinkHardwareCount" name=downlinkHardwareCount>downlinkHardwareCount</a>
            </span>
            <div class='views-field-body'>A count of all hardware that has uplink network connections to a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#downlinkNetworkHardwareCount" name=downlinkNetworkHardwareCount>downlinkNetworkHardwareCount</a>
            </span>
            <div class='views-field-body'>A count of all hardware that has uplink network connections to a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#downlinkServerCount" name=downlinkServerCount>downlinkServerCount</a>
            </span>
            <div class='views-field-body'>A count of information regarding all servers attached to a piece of network hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#downlinkVirtualGuestCount" name=downlinkVirtualGuestCount>downlinkVirtualGuestCount</a>
            </span>
            <div class='views-field-body'>A count of information regarding all virtual guests attached to a piece of network hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#downstreamHardwareBindingCount" name=downstreamHardwareBindingCount>downstreamHardwareBindingCount</a>
            </span>
            <div class='views-field-body'>A count of all hardware downstream from a network device. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#downstreamNetworkHardwareCount" name=downstreamNetworkHardwareCount>downstreamNetworkHardwareCount</a>
            </span>
            <div class='views-field-body'>A count of all network hardware downstream from the selected piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#downstreamNetworkHardwareWithIncidentCount" name=downstreamNetworkHardwareWithIncidentCount>downstreamNetworkHardwareWithIncidentCount</a>
            </span>
            <div class='views-field-body'>A count of all network hardware with monitoring warnings or errors that are downstream from the selected piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#downstreamServerCount" name=downstreamServerCount>downstreamServerCount</a>
            </span>
            <div class='views-field-body'>A count of information regarding all servers attached downstream to a piece of network hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#downstreamVirtualGuestCount" name=downstreamVirtualGuestCount>downstreamVirtualGuestCount</a>
            </span>
            <div class='views-field-body'>A count of information regarding all virtual guests attached to a piece of network hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#driveControllerCount" name=driveControllerCount>driveControllerCount</a>
            </span>
            <div class='views-field-body'>A count of the drive controllers contained within a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#evaultNetworkStorageCount" name=evaultNetworkStorageCount>evaultNetworkStorageCount</a>
            </span>
            <div class='views-field-body'>A count of information regarding a piece of hardware's associated EVault network storage service account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#frontendNetworkComponentCount" name=frontendNetworkComponentCount>frontendNetworkComponentCount</a>
            </span>
            <div class='views-field-body'>A count of a piece of hardware's front-end or public network components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#frontendRouterCount" name=frontendRouterCount>frontendRouterCount</a>
            </span>
            <div class='views-field-body'>A count of a hardware's frontend or public router. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardDriveCount" name=hardDriveCount>hardDriveCount</a>
            </span>
            <div class='views-field-body'>A count of the hard drives contained within a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#memoryCount" name=memoryCount>memoryCount</a>
            </span>
            <div class='views-field-body'>A count of information regarding a piece of hardware's memory. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#moduleCount" name=moduleCount>moduleCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#monitoringAgentCount" name=monitoringAgentCount>monitoringAgentCount</a>
            </span>
            <div class='views-field-body'>A count of information regarding the monitoring agents associated with a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkCardCount" name=networkCardCount>networkCardCount</a>
            </span>
            <div class='views-field-body'>A count of information regarding a piece of hardware's network cards. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkComponentCount" name=networkComponentCount>networkComponentCount</a>
            </span>
            <div class='views-field-body'>A count of returns a hardware's network components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMonitorAttachedDownHardwareCount" name=networkMonitorAttachedDownHardwareCount>networkMonitorAttachedDownHardwareCount</a>
            </span>
            <div class='views-field-body'>A count of all servers with failed monitoring that are attached downstream to a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMonitorAttachedDownVirtualGuestCount" name=networkMonitorAttachedDownVirtualGuestCount>networkMonitorAttachedDownVirtualGuestCount</a>
            </span>
            <div class='views-field-body'>A count of virtual guests that are attached downstream to a hardware that have failed monitoring </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMonitorCount" name=networkMonitorCount>networkMonitorCount</a>
            </span>
            <div class='views-field-body'>A count of information regarding a piece of hardware's network monitors. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMonitorIncidentCount" name=networkMonitorIncidentCount>networkMonitorIncidentCount</a>
            </span>
            <div class='views-field-body'>A count of the status of all of a piece of hardware's network monitoring incidents. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkStorageCount" name=networkStorageCount>networkStorageCount</a>
            </span>
            <div class='views-field-body'>A count of information regarding a piece of hardware's associated network storage service account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkVlanCount" name=networkVlanCount>networkVlanCount</a>
            </span>
            <div class='views-field-body'>A count of the network virtual LANs (VLANs) associated with a piece of hardware's network components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#notesHistoryCount" name=notesHistoryCount>notesHistoryCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#nvRamComponentModelCount" name=nvRamComponentModelCount>nvRamComponentModelCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#powerComponentCount" name=powerComponentCount>powerComponentCount</a>
            </span>
            <div class='views-field-body'>A count of the power components for a hardware object. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#powerSupplyCount" name=powerSupplyCount>powerSupplyCount</a>
            </span>
            <div class='views-field-body'>A count of information regarding a piece of hardware's power supply. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#processorCount" name=processorCount>processorCount</a>
            </span>
            <div class='views-field-body'>A count of information regarding a piece of hardware's processors. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#raidControllerCount" name=raidControllerCount>raidControllerCount</a>
            </span>
            <div class='views-field-body'>A count of the RAID controllers contained within a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#recentEventCount" name=recentEventCount>recentEventCount</a>
            </span>
            <div class='views-field-body'>A count of recent events that impact this hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#remoteManagementAccountCount" name=remoteManagementAccountCount>remoteManagementAccountCount</a>
            </span>
            <div class='views-field-body'>A count of user credentials to issue commands and/or interact with the server's remote management card. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#resourceConfigurationCount" name=resourceConfigurationCount>resourceConfigurationCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#resourceGroupCount" name=resourceGroupCount>resourceGroupCount</a>
            </span>
            <div class='views-field-body'>A count of the resource groups in which this hardware is a member. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#resourceGroupMemberReferenceCount" name=resourceGroupMemberReferenceCount>resourceGroupMemberReferenceCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#resourceGroupRoleCount" name=resourceGroupRoleCount>resourceGroupRoleCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#routerCount" name=routerCount>routerCount</a>
            </span>
            <div class='views-field-body'>A count of a hardware's routers. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#scaleAssetCount" name=scaleAssetCount>scaleAssetCount</a>
            </span>
            <div class='views-field-body'>A count of collection of scale assets this hardware corresponds to. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#securityScanRequestCount" name=securityScanRequestCount>securityScanRequestCount</a>
            </span>
            <div class='views-field-body'>A count of information regarding a piece of hardware's vulnerability scan requests. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#softwareComponentCount" name=softwareComponentCount>softwareComponentCount</a>
            </span>
            <div class='views-field-body'>A count of information regarding a piece of hardware's installed software. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#sshKeyCount" name=sshKeyCount>sshKeyCount</a>
            </span>
            <div class='views-field-body'>A count of sSH keys to be installed on the server during provisioning or an OS reload. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#storageNetworkComponentCount" name=storageNetworkComponentCount>storageNetworkComponentCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#tagReferenceCount" name=tagReferenceCount>tagReferenceCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#uplinkNetworkComponentCount" name=uplinkNetworkComponentCount>uplinkNetworkComponentCount</a>
            </span>
            <div class='views-field-body'>A count of information regarding the network component that is one level higher than a piece of hardware on the network infrastructure. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#userDataCount" name=userDataCount>userDataCount</a>
            </span>
            <div class='views-field-body'>A count of an array containing a single string of custom user data for a hardware order. Max size is 16 kb. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualChassisSiblingCount" name=virtualChassisSiblingCount>virtualChassisSiblingCount</a>
            </span>
            <div class='views-field-body'>A count of information regarding the virtual chassis siblings for a piece of hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualLicenseCount" name=virtualLicenseCount>virtualLicenseCount</a>
            </span>
            <div class='views-field-body'>A count of information regarding a piece of hardware's virtual software licenses. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
            </div>
</div>


