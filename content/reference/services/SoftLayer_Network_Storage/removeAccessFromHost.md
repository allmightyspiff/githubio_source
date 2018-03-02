---
title: "removeAccessFromHost"
description: "This method is used to modify the access control list for this Storage volume.  The [[SoftLayer_Hardware|SoftLayer_Virtu... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Storage"
---
# SoftLayer_Network_Storage::removeAccessFromHost
## Overview 
This method is used to modify the access control list for this Storage volume.  The [[SoftLayer_Hardware|SoftLayer_Virtual_Guest|SoftLayer_Network_Subnet|SoftLayer_Network_Subnet_IpAddress]] objects which have been allowed access to this storage will be listed in the [[allowedHardware|allowedVirtualGuests|allowedSubnets|allowedIpAddresses]] property of this storage volume. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|typeClassName| string| The type of class name, among: 'SoftLayer_Hardware', 'SoftLayer_Virtual_Guest', 'SoftLayer_Network_Subnet', 'SoftLayer_Network_Subnet_IpAddress'.|
|hostId| integer| |


### Required Headers
* authenticate
* SoftLayer_Network_StorageInitParameters

### Optional Headers
* SoftLayer_Network_StorageObjectMask
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Network_Storage_Allowed_Host'>SoftLayer_Network_Storage_Allowed_Host </a>
