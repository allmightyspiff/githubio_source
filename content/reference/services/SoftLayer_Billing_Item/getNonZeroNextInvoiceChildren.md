---
title: "getNonZeroNextInvoiceChildren"
description: "Retrieve a Billing Item's associated child billing items, excluding ALL items with a $0.00 recurring fee."
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Billing"
classes:
    - "SoftLayer_Billing_Item"
---
# SoftLayer_Billing_Item::getNonZeroNextInvoiceChildren
## Overview 
Retrieve a Billing Item's associated child billing items, excluding ALL items with a $0.00 recurring fee.

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* SoftLayer_Billing_ItemInitParameters
* authenticate

### Optional Headers
* SoftLayer_Billing_ItemObjectMask
* SoftLayer_Billing_ItemObjectFilter
* resultLimit
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Billing_Item'>SoftLayer_Billing_Item[] </a>
