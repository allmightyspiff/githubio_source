---
title: "SoftLayer_Network_Storage"
description: "The SoftLayer_Network_Storage data type contains general information regarding a Storage product such as account id, acc... "
layout: "datatype"
tags:
    - "datatype"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Storage"
---

# SoftLayer_Network_Storage
<div id='service-datatype'>
    <ul id='sldn-reference-tabs'>
    <li id='service'> <a href='/reference/services/SoftLayer_Network_Storage' >Service</a></li>    <li id='datatype'> <a href='/reference/datatypes/SoftLayer_Network_Storage' >Datatype</a></li>
    </ul>
</div>

## Description 
The SoftLayer_Network_Storage data type contains general information regarding a Storage product such as account id, access username and password, the Storage product type, and the server the Storage service is associated with. Currently, only EVault backup storage has an associated server. 


### associatedMethods

*  [SoftLayer_Network_Storage::getByUsername](/reference/services/SoftLayer_Network_Storage/getByUsername )
*  [SoftLayer_Network_Storage::getObject](/reference/services/SoftLayer_Network_Storage/getObject )
*  [SoftLayer_Account::getNetworkStorage](/reference/services/SoftLayer_Account/getNetworkStorage )
*  [SoftLayer_Account::getNasNetworkStorage](/reference/services/SoftLayer_Account/getNasNetworkStorage )
*  [SoftLayer_Account::getLockboxNetworkStorage](/reference/services/SoftLayer_Account/getLockboxNetworkStorage )
*  [SoftLayer_Account::getIscsiNetworkStorage](/reference/services/SoftLayer_Account/getIscsiNetworkStorage )
*  [SoftLayer_Account::getEvaultNetworkStorage](/reference/services/SoftLayer_Account/getEvaultNetworkStorage )
*  [SoftLayer_Account::getHubNetworkStorage](/reference/services/SoftLayer_Account/getHubNetworkStorage )
*  [SoftLayer_Hardware::getEvaultNetworkStorage](/reference/services/SoftLayer_Hardware/getEvaultNetworkStorage )



### seeAlso

* [SoftLayer_Network_Storage_Nas](/reference/datatypes/SoftLayer_Network_Storage_Nas )


* [SoftLayer_Network_Storage_Iscsi](/reference/services/SoftLayer_Network_Storage_Iscsi )


* [SoftLayer_Network_Storage_Hub](/reference/datatypes/SoftLayer_Network_Storage_Hub )


* [SoftLayer_Network_Storage_Backup_Evault](/reference/services/SoftLayer_Network_Storage_Backup_Evault )




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
            <div class='views-field-body'>The internal identifier of the SoftLayer customer account that a Storage account belongs to.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#capacityGb" name=capacityGb>capacityGb</a>
            </span>
            <div class='views-field-body'>A Storage account's capacity, measured in gigabytes.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#createDate" name=createDate>createDate</a>
            </span>
            <div class='views-field-body'>The date a network storage volume was created. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>dateTime</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#guestId" name=guestId>guestId</a>
            </span>
            <div class='views-field-body'>The unique identification number of the guest associated with a Storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareId" name=hardwareId>hardwareId</a>
            </span>
            <div class='views-field-body'>The server that is associated with a Storage service.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hostId" name=hostId>hostId</a>
            </span>
            <div class='views-field-body'>The unique identification number of the host associated with a Storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#id" name=id>id</a>
            </span>
            <div class='views-field-body'>A Storage account's unique identifier. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#nasType" name=nasType>nasType</a>
            </span>
            <div class='views-field-body'>A Storage account's type. Valid examples are "NAS", "LOCKBOX", "ISCSI", "EVAULT", and "HUB".  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#notes" name=notes>notes</a>
            </span>
            <div class='views-field-body'>Public notes related to a Storage volume.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#password" name=password>password</a>
            </span>
            <div class='views-field-body'>The password used to access a non-EVault Storage volume. This password is used to register the EVault server agent with the vault backup system.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#serviceProviderId" name=serviceProviderId>serviceProviderId</a>
            </span>
            <div class='views-field-body'>Service Provider ID  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#storageTypeId" name=storageTypeId>storageTypeId</a>
            </span>
            <div class='views-field-body'>A storage object's type.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#upgradableFlag" name=upgradableFlag>upgradableFlag</a>
            </span>
            <div class='views-field-body'>This flag indicates whether this storage type is upgradable or not.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#username" name=username>username</a>
            </span>
            <div class='views-field-body'>The username used to access a non-EVault Storage volume. This username is used to register the EVault server agent with the vault backup system.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
            </div>
        <div id="relationalProperties"  class="prop-content" >
        <h2>Relational</h2>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#account" name=account>account</a>
            </span>
            <div class='views-field-body'>The account that a Storage services belongs to. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account'>SoftLayer_Account </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#accountPassword" name=accountPassword>accountPassword</a>
            </span>
            <div class='views-field-body'>Other usernames and passwords associated with a Storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Password'>SoftLayer_Account_Password </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeTransactions" name=activeTransactions>activeTransactions</a>
            </span>
            <div class='views-field-body'>The currently active transactions on a network storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Provisioning_Version1_Transaction'>SoftLayer_Provisioning_Version1_Transaction[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedHardware" name=allowedHardware>allowedHardware</a>
            </span>
            <div class='views-field-body'>The SoftLayer_Hardware objects which are allowed access to this storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedIpAddresses" name=allowedIpAddresses>allowedIpAddresses</a>
            </span>
            <div class='views-field-body'>The SoftLayer_Network_Subnet_IpAddress objects which are allowed access to this storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet_IpAddress'>SoftLayer_Network_Subnet_IpAddress[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedReplicationHardware" name=allowedReplicationHardware>allowedReplicationHardware</a>
            </span>
            <div class='views-field-body'>The SoftLayer_Hardware objects which are allowed access to this storage volume's Replicant. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedReplicationIpAddresses" name=allowedReplicationIpAddresses>allowedReplicationIpAddresses</a>
            </span>
            <div class='views-field-body'>The SoftLayer_Network_Subnet_IpAddress objects which are allowed access to this storage volume's Replicant. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet_IpAddress'>SoftLayer_Network_Subnet_IpAddress[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedReplicationSubnets" name=allowedReplicationSubnets>allowedReplicationSubnets</a>
            </span>
            <div class='views-field-body'>The SoftLayer_Network_Subnet objects which are allowed access to this storage volume's Replicant. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet'>SoftLayer_Network_Subnet[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedReplicationVirtualGuests" name=allowedReplicationVirtualGuests>allowedReplicationVirtualGuests</a>
            </span>
            <div class='views-field-body'>The SoftLayer_Hardware objects which are allowed access to this storage volume's Replicant. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedSubnets" name=allowedSubnets>allowedSubnets</a>
            </span>
            <div class='views-field-body'>The SoftLayer_Network_Subnet objects which are allowed access to this storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet'>SoftLayer_Network_Subnet[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedVirtualGuests" name=allowedVirtualGuests>allowedVirtualGuests</a>
            </span>
            <div class='views-field-body'>The SoftLayer_Virtual_Guest objects which are allowed access to this storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#billingItem" name=billingItem>billingItem</a>
            </span>
            <div class='views-field-body'>The current billing item for a Storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item'>SoftLayer_Billing_Item </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#billingItemCategory" name=billingItemCategory>billingItemCategory</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Product_Item_Category'>SoftLayer_Product_Item_Category </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#bytesUsed" name=bytesUsed>bytesUsed</a>
            </span>
            <div class='views-field-body'>The amount of space used by the volume, in bytes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#creationScheduleId" name=creationScheduleId>creationScheduleId</a>
            </span>
            <div class='views-field-body'>The schedule id which was executed to create a snapshot. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#credentials" name=credentials>credentials</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage_Credential'>SoftLayer_Network_Storage_Credential[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#dailySchedule" name=dailySchedule>dailySchedule</a>
            </span>
            <div class='views-field-body'>The Daily Schedule which is associated with this network storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage_Schedule'>SoftLayer_Network_Storage_Schedule </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#events" name=events>events</a>
            </span>
            <div class='views-field-body'>The events which have taken place on a network storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage_Event'>SoftLayer_Network_Storage_Event[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#fileNetworkMountAddress" name=fileNetworkMountAddress>fileNetworkMountAddress</a>
            </span>
            <div class='views-field-body'>Retrieves the NFS Network Mount Address Name for a given File Storage Volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardware" name=hardware>hardware</a>
            </span>
            <div class='views-field-body'>When applicable, the hardware associated with a Storage service. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hasEncryptionAtRest" name=hasEncryptionAtRest>hasEncryptionAtRest</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hourlySchedule" name=hourlySchedule>hourlySchedule</a>
            </span>
            <div class='views-field-body'>The Hourly Schedule which is associated with this network storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage_Schedule'>SoftLayer_Network_Storage_Schedule </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#intervalSchedule" name=intervalSchedule>intervalSchedule</a>
            </span>
            <div class='views-field-body'>The Interval Schedule which is associated with this network storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage_Schedule'>SoftLayer_Network_Storage_Schedule </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#iops" name=iops>iops</a>
            </span>
            <div class='views-field-body'>The maximum number of IOPs selected for this volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#isReadyForSnapshot" name=isReadyForSnapshot>isReadyForSnapshot</a>
            </span>
            <div class='views-field-body'>Determines whether a volume is ready to order snapshot space, or, if snapshot space is already available, to assign a snapshot schedule, or to take a manual snapshot. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#isReadyToMount" name=isReadyToMount>isReadyToMount</a>
            </span>
            <div class='views-field-body'>Determines whether a volume is ready to have Hosts authorized to access it. This does not indicate whether another operation may be blocking, please refer to this volume's volumeStatus property for details. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#iscsiLuns" name=iscsiLuns>iscsiLuns</a>
            </span>
            <div class='views-field-body'>Relationship between a container volume and iSCSI LUNs. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#iscsiTargetIpAddresses" name=iscsiTargetIpAddresses>iscsiTargetIpAddresses</a>
            </span>
            <div class='views-field-body'>Returns the target IP addresses of an iSCSI volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>array of strings</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lunId" name=lunId>lunId</a>
            </span>
            <div class='views-field-body'>The ID of the LUN volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#manualSnapshots" name=manualSnapshots>manualSnapshots</a>
            </span>
            <div class='views-field-body'>The manually-created snapshots associated with this SoftLayer_Network_Storage volume. Does not support pagination by result limit and offset. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#metricTrackingObject" name=metricTrackingObject>metricTrackingObject</a>
            </span>
            <div class='views-field-body'>A network storage volume's metric tracking object. This object records all periodic polled data available to this volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Metric_Tracking_Object'>SoftLayer_Metric_Tracking_Object </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#mountableFlag" name=mountableFlag>mountableFlag</a>
            </span>
            <div class='views-field-body'>Whether or not a network storage volume may be mounted. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#moveAndSplitStatus" name=moveAndSplitStatus>moveAndSplitStatus</a>
            </span>
            <div class='views-field-body'>The current status of split or move operation as a part of volume duplication. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#notificationSubscribers" name=notificationSubscribers>notificationSubscribers</a>
            </span>
            <div class='views-field-body'>The subscribers that will be notified for usage amount warnings and overages. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Notification_User_Subscriber'>SoftLayer_Notification_User_Subscriber[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#originalSnapshotName" name=originalSnapshotName>originalSnapshotName</a>
            </span>
            <div class='views-field-body'>The name of the snapshot that this volume was duplicated from. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#originalVolumeName" name=originalVolumeName>originalVolumeName</a>
            </span>
            <div class='views-field-body'>The name of the volume that this volume was duplicated from. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#originalVolumeSize" name=originalVolumeSize>originalVolumeSize</a>
            </span>
            <div class='views-field-body'>The size (in GB) of the volume or LUN before any size expansion, or of the volume (before any possible size expansion) from which the duplicate volume or LUN was created. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#osType" name=osType>osType</a>
            </span>
            <div class='views-field-body'>A volume's configured SoftLayer_Network_Storage_Iscsi_OS_Type. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage_Iscsi_OS_Type'>SoftLayer_Network_Storage_Iscsi_OS_Type </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#osTypeId" name=osTypeId>osTypeId</a>
            </span>
            <div class='views-field-body'>A volume's configured SoftLayer_Network_Storage_Iscsi_OS_Type ID. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#parentPartnerships" name=parentPartnerships>parentPartnerships</a>
            </span>
            <div class='views-field-body'>The volumes or snapshots partnered with a network storage volume in a parental role. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage_Partnership'>SoftLayer_Network_Storage_Partnership[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#parentVolume" name=parentVolume>parentVolume</a>
            </span>
            <div class='views-field-body'>The parent volume of a volume in a complex storage relationship. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#partnerships" name=partnerships>partnerships</a>
            </span>
            <div class='views-field-body'>The volumes or snapshots partnered with a network storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage_Partnership'>SoftLayer_Network_Storage_Partnership[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#permissionsGroups" name=permissionsGroups>permissionsGroups</a>
            </span>
            <div class='views-field-body'>All permissions group(s) this volume is in. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage_Group'>SoftLayer_Network_Storage_Group[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#properties" name=properties>properties</a>
            </span>
            <div class='views-field-body'>The properties used to provide additional details about a network storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage_Property'>SoftLayer_Network_Storage_Property[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#provisionedIops" name=provisionedIops>provisionedIops</a>
            </span>
            <div class='views-field-body'>The number of IOPs provisioned for this volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#replicatingLuns" name=replicatingLuns>replicatingLuns</a>
            </span>
            <div class='views-field-body'>The iSCSI LUN volumes being replicated by this network storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#replicatingVolume" name=replicatingVolume>replicatingVolume</a>
            </span>
            <div class='views-field-body'>The network storage volume being replicated by a volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#replicationEvents" name=replicationEvents>replicationEvents</a>
            </span>
            <div class='views-field-body'>The volume replication events. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage_Event'>SoftLayer_Network_Storage_Event[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#replicationPartners" name=replicationPartners>replicationPartners</a>
            </span>
            <div class='views-field-body'>The network storage volumes configured to be replicants of a volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#replicationSchedule" name=replicationSchedule>replicationSchedule</a>
            </span>
            <div class='views-field-body'>The Replication Schedule associated with a network storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage_Schedule'>SoftLayer_Network_Storage_Schedule </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#replicationStatus" name=replicationStatus>replicationStatus</a>
            </span>
            <div class='views-field-body'>The current replication status of a network storage volume. Indicates Failover or Failback status. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#schedules" name=schedules>schedules</a>
            </span>
            <div class='views-field-body'>The schedules which are associated with a network storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage_Schedule'>SoftLayer_Network_Storage_Schedule[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#serviceResource" name=serviceResource>serviceResource</a>
            </span>
            <div class='views-field-body'>The network resource a Storage service is connected to. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Service_Resource'>SoftLayer_Network_Service_Resource </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#serviceResourceBackendIpAddress" name=serviceResourceBackendIpAddress>serviceResourceBackendIpAddress</a>
            </span>
            <div class='views-field-body'>The IP address of a Storage resource. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#serviceResourceName" name=serviceResourceName>serviceResourceName</a>
            </span>
            <div class='views-field-body'>The name of a Storage's network resource. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#snapshotCapacityGb" name=snapshotCapacityGb>snapshotCapacityGb</a>
            </span>
            <div class='views-field-body'>A volume's configured snapshot space size. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#snapshotCreationTimestamp" name=snapshotCreationTimestamp>snapshotCreationTimestamp</a>
            </span>
            <div class='views-field-body'>The creation timestamp of the snapshot on the storage platform. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#snapshotDeletionThresholdPercentage" name=snapshotDeletionThresholdPercentage>snapshotDeletionThresholdPercentage</a>
            </span>
            <div class='views-field-body'>The percentage of used snapshot space after which to delete automated snapshots. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#snapshotSizeBytes" name=snapshotSizeBytes>snapshotSizeBytes</a>
            </span>
            <div class='views-field-body'>The snapshot size in bytes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#snapshotSpaceAvailable" name=snapshotSpaceAvailable>snapshotSpaceAvailable</a>
            </span>
            <div class='views-field-body'>A volume's available snapshot reservation space. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#snapshots" name=snapshots>snapshots</a>
            </span>
            <div class='views-field-body'>The snapshots associated with this SoftLayer_Network_Storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#staasVersion" name=staasVersion>staasVersion</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#storageGroups" name=storageGroups>storageGroups</a>
            </span>
            <div class='views-field-body'>The network storage groups this volume is attached to. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage_Group'>SoftLayer_Network_Storage_Group[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#storageTierLevel" name=storageTierLevel>storageTierLevel</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#storageType" name=storageType>storageType</a>
            </span>
            <div class='views-field-body'>A description of the Storage object. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage_Type'>SoftLayer_Network_Storage_Type </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#totalBytesUsed" name=totalBytesUsed>totalBytesUsed</a>
            </span>
            <div class='views-field-body'>The amount of space used by the volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#totalScheduleSnapshotRetentionCount" name=totalScheduleSnapshotRetentionCount>totalScheduleSnapshotRetentionCount</a>
            </span>
            <div class='views-field-body'>The total snapshot retention count of all schedules on this network storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsigned integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#usageNotification" name=usageNotification>usageNotification</a>
            </span>
            <div class='views-field-body'>The usage notification for SL Storage services. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Notification'>SoftLayer_Notification </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#vendorName" name=vendorName>vendorName</a>
            </span>
            <div class='views-field-body'>The type of network storage service. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuest" name=virtualGuest>virtualGuest</a>
            </span>
            <div class='views-field-body'>When applicable, the virtual guest associated with a Storage service. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#volumeHistory" name=volumeHistory>volumeHistory</a>
            </span>
            <div class='views-field-body'>The username and password history for a Storage service. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage_History'>SoftLayer_Network_Storage_History[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#volumeStatus" name=volumeStatus>volumeStatus</a>
            </span>
            <div class='views-field-body'>The current status of a network storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#webccAccount" name=webccAccount>webccAccount</a>
            </span>
            <div class='views-field-body'>The account username and password for the EVault webCC interface. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Password'>SoftLayer_Account_Password </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#weeklySchedule" name=weeklySchedule>weeklySchedule</a>
            </span>
            <div class='views-field-body'>The Weekly Schedule which is associated with this network storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage_Schedule'>SoftLayer_Network_Storage_Schedule </a></p>
            </div>
        </div>
                <h2>Count</h2>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeTransactionCount" name=activeTransactionCount>activeTransactionCount</a>
            </span>
            <div class='views-field-body'>A count of the currently active transactions on a network storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedHardwareCount" name=allowedHardwareCount>allowedHardwareCount</a>
            </span>
            <div class='views-field-body'>A count of the SoftLayer_Hardware objects which are allowed access to this storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedIpAddressCount" name=allowedIpAddressCount>allowedIpAddressCount</a>
            </span>
            <div class='views-field-body'>A count of the SoftLayer_Network_Subnet_IpAddress objects which are allowed access to this storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedReplicationHardwareCount" name=allowedReplicationHardwareCount>allowedReplicationHardwareCount</a>
            </span>
            <div class='views-field-body'>A count of the SoftLayer_Hardware objects which are allowed access to this storage volume's Replicant. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedReplicationIpAddressCount" name=allowedReplicationIpAddressCount>allowedReplicationIpAddressCount</a>
            </span>
            <div class='views-field-body'>A count of the SoftLayer_Network_Subnet_IpAddress objects which are allowed access to this storage volume's Replicant. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedReplicationSubnetCount" name=allowedReplicationSubnetCount>allowedReplicationSubnetCount</a>
            </span>
            <div class='views-field-body'>A count of the SoftLayer_Network_Subnet objects which are allowed access to this storage volume's Replicant. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedReplicationVirtualGuestCount" name=allowedReplicationVirtualGuestCount>allowedReplicationVirtualGuestCount</a>
            </span>
            <div class='views-field-body'>A count of the SoftLayer_Hardware objects which are allowed access to this storage volume's Replicant. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedSubnetCount" name=allowedSubnetCount>allowedSubnetCount</a>
            </span>
            <div class='views-field-body'>A count of the SoftLayer_Network_Subnet objects which are allowed access to this storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedVirtualGuestCount" name=allowedVirtualGuestCount>allowedVirtualGuestCount</a>
            </span>
            <div class='views-field-body'>A count of the SoftLayer_Virtual_Guest objects which are allowed access to this storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#credentialCount" name=credentialCount>credentialCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#eventCount" name=eventCount>eventCount</a>
            </span>
            <div class='views-field-body'>A count of the events which have taken place on a network storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#iscsiLunCount" name=iscsiLunCount>iscsiLunCount</a>
            </span>
            <div class='views-field-body'>A count of relationship between a container volume and iSCSI LUNs. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#iscsiTargetIpAddressCount" name=iscsiTargetIpAddressCount>iscsiTargetIpAddressCount</a>
            </span>
            <div class='views-field-body'>A count of returns the target IP addresses of an iSCSI volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#manualSnapshotCount" name=manualSnapshotCount>manualSnapshotCount</a>
            </span>
            <div class='views-field-body'>A count of the manually-created snapshots associated with this SoftLayer_Network_Storage volume. Does not support pagination by result limit and offset. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#notificationSubscriberCount" name=notificationSubscriberCount>notificationSubscriberCount</a>
            </span>
            <div class='views-field-body'>A count of the subscribers that will be notified for usage amount warnings and overages. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#parentPartnershipCount" name=parentPartnershipCount>parentPartnershipCount</a>
            </span>
            <div class='views-field-body'>A count of the volumes or snapshots partnered with a network storage volume in a parental role. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#partnershipCount" name=partnershipCount>partnershipCount</a>
            </span>
            <div class='views-field-body'>A count of the volumes or snapshots partnered with a network storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#permissionsGroupCount" name=permissionsGroupCount>permissionsGroupCount</a>
            </span>
            <div class='views-field-body'>A count of all permissions group(s) this volume is in. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#propertyCount" name=propertyCount>propertyCount</a>
            </span>
            <div class='views-field-body'>A count of the properties used to provide additional details about a network storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#replicatingLunCount" name=replicatingLunCount>replicatingLunCount</a>
            </span>
            <div class='views-field-body'>A count of the iSCSI LUN volumes being replicated by this network storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#replicationEventCount" name=replicationEventCount>replicationEventCount</a>
            </span>
            <div class='views-field-body'>A count of the volume replication events. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#replicationPartnerCount" name=replicationPartnerCount>replicationPartnerCount</a>
            </span>
            <div class='views-field-body'>A count of the network storage volumes configured to be replicants of a volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#scheduleCount" name=scheduleCount>scheduleCount</a>
            </span>
            <div class='views-field-body'>A count of the schedules which are associated with a network storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#snapshotCount" name=snapshotCount>snapshotCount</a>
            </span>
            <div class='views-field-body'>A count of the snapshots associated with this SoftLayer_Network_Storage volume. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#storageGroupCount" name=storageGroupCount>storageGroupCount</a>
            </span>
            <div class='views-field-body'>A count of the network storage groups this volume is attached to. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#volumeHistoryCount" name=volumeHistoryCount>volumeHistoryCount</a>
            </span>
            <div class='views-field-body'>A count of the username and password history for a Storage service. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
            </div>
</div>


