---
title: "reconnectCompute"
description: "Takes the original disconnected lockdown event ID, and an optional reconnect date. If no reconnect date is passed with t... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Account"
classes:
    - "SoftLayer_Account_Lockdown_Request"
---
# SoftLayer_Account_Lockdown_Request::reconnectCompute
## Overview 
Takes the original disconnected lockdown event ID, and an optional reconnect date. If no reconnect date is passed with the API call, the account reconnection will happen immediately. Otherwise, the account reconnection will happen on the date given. The associated lockdown event will be unlocked and closed at that time. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|reconnectDate| string| |


### Required Headers
* authenticate
* SoftLayer_Account_Lockdown_RequestInitParameters

### Optional Headers

### Return Values
integer
