---
title: "getHosts"
description: "Retrieve the hosts in the load balancing pool for a global load balancer account."
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_LoadBalancer_Global_Account"
---
# SoftLayer_Network_LoadBalancer_Global_Account::getHosts
## Overview 
Retrieve the hosts in the load balancing pool for a global load balancer account.

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* SoftLayer_Network_LoadBalancer_Global_AccountInitParameters
* authenticate

### Optional Headers
* SoftLayer_Network_LoadBalancer_Global_AccountObjectMask
* SoftLayer_Network_LoadBalancer_Global_AccountObjectFilter
* resultLimit
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Network_LoadBalancer_Global_Host'>SoftLayer_Network_LoadBalancer_Global_Host[] </a>
