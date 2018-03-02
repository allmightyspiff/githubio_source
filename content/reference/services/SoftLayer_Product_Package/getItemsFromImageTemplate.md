---
title: "getItemsFromImageTemplate"
description: "Return a collection of [[SoftLayer_Product_Item]] objects from a [[SoftLayer_Virtual_Guest_Block_Device_Template_Group]]... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Product"
classes:
    - "SoftLayer_Product_Package"
---
# SoftLayer_Product_Package::getItemsFromImageTemplate
## Overview 
Return a collection of [[SoftLayer_Product_Item]] objects from a [[SoftLayer_Virtual_Guest_Block_Device_Template_Group]] object

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|imageTemplate| <a href='/reference/datatypes/SoftLayer_Virtual_Guest_Block_Device_Template_Group'>SoftLayer_Virtual_Guest_Block_Device_Template_Group </a>| The image template that the items will be returned for.|


### Required Headers
* authenticate
* SoftLayer_Product_PackageInitParameters

### Optional Headers
* SoftLayer_Product_PackageObjectMask
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Product_Item'>SoftLayer_Product_Item[] </a>
