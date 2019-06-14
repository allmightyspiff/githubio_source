---
title: "SoftLayer_Container_Product_Order_Network_LoadBalancer_AsAService"
description: "This is the datatype that needs to be populated and sent to SoftLayer_Product_Order::placeOrder. This datatype has every... "
layout: "datatype"
tags:
    - "datatype"
    - "sldn"
    - "Container"
classes:
    - "SoftLayer_Container_Product_Order_Network_LoadBalancer_AsAService"
---

# SoftLayer_Container_Product_Order_Network_LoadBalancer_AsAService
<div id='service-datatype'>
    <ul id='sldn-reference-tabs'>
        <li id='datatype'> <a href='/reference/datatypes/SoftLayer_Container_Product_Order_Network_LoadBalancer_AsAService' >Datatype</a></li>
    </ul>
</div>

## Description 
This is the datatype that needs to be populated and sent to SoftLayer_Product_Order::placeOrder. This datatype has everything required to place an order for a Load Balancer as a Service. 


### associatedMethods

*  [SoftLayer_Product_Order::verifyOrder](/reference/services/SoftLayer_Product_Order/verifyOrder )
*  [SoftLayer_Product_Order::placeOrder](/reference/services/SoftLayer_Product_Order/placeOrder )





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
                <a href="#bigDataOrderFlag" name=bigDataOrderFlag>bigDataOrderFlag</a>
            </span>
            <div class='views-field-body'>Flag for identifying an order for Big Data Deployment. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#billingInformation" name=billingInformation>billingInformation</a>
            </span>
            <div class='views-field-body'>Billing Information associated with an order. For existing customers this information is completely ignored. Do not send this information for existing customers.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Container_Product_Order_Billing_Information'>SoftLayer_Container_Product_Order_Billing_Information </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#billingOrderItemId" name=billingOrderItemId>billingOrderItemId</a>
            </span>
            <div class='views-field-body'>This is the ID of the [[SoftLayer_Billing_Order_Item]] of this configuration/container. It is used for rebuilding an order container from a quote and is set automatically.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#cancelUrl" name=cancelUrl>cancelUrl</a>
            </span>
            <div class='views-field-body'>The URL to which PayPal redirects browser after checkout has been canceled before completion of a payment. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#containerIdentifier" name=containerIdentifier>containerIdentifier</a>
            </span>
            <div class='views-field-body'>User-specified description to identify a particular order container. This is useful if you have a multi-configuration order (multiple <code>orderContainers</code>) and you want to be able to easily determine one from another. Populating this value may be helpful if an exception is thrown when placing an order and it's tied to a specific order container.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#containerSplHash" name=containerSplHash>containerSplHash</a>
            </span>
            <div class='views-field-body'>This hash is internally-generated and is used to for tracking order containers. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#currencyShortName" name=currencyShortName>currencyShortName</a>
            </span>
            <div class='views-field-body'>The currency type chosen at checkout.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#description" name=description>description</a>
            </span>
            <div class='views-field-body'>A description of this Load Balancer. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#deviceFingerprintId" name=deviceFingerprintId>deviceFingerprintId</a>
            </span>
            <div class='views-field-body'>Device Fingerprint Identifier - Optional. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#displayLayerSessionId" name=displayLayerSessionId>displayLayerSessionId</a>
            </span>
            <div class='views-field-body'>This is the configuration identifier for tracking orders on the HTML order forms.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#extendedHardwareTesting" name=extendedHardwareTesting>extendedHardwareTesting</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#flexibleCreditProgramPrice" name=flexibleCreditProgramPrice>flexibleCreditProgramPrice</a>
            </span>
            <div class='views-field-body'>The [[SoftLayer_Product_Item_Price]] for the Flexible Credit Program discount.  The <code>oneTimeFee</code> field contains the calculated discount being applied to the order.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Product_Item_Price'>SoftLayer_Product_Item_Price </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#gdprConsentFlag" name=gdprConsentFlag>gdprConsentFlag</a>
            </span>
            <div class='views-field-body'>This flag indicates that the customer consented to the GDPR terms for the quote. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardware" name=hardware>hardware</a>
            </span>
            <div class='views-field-body'>For orders that contain servers (bare metal, virtual server, big data, etc.), the hardware property is required. This property is an array of [[SoftLayer_Hardware]] objects. The <code>hostname</code> and <code>domain</code> properties are required for each hardware object. Note that virtual server ([[SoftLayer_Container_Product_Order_Virtual_Guest]]) orders may populate this field instead of the <code>virtualGuests</code> property.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#healthMonitorConfigurations" name=healthMonitorConfigurations>healthMonitorConfigurations</a>
            </span>
            <div class='views-field-body'>The [[SoftLayer_Network_LBaaS_LoadBalancerHealthMonitorConfiguration]]s for this Load Balancer. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_LBaaS_LoadBalancerHealthMonitorConfiguration'>SoftLayer_Network_LBaaS_LoadBalancerHealthMonitorConfiguration[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#imageTemplateGlobalIdentifier" name=imageTemplateGlobalIdentifier>imageTemplateGlobalIdentifier</a>
            </span>
            <div class='views-field-body'>An optional virtual disk image template identifier to be used as an installation base for a computing instance order </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#imageTemplateId" name=imageTemplateId>imageTemplateId</a>
            </span>
            <div class='views-field-body'>An optional virtual disk image template identifier to be used as an installation base for a computing instance order </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#isManagedOrder" name=isManagedOrder>isManagedOrder</a>
            </span>
            <div class='views-field-body'>Flag to identify a "managed" order. This value is set internally. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#isPublic" name=isPublic>isPublic</a>
            </span>
            <div class='views-field-body'>Specify whether this load balancer is a public or internal facing load balancer. If this value is omitted, the value will default to true.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#itemCategoryQuestionAnswers" name=itemCategoryQuestionAnswers>itemCategoryQuestionAnswers</a>
            </span>
            <div class='views-field-body'>The collection of [[SoftLayer_Container_Product_Item_Category_Question_Answer]] for any product category that has additional questions requiring user input.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Container_Product_Item_Category_Question_Answer'>SoftLayer_Container_Product_Item_Category_Question_Answer[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#location" name=location>location</a>
            </span>
            <div class='views-field-body'>The [[SoftLayer_Location_Region]] keyname or specific [[SoftLayer_Location_Datacenter]] id where the order should be provisioned. If this value is provided and the <code>regionalGroup</code> property is also specified, an exception will be thrown indicating that only 1 is allowed.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#locationObject" name=locationObject>locationObject</a>
            </span>
            <div class='views-field-body'>This [[SoftLayer_Location]] object will be determined from the <code>location</code> property and will be returned in the order verification or placement response. Any value specified here will get overwritten by the verification process.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Location'>SoftLayer_Location </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#message" name=message>message</a>
            </span>
            <div class='views-field-body'>A generic message about the order. Does not need to be sent in with any orders.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#name" name=name>name</a>
            </span>
            <div class='views-field-body'>A name to identify this Load Balancer. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#orderContainers" name=orderContainers>orderContainers</a>
            </span>
            <div class='views-field-body'>Orders may contain an array of configurations. Populating this property allows you to purchase multiple configurations within a single order. Each order container will have its own individual settings independent of the other order containers. For example, it is possible to order a bare metal server in one configuration and a virtual server in another. 

If <code>orderContainers</code> is populated on the base order container, most of the configuration-specific properties are ignored on the base container. For example, <code>prices</code>, <code>location</code> and <code>packageId</code> will be ignored on the base container, but since the <code>billingInformation</code> is a property that's not specific to a single order container (but the order as a whole) it must be populated on the base container.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Container_Product_Order'>SoftLayer_Container_Product_Order[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#orderHostnames" name=orderHostnames>orderHostnames</a>
            </span>
            <div class='views-field-body'>This is deprecated and does not do anything.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>array of strings</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#orderVerificationExceptions" name=orderVerificationExceptions>orderVerificationExceptions</a>
            </span>
            <div class='views-field-body'>Collection of exceptions resulting from the verification of the order. This value is set internally and is not required for end users when placing an order. When placing API orders, users can use this value to determine the container-specific exception that was thrown.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Container_Exception'>SoftLayer_Container_Exception[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#packageId" name=packageId>packageId</a>
            </span>
            <div class='views-field-body'>The [[SoftLayer_Product_Package]] id for an order container. This is required to place an order. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#paymentType" name=paymentType>paymentType</a>
            </span>
            <div class='views-field-body'>The Payment Type is Optional. If nothing is sent in, then the normal method of payment will be used. For paypal customers, this means a paypalToken will be returned in the receipt. This token is to be used on the paypal website to complete the order. For Credit Card customers, the card on file in our system will be used to make an initial authorization. To force the order to use a payment type, use one of the following: CARD_ON_FILE or PAYPAL  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#postTaxRecurring" name=postTaxRecurring>postTaxRecurring</a>
            </span>
            <div class='views-field-body'>The post-tax recurring charge for the order. This is the sum of preTaxRecurring + totalRecurringTax. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#postTaxRecurringHourly" name=postTaxRecurringHourly>postTaxRecurringHourly</a>
            </span>
            <div class='views-field-body'>The post-tax recurring hourly charge for the order. Since taxes are not calculated for hourly orders, this value will be the same as preTaxRecurringHourly.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#postTaxRecurringMonthly" name=postTaxRecurringMonthly>postTaxRecurringMonthly</a>
            </span>
            <div class='views-field-body'>The post-tax recurring monthly charge for the order. This is the sum of preTaxRecurringMonthly + totalRecurringTax.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#postTaxSetup" name=postTaxSetup>postTaxSetup</a>
            </span>
            <div class='views-field-body'>The post-tax setup fees of the order. This is the sum of preTaxSetup + totalSetupTax; </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#preTaxRecurring" name=preTaxRecurring>preTaxRecurring</a>
            </span>
            <div class='views-field-body'>The pre-tax recurring total of the order. If there are mixed monthly and hourly prices on the order, this will be the sum of preTaxRecurringHourly and preTaxRecurringMonthly.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#preTaxRecurringHourly" name=preTaxRecurringHourly>preTaxRecurringHourly</a>
            </span>
            <div class='views-field-body'>The pre-tax hourly recurring total of the order. If there are only monthly prices on the order, this value will be 0.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#preTaxRecurringMonthly" name=preTaxRecurringMonthly>preTaxRecurringMonthly</a>
            </span>
            <div class='views-field-body'>The pre-tax monthly recurring total of the order. If there are only hourly prices on the order, this value will be 0.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#preTaxSetup" name=preTaxSetup>preTaxSetup</a>
            </span>
            <div class='views-field-body'>The pre-tax setup fee total of the order. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#presaleEvent" name=presaleEvent>presaleEvent</a>
            </span>
            <div class='views-field-body'>If there are any presale events available for an order, this value will be populated. It is set internally and is not required for end users when placing an order. See [[SoftLayer_Sales_Presale_Event]] for more info.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Sales_Presale_Event'>SoftLayer_Sales_Presale_Event </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#presetId" name=presetId>presetId</a>
            </span>
            <div class='views-field-body'>A preset configuration id for the package. Is required if not submitting any prices. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#prices" name=prices>prices</a>
            </span>
            <div class='views-field-body'>This is a collection of [[SoftLayer_Product_Item_Price]] objects. The only required property to populate for an item price object when ordering is its <code>id</code> - all other supplied information about the price (e.g., recurringFee, setupFee, etc.) will be ignored. Unless the [[SoftLayer_Product_Package]] associated with the order allows for preset prices, this property is required to place an order.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Product_Item_Price'>SoftLayer_Product_Item_Price[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#primaryDiskPartitionId" name=primaryDiskPartitionId>primaryDiskPartitionId</a>
            </span>
            <div class='views-field-body'>The id of a [[SoftLayer_Hardware_Component_Partition_Template]]. This property is optional. If no partition template is provided, a default will be used according to the operating system chosen with the order. Using the [[SoftLayer_Hardware_Component_Partition_OperatingSystem]] service, getPartitionTemplates will return those available for the particular operating system.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#priorities" name=priorities>priorities</a>
            </span>
            <div class='views-field-body'>Priorities to set on replication set servers. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>array of strings</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#privateCloudOrderFlag" name=privateCloudOrderFlag>privateCloudOrderFlag</a>
            </span>
            <div class='views-field-body'>Flag for identifying a container as Virtual Server (Private Node). </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#privateCloudOrderType" name=privateCloudOrderType>privateCloudOrderType</a>
            </span>
            <div class='views-field-body'>Type of Virtual Server (Private Node) order. Potential values: INITIAL, ADDHOST, ADDIPS, ADDZONE  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#promotionCode" name=promotionCode>promotionCode</a>
            </span>
            <div class='views-field-body'>Optional promotion code for an order. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#properties" name=properties>properties</a>
            </span>
            <div class='views-field-body'>Generic properties. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Container_Product_Order_Property'>SoftLayer_Container_Product_Order_Property[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#proratedInitialCharge" name=proratedInitialCharge>proratedInitialCharge</a>
            </span>
            <div class='views-field-body'>The Prorated Initial Charge plus the balance on the account. Only the recurring fees are prorated. Here's how the calculation works: We take the postTaxRecurring value and we prorate it based on the time between now and the next bill date for this account. After this, we add in the setup fee since this is not prorated. Then, if there is a balance on the account, we add that to the account. In the event that there is a credit balance on the account, we will subtract this amount from the order total. If the credit balance on the account is greater than the prorated initial charge, the order will go through without a charge to the credit card on the account or requiring a paypal payment. The credit on the account will be reduced by the order total, and the order will await approval from sales, as normal. If there is a pending order already in the system, We will ignore the balance on the account completely, in the calculation of the initial charge. This is to protect against two orders coming into the system and getting the benefit of a credit balance, or worse, both orders being charged the order amount + the balance on the account.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#proratedOrderTotal" name=proratedOrderTotal>proratedOrderTotal</a>
            </span>
            <div class='views-field-body'>This is the same as the proratedInitialCharge, except the balance on the account is ignored. This is the prorated total amount of the order.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#protocolConfigurations" name=protocolConfigurations>protocolConfigurations</a>
            </span>
            <div class='views-field-body'>The [[SoftLayer_Network_LBaaS_LoadBalancerProtocolConfiguration]]s for this Load Balancer. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_LBaaS_LoadBalancerProtocolConfiguration'>SoftLayer_Network_LBaaS_LoadBalancerProtocolConfiguration[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#provisionScripts" name=provisionScripts>provisionScripts</a>
            </span>
            <div class='views-field-body'>The URLs for scripts to execute on their respective servers after they have been provisioned. Provision scripts are not available for Microsoft Windows servers. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>array of strings</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#quantity" name=quantity>quantity</a>
            </span>
            <div class='views-field-body'>The quantity of the item being ordered </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#quoteName" name=quoteName>quoteName</a>
            </span>
            <div class='views-field-body'>A custom name to be assigned to the quote.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#regionalGroup" name=regionalGroup>regionalGroup</a>
            </span>
            <div class='views-field-body'>Specifying a regional group name allows you to not worry about placing your server or service at a specific datacenter, but to any datacenter within that regional group. See [[SoftLayer_Location_Group_Regional]] to get a list of available regional group names. 

<code>location</code> and <code>regionalGroup</code> are mutually exclusive on an order container. If both location and regionalGroup are provided, an exception will be thrown indicating that only 1 is allowed. 

If a regional group is provided and VLANs are specified (within the <code>hardware</code> or <code>virtualGuests</code> properties), we will use the datacenter where the VLANs are located. If no VLANs are specified, we will use the preferred datacenter on the regional group object.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#resourceGroupId" name=resourceGroupId>resourceGroupId</a>
            </span>
            <div class='views-field-body'>An optional resource group identifier specifying the resource group to attach the order to </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#resourceGroupName" name=resourceGroupName>resourceGroupName</a>
            </span>
            <div class='views-field-body'>This variable specifies the name of the resource group the server configuration belongs to. For MongoDB Replica sets, it would be the replica set name. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#resourceGroupTemplateId" name=resourceGroupTemplateId>resourceGroupTemplateId</a>
            </span>
            <div class='views-field-body'>An optional resource group template identifier to be used as a deployment base for a Virtual Server (Private Node) order.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#returnUrl" name=returnUrl>returnUrl</a>
            </span>
            <div class='views-field-body'>The URL to which PayPal redirects browser after a payment is completed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#sendQuoteEmailFlag" name=sendQuoteEmailFlag>sendQuoteEmailFlag</a>
            </span>
            <div class='views-field-body'>This flag indicates that the quote should be sent to the email address associated with the account or order. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#serverCoreCount" name=serverCoreCount>serverCoreCount</a>
            </span>
            <div class='views-field-body'>The number of cores for the server being ordered. This value is set internally.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#serverInstancesInformation" name=serverInstancesInformation>serverInstancesInformation</a>
            </span>
            <div class='views-field-body'>The [[SoftLayer_Network_LBaaS_LoadBalancerServerInstanceInfo]]s for this Load Balancer. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_LBaaS_LoadBalancerServerInstanceInfo'>SoftLayer_Network_LBaaS_LoadBalancerServerInstanceInfo[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#serviceToken" name=serviceToken>serviceToken</a>
            </span>
            <div class='views-field-body'>The token of a requesting service. Do not set. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#sourceVirtualGuestId" name=sourceVirtualGuestId>sourceVirtualGuestId</a>
            </span>
            <div class='views-field-body'>An optional computing instance identifier to be used as an installation base for a computing instance order </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#sshKeys" name=sshKeys>sshKeys</a>
            </span>
            <div class='views-field-body'>The containers which hold SoftLayer_Security_Ssh_Key IDs to add to their respective servers. The order of containers passed in needs to match the order they are assigned to either hardware or virtualGuests. SSH Keys will not be assigned for servers with Microsoft Windows.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Container_Product_Order_SshKeys'>SoftLayer_Container_Product_Order_SshKeys[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#stepId" name=stepId>stepId</a>
            </span>
            <div class='views-field-body'>An optional parameter for step-based order processing. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#storageGroups" name=storageGroups>storageGroups</a>
            </span>
            <div class='views-field-body'>

For orders that want to add storage groups such as RAID across multiple disks, simply add [[SoftLayer_Container_Product_Order_Storage_Group]] objects to this array. Storage groups will only be used if the 'RAID' disk controller price is selected. Any other disk controller types will ignore the storage groups set here. 

The first storage group in this array will be considered the primary storage group, which is used for the OS. Any other storage groups will act as data storage. 

 </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Container_Product_Order_Storage_Group'>SoftLayer_Container_Product_Order_Storage_Group[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#subnets" name=subnets>subnets</a>
            </span>
            <div class='views-field-body'>The [[SoftLayer_Network_Subnet]]s where this Load Balancer will be provisioned. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet'>SoftLayer_Network_Subnet[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#taxCacheHash" name=taxCacheHash>taxCacheHash</a>
            </span>
            <div class='views-field-body'>The order container may not contain the final tax rates when it is returned from [[SoftLayer_Product_Order/verifyOrder|verifyOrder]]. This hash will facilitate checking if the tax rates have finished being calculated and retrieving the accurate tax rate values.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#taxCompletedFlag" name=taxCompletedFlag>taxCompletedFlag</a>
            </span>
            <div class='views-field-body'>Flag to indicate if the order container has the final tax rates for the order. Some tax rates are calculated in the background because they take longer, and they might not be finished when the container is returned from [[SoftLayer_Product_Order/verifyOrder|verifyOrder]].  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#techIncubatorItemPrice" name=techIncubatorItemPrice>techIncubatorItemPrice</a>
            </span>
            <div class='views-field-body'>The SoftLayer_Product_Item_Price for the Tech Incubator discount.  The oneTimeFee field contain the calculated discount being applied to the order.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Product_Item_Price'>SoftLayer_Product_Item_Price </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#totalRecurringTax" name=totalRecurringTax>totalRecurringTax</a>
            </span>
            <div class='views-field-body'>The total tax portion of the recurring fees. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#totalSetupTax" name=totalSetupTax>totalSetupTax</a>
            </span>
            <div class='views-field-body'>The tax amount of the setup fees. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#type" name=type>type</a>
            </span>
            <div class='views-field-body'>Specify the type of this load balancer. If isPublic is omitted, it specifies the load balacner as private(0), public(1) or public to public(2). If isPublic is set as True, only public(1) or public to public(2) is valid. If isPublic is set as False, this value is ignored. If this value is omitted, the value will be set according to isPublic value.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#usagePrices" name=usagePrices>usagePrices</a>
            </span>
            <div class='views-field-body'>This is a collection of [[SoftLayer_Product_Item_Price]] objects which will be used when the service offering being ordered generates usage. This is a read-only property. Setting this property will not change the order.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Product_Item_Price'>SoftLayer_Product_Item_Price[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#useHourlyPricing" name=useHourlyPricing>useHourlyPricing</a>
            </span>
            <div class='views-field-body'>An optional flag to use hourly pricing instead of standard monthly pricing. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#useSystemPublicIpPool" name=useSystemPublicIpPool>useSystemPublicIpPool</a>
            </span>
            <div class='views-field-body'>Specify if this load balancer uses system IP pool (true, default) or customer's (null|false) public subnet to allocate IP addresses. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
            </div>
    </div>


