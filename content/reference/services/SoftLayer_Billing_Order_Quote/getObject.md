---
title: "getObject"
description: "getObject retrieves the SoftLayer_Billing_Order_Quote object whose ID number corresponds to the ID number of the init pa... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Billing"
classes:
    - "SoftLayer_Billing_Order_Quote"
---
# SoftLayer_Billing_Order_Quote::getObject
## Overview 
getObject retrieves the SoftLayer_Billing_Order_Quote object whose ID number corresponds to the ID number of the init parameter passed to the SoftLayer_Billing_Order_Quote service. You can only retrieve quotes that are assigned to your portal user's account. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* SoftLayer_Billing_Order_QuoteInitParameters
* authenticate

### Optional Headers
* SoftLayer_Billing_Order_QuoteObjectMask
* SoftLayer_Billing_Order_QuoteObjectFilter
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Billing_Order_Quote'>SoftLayer_Billing_Order_Quote </a>
