---
title: "SoftLayer_Software_Component_Security_SafeNet"
description: "This object specifies a specific Software Component:  A SafeNet instance. SafeNet installations have custom configuratio... "
layout: "datatype"
tags:
    - "datatype"
    - "sldn"
    - "Software"
classes:
    - "SoftLayer_Software_Component_Security_SafeNet"
---

# SoftLayer_Software_Component_Security_SafeNet
<div id='service-datatype'>
    <ul id='sldn-reference-tabs'>
        <li id='datatype'> <a href='/reference/datatypes/SoftLayer_Software_Component_Security_SafeNet' >Datatype</a></li>
    </ul>
</div>

## Description 
This object specifies a specific Software Component:  A SafeNet instance. SafeNet installations have custom configurations for password requirements. 



### seeAlso

* [SoftLayer_Software_Component](/reference/services/SoftLayer_Software_Component )




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
                <a href="#hardwareId" name=hardwareId>hardwareId</a>
            </span>
            <div class='views-field-body'>Hardware Identification Number for the server this Software Component is installed upon. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#id" name=id>id</a>
            </span>
            <div class='views-field-body'>An ID number identifying this Software Component (Software Installation) </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#manufacturerActivationCode" name=manufacturerActivationCode>manufacturerActivationCode</a>
            </span>
            <div class='views-field-body'>The manufacturer code that is needed to activate a license. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#manufacturerLicenseInstance" name=manufacturerLicenseInstance>manufacturerLicenseInstance</a>
            </span>
            <div class='views-field-body'>A license key for this specific installation of software, if it is needed. </div>
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
                <a href="#averageInstallationDuration" name=averageInstallationDuration>averageInstallationDuration</a>
            </span>
            <div class='views-field-body'>The average amount of time that a software component takes to install. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsigned long</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#billingItem" name=billingItem>billingItem</a>
            </span>
            <div class='views-field-body'>The billing item for a software component. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item'>SoftLayer_Billing_Item </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardware" name=hardware>hardware</a>
            </span>
            <div class='views-field-body'>The hardware this Software Component is installed upon. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#passwordHistory" name=passwordHistory>passwordHistory</a>
            </span>
            <div class='views-field-body'>History Records for Software Passwords. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Software_Component_Password_History'>SoftLayer_Software_Component_Password_History[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#passwords" name=passwords>passwords</a>
            </span>
            <div class='views-field-body'>Username/Password pairs used for access to this Software Installation. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Software_Component_Password'>SoftLayer_Software_Component_Password[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#softwareDescription" name=softwareDescription>softwareDescription</a>
            </span>
            <div class='views-field-body'>The Software Description of this Software Component. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Software_Description'>SoftLayer_Software_Description </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#softwareLicense" name=softwareLicense>softwareLicense</a>
            </span>
            <div class='views-field-body'>The License this Software Component uses. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Software_License'>SoftLayer_Software_License </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuest" name=virtualGuest>virtualGuest</a>
            </span>
            <div class='views-field-body'>The virtual guest this software component is installed upon. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest </a></p>
            </div>
        </div>
                <h2>Count</h2>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#passwordCount" name=passwordCount>passwordCount</a>
            </span>
            <div class='views-field-body'>A count of username/Password pairs used for access to this Software Installation. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#passwordHistoryCount" name=passwordHistoryCount>passwordHistoryCount</a>
            </span>
            <div class='views-field-body'>A count of history Records for Software Passwords. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
            </div>
</div>


