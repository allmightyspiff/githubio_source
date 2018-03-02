---
title: "getExecutiveSummaryPdf"
description: "This method will return a PDF of the specified report, with the specified period within the start and end dates. The pdf... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Account"
classes:
    - "SoftLayer_Account"
---
# SoftLayer_Account::getExecutiveSummaryPdf
## Overview 
This method will return a PDF of the specified report, with the specified period within the start and end dates. The pdfType must be one of 'snapshot', or 'historical'. Possible historicalType parameters are 'monthly', 'yearly', and 'quarterly'. Start and end dates should be in ISO 8601 date format. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|pdfType| string| type of PDF report: snapshot, historical|
|historicalType| string| type of historical report: monthly, yearly, quarterly|
|startDate| string| start date of the historical report|
|endDate| string| end date of the historical report|


### Required Headers
* authenticate

### Optional Headers

### Return Values
binary data
