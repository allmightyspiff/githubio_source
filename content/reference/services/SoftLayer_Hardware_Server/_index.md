---
title: "SoftLayer_Hardware_Server"
description: "Every SoftLayer server is defined in the SoftLayer_Hardware_Server service. SoftLayer servers have all the functionality... "
date: "2018-02-12"
layout: "service"
tags:
    - "service"
    - "sldn"
    - "Hardware"
classes:
    - "SoftLayer_Hardware_Server"
---
# SoftLayer_Hardware_Server
<div id='service-datatype'>
    <ul id='sldn-reference-tabs'>
    <li id='service'> <a href='/reference/services/SoftLayer_Hardware_Server' >Service</a></li>    <li id='datatype'> <a href='/reference/datatypes/SoftLayer_Hardware_Server' >Datatype</a></li>
    </ul>
</div>

## Description
Every SoftLayer server is defined in the SoftLayer_Hardware_Server service. SoftLayer servers have all the functionality of SoftLayer_Hardware with the of server specific data and functionality such as Operating System reload dates and motherboard components. The SoftLayer_Hardware service is a convenient way to obtain general information about your SoftLayer server. Use the data returned by these methods with other API services to get more detailed information about your services and to make changes to your servers and services. 



### seeAlso

* [SoftLayer_Hardware](/reference/services/SoftLayer_Hardware )


        
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
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/activatePrivatePort'> activatePrivatePort</a> </span>
            <div class='views-field-body'>Activate a server's private network interface.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/activatePublicPort'> activatePublicPort</a> </span>
            <div class='views-field-body'>Activate a server's public network interface.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/allowAccessToNetworkStorage'> allowAccessToNetworkStorage</a> </span>
            <div class='views-field-body'>Allow access to a SoftLayer_Network_Storage volume from this device. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/allowAccessToNetworkStorageList'> allowAccessToNetworkStorageList</a> </span>
            <div class='views-field-body'>Allow access to multiple SoftLayer_Network_Storage volumes from this device. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/bootToRescueLayer'> bootToRescueLayer</a> </span>
            <div class='views-field-body'>Initiates the Rescue Kernel to bring a server online to troubleshoot system problems.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/captureImage'> captureImage</a> </span>
            <div class='views-field-body'>Captures a Flex Image of the hard disk on the physical machine.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/closeAlarm'> closeAlarm</a> </span>
            <div class='views-field-body'>Returns monitoring alarm detailed history</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/createFirmwareReflashTransaction'> createFirmwareReflashTransaction</a> </span>
            <div class='views-field-body'>Runs firmware reflash on the servers components.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/createFirmwareUpdateTransaction'> createFirmwareUpdateTransaction</a> </span>
            <div class='views-field-body'>Runs firmware updates on the servers components.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/createHyperThreadingUpdateTransaction'> createHyperThreadingUpdateTransaction</a> </span>
            <div class='views-field-body'>Runs BIOS update on the server to change the hyper-threading configuration.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/createObject'> createObject</a> </span>
            <div class='views-field-body'>Create a new server</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/createPostSoftwareInstallTransaction'> createPostSoftwareInstallTransaction</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/deleteObject'> deleteObject</a> </span>
            <div class='views-field-body'>Delete a server</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/deleteSoftwareComponentPasswords'> deleteSoftwareComponentPasswords</a> </span>
            <div class='views-field-body'>Delete software component passwords.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/deleteTag'> deleteTag</a> </span>
            <div class='views-field-body'>Delete a tag</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/editObject'> editObject</a> </span>
            <div class='views-field-body'>Edit a server's properties</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/editSoftwareComponentPasswords'> editSoftwareComponentPasswords</a> </span>
            <div class='views-field-body'>Edit the properties of software component passwords.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/executeRemoteScript'> executeRemoteScript</a> </span>
            <div class='views-field-body'>Download and run remote script from uri on the hardware. Requires https for script to be executed after download. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/findByIpAddress'> findByIpAddress</a> </span>
            <div class='views-field-body'>Find hardware by its primary public or private IP (ipv4) address.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/generateOrderTemplate'> generateOrderTemplate</a> </span>
            <div class='views-field-body'>Obtain an order container for a given template object</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getAccount'> getAccount</a> </span>
            <div class='views-field-body'>Retrieve the account associated with a piece of hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getActiveComponents'> getActiveComponents</a> </span>
            <div class='views-field-body'>Retrieve a piece of hardware's active physical components.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getActiveNetworkFirewallBillingItem'> getActiveNetworkFirewallBillingItem</a> </span>
            <div class='views-field-body'>Retrieve the billing item for a server's attached network firewall.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getActiveNetworkMonitorIncident'> getActiveNetworkMonitorIncident</a> </span>
            <div class='views-field-body'>Retrieve a piece of hardware's active network monitoring incidents.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getActiveTickets'> getActiveTickets</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getActiveTransaction'> getActiveTransaction</a> </span>
            <div class='views-field-body'>Retrieve transaction currently running for server.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getActiveTransactions'> getActiveTransactions</a> </span>
            <div class='views-field-body'>Retrieve any active transaction(s) that are currently running for the server (example: os reload).</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getAlarmHistory'> getAlarmHistory</a> </span>
            <div class='views-field-body'>Returns monitoring alarm detailed history</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getAllPowerComponents'> getAllPowerComponents</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getAllowedHost'> getAllowedHost</a> </span>
            <div class='views-field-body'>Retrieve the SoftLayer_Network_Storage_Allowed_Host information to connect this server to Network Storage volumes that require access control lists.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getAllowedNetworkStorage'> getAllowedNetworkStorage</a> </span>
            <div class='views-field-body'>Retrieve the SoftLayer_Network_Storage objects that this SoftLayer_Hardware has access to.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getAllowedNetworkStorageReplicas'> getAllowedNetworkStorageReplicas</a> </span>
            <div class='views-field-body'>Retrieve the SoftLayer_Network_Storage objects whose Replica that this SoftLayer_Hardware has access to.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getAntivirusSpywareSoftwareComponent'> getAntivirusSpywareSoftwareComponent</a> </span>
            <div class='views-field-body'>Retrieve information regarding an antivirus/spyware software component object.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getAttachedNetworkStorages'> getAttachedNetworkStorages</a> </span>
            <div class='views-field-body'>Return a list of SoftLayer_Network_Storage volumes authorized to this device. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getAttributes'> getAttributes</a> </span>
            <div class='views-field-body'>Retrieve information regarding a piece of hardware's specific attributes.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getAvailableMonitoring'> getAvailableMonitoring</a> </span>
            <div class='views-field-body'>Retrieve an object that stores the maximum level for the monitoring query types and response types.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getAvailableNetworkStorages'> getAvailableNetworkStorages</a> </span>
            <div class='views-field-body'>Return a list of SoftLayer_Network_Storage volumes that can be authorized to this device. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getAverageDailyBandwidthUsage'> getAverageDailyBandwidthUsage</a> </span>
            <div class='views-field-body'>Retrieve the average daily total bandwidth usage for the current billing cycle.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getAverageDailyPrivateBandwidthUsage'> getAverageDailyPrivateBandwidthUsage</a> </span>
            <div class='views-field-body'>Retrieve the average daily private bandwidth usage for the current billing cycle.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getAverageDailyPublicBandwidthUsage'> getAverageDailyPublicBandwidthUsage</a> </span>
            <div class='views-field-body'>Retrieve the average daily public bandwidth usage for the current billing cycle.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getBackendBandwidthUsage'> getBackendBandwidthUsage</a> </span>
            <div class='views-field-body'>Retrieves public bandwidth usage records.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getBackendBandwidthUse'> getBackendBandwidthUse</a> </span>
            <div class='views-field-body'>Retrieves private bandwidth usage records.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getBackendIncomingBandwidth'> getBackendIncomingBandwidth</a> </span>
            <div class='views-field-body'>Retrieve the amount of incoming private network bandwidth used by a server over a period of time. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getBackendNetworkComponents'> getBackendNetworkComponents</a> </span>
            <div class='views-field-body'>Retrieve a piece of hardware's back-end or private network components.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getBackendOutgoingBandwidth'> getBackendOutgoingBandwidth</a> </span>
            <div class='views-field-body'>Retrieve the amount of outgoing private network bandwidth used by a server over a period of time. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getBackendRouters'> getBackendRouters</a> </span>
            <div class='views-field-body'>Retrieve a hardware's backend or private router.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getBandwidthAllocation'> getBandwidthAllocation</a> </span>
            <div class='views-field-body'>Retrieve a hardware's allotted bandwidth (measured in GB).</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getBandwidthAllotmentDetail'> getBandwidthAllotmentDetail</a> </span>
            <div class='views-field-body'>Retrieve a hardware's allotted detail record. Allotment details link bandwidth allocation with allotments.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getBandwidthForDateRange'> getBandwidthForDateRange</a> </span>
            <div class='views-field-body'>Retrieve bandwidth data from a tracking object.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getBandwidthImage'> getBandwidthImage</a> </span>
            <div class='views-field-body'>Retrieve a bandwidth image and textual description of that image for this server.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getBenchmarkCertifications'> getBenchmarkCertifications</a> </span>
            <div class='views-field-body'>Retrieve information regarding a piece of hardware's benchmark certifications.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getBillingCycleBandwidthUsage'> getBillingCycleBandwidthUsage</a> </span>
            <div class='views-field-body'>Retrieve the raw bandwidth usage data for the current billing cycle. One object will be returned for each network this server is attached to.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getBillingCyclePrivateBandwidthUsage'> getBillingCyclePrivateBandwidthUsage</a> </span>
            <div class='views-field-body'>Retrieve the raw private bandwidth usage data for the current billing cycle.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getBillingCyclePublicBandwidthUsage'> getBillingCyclePublicBandwidthUsage</a> </span>
            <div class='views-field-body'>Retrieve the raw public bandwidth usage data for the current billing cycle.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getBillingItem'> getBillingItem</a> </span>
            <div class='views-field-body'>Retrieve the billing item for a server.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getBillingItemFlag'> getBillingItemFlag</a> </span>
            <div class='views-field-body'>Retrieve a flag indicating that a billing item exists.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getBiosPasswordNullFlag'> getBiosPasswordNullFlag</a> </span>
            <div class='views-field-body'>Retrieve determine if BIOS password should be left as null.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getBlockCancelBecauseDisconnectedFlag'> getBlockCancelBecauseDisconnectedFlag</a> </span>
            <div class='views-field-body'>Retrieve determines whether the hardware is ineligible for cancellation because it is disconnected.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getBootModeOptions'> getBootModeOptions</a> </span>
            <div class='views-field-body'>Retrieve the valid boot modes for this server.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getBusinessContinuanceInsuranceFlag'> getBusinessContinuanceInsuranceFlag</a> </span>
            <div class='views-field-body'>Retrieve status indicating whether or not a piece of hardware has business continuance insurance.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getChildrenHardware'> getChildrenHardware</a> </span>
            <div class='views-field-body'>Retrieve child hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getComponentDetailsXML'> getComponentDetailsXML</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getComponents'> getComponents</a> </span>
            <div class='views-field-body'>Retrieve a piece of hardware's components.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getContainsSolidStateDrivesFlag'> getContainsSolidStateDrivesFlag</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getContinuousDataProtectionSoftwareComponent'> getContinuousDataProtectionSoftwareComponent</a> </span>
            <div class='views-field-body'>Retrieve a continuous data protection/server backup software component object.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getControlPanel'> getControlPanel</a> </span>
            <div class='views-field-body'>Retrieve a server's control panel.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getCost'> getCost</a> </span>
            <div class='views-field-body'>Retrieve the total cost of a server, measured in US Dollars ($USD).</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getCreateObjectOptions'> getCreateObjectOptions</a> </span>
            <div class='views-field-body'>Determine options available when creating a server</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getCurrentBandwidthSummary'> getCurrentBandwidthSummary</a> </span>
            <div class='views-field-body'>Retrieve an object that provides commonly used bandwidth summary components for the current billing cycle.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getCurrentBenchmarkCertificationResultFile'> getCurrentBenchmarkCertificationResultFile</a> </span>
            <div class='views-field-body'>Get the file for the current benchmark certification result, if it exists.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getCurrentBillableBandwidthUsage'> getCurrentBillableBandwidthUsage</a> </span>
            <div class='views-field-body'>Retrieve the current billable public outbound bandwidth for this hardware for the current billing cycle.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getCurrentBillingDetail'> getCurrentBillingDetail</a> </span>
            <div class='views-field-body'><< EOT</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getCurrentBillingTotal'> getCurrentBillingTotal</a> </span>
            <div class='views-field-body'>Get the billing total for this instance's usage up to this point. This total includes all bandwidth charges. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getCustomBandwidthDataByDate'> getCustomBandwidthDataByDate</a> </span>
            <div class='views-field-body'>Retrieve bandwidth graph by date.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getCustomerInstalledOperatingSystemFlag'> getCustomerInstalledOperatingSystemFlag</a> </span>
            <div class='views-field-body'>Retrieve indicates if a server has a Customer Installed OS</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getCustomerOwnedFlag'> getCustomerOwnedFlag</a> </span>
            <div class='views-field-body'>Retrieve indicates if a server is a customer owned device.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getDailyAverage'> getDailyAverage</a> </span>
            <div class='views-field-body'>calculate the average daily network traffic used by a server in gigabytes.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getDatacenter'> getDatacenter</a> </span>
            <div class='views-field-body'>Retrieve information regarding the datacenter in which a piece of hardware resides.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getDatacenterName'> getDatacenterName</a> </span>
            <div class='views-field-body'>Retrieve the name of the datacenter in which a piece of hardware resides.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getDaysInSparePool'> getDaysInSparePool</a> </span>
            <div class='views-field-body'>Retrieve number of day(s) a server have been in spare pool.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getDownlinkHardware'> getDownlinkHardware</a> </span>
            <div class='views-field-body'>Retrieve all hardware that has uplink network connections to a piece of hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getDownlinkNetworkHardware'> getDownlinkNetworkHardware</a> </span>
            <div class='views-field-body'>Retrieve all hardware that has uplink network connections to a piece of hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getDownlinkServers'> getDownlinkServers</a> </span>
            <div class='views-field-body'>Retrieve information regarding all servers attached to a piece of network hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getDownlinkVirtualGuests'> getDownlinkVirtualGuests</a> </span>
            <div class='views-field-body'>Retrieve information regarding all virtual guests attached to a piece of network hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getDownstreamHardwareBindings'> getDownstreamHardwareBindings</a> </span>
            <div class='views-field-body'>Retrieve all hardware downstream from a network device.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getDownstreamNetworkHardware'> getDownstreamNetworkHardware</a> </span>
            <div class='views-field-body'>Retrieve all network hardware downstream from the selected piece of hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getDownstreamNetworkHardwareWithIncidents'> getDownstreamNetworkHardwareWithIncidents</a> </span>
            <div class='views-field-body'>Retrieve all network hardware with monitoring warnings or errors that are downstream from the selected piece of hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getDownstreamServers'> getDownstreamServers</a> </span>
            <div class='views-field-body'>Retrieve information regarding all servers attached downstream to a piece of network hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getDownstreamVirtualGuests'> getDownstreamVirtualGuests</a> </span>
            <div class='views-field-body'>Retrieve information regarding all virtual guests attached to a piece of network hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getDriveControllers'> getDriveControllers</a> </span>
            <div class='views-field-body'>Retrieve the drive controllers contained within a piece of hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getEvaultNetworkStorage'> getEvaultNetworkStorage</a> </span>
            <div class='views-field-body'>Retrieve information regarding a piece of hardware's associated EVault network storage service account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getFirewallProtectableSubnets'> getFirewallProtectableSubnets</a> </span>
            <div class='views-field-body'>Get the subnets associated with this server that are protectable by a network component firewall.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getFirewallServiceComponent'> getFirewallServiceComponent</a> </span>
            <div class='views-field-body'>Retrieve information regarding a piece of hardware's firewall services.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getFixedConfigurationPreset'> getFixedConfigurationPreset</a> </span>
            <div class='views-field-body'>Retrieve defines the fixed components in a fixed configuration bare metal server.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getFrontendBandwidthUsage'> getFrontendBandwidthUsage</a> </span>
            <div class='views-field-body'>Retrieves public bandwidth usage records.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getFrontendBandwidthUse'> getFrontendBandwidthUse</a> </span>
            <div class='views-field-body'>Retrieves public bandwidth usage records.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getFrontendIncomingBandwidth'> getFrontendIncomingBandwidth</a> </span>
            <div class='views-field-body'>Retrieve the amount of incoming public network bandwidth used by a server over a period of time. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getFrontendNetworkComponents'> getFrontendNetworkComponents</a> </span>
            <div class='views-field-body'>Retrieve a piece of hardware's front-end or public network components.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getFrontendOutgoingBandwidth'> getFrontendOutgoingBandwidth</a> </span>
            <div class='views-field-body'>Retrieve the amount of outgoing public network bandwidth used by a server over a period of time. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getFrontendRouters'> getFrontendRouters</a> </span>
            <div class='views-field-body'>Retrieve a hardware's frontend or public router.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getGlobalIdentifier'> getGlobalIdentifier</a> </span>
            <div class='views-field-body'>Retrieve a hardware's universally unique identifier.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getHardDrives'> getHardDrives</a> </span>
            <div class='views-field-body'>Retrieve the hard drives contained within a piece of hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getHardwareByIpAddress'> getHardwareByIpAddress</a> </span>
            <div class='views-field-body'>Retrieve a SoftLayer_Hardware_Server object by IP address.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getHardwareChassis'> getHardwareChassis</a> </span>
            <div class='views-field-body'>Retrieve the chassis that a piece of hardware is housed in.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getHardwareFunction'> getHardwareFunction</a> </span>
            <div class='views-field-body'>Retrieve a hardware's function.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getHardwareFunctionDescription'> getHardwareFunctionDescription</a> </span>
            <div class='views-field-body'>Retrieve a hardware's function.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getHardwareStatus'> getHardwareStatus</a> </span>
            <div class='views-field-body'>Retrieve a hardware's status.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getHasSingleRootVirtualizationBillingItemFlag'> getHasSingleRootVirtualizationBillingItemFlag</a> </span>
            <div class='views-field-body'>Retrieve determine if hardware has Single Root IO VIrtualization (SR-IOV) billing item.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getHasTrustedPlatformModuleBillingItemFlag'> getHasTrustedPlatformModuleBillingItemFlag</a> </span>
            <div class='views-field-body'>Retrieve determine in hardware object has TPM enabled.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getHostIpsSoftwareComponent'> getHostIpsSoftwareComponent</a> </span>
            <div class='views-field-body'>Retrieve information regarding a host IPS software component object.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getHourlyBandwidth'> getHourlyBandwidth</a> </span>
            <div class='views-field-body'>Retrieves bandwidth hourly over a 24-hour period for the specified hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getHourlyBillingFlag'> getHourlyBillingFlag</a> </span>
            <div class='views-field-body'>Retrieve a server's hourly billing status.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getInboundBandwidthUsage'> getInboundBandwidthUsage</a> </span>
            <div class='views-field-body'>Retrieve the sum of all the inbound network traffic data for the last 30 days.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getInboundPrivateBandwidthUsage'> getInboundPrivateBandwidthUsage</a> </span>
            <div class='views-field-body'>Retrieve the total private inbound bandwidth for this hardware for the current billing cycle.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getInboundPublicBandwidthUsage'> getInboundPublicBandwidthUsage</a> </span>
            <div class='views-field-body'>Retrieve the total public inbound bandwidth for this hardware for the current billing cycle.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getIsCloudReadyNodeCertified'> getIsCloudReadyNodeCertified</a> </span>
            <div class='views-field-body'>Retrieve determine if hardware object has the IBM_CLOUD_READY_NODE_CERTIFIED attribute.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getIsIpmiDisabled'> getIsIpmiDisabled</a> </span>
            <div class='views-field-body'>Retrieve determine if remote management has been disabled due to port speed.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getIsVirtualPrivateCloudNode'> getIsVirtualPrivateCloudNode</a> </span>
            <div class='views-field-body'>Retrieve determine if hardware object is a Virtual Private Cloud node.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getItemPricesFromSoftwareDescriptions'> getItemPricesFromSoftwareDescriptions</a> </span>
            <div class='views-field-body'>Return a collection of SoftLayer_Item_Price objects from a collection of SoftLayer_Software_Description</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getLastOperatingSystemReload'> getLastOperatingSystemReload</a> </span>
            <div class='views-field-body'>Retrieve the last transaction that a server's operating system was loaded.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getLastTransaction'> getLastTransaction</a> </span>
            <div class='views-field-body'>Retrieve information regarding the last transaction a server performed.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getLatestNetworkMonitorIncident'> getLatestNetworkMonitorIncident</a> </span>
            <div class='views-field-body'>Retrieve a piece of hardware's latest network monitoring incident.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getLocation'> getLocation</a> </span>
            <div class='views-field-body'>Retrieve where a piece of hardware is located within SoftLayer's location hierarchy.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getLocationPathString'> getLocationPathString</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getLockboxNetworkStorage'> getLockboxNetworkStorage</a> </span>
            <div class='views-field-body'>Retrieve information regarding a lockbox account associated with a server.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getManagedResourceFlag'> getManagedResourceFlag</a> </span>
            <div class='views-field-body'>Retrieve a flag indicating that the hardware is a managed resource.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getManagementNetworkComponent'> getManagementNetworkComponent</a> </span>
            <div class='views-field-body'>Retrieve a server's management network component.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getMemory'> getMemory</a> </span>
            <div class='views-field-body'>Retrieve information regarding a piece of hardware's memory.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getMemoryCapacity'> getMemoryCapacity</a> </span>
            <div class='views-field-body'>Retrieve the amount of memory a piece of hardware has, measured in gigabytes.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getMetricTrackingObject'> getMetricTrackingObject</a> </span>
            <div class='views-field-body'>Retrieve a piece of hardware's metric tracking object.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getMetricTrackingObjectId'> getMetricTrackingObjectId</a> </span>
            <div class='views-field-body'>Retrieve the metric tracking object id for this server.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getModules'> getModules</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getMonitoringActiveAlarms'> getMonitoringActiveAlarms</a> </span>
            <div class='views-field-body'>Returns open monitoring alarms for a given time period</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getMonitoringAgents'> getMonitoringAgents</a> </span>
            <div class='views-field-body'>Retrieve information regarding the monitoring agents associated with a piece of hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getMonitoringClosedAlarms'> getMonitoringClosedAlarms</a> </span>
            <div class='views-field-body'>Returns closed monitoring alarms for a given time period</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getMonitoringRobot'> getMonitoringRobot</a> </span>
            <div class='views-field-body'>Retrieve information regarding the hardware's monitoring robot.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getMonitoringServiceComponent'> getMonitoringServiceComponent</a> </span>
            <div class='views-field-body'>Retrieve information regarding a piece of hardware's network monitoring services.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getMonitoringServiceEligibilityFlag'> getMonitoringServiceEligibilityFlag</a> </span>
            <div class='views-field-body'>Retrieve the monitoring service flag eligibility status for a piece of hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getMonitoringServiceFlag'> getMonitoringServiceFlag</a> </span>
            <div class='views-field-body'>Retrieve the service flag status for a piece of hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getMonitoringUserNotification'> getMonitoringUserNotification</a> </span>
            <div class='views-field-body'>Retrieve the monitoring notification objects for this hardware. Each object links this hardware instance to a user account that will be notified if monitoring on this hardware object fails</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getMotherboard'> getMotherboard</a> </span>
            <div class='views-field-body'>Retrieve a server's motherboard.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getNetworkCards'> getNetworkCards</a> </span>
            <div class='views-field-body'>Retrieve information regarding a piece of hardware's network cards.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getNetworkComponentFirewallProtectableIpAddresses'> getNetworkComponentFirewallProtectableIpAddresses</a> </span>
            <div class='views-field-body'>Get the IP addresses associated with this server that are protectable by a network component firewall.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getNetworkComponents'> getNetworkComponents</a> </span>
            <div class='views-field-body'>Retrieve returns a hardware's network components.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getNetworkGatewayMember'> getNetworkGatewayMember</a> </span>
            <div class='views-field-body'>Retrieve the gateway member if this device is part of a network gateway.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getNetworkGatewayMemberFlag'> getNetworkGatewayMemberFlag</a> </span>
            <div class='views-field-body'>Retrieve whether or not this device is part of a network gateway.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getNetworkManagementIpAddress'> getNetworkManagementIpAddress</a> </span>
            <div class='views-field-body'>Retrieve a piece of hardware's network management IP address.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getNetworkMonitorAttachedDownHardware'> getNetworkMonitorAttachedDownHardware</a> </span>
            <div class='views-field-body'>Retrieve all servers with failed monitoring that are attached downstream to a piece of hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getNetworkMonitorAttachedDownVirtualGuests'> getNetworkMonitorAttachedDownVirtualGuests</a> </span>
            <div class='views-field-body'>Retrieve virtual guests that are attached downstream to a hardware that have failed monitoring</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getNetworkMonitorIncidents'> getNetworkMonitorIncidents</a> </span>
            <div class='views-field-body'>Retrieve the status of all of a piece of hardware's network monitoring incidents.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getNetworkMonitors'> getNetworkMonitors</a> </span>
            <div class='views-field-body'>Retrieve information regarding a piece of hardware's network monitors.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getNetworkStatus'> getNetworkStatus</a> </span>
            <div class='views-field-body'>Retrieve the value of a hardware's network status attribute.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getNetworkStatusAttribute'> getNetworkStatusAttribute</a> </span>
            <div class='views-field-body'>Retrieve the hardware's related network status attribute.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getNetworkStorage'> getNetworkStorage</a> </span>
            <div class='views-field-body'>Retrieve information regarding a piece of hardware's associated network storage service account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getNetworkVlans'> getNetworkVlans</a> </span>
            <div class='views-field-body'>Retrieve the network virtual LANs (VLANs) associated with a piece of hardware's network components.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getNextBillingCycleBandwidthAllocation'> getNextBillingCycleBandwidthAllocation</a> </span>
            <div class='views-field-body'>Retrieve a hardware's allotted bandwidth for the next billing cycle (measured in GB).</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getNotesHistory'> getNotesHistory</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getNvRamCapacity'> getNvRamCapacity</a> </span>
            <div class='views-field-body'>Retrieve the amount of non-volatile memory a piece of hardware has, measured in gigabytes.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getNvRamComponentModels'> getNvRamComponentModels</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getObject'> getObject</a> </span>
            <div class='views-field-body'>Retrieve a SoftLayer_Hardware_Server record.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getOpenCancellationTicket'> getOpenCancellationTicket</a> </span>
            <div class='views-field-body'>Retrieve an open ticket requesting cancellation of this server, if one exists.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getOperatingSystem'> getOperatingSystem</a> </span>
            <div class='views-field-body'>Retrieve information regarding a piece of hardware's operating system.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getOperatingSystemReferenceCode'> getOperatingSystemReferenceCode</a> </span>
            <div class='views-field-body'>Retrieve a hardware's operating system software description.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getOutboundBandwidthUsage'> getOutboundBandwidthUsage</a> </span>
            <div class='views-field-body'>Retrieve the sum of all the outbound network traffic data for the last 30 days.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getOutboundPrivateBandwidthUsage'> getOutboundPrivateBandwidthUsage</a> </span>
            <div class='views-field-body'>Retrieve the total private outbound bandwidth for this hardware for the current billing cycle.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getOutboundPublicBandwidthUsage'> getOutboundPublicBandwidthUsage</a> </span>
            <div class='views-field-body'>Retrieve the total public outbound bandwidth for this hardware for the current billing cycle.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getOverBandwidthAllocationFlag'> getOverBandwidthAllocationFlag</a> </span>
            <div class='views-field-body'>Retrieve whether the bandwidth usage for this hardware for the current billing cycle exceeds the allocation.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPMInfo'> getPMInfo</a> </span>
            <div class='views-field-body'>Retrieve a server's hardware state via its internal sensors.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getParentBay'> getParentBay</a> </span>
            <div class='views-field-body'>Retrieve blade Bay</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getParentHardware'> getParentHardware</a> </span>
            <div class='views-field-body'>Retrieve parent Hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPointOfPresenceLocation'> getPointOfPresenceLocation</a> </span>
            <div class='views-field-body'>Retrieve information regarding the Point of Presence (PoP) location in which a piece of hardware resides.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPowerComponents'> getPowerComponents</a> </span>
            <div class='views-field-body'>Retrieve the power components for a hardware object.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPowerSupply'> getPowerSupply</a> </span>
            <div class='views-field-body'>Retrieve a server's power supply.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPrimaryBackendIpAddress'> getPrimaryBackendIpAddress</a> </span>
            <div class='views-field-body'>Retrieve the hardware's primary private IP address.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPrimaryBackendNetworkComponent'> getPrimaryBackendNetworkComponent</a> </span>
            <div class='views-field-body'>Retrieve information regarding the hardware's primary back-end network component.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPrimaryDriveSize'> getPrimaryDriveSize</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPrimaryIpAddress'> getPrimaryIpAddress</a> </span>
            <div class='views-field-body'>Retrieve the hardware's primary public IP address.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPrimaryNetworkComponent'> getPrimaryNetworkComponent</a> </span>
            <div class='views-field-body'>Retrieve information regarding the hardware's primary public network component.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPrivateBandwidthData'> getPrivateBandwidthData</a> </span>
            <div class='views-field-body'>Retrieve a graph of a server's private network usage.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPrivateBandwidthDataSummary'> getPrivateBandwidthDataSummary</a> </span>
            <div class='views-field-body'>Retrieve a server's private bandwidth usage summary</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPrivateBandwidthGraphImage'> getPrivateBandwidthGraphImage</a> </span>
            <div class='views-field-body'>Retrieve a graph of a server's private network usage.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPrivateIpAddress'> getPrivateIpAddress</a> </span>
            <div class='views-field-body'>Retrieve a server's primary private IP address.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPrivateNetworkComponent'> getPrivateNetworkComponent</a> </span>
            <div class='views-field-body'>Retrieve a server's private network component.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPrivateNetworkOnlyFlag'> getPrivateNetworkOnlyFlag</a> </span>
            <div class='views-field-body'>Retrieve whether the hardware only has access to the private network.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPrivateVlan'> getPrivateVlan</a> </span>
            <div class='views-field-body'>Retrieve the backend VLAN for the primary IP address of the server.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPrivateVlanByIpAddress'> getPrivateVlanByIpAddress</a> </span>
            <div class='views-field-body'>Retrieve a backend network VLAN by searching for an IP address.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getProcessorCoreAmount'> getProcessorCoreAmount</a> </span>
            <div class='views-field-body'>Retrieve the total number of processor cores, summed from all processors that are attached to a piece of hardware</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getProcessorPhysicalCoreAmount'> getProcessorPhysicalCoreAmount</a> </span>
            <div class='views-field-body'>Retrieve the total number of physical processor cores, summed from all processors that are attached to a piece of hardware</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getProcessors'> getProcessors</a> </span>
            <div class='views-field-body'>Retrieve information regarding a piece of hardware's processors.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getProjectedOverBandwidthAllocationFlag'> getProjectedOverBandwidthAllocationFlag</a> </span>
            <div class='views-field-body'>Retrieve whether the bandwidth usage for this hardware for the current billing cycle is projected to exceed the allocation.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getProjectedPublicBandwidthUsage'> getProjectedPublicBandwidthUsage</a> </span>
            <div class='views-field-body'>Retrieve the projected public outbound bandwidth for this hardware for the current billing cycle.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getProvisionDate'> getProvisionDate</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPublicBandwidthData'> getPublicBandwidthData</a> </span>
            <div class='views-field-body'>Retrieve a graph of a server's public network usage.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPublicBandwidthDataSummary'> getPublicBandwidthDataSummary</a> </span>
            <div class='views-field-body'>Retrieve a server's public bandwidth usage summary</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPublicBandwidthGraphImage'> getPublicBandwidthGraphImage</a> </span>
            <div class='views-field-body'>Retrieve a graph of a server's public network usage.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPublicBandwidthTotal'> getPublicBandwidthTotal</a> </span>
            <div class='views-field-body'>Retrieve total number of public bytes used by a server over time period specified.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPublicNetworkComponent'> getPublicNetworkComponent</a> </span>
            <div class='views-field-body'>Retrieve a server's public network component.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPublicVlan'> getPublicVlan</a> </span>
            <div class='views-field-body'>Retrieve the frontend VLAN for the primary IP address of the server</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getPublicVlanByHostname'> getPublicVlanByHostname</a> </span>
            <div class='views-field-body'>Retrieve the frontend VLAN by a server's hostname.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getRack'> getRack</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getRaidControllers'> getRaidControllers</a> </span>
            <div class='views-field-body'>Retrieve the RAID controllers contained within a piece of hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getReadyNodeFlag'> getReadyNodeFlag</a> </span>
            <div class='views-field-body'>Retrieve determine if hardware object is vSan Ready Node.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getRecentEvents'> getRecentEvents</a> </span>
            <div class='views-field-body'>Retrieve recent events that impact this hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getRecentRemoteManagementCommands'> getRecentRemoteManagementCommands</a> </span>
            <div class='views-field-body'>Retrieve the last five commands issued to the server's remote management card.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getRegionalInternetRegistry'> getRegionalInternetRegistry</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getRemoteManagement'> getRemoteManagement</a> </span>
            <div class='views-field-body'>Retrieve a server's remote management card.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getRemoteManagementAccounts'> getRemoteManagementAccounts</a> </span>
            <div class='views-field-body'>Retrieve user credentials to issue commands and/or interact with the server's remote management card.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getRemoteManagementComponent'> getRemoteManagementComponent</a> </span>
            <div class='views-field-body'>Retrieve a hardware's associated remote management component. This is normally IPMI.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getRemoteManagementUsers'> getRemoteManagementUsers</a> </span>
            <div class='views-field-body'>Retrieve user(s) who have access to issue commands and/or interact with the server's remote management card.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getResourceConfigurations'> getResourceConfigurations</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getResourceGroupMemberReferences'> getResourceGroupMemberReferences</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getResourceGroupRoles'> getResourceGroupRoles</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getResourceGroups'> getResourceGroups</a> </span>
            <div class='views-field-body'>Retrieve the resource groups in which this hardware is a member.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getReverseDomainRecords'> getReverseDomainRecords</a> </span>
            <div class='views-field-body'>Retrieve the reverse domain records associated with a server.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getRouters'> getRouters</a> </span>
            <div class='views-field-body'>Retrieve a hardware's routers.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getScaleAssets'> getScaleAssets</a> </span>
            <div class='views-field-body'>Retrieve collection of scale assets this hardware corresponds to.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getSecurityScanRequests'> getSecurityScanRequests</a> </span>
            <div class='views-field-body'>Retrieve information regarding a piece of hardware's vulnerability scan requests.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getSensorData'> getSensorData</a> </span>
            <div class='views-field-body'>Retrieve a server's hardware state via its internal sensors.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getSensorDataWithGraphs'> getSensorDataWithGraphs</a> </span>
            <div class='views-field-body'>Retrieve server's temperature and fan speed graphs as well the sensor raw data.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getServerDetails'> getServerDetails</a> </span>
            <div class='views-field-body'>Retrieve a server's hardware components, software, and network components.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getServerFanSpeedGraphs'> getServerFanSpeedGraphs</a> </span>
            <div class='views-field-body'>Retrieve server's fan speed graphs.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getServerPowerState'> getServerPowerState</a> </span>
            <div class='views-field-body'>Retrieves server's power state</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getServerRoom'> getServerRoom</a> </span>
            <div class='views-field-body'>Retrieve information regarding the server room in which the hardware is located.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getServerTemperatureGraphs'> getServerTemperatureGraphs</a> </span>
            <div class='views-field-body'>Retrieve server's temperature graphs</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getServiceProvider'> getServiceProvider</a> </span>
            <div class='views-field-body'>Retrieve information regarding the piece of hardware's service provider.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getSoftwareComponents'> getSoftwareComponents</a> </span>
            <div class='views-field-body'>Retrieve information regarding a piece of hardware's installed software.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getSoftwareGuardExtensionEnabled'> getSoftwareGuardExtensionEnabled</a> </span>
            <div class='views-field-body'>Retrieve determine if hardware object has Software Guard Extension (SGX) enabled.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getSshKeys'> getSshKeys</a> </span>
            <div class='views-field-body'>Retrieve sSH keys to be installed on the server during provisioning or an OS reload.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getStatisticsRemoteManagement'> getStatisticsRemoteManagement</a> </span>
            <div class='views-field-body'>Retrieve a server's remote management card used for statistics.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getStorageNetworkComponents'> getStorageNetworkComponents</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getTagReferences'> getTagReferences</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getTopLevelLocation'> getTopLevelLocation</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getTransactionHistory'> getTransactionHistory</a> </span>
            <div class='views-field-body'>Get transaction history for a piece of hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getUefiBootFlag'> getUefiBootFlag</a> </span>
            <div class='views-field-body'>Retrieve whether to use UEFI boot instead of BIOS.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getUpgradeItemPrices'> getUpgradeItemPrices</a> </span>
            <div class='views-field-body'>Retrieve a list of upgradable items available to a piece of hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getUpgradeRequest'> getUpgradeRequest</a> </span>
            <div class='views-field-body'>Retrieve an account's associated upgrade request object, if any.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getUplinkHardware'> getUplinkHardware</a> </span>
            <div class='views-field-body'>Retrieve the network device connected to a piece of hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getUplinkNetworkComponents'> getUplinkNetworkComponents</a> </span>
            <div class='views-field-body'>Retrieve information regarding the network component that is one level higher than a piece of hardware on the network infrastructure.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getUserData'> getUserData</a> </span>
            <div class='views-field-body'>Retrieve an array containing a single string of custom user data for a hardware order. Max size is 16 kb.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getUsers'> getUsers</a> </span>
            <div class='views-field-body'>Retrieve a list of users that have access to this computing instance.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getValidBlockDeviceTemplateGroups'> getValidBlockDeviceTemplateGroups</a> </span>
            <div class='views-field-body'>Return a list of valid block device template groups based on this host</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getVirtualChassis'> getVirtualChassis</a> </span>
            <div class='views-field-body'>Retrieve information regarding the virtual chassis for a piece of hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getVirtualChassisSiblings'> getVirtualChassisSiblings</a> </span>
            <div class='views-field-body'>Retrieve information regarding the virtual chassis siblings for a piece of hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getVirtualGuests'> getVirtualGuests</a> </span>
            <div class='views-field-body'>Retrieve a hardware server's virtual servers.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getVirtualHost'> getVirtualHost</a> </span>
            <div class='views-field-body'>Retrieve a piece of hardware's virtual host record.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getVirtualLicenses'> getVirtualLicenses</a> </span>
            <div class='views-field-body'>Retrieve information regarding a piece of hardware's virtual software licenses.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getVirtualRack'> getVirtualRack</a> </span>
            <div class='views-field-body'>Retrieve information regarding the bandwidth allotment to which a piece of hardware belongs.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getVirtualRackId'> getVirtualRackId</a> </span>
            <div class='views-field-body'>Retrieve the name of the bandwidth allotment belonging to a piece of hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getVirtualRackName'> getVirtualRackName</a> </span>
            <div class='views-field-body'>Retrieve the name of the bandwidth allotment belonging to a piece of hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getVirtualizationPlatform'> getVirtualizationPlatform</a> </span>
            <div class='views-field-body'>Retrieve a piece of hardware's virtualization platform software.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getWindowsUpdateAvailableUpdates'> getWindowsUpdateAvailableUpdates</a> </span>
            <div class='views-field-body'>Retrieve a list of Windows updates available to a server.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getWindowsUpdateInstalledUpdates'> getWindowsUpdateInstalledUpdates</a> </span>
            <div class='views-field-body'>Retrieve a list of Windows updates installed on a server.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/getWindowsUpdateStatus'> getWindowsUpdateStatus</a> </span>
            <div class='views-field-body'>Retrieve a server's Windows update synchronization status</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/importVirtualHost'> importVirtualHost</a> </span>
            <div class='views-field-body'>attempt to import the host record for the virtualization platform running on a server</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/initiateIderaBareMetalRestore'> initiateIderaBareMetalRestore</a> </span>
            <div class='views-field-body'>Initiate an Idera bare metal restore for the server tied to an Idera Server Backup</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/initiateR1SoftBareMetalRestore'> initiateR1SoftBareMetalRestore</a> </span>
            <div class='views-field-body'>Initiate an R1Soft bare metal restore for the server tied to an R1Soft CDP Server</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/isBackendPingable'> isBackendPingable</a> </span>
            <div class='views-field-body'>Verifies if a server's backend ip address is pingable.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/isPingable'> isPingable</a> </span>
            <div class='views-field-body'>Verifies if server is pingable.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/isWindowsServer'> isWindowsServer</a> </span>
            <div class='views-field-body'>Determine if a server runs the Microsoft Windows operating system.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/massFirmwareReflash'> massFirmwareReflash</a> </span>
            <div class='views-field-body'>Runs firmware reflashes on the servers components.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/massFirmwareUpdate'> massFirmwareUpdate</a> </span>
            <div class='views-field-body'>Runs firmware updates on the servers components.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/massHyperThreadingUpdate'> massHyperThreadingUpdate</a> </span>
            <div class='views-field-body'>Runs firmware reflashes on the servers components.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/massReloadOperatingSystem'> massReloadOperatingSystem</a> </span>
            <div class='views-field-body'>Reloads operating system configuration on a set of hardware Ids.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/massSparePool'> massSparePool</a> </span>
            <div class='views-field-body'>Allows multiple servers to be added to or removed from the spare pool.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/ping'> ping</a> </span>
            <div class='views-field-body'>Issues ping command.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/populateServerRam'> populateServerRam</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/powerCycle'> powerCycle</a> </span>
            <div class='views-field-body'>Issues power cycle to server.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/powerOff'> powerOff</a> </span>
            <div class='views-field-body'>Power off server.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/powerOn'> powerOn</a> </span>
            <div class='views-field-body'>Power on server.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/rebootDefault'> rebootDefault</a> </span>
            <div class='views-field-body'>Reboot the server via the default method.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/rebootHard'> rebootHard</a> </span>
            <div class='views-field-body'>Reboot the server via "hard" reboot.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/rebootSoft'> rebootSoft</a> </span>
            <div class='views-field-body'>Reboot the server via gracefully (soft reboot).</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/reloadCurrentOperatingSystemConfiguration'> reloadCurrentOperatingSystemConfiguration</a> </span>
            <div class='views-field-body'>Reloads current operating system configuration.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/reloadOperatingSystem'> reloadOperatingSystem</a> </span>
            <div class='views-field-body'>Reloads operating system configuration.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/removeAccessToNetworkStorage'> removeAccessToNetworkStorage</a> </span>
            <div class='views-field-body'>Remove access to a SoftLayer_Network_Storage volume from this device. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/removeAccessToNetworkStorageList'> removeAccessToNetworkStorageList</a> </span>
            <div class='views-field-body'>Remove access to multiple SoftLayer_Network_Storage volumes from this device. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/removeTags'> removeTags</a> </span>
            <div class='views-field-body'>Remove a tag reference</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/runPassmarkCertificationBenchmark'> runPassmarkCertificationBenchmark</a> </span>
            <div class='views-field-body'>Runs a hardware stress test on the server to obtain a Passmark Certification.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/setOperatingSystemPassword'> setOperatingSystemPassword</a> </span>
            <div class='views-field-body'>Changes the password stored in our system for a servers' Operating System</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/setPrivateNetworkInterfaceSpeed'> setPrivateNetworkInterfaceSpeed</a> </span>
            <div class='views-field-body'>Set the speed and redundancy configuration of a server's private network interface.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/setPublicNetworkInterfaceSpeed'> setPublicNetworkInterfaceSpeed</a> </span>
            <div class='views-field-body'>Set the speed and redundancy configuration of a server's public network interface.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/setTags'> setTags</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/setUserMetadata'> setUserMetadata</a> </span>
            <div class='views-field-body'>Sets the server's user metadata value.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/shutdownPrivatePort'> shutdownPrivatePort</a> </span>
            <div class='views-field-body'>Disconnect a server's private network interface.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/shutdownPublicPort'> shutdownPublicPort</a> </span>
            <div class='views-field-body'>Disconnect a server's public network interface.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/sparePool'> sparePool</a> </span>
            <div class='views-field-body'>Allows servers to be added to or removed from the spare pool.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/toggleManagementInterface'> toggleManagementInterface</a> </span>
            <div class='views-field-body'>Toggle the IPMI interface on and off.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/updateIpmiPassword'> updateIpmiPassword</a> </span>
            <div class='views-field-body'>Update the root IPMI user password </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Hardware_Server/validatePartitionsForOperatingSystem'> validatePartitionsForOperatingSystem</a> </span>
            <div class='views-field-body'>Validates a collection of partitions for an operating system</div>
        </div>
        </div>
</div>

