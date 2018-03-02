---
title: "createReverseDomainRecords"
description: "Create the default PTR records for this subnet"
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Subnet"
---
# SoftLayer_Network_Subnet::createReverseDomainRecords
## Overview 
Create the default PTR records for this subnet 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* authenticate
* SoftLayer_Network_SubnetInitParameters

### Optional Headers
* SoftLayer_Network_SubnetObjectMask
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Dns_Domain_Reverse'>SoftLayer_Dns_Domain_Reverse </a>


### associatedMethods

*  [SoftLayer_Network_Vlan::getReverseDomainRecords](/reference/services/SoftLayer_Network_Vlan/getReverseDomainRecords )
