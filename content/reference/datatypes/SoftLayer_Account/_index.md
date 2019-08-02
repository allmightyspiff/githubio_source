---
title: "SoftLayer_Account"
description: "The SoftLayer_Account data type contains general information relating to a single SoftLayer customer account. Personal i... "
layout: "datatype"
tags:
    - "datatype"
    - "sldn"
    - "Account"
classes:
    - "SoftLayer_Account"
---

# SoftLayer_Account
<div id='service-datatype'>
    <ul id='sldn-reference-tabs'>
    <li id='service'> <a href='/reference/services/SoftLayer_Account' >Service</a></li>    <li id='datatype'> <a href='/reference/datatypes/SoftLayer_Account' >Datatype</a></li>
    </ul>
</div>

## Description 
The SoftLayer_Account data type contains general information relating to a single SoftLayer customer account. Personal information in this type such as names, addresses, and phone numbers are assigned to the account only and not to users belonging to the account. The SoftLayer_Account data type contains a number of relational properties that are used by the SoftLayer customer portal to quickly present a variety of account related services to it's users. 

SoftLayer customers are unable to change their company account information in the portal or the API. If you need to change this information please open a sales ticket in our customer portal and our account management staff will assist you. 


### associatedMethods

*  [SoftLayer_Account::getObject](/reference/services/SoftLayer_Account/getObject )
*  [SoftLayer_Billing_Invoice::getAccount](/reference/services/SoftLayer_Billing_Invoice/getAccount )





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
                <a href="#accountManagedResourcesFlag" name=accountManagedResourcesFlag>accountManagedResourcesFlag</a>
            </span>
            <div class='views-field-body'>A flag indicating that the account has a managed resource. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#accountStatusId" name=accountStatusId>accountStatusId</a>
            </span>
            <div class='views-field-body'>A number reflecting the state of an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#address1" name=address1>address1</a>
            </span>
            <div class='views-field-body'>The first line of the mailing address belonging to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#address2" name=address2>address2</a>
            </span>
            <div class='views-field-body'>The second line of the mailing address belonging to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowedPptpVpnQuantity" name=allowedPptpVpnQuantity>allowedPptpVpnQuantity</a>
            </span>
            <div class='views-field-body'>The number of PPTP VPN users allowed on an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#alternatePhone" name=alternatePhone>alternatePhone</a>
            </span>
            <div class='views-field-body'>A secondary phone number assigned to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#brandId" name=brandId>brandId</a>
            </span>
            <div class='views-field-body'>The Brand tied to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#city" name=city>city</a>
            </span>
            <div class='views-field-body'>The city of the mailing address belonging to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#claimedTaxExemptTxFlag" name=claimedTaxExemptTxFlag>claimedTaxExemptTxFlag</a>
            </span>
            <div class='views-field-body'>Whether an account is exempt from taxes on their invoices. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#companyName" name=companyName>companyName</a>
            </span>
            <div class='views-field-body'>The company name associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#country" name=country>country</a>
            </span>
            <div class='views-field-body'>A two-letter abbreviation of the country in the mailing address belonging to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#createDate" name=createDate>createDate</a>
            </span>
            <div class='views-field-body'>The date an account was created. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>dateTime</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#deviceFingerprintId" name=deviceFingerprintId>deviceFingerprintId</a>
            </span>
            <div class='views-field-body'>Device Fingerprint Identifier - Used internally and can safely be ignored. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#email" name=email>email</a>
            </span>
            <div class='views-field-body'>A general email address assigned to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#faxPhone" name=faxPhone>faxPhone</a>
            </span>
            <div class='views-field-body'>A fax phone number assigned to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#firstName" name=firstName>firstName</a>
            </span>
            <div class='views-field-body'>Each customer account is listed under a single individual. This is that individual's first name. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#id" name=id>id</a>
            </span>
            <div class='views-field-body'>A customer account's internal identifier. Account numbers are typically preceded by the string "SL" in the customer portal. Every SoftLayer account has at least one portal user whose username follows the "SL" + account number naming scheme.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#isReseller" name=isReseller>isReseller</a>
            </span>
            <div class='views-field-body'>A flag indicating if an account belongs to a reseller or not. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lastName" name=lastName>lastName</a>
            </span>
            <div class='views-field-body'>Each customer account is listed under a single individual. This is that individual's last name. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lateFeeProtectionFlag" name=lateFeeProtectionFlag>lateFeeProtectionFlag</a>
            </span>
            <div class='views-field-body'>Whether an account has late fee protection. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#modifyDate" name=modifyDate>modifyDate</a>
            </span>
            <div class='views-field-body'>The date an account was last modified. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>dateTime</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#officePhone" name=officePhone>officePhone</a>
            </span>
            <div class='views-field-body'>An office phone number assigned to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#postalCode" name=postalCode>postalCode</a>
            </span>
            <div class='views-field-body'>The postal code of the mailing address belonging to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#resellerLevel" name=resellerLevel>resellerLevel</a>
            </span>
            <div class='views-field-body'>The Reseller level of the account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#state" name=state>state</a>
            </span>
            <div class='views-field-body'>A two-letter abbreviation of the state in the mailing address belonging to an account. If an account does not reside in a province then this is typically blank. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#statusDate" name=statusDate>statusDate</a>
            </span>
            <div class='views-field-body'>The date of an account's last status change. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>dateTime</p>
            </div>
        </div>
            </div>
        <div id="relationalProperties"  class="prop-content" >
        <h2>Relational</h2>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#abuseEmail" name=abuseEmail>abuseEmail</a>
            </span>
            <div class='views-field-body'>An email address that is responsible for abuse and legal inquiries on behalf of an account. For instance, new legal and abuse tickets are sent to this address. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#abuseEmails" name=abuseEmails>abuseEmails</a>
            </span>
            <div class='views-field-body'>Email addresses that are responsible for abuse and legal inquiries on behalf of an account. For instance, new legal and abuse tickets are sent to these addresses. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_AbuseEmail'>SoftLayer_Account_AbuseEmail[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#accountContacts" name=accountContacts>accountContacts</a>
            </span>
            <div class='views-field-body'>The account contacts on an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Contact'>SoftLayer_Account_Contact[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#accountLicenses" name=accountLicenses>accountLicenses</a>
            </span>
            <div class='views-field-body'>The account software licenses owned by an account </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Software_AccountLicense'>SoftLayer_Software_AccountLicense[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#accountLinks" name=accountLinks>accountLinks</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Link'>SoftLayer_Account_Link[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#accountStatus" name=accountStatus>accountStatus</a>
            </span>
            <div class='views-field-body'>An account's status presented in a more detailed data type. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Status'>SoftLayer_Account_Status </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeAccountDiscountBillingItem" name=activeAccountDiscountBillingItem>activeAccountDiscountBillingItem</a>
            </span>
            <div class='views-field-body'>The billing item associated with an account's monthly discount. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item'>SoftLayer_Billing_Item </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeAccountLicenses" name=activeAccountLicenses>activeAccountLicenses</a>
            </span>
            <div class='views-field-body'>The active account software licenses owned by an account </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Software_AccountLicense'>SoftLayer_Software_AccountLicense[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeAddresses" name=activeAddresses>activeAddresses</a>
            </span>
            <div class='views-field-body'>The active address(es) that belong to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Address'>SoftLayer_Account_Address[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeAgreements" name=activeAgreements>activeAgreements</a>
            </span>
            <div class='views-field-body'>All active agreements for an account </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Agreement'>SoftLayer_Account_Agreement[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeBillingAgreements" name=activeBillingAgreements>activeBillingAgreements</a>
            </span>
            <div class='views-field-body'>All billing agreements for an account </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Agreement'>SoftLayer_Account_Agreement[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeCatalystEnrollment" name=activeCatalystEnrollment>activeCatalystEnrollment</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Catalyst_Enrollment'>SoftLayer_Catalyst_Enrollment </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeColocationContainers" name=activeColocationContainers>activeColocationContainers</a>
            </span>
            <div class='views-field-body'>The account's active top level colocation containers. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item'>SoftLayer_Billing_Item[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeFlexibleCreditEnrollment" name=activeFlexibleCreditEnrollment>activeFlexibleCreditEnrollment</a>
            </span>
            <div class='views-field-body'>Account's currently active Flexible Credit enrollment. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_FlexibleCredit_Enrollment'>SoftLayer_FlexibleCredit_Enrollment </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeNotificationSubscribers" name=activeNotificationSubscribers>activeNotificationSubscribers</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Notification_Subscriber'>SoftLayer_Notification_Subscriber[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeQuotes" name=activeQuotes>activeQuotes</a>
            </span>
            <div class='views-field-body'>An account's non-expired quotes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Order_Quote'>SoftLayer_Billing_Order_Quote[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeReservedCapacityAgreements" name=activeReservedCapacityAgreements>activeReservedCapacityAgreements</a>
            </span>
            <div class='views-field-body'>Active reserved capacity agreements for an account </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Agreement'>SoftLayer_Account_Agreement[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeVirtualLicenses" name=activeVirtualLicenses>activeVirtualLicenses</a>
            </span>
            <div class='views-field-body'>The virtual software licenses controlled by an account </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Software_VirtualLicense'>SoftLayer_Software_VirtualLicense[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#adcLoadBalancers" name=adcLoadBalancers>adcLoadBalancers</a>
            </span>
            <div class='views-field-body'>An account's associated load balancers. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Application_Delivery_Controller_LoadBalancer_VirtualIpAddress'>SoftLayer_Network_Application_Delivery_Controller_LoadBalancer_VirtualIpAddress[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#addresses" name=addresses>addresses</a>
            </span>
            <div class='views-field-body'>All the address(es) that belong to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Address'>SoftLayer_Account_Address[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#affiliateId" name=affiliateId>affiliateId</a>
            </span>
            <div class='views-field-body'>An affiliate identifier associated with the customer account.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allBillingItems" name=allBillingItems>allBillingItems</a>
            </span>
            <div class='views-field-body'>The billing items that will be on an account's next invoice. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item'>SoftLayer_Billing_Item[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allCommissionBillingItems" name=allCommissionBillingItems>allCommissionBillingItems</a>
            </span>
            <div class='views-field-body'>The billing items that will be on an account's next invoice. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item'>SoftLayer_Billing_Item[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allRecurringTopLevelBillingItems" name=allRecurringTopLevelBillingItems>allRecurringTopLevelBillingItems</a>
            </span>
            <div class='views-field-body'>The billing items that will be on an account's next invoice. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item'>SoftLayer_Billing_Item[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allRecurringTopLevelBillingItemsUnfiltered" name=allRecurringTopLevelBillingItemsUnfiltered>allRecurringTopLevelBillingItemsUnfiltered</a>
            </span>
            <div class='views-field-body'>The billing items that will be on an account's next invoice. Does not consider associated items. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item'>SoftLayer_Billing_Item[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allSubnetBillingItems" name=allSubnetBillingItems>allSubnetBillingItems</a>
            </span>
            <div class='views-field-body'>The billing items that will be on an account's next invoice. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item'>SoftLayer_Billing_Item[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allTopLevelBillingItems" name=allTopLevelBillingItems>allTopLevelBillingItems</a>
            </span>
            <div class='views-field-body'>All billing items of an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item'>SoftLayer_Billing_Item[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allTopLevelBillingItemsUnfiltered" name=allTopLevelBillingItemsUnfiltered>allTopLevelBillingItemsUnfiltered</a>
            </span>
            <div class='views-field-body'>The billing items that will be on an account's next invoice. Does not consider associated items. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item'>SoftLayer_Billing_Item[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowIbmIdSilentMigrationFlag" name=allowIbmIdSilentMigrationFlag>allowIbmIdSilentMigrationFlag</a>
            </span>
            <div class='views-field-body'>Indicates whether this account is allowed to silently migrate to use IBMid Authentication. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allowsBluemixAccountLinkingFlag" name=allowsBluemixAccountLinkingFlag>allowsBluemixAccountLinkingFlag</a>
            </span>
            <div class='views-field-body'>Flag indicating if this account can be linked with Bluemix. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#applicationDeliveryControllers" name=applicationDeliveryControllers>applicationDeliveryControllers</a>
            </span>
            <div class='views-field-body'>An account's associated application delivery controller records. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Application_Delivery_Controller'>SoftLayer_Network_Application_Delivery_Controller[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#attributes" name=attributes>attributes</a>
            </span>
            <div class='views-field-body'>The account attribute values for a SoftLayer customer account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Attribute'>SoftLayer_Account_Attribute[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#availablePublicNetworkVlans" name=availablePublicNetworkVlans>availablePublicNetworkVlans</a>
            </span>
            <div class='views-field-body'>The public network VLANs assigned to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Vlan'>SoftLayer_Network_Vlan[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#balance" name=balance>balance</a>
            </span>
            <div class='views-field-body'>The account balance of a SoftLayer customer account. An account's balance is the amount of money owed to SoftLayer by the account holder, returned as a floating point number with two decimal places, measured in US Dollars ($USD). A negative account balance means the account holder has overpaid and is owed money by SoftLayer. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#bandwidthAllotments" name=bandwidthAllotments>bandwidthAllotments</a>
            </span>
            <div class='views-field-body'>The bandwidth allotments for an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Bandwidth_Version1_Allotment'>SoftLayer_Network_Bandwidth_Version1_Allotment[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#bandwidthAllotmentsOverAllocation" name=bandwidthAllotmentsOverAllocation>bandwidthAllotmentsOverAllocation</a>
            </span>
            <div class='views-field-body'>The bandwidth allotments for an account currently over allocation. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Bandwidth_Version1_Allotment'>SoftLayer_Network_Bandwidth_Version1_Allotment[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#bandwidthAllotmentsProjectedOverAllocation" name=bandwidthAllotmentsProjectedOverAllocation>bandwidthAllotmentsProjectedOverAllocation</a>
            </span>
            <div class='views-field-body'>The bandwidth allotments for an account projected to go over allocation. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Bandwidth_Version1_Allotment'>SoftLayer_Network_Bandwidth_Version1_Allotment[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#bareMetalInstances" name=bareMetalInstances>bareMetalInstances</a>
            </span>
            <div class='views-field-body'>An account's associated bare metal server objects. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#billingAgreements" name=billingAgreements>billingAgreements</a>
            </span>
            <div class='views-field-body'>All billing agreements for an account </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Agreement'>SoftLayer_Account_Agreement[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#billingInfo" name=billingInfo>billingInfo</a>
            </span>
            <div class='views-field-body'>An account's billing information. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Info'>SoftLayer_Billing_Info </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#blockDeviceTemplateGroups" name=blockDeviceTemplateGroups>blockDeviceTemplateGroups</a>
            </span>
            <div class='views-field-body'>Private template group objects (parent and children) and the shared template group objects (parent only) for an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest_Block_Device_Template_Group'>SoftLayer_Virtual_Guest_Block_Device_Template_Group[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#bluemixAccountLink" name=bluemixAccountLink>bluemixAccountLink</a>
            </span>
            <div class='views-field-body'>The Bluemix account link associated with this SoftLayer account, if one exists. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Link_Bluemix'>SoftLayer_Account_Link_Bluemix </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#bluemixLinkedFlag" name=bluemixLinkedFlag>bluemixLinkedFlag</a>
            </span>
            <div class='views-field-body'>Returns true if this account is linked to IBM Bluemix, false if not. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#brand" name=brand>brand</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Brand'>SoftLayer_Brand </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#brandAccountFlag" name=brandAccountFlag>brandAccountFlag</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#brandKeyName" name=brandKeyName>brandKeyName</a>
            </span>
            <div class='views-field-body'>The brand keyName. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#businessPartner" name=businessPartner>businessPartner</a>
            </span>
            <div class='views-field-body'>The Business Partner details for the account. Country Enterprise Code, Channel, Segment, Reseller Level. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Business_Partner'>SoftLayer_Account_Business_Partner </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#canOrderAdditionalVlansFlag" name=canOrderAdditionalVlansFlag>canOrderAdditionalVlansFlag</a>
            </span>
            <div class='views-field-body'>[DEPRECATED] All accounts may order VLANs. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#carts" name=carts>carts</a>
            </span>
            <div class='views-field-body'>An account's active carts. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Order_Quote'>SoftLayer_Billing_Order_Quote[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#catalystEnrollments" name=catalystEnrollments>catalystEnrollments</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Catalyst_Enrollment'>SoftLayer_Catalyst_Enrollment[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#closedTickets" name=closedTickets>closedTickets</a>
            </span>
            <div class='views-field-body'>All closed tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Ticket'>SoftLayer_Ticket[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#datacentersWithSubnetAllocations" name=datacentersWithSubnetAllocations>datacentersWithSubnetAllocations</a>
            </span>
            <div class='views-field-body'>Datacenters which contain subnets that the account has access to route. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Location'>SoftLayer_Location[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#dedicatedHosts" name=dedicatedHosts>dedicatedHosts</a>
            </span>
            <div class='views-field-body'>An account's associated virtual dedicated host objects. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_DedicatedHost'>SoftLayer_Virtual_DedicatedHost[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#disablePaymentProcessingFlag" name=disablePaymentProcessingFlag>disablePaymentProcessingFlag</a>
            </span>
            <div class='views-field-body'>A flag indicating whether payments are processed for this account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#displaySupportRepresentativeAssignments" name=displaySupportRepresentativeAssignments>displaySupportRepresentativeAssignments</a>
            </span>
            <div class='views-field-body'>The SoftLayer employees that an account is assigned to. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Attachment_Employee'>SoftLayer_Account_Attachment_Employee[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#domainRegistrations" name=domainRegistrations>domainRegistrations</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Dns_Domain_Registration'>SoftLayer_Dns_Domain_Registration[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#domains" name=domains>domains</a>
            </span>
            <div class='views-field-body'>The DNS domains associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Dns_Domain'>SoftLayer_Dns_Domain[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#domainsWithoutSecondaryDnsRecords" name=domainsWithoutSecondaryDnsRecords>domainsWithoutSecondaryDnsRecords</a>
            </span>
            <div class='views-field-body'>The DNS domains associated with an account that were not created as a result of a secondary DNS zone transfer. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Dns_Domain'>SoftLayer_Dns_Domain[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#euSupportedFlag" name=euSupportedFlag>euSupportedFlag</a>
            </span>
            <div class='views-field-body'>Boolean flag dictating whether or not this account has the EU Supported flag. This flag indicates that this account uses IBM Cloud services to process EU citizen's personal data. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#evaultCapacityGB" name=evaultCapacityGB>evaultCapacityGB</a>
            </span>
            <div class='views-field-body'>The total capacity of Legacy EVault Volumes on an account, in GB. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsigned integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#evaultMasterUsers" name=evaultMasterUsers>evaultMasterUsers</a>
            </span>
            <div class='views-field-body'>An account's master EVault user. This is only used when an account has EVault service. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Password'>SoftLayer_Account_Password[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#evaultNetworkStorage" name=evaultNetworkStorage>evaultNetworkStorage</a>
            </span>
            <div class='views-field-body'>An account's associated EVault storage volumes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#expiredSecurityCertificates" name=expiredSecurityCertificates>expiredSecurityCertificates</a>
            </span>
            <div class='views-field-body'>Stored security certificates that are expired (ie. SSL) </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Security_Certificate'>SoftLayer_Security_Certificate[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#facilityLogs" name=facilityLogs>facilityLogs</a>
            </span>
            <div class='views-field-body'>Logs of who entered a colocation area which is assigned to this account, or when a user under this account enters a datacenter. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_User_Access_Facility_Log'>SoftLayer_User_Access_Facility_Log[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#fileBlockBetaAccessFlag" name=fileBlockBetaAccessFlag>fileBlockBetaAccessFlag</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#flexibleCreditEnrollments" name=flexibleCreditEnrollments>flexibleCreditEnrollments</a>
            </span>
            <div class='views-field-body'>All of the account's current and former Flexible Credit enrollments. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_FlexibleCredit_Enrollment'>SoftLayer_FlexibleCredit_Enrollment[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#forcePaasAccountLinkDate" name=forcePaasAccountLinkDate>forcePaasAccountLinkDate</a>
            </span>
            <div class='views-field-body'>Timestamp representing the point in time when an account is required to link with PaaS. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#globalIpRecords" name=globalIpRecords>globalIpRecords</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet_IpAddress_Global'>SoftLayer_Network_Subnet_IpAddress_Global[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#globalIpv4Records" name=globalIpv4Records>globalIpv4Records</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet_IpAddress_Global'>SoftLayer_Network_Subnet_IpAddress_Global[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#globalIpv6Records" name=globalIpv6Records>globalIpv6Records</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet_IpAddress_Global'>SoftLayer_Network_Subnet_IpAddress_Global[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#globalLoadBalancerAccounts" name=globalLoadBalancerAccounts>globalLoadBalancerAccounts</a>
            </span>
            <div class='views-field-body'>The global load balancer accounts for a softlayer customer account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_LoadBalancer_Global_Account'>SoftLayer_Network_LoadBalancer_Global_Account[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardware" name=hardware>hardware</a>
            </span>
            <div class='views-field-body'>An account's associated hardware objects. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareOverBandwidthAllocation" name=hardwareOverBandwidthAllocation>hardwareOverBandwidthAllocation</a>
            </span>
            <div class='views-field-body'>An account's associated hardware objects currently over bandwidth allocation. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareProjectedOverBandwidthAllocation" name=hardwareProjectedOverBandwidthAllocation>hardwareProjectedOverBandwidthAllocation</a>
            </span>
            <div class='views-field-body'>An account's associated hardware objects projected to go over bandwidth allocation. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareWithCpanel" name=hardwareWithCpanel>hardwareWithCpanel</a>
            </span>
            <div class='views-field-body'>All hardware associated with an account that has the cPanel web hosting control panel installed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareWithHelm" name=hardwareWithHelm>hardwareWithHelm</a>
            </span>
            <div class='views-field-body'>All hardware associated with an account that has the Helm web hosting control panel installed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareWithMcafee" name=hardwareWithMcafee>hardwareWithMcafee</a>
            </span>
            <div class='views-field-body'>All hardware associated with an account that has McAfee Secure software components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareWithMcafeeAntivirusRedhat" name=hardwareWithMcafeeAntivirusRedhat>hardwareWithMcafeeAntivirusRedhat</a>
            </span>
            <div class='views-field-body'>All hardware associated with an account that has McAfee Secure AntiVirus for Redhat software components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareWithMcafeeAntivirusWindows" name=hardwareWithMcafeeAntivirusWindows>hardwareWithMcafeeAntivirusWindows</a>
            </span>
            <div class='views-field-body'>All hardware associated with an account that has McAfee Secure AntiVirus for Windows software components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareWithMcafeeIntrusionDetectionSystem" name=hardwareWithMcafeeIntrusionDetectionSystem>hardwareWithMcafeeIntrusionDetectionSystem</a>
            </span>
            <div class='views-field-body'>All hardware associated with an account that has McAfee Secure Intrusion Detection System software components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareWithPlesk" name=hardwareWithPlesk>hardwareWithPlesk</a>
            </span>
            <div class='views-field-body'>All hardware associated with an account that has the Plesk web hosting control panel installed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareWithQuantastor" name=hardwareWithQuantastor>hardwareWithQuantastor</a>
            </span>
            <div class='views-field-body'>All hardware associated with an account that has the QuantaStor storage system installed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareWithUrchin" name=hardwareWithUrchin>hardwareWithUrchin</a>
            </span>
            <div class='views-field-body'>All hardware associated with an account that has the Urchin web traffic analytics package installed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareWithWindows" name=hardwareWithWindows>hardwareWithWindows</a>
            </span>
            <div class='views-field-body'>All hardware associated with an account that is running a version of the Microsoft Windows operating system. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hasEvaultBareMetalRestorePluginFlag" name=hasEvaultBareMetalRestorePluginFlag>hasEvaultBareMetalRestorePluginFlag</a>
            </span>
            <div class='views-field-body'>Return 1 if one of the account's hardware has the EVault Bare Metal Server Restore Plugin otherwise 0. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hasIderaBareMetalRestorePluginFlag" name=hasIderaBareMetalRestorePluginFlag>hasIderaBareMetalRestorePluginFlag</a>
            </span>
            <div class='views-field-body'>Return 1 if one of the account's hardware has an installation of Idera Server Backup otherwise 0. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hasPendingOrder" name=hasPendingOrder>hasPendingOrder</a>
            </span>
            <div class='views-field-body'>The number of orders in a PENDING status for a SoftLayer customer account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsigned integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hasR1softBareMetalRestorePluginFlag" name=hasR1softBareMetalRestorePluginFlag>hasR1softBareMetalRestorePluginFlag</a>
            </span>
            <div class='views-field-body'>Return 1 if one of the account's hardware has an installation of R1Soft CDP otherwise 0. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hourlyBareMetalInstances" name=hourlyBareMetalInstances>hourlyBareMetalInstances</a>
            </span>
            <div class='views-field-body'>An account's associated hourly bare metal server objects. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hourlyServiceBillingItems" name=hourlyServiceBillingItems>hourlyServiceBillingItems</a>
            </span>
            <div class='views-field-body'>Hourly service billing items that will be on an account's next invoice. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item'>SoftLayer_Billing_Item[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hourlyVirtualGuests" name=hourlyVirtualGuests>hourlyVirtualGuests</a>
            </span>
            <div class='views-field-body'>An account's associated hourly virtual guest objects. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hubNetworkStorage" name=hubNetworkStorage>hubNetworkStorage</a>
            </span>
            <div class='views-field-body'>An account's associated Virtual Storage volumes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#ibmCustomerNumber" name=ibmCustomerNumber>ibmCustomerNumber</a>
            </span>
            <div class='views-field-body'>Unique identifier for a customer used throughout IBM. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#ibmIdAuthenticationRequiredFlag" name=ibmIdAuthenticationRequiredFlag>ibmIdAuthenticationRequiredFlag</a>
            </span>
            <div class='views-field-body'>Indicates whether this account requires IBMid authentication. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#ibmIdMigrationExpirationTimestamp" name=ibmIdMigrationExpirationTimestamp>ibmIdMigrationExpirationTimestamp</a>
            </span>
            <div class='views-field-body'>This key is deprecated and should not be used. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#inProgressExternalAccountSetup" name=inProgressExternalAccountSetup>inProgressExternalAccountSetup</a>
            </span>
            <div class='views-field-body'>An in progress request to switch billing systems. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_External_Setup'>SoftLayer_Account_External_Setup </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#internalNotes" name=internalNotes>internalNotes</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Note'>SoftLayer_Account_Note[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#invoices" name=invoices>invoices</a>
            </span>
            <div class='views-field-body'>An account's associated billing invoices. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Invoice'>SoftLayer_Billing_Invoice[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#ipAddresses" name=ipAddresses>ipAddresses</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet_IpAddress'>SoftLayer_Network_Subnet_IpAddress[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#iscsiIsolationDisabled" name=iscsiIsolationDisabled>iscsiIsolationDisabled</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#iscsiNetworkStorage" name=iscsiNetworkStorage>iscsiNetworkStorage</a>
            </span>
            <div class='views-field-body'>An account's associated iSCSI storage volumes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lastCanceledBillingItem" name=lastCanceledBillingItem>lastCanceledBillingItem</a>
            </span>
            <div class='views-field-body'>The most recently canceled billing item. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item'>SoftLayer_Billing_Item </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lastCancelledServerBillingItem" name=lastCancelledServerBillingItem>lastCancelledServerBillingItem</a>
            </span>
            <div class='views-field-body'>The most recent cancelled server billing item. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item'>SoftLayer_Billing_Item </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lastFiveClosedAbuseTickets" name=lastFiveClosedAbuseTickets>lastFiveClosedAbuseTickets</a>
            </span>
            <div class='views-field-body'>The five most recently closed abuse tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Ticket'>SoftLayer_Ticket[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lastFiveClosedAccountingTickets" name=lastFiveClosedAccountingTickets>lastFiveClosedAccountingTickets</a>
            </span>
            <div class='views-field-body'>The five most recently closed accounting tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Ticket'>SoftLayer_Ticket[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lastFiveClosedOtherTickets" name=lastFiveClosedOtherTickets>lastFiveClosedOtherTickets</a>
            </span>
            <div class='views-field-body'>The five most recently closed tickets that do not belong to the abuse, accounting, sales, or support groups associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Ticket'>SoftLayer_Ticket[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lastFiveClosedSalesTickets" name=lastFiveClosedSalesTickets>lastFiveClosedSalesTickets</a>
            </span>
            <div class='views-field-body'>The five most recently closed sales tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Ticket'>SoftLayer_Ticket[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lastFiveClosedSupportTickets" name=lastFiveClosedSupportTickets>lastFiveClosedSupportTickets</a>
            </span>
            <div class='views-field-body'>The five most recently closed support tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Ticket'>SoftLayer_Ticket[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lastFiveClosedTickets" name=lastFiveClosedTickets>lastFiveClosedTickets</a>
            </span>
            <div class='views-field-body'>The five most recently closed tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Ticket'>SoftLayer_Ticket[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#latestBillDate" name=latestBillDate>latestBillDate</a>
            </span>
            <div class='views-field-body'>An account's most recent billing date. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>dateTime</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#latestRecurringInvoice" name=latestRecurringInvoice>latestRecurringInvoice</a>
            </span>
            <div class='views-field-body'>An account's latest recurring invoice. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Invoice'>SoftLayer_Billing_Invoice </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#latestRecurringPendingInvoice" name=latestRecurringPendingInvoice>latestRecurringPendingInvoice</a>
            </span>
            <div class='views-field-body'>An account's latest recurring pending invoice. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Invoice'>SoftLayer_Billing_Invoice </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#legacyBandwidthAllotments" name=legacyBandwidthAllotments>legacyBandwidthAllotments</a>
            </span>
            <div class='views-field-body'>The legacy bandwidth allotments for an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Bandwidth_Version1_Allotment'>SoftLayer_Network_Bandwidth_Version1_Allotment[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#legacyIscsiCapacityGB" name=legacyIscsiCapacityGB>legacyIscsiCapacityGB</a>
            </span>
            <div class='views-field-body'>The total capacity of Legacy iSCSI Volumes on an account, in GB. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsigned integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#loadBalancers" name=loadBalancers>loadBalancers</a>
            </span>
            <div class='views-field-body'>An account's associated load balancers. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_LoadBalancer_VirtualIpAddress'>SoftLayer_Network_LoadBalancer_VirtualIpAddress[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lockboxCapacityGB" name=lockboxCapacityGB>lockboxCapacityGB</a>
            </span>
            <div class='views-field-body'>The total capacity of Legacy lockbox Volumes on an account, in GB. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsigned integer</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lockboxNetworkStorage" name=lockboxNetworkStorage>lockboxNetworkStorage</a>
            </span>
            <div class='views-field-body'>An account's associated Lockbox storage volumes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#manualPaymentsUnderReview" name=manualPaymentsUnderReview>manualPaymentsUnderReview</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Payment_Card_ManualPayment'>SoftLayer_Billing_Payment_Card_ManualPayment[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#masterUser" name=masterUser>masterUser</a>
            </span>
            <div class='views-field-body'>An account's master user. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_User_Customer'>SoftLayer_User_Customer </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#mediaDataTransferRequests" name=mediaDataTransferRequests>mediaDataTransferRequests</a>
            </span>
            <div class='views-field-body'>An account's media transfer service requests. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Media_Data_Transfer_Request'>SoftLayer_Account_Media_Data_Transfer_Request[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#migratedToIbmCloudPortalFlag" name=migratedToIbmCloudPortalFlag>migratedToIbmCloudPortalFlag</a>
            </span>
            <div class='views-field-body'>Flag indicating whether this account is restricted to the IBM Cloud portal. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#monthlyBareMetalInstances" name=monthlyBareMetalInstances>monthlyBareMetalInstances</a>
            </span>
            <div class='views-field-body'>An account's associated monthly bare metal server objects. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#monthlyVirtualGuests" name=monthlyVirtualGuests>monthlyVirtualGuests</a>
            </span>
            <div class='views-field-body'>An account's associated monthly virtual guest objects. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#nasNetworkStorage" name=nasNetworkStorage>nasNetworkStorage</a>
            </span>
            <div class='views-field-body'>An account's associated NAS storage volumes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkCreationFlag" name=networkCreationFlag>networkCreationFlag</a>
            </span>
            <div class='views-field-body'>Whether or not this account can define their own networks. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkGateways" name=networkGateways>networkGateways</a>
            </span>
            <div class='views-field-body'>All network gateway devices on this account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Gateway'>SoftLayer_Network_Gateway[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkHardware" name=networkHardware>networkHardware</a>
            </span>
            <div class='views-field-body'>An account's associated network hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMessageDeliveryAccounts" name=networkMessageDeliveryAccounts>networkMessageDeliveryAccounts</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Message_Delivery'>SoftLayer_Network_Message_Delivery[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMonitorDownHardware" name=networkMonitorDownHardware>networkMonitorDownHardware</a>
            </span>
            <div class='views-field-body'>Hardware which is currently experiencing a service failure. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMonitorDownVirtualGuests" name=networkMonitorDownVirtualGuests>networkMonitorDownVirtualGuests</a>
            </span>
            <div class='views-field-body'>Virtual guest which is currently experiencing a service failure. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMonitorRecoveringHardware" name=networkMonitorRecoveringHardware>networkMonitorRecoveringHardware</a>
            </span>
            <div class='views-field-body'>Hardware which is currently recovering from a service failure. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMonitorRecoveringVirtualGuests" name=networkMonitorRecoveringVirtualGuests>networkMonitorRecoveringVirtualGuests</a>
            </span>
            <div class='views-field-body'>Virtual guest which is currently recovering from a service failure. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMonitorUpHardware" name=networkMonitorUpHardware>networkMonitorUpHardware</a>
            </span>
            <div class='views-field-body'>Hardware which is currently online. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMonitorUpVirtualGuests" name=networkMonitorUpVirtualGuests>networkMonitorUpVirtualGuests</a>
            </span>
            <div class='views-field-body'>Virtual guest which is currently online. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkStorage" name=networkStorage>networkStorage</a>
            </span>
            <div class='views-field-body'>An account's associated storage volumes. This includes Lockbox, NAS, EVault, and iSCSI volumes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkStorageGroups" name=networkStorageGroups>networkStorageGroups</a>
            </span>
            <div class='views-field-body'>An account's Network Storage groups. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage_Group'>SoftLayer_Network_Storage_Group[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkTunnelContexts" name=networkTunnelContexts>networkTunnelContexts</a>
            </span>
            <div class='views-field-body'>IPSec network tunnels for an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Tunnel_Module_Context'>SoftLayer_Network_Tunnel_Module_Context[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkVlanSpan" name=networkVlanSpan>networkVlanSpan</a>
            </span>
            <div class='views-field-body'>Whether or not an account has automatic private VLAN spanning enabled. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Network_Vlan_Span'>SoftLayer_Account_Network_Vlan_Span </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkVlans" name=networkVlans>networkVlans</a>
            </span>
            <div class='views-field-body'>All network VLANs assigned to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Vlan'>SoftLayer_Network_Vlan[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#nextBillingPublicAllotmentHardwareBandwidthDetails" name=nextBillingPublicAllotmentHardwareBandwidthDetails>nextBillingPublicAllotmentHardwareBandwidthDetails</a>
            </span>
            <div class='views-field-body'>DEPRECATED - This information can be pulled directly through tapping keys now - DEPRECATED. The allotments for this account and their servers for the next billing cycle. The public inbound and outbound bandwidth is calculated for each server in addition to the daily average network traffic since the last billing date. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Bandwidth_Version1_Allotment'>SoftLayer_Network_Bandwidth_Version1_Allotment[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#nextInvoiceIncubatorExemptTotal" name=nextInvoiceIncubatorExemptTotal>nextInvoiceIncubatorExemptTotal</a>
            </span>
            <div class='views-field-body'>The pre-tax total amount exempt from incubator credit for the account's next invoice. This field is now deprecated and will soon be removed. Please update all references to instead use nextInvoiceTotalAmount </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#nextInvoiceRecurringAmountEligibleForAccountDiscount" name=nextInvoiceRecurringAmountEligibleForAccountDiscount>nextInvoiceRecurringAmountEligibleForAccountDiscount</a>
            </span>
            <div class='views-field-body'>The total recurring charge amount of an account's next invoice eligible for account discount measured in US Dollars ($USD), assuming no changes or charges occur between now and time of billing. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#nextInvoiceTopLevelBillingItems" name=nextInvoiceTopLevelBillingItems>nextInvoiceTopLevelBillingItems</a>
            </span>
            <div class='views-field-body'>The billing items that will be on an account's next invoice. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item'>SoftLayer_Billing_Item[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#nextInvoiceTotalAmount" name=nextInvoiceTotalAmount>nextInvoiceTotalAmount</a>
            </span>
            <div class='views-field-body'>The pre-tax total amount of an account's next invoice measured in US Dollars ($USD), assuming no changes or charges occur between now and time of billing. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>float</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#nextInvoiceTotalOneTimeAmount" name=nextInvoiceTotalOneTimeAmount>nextInvoiceTotalOneTimeAmount</a>
            </span>
            <div class='views-field-body'>The total one-time charge amount of an account's next invoice measured in US Dollars ($USD), assuming no changes or charges occur between now and time of billing. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#nextInvoiceTotalOneTimeTaxAmount" name=nextInvoiceTotalOneTimeTaxAmount>nextInvoiceTotalOneTimeTaxAmount</a>
            </span>
            <div class='views-field-body'>The total one-time tax amount of an account's next invoice measured in US Dollars ($USD), assuming no changes or charges occur between now and time of billing. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#nextInvoiceTotalRecurringAmount" name=nextInvoiceTotalRecurringAmount>nextInvoiceTotalRecurringAmount</a>
            </span>
            <div class='views-field-body'>The total recurring charge amount of an account's next invoice measured in US Dollars ($USD), assuming no changes or charges occur between now and time of billing. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#nextInvoiceTotalRecurringAmountBeforeAccountDiscount" name=nextInvoiceTotalRecurringAmountBeforeAccountDiscount>nextInvoiceTotalRecurringAmountBeforeAccountDiscount</a>
            </span>
            <div class='views-field-body'>The total recurring charge amount of an account's next invoice measured in US Dollars ($USD), assuming no changes or charges occur between now and time of billing. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#nextInvoiceTotalRecurringTaxAmount" name=nextInvoiceTotalRecurringTaxAmount>nextInvoiceTotalRecurringTaxAmount</a>
            </span>
            <div class='views-field-body'>The total recurring tax amount of an account's next invoice measured in US Dollars ($USD), assuming no changes or charges occur between now and time of billing. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>float</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#nextInvoiceTotalTaxableRecurringAmount" name=nextInvoiceTotalTaxableRecurringAmount>nextInvoiceTotalTaxableRecurringAmount</a>
            </span>
            <div class='views-field-body'>The total recurring charge amount of an account's next invoice measured in US Dollars ($USD), assuming no changes or charges occur between now and time of billing. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#notificationSubscribers" name=notificationSubscribers>notificationSubscribers</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Notification_Subscriber'>SoftLayer_Notification_Subscriber[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openAbuseTickets" name=openAbuseTickets>openAbuseTickets</a>
            </span>
            <div class='views-field-body'>The open abuse tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Ticket'>SoftLayer_Ticket[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openAccountingTickets" name=openAccountingTickets>openAccountingTickets</a>
            </span>
            <div class='views-field-body'>The open accounting tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Ticket'>SoftLayer_Ticket[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openBillingTickets" name=openBillingTickets>openBillingTickets</a>
            </span>
            <div class='views-field-body'>The open billing tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Ticket'>SoftLayer_Ticket[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openCancellationRequests" name=openCancellationRequests>openCancellationRequests</a>
            </span>
            <div class='views-field-body'>An open ticket requesting cancellation of this server, if one exists. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item_Cancellation_Request'>SoftLayer_Billing_Item_Cancellation_Request[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openOtherTickets" name=openOtherTickets>openOtherTickets</a>
            </span>
            <div class='views-field-body'>The open tickets that do not belong to the abuse, accounting, sales, or support groups associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Ticket'>SoftLayer_Ticket[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openRecurringInvoices" name=openRecurringInvoices>openRecurringInvoices</a>
            </span>
            <div class='views-field-body'>An account's recurring invoices. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Invoice'>SoftLayer_Billing_Invoice[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openSalesTickets" name=openSalesTickets>openSalesTickets</a>
            </span>
            <div class='views-field-body'>The open sales tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Ticket'>SoftLayer_Ticket[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openStackAccountLinks" name=openStackAccountLinks>openStackAccountLinks</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Link'>SoftLayer_Account_Link[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openStackObjectStorage" name=openStackObjectStorage>openStackObjectStorage</a>
            </span>
            <div class='views-field-body'>An account's associated Openstack related Object Storage accounts. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openSupportTickets" name=openSupportTickets>openSupportTickets</a>
            </span>
            <div class='views-field-body'>The open support tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Ticket'>SoftLayer_Ticket[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openTickets" name=openTickets>openTickets</a>
            </span>
            <div class='views-field-body'>All open tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Ticket'>SoftLayer_Ticket[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openTicketsWaitingOnCustomer" name=openTicketsWaitingOnCustomer>openTicketsWaitingOnCustomer</a>
            </span>
            <div class='views-field-body'>All open tickets associated with an account last edited by an employee. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Ticket'>SoftLayer_Ticket[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#orders" name=orders>orders</a>
            </span>
            <div class='views-field-body'>An account's associated billing orders excluding upgrades. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Order'>SoftLayer_Billing_Order[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#orphanBillingItems" name=orphanBillingItems>orphanBillingItems</a>
            </span>
            <div class='views-field-body'>The billing items that have no parent billing item. These are items that don't necessarily belong to a single server. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item'>SoftLayer_Billing_Item[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#ownedBrands" name=ownedBrands>ownedBrands</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Brand'>SoftLayer_Brand[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#ownedHardwareGenericComponentModels" name=ownedHardwareGenericComponentModels>ownedHardwareGenericComponentModels</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Component_Model_Generic'>SoftLayer_Hardware_Component_Model_Generic[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#paymentProcessors" name=paymentProcessors>paymentProcessors</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Payment_Processor'>SoftLayer_Billing_Payment_Processor[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#pendingEvents" name=pendingEvents>pendingEvents</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Notification_Occurrence_Event'>SoftLayer_Notification_Occurrence_Event[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#pendingInvoice" name=pendingInvoice>pendingInvoice</a>
            </span>
            <div class='views-field-body'>An account's latest open (pending) invoice. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Invoice'>SoftLayer_Billing_Invoice </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#pendingInvoiceTopLevelItems" name=pendingInvoiceTopLevelItems>pendingInvoiceTopLevelItems</a>
            </span>
            <div class='views-field-body'>A list of top-level invoice items that are on an account's currently pending invoice. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Invoice_Item'>SoftLayer_Billing_Invoice_Item[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#pendingInvoiceTotalAmount" name=pendingInvoiceTotalAmount>pendingInvoiceTotalAmount</a>
            </span>
            <div class='views-field-body'>The total amount of an account's pending invoice, if one exists. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#pendingInvoiceTotalOneTimeAmount" name=pendingInvoiceTotalOneTimeAmount>pendingInvoiceTotalOneTimeAmount</a>
            </span>
            <div class='views-field-body'>The total one-time charges for an account's pending invoice, if one exists. In other words, it is the sum of one-time charges, setup fees, and labor fees. It does not include taxes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#pendingInvoiceTotalOneTimeTaxAmount" name=pendingInvoiceTotalOneTimeTaxAmount>pendingInvoiceTotalOneTimeTaxAmount</a>
            </span>
            <div class='views-field-body'>The sum of all the taxes related to one time charges for an account's pending invoice, if one exists. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#pendingInvoiceTotalRecurringAmount" name=pendingInvoiceTotalRecurringAmount>pendingInvoiceTotalRecurringAmount</a>
            </span>
            <div class='views-field-body'>The total recurring amount of an account's pending invoice, if one exists. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#pendingInvoiceTotalRecurringTaxAmount" name=pendingInvoiceTotalRecurringTaxAmount>pendingInvoiceTotalRecurringTaxAmount</a>
            </span>
            <div class='views-field-body'>The total amount of the recurring taxes on an account's pending invoice, if one exists. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#permissionGroups" name=permissionGroups>permissionGroups</a>
            </span>
            <div class='views-field-body'>An account's permission groups. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_User_Permission_Group'>SoftLayer_User_Permission_Group[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#permissionRoles" name=permissionRoles>permissionRoles</a>
            </span>
            <div class='views-field-body'>An account's user roles. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_User_Permission_Role'>SoftLayer_User_Permission_Role[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#placementGroups" name=placementGroups>placementGroups</a>
            </span>
            <div class='views-field-body'>An account's associated virtual placement groups. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_PlacementGroup'>SoftLayer_Virtual_PlacementGroup[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#portableStorageVolumes" name=portableStorageVolumes>portableStorageVolumes</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Disk_Image'>SoftLayer_Virtual_Disk_Image[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#postProvisioningHooks" name=postProvisioningHooks>postProvisioningHooks</a>
            </span>
            <div class='views-field-body'>Customer specified URIs that are downloaded onto a newly provisioned or reloaded server. If the URI is sent over https it will be executed directly on the server. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Provisioning_Hook'>SoftLayer_Provisioning_Hook[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#pptpVpnAllowedFlag" name=pptpVpnAllowedFlag>pptpVpnAllowedFlag</a>
            </span>
            <div class='views-field-body'>Boolean flag dictating whether or not this account supports PPTP VPN Access. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#pptpVpnUsers" name=pptpVpnUsers>pptpVpnUsers</a>
            </span>
            <div class='views-field-body'>An account's associated portal users with PPTP VPN access. (Deprecated) </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_User_Customer'>SoftLayer_User_Customer[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#previousRecurringRevenue" name=previousRecurringRevenue>previousRecurringRevenue</a>
            </span>
            <div class='views-field-body'>The total recurring amount for an accounts previous revenue. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>decimal</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#priceRestrictions" name=priceRestrictions>priceRestrictions</a>
            </span>
            <div class='views-field-body'>The item price that an account is restricted to. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Product_Item_Price_Account_Restriction'>SoftLayer_Product_Item_Price_Account_Restriction[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#priorityOneTickets" name=priorityOneTickets>priorityOneTickets</a>
            </span>
            <div class='views-field-body'>All priority one tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Ticket'>SoftLayer_Ticket[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#privateAllotmentHardwareBandwidthDetails" name=privateAllotmentHardwareBandwidthDetails>privateAllotmentHardwareBandwidthDetails</a>
            </span>
            <div class='views-field-body'>DEPRECATED - This information can be pulled directly through tapping keys now - DEPRECATED. The allotments for this account and their servers. The private inbound and outbound bandwidth is calculated for each server in addition to the daily average network traffic since the last billing date. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Bandwidth_Version1_Allotment'>SoftLayer_Network_Bandwidth_Version1_Allotment[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#privateBlockDeviceTemplateGroups" name=privateBlockDeviceTemplateGroups>privateBlockDeviceTemplateGroups</a>
            </span>
            <div class='views-field-body'>Private and shared template group objects (parent only) for an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest_Block_Device_Template_Group'>SoftLayer_Virtual_Guest_Block_Device_Template_Group[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#privateIpAddresses" name=privateIpAddresses>privateIpAddresses</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet_IpAddress'>SoftLayer_Network_Subnet_IpAddress[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#privateNetworkVlans" name=privateNetworkVlans>privateNetworkVlans</a>
            </span>
            <div class='views-field-body'>The private network VLANs assigned to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Vlan'>SoftLayer_Network_Vlan[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#privateSubnets" name=privateSubnets>privateSubnets</a>
            </span>
            <div class='views-field-body'>All private subnets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet'>SoftLayer_Network_Subnet[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#proofOfConceptAccountFlag" name=proofOfConceptAccountFlag>proofOfConceptAccountFlag</a>
            </span>
            <div class='views-field-body'>Boolean flag indicating whether or not this account is a Proof of Concept account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#publicAllotmentHardwareBandwidthDetails" name=publicAllotmentHardwareBandwidthDetails>publicAllotmentHardwareBandwidthDetails</a>
            </span>
            <div class='views-field-body'>DEPRECATED - This information can be pulled directly through tapping keys now - DEPRECATED. The allotments for this account and their servers. The public inbound and outbound bandwidth is calculated for each server in addition to the daily average network traffic since the last billing date. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Bandwidth_Version1_Allotment'>SoftLayer_Network_Bandwidth_Version1_Allotment[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#publicIpAddresses" name=publicIpAddresses>publicIpAddresses</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet_IpAddress'>SoftLayer_Network_Subnet_IpAddress[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#publicNetworkVlans" name=publicNetworkVlans>publicNetworkVlans</a>
            </span>
            <div class='views-field-body'>The public network VLANs assigned to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Vlan'>SoftLayer_Network_Vlan[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#publicSubnets" name=publicSubnets>publicSubnets</a>
            </span>
            <div class='views-field-body'>All public network subnets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet'>SoftLayer_Network_Subnet[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#quotes" name=quotes>quotes</a>
            </span>
            <div class='views-field-body'>An account's quotes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Order_Quote'>SoftLayer_Billing_Order_Quote[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#recentEvents" name=recentEvents>recentEvents</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Notification_Occurrence_Event'>SoftLayer_Notification_Occurrence_Event[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#referralPartner" name=referralPartner>referralPartner</a>
            </span>
            <div class='views-field-body'>The Referral Partner for this account, if any. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account'>SoftLayer_Account </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#referredAccounts" name=referredAccounts>referredAccounts</a>
            </span>
            <div class='views-field-body'>If this is a account is a referral partner, the accounts this referral partner has referred </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account'>SoftLayer_Account[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#regulatedWorkloads" name=regulatedWorkloads>regulatedWorkloads</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Legal_RegulatedWorkload'>SoftLayer_Legal_RegulatedWorkload[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#remoteManagementCommandRequests" name=remoteManagementCommandRequests>remoteManagementCommandRequests</a>
            </span>
            <div class='views-field-body'>Remote management command requests for an account </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware_Component_RemoteManagement_Command_Request'>SoftLayer_Hardware_Component_RemoteManagement_Command_Request[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#replicationEvents" name=replicationEvents>replicationEvents</a>
            </span>
            <div class='views-field-body'>The Replication events for all Network Storage volumes on an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Storage_Event'>SoftLayer_Network_Storage_Event[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#requireSilentIBMidUserCreation" name=requireSilentIBMidUserCreation>requireSilentIBMidUserCreation</a>
            </span>
            <div class='views-field-body'>Indicates whether newly created users under this account will be associated with IBMid via an email requiring a response, or not. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#reservedCapacityAgreements" name=reservedCapacityAgreements>reservedCapacityAgreements</a>
            </span>
            <div class='views-field-body'>All reserved capacity agreements for an account </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Agreement'>SoftLayer_Account_Agreement[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#reservedCapacityGroups" name=reservedCapacityGroups>reservedCapacityGroups</a>
            </span>
            <div class='views-field-body'>The reserved capacity groups owned by this account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_ReservedCapacityGroup'>SoftLayer_Virtual_ReservedCapacityGroup[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#resourceGroups" name=resourceGroups>resourceGroups</a>
            </span>
            <div class='views-field-body'>An account's associated top-level resource groups. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Resource_Group'>SoftLayer_Resource_Group[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#routers" name=routers>routers</a>
            </span>
            <div class='views-field-body'>All Routers that an accounts VLANs reside on </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Hardware'>SoftLayer_Hardware[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#rwhoisData" name=rwhoisData>rwhoisData</a>
            </span>
            <div class='views-field-body'>An account's reverse WHOIS data. This data is used when making SWIP requests. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet_Rwhois_Data'>SoftLayer_Network_Subnet_Rwhois_Data </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#samlAuthentication" name=samlAuthentication>samlAuthentication</a>
            </span>
            <div class='views-field-body'>The SAML configuration for this account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Authentication_Saml'>SoftLayer_Account_Authentication_Saml </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#scaleGroups" name=scaleGroups>scaleGroups</a>
            </span>
            <div class='views-field-body'>All scale groups on this account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Scale_Group'>SoftLayer_Scale_Group[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#secondaryDomains" name=secondaryDomains>secondaryDomains</a>
            </span>
            <div class='views-field-body'>The secondary DNS records for a SoftLayer customer account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Dns_Secondary'>SoftLayer_Dns_Secondary[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#securityCertificates" name=securityCertificates>securityCertificates</a>
            </span>
            <div class='views-field-body'>Stored security certificates (ie. SSL) </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Security_Certificate'>SoftLayer_Security_Certificate[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#securityGroups" name=securityGroups>securityGroups</a>
            </span>
            <div class='views-field-body'>The security groups belonging to this account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_SecurityGroup'>SoftLayer_Network_SecurityGroup[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#securityLevel" name=securityLevel>securityLevel</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Security_Level'>SoftLayer_Security_Level </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#securityScanRequests" name=securityScanRequests>securityScanRequests</a>
            </span>
            <div class='views-field-body'>An account's vulnerability scan requests. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Security_Scanner_Request'>SoftLayer_Network_Security_Scanner_Request[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#serviceBillingItems" name=serviceBillingItems>serviceBillingItems</a>
            </span>
            <div class='views-field-body'>The service billing items that will be on an account's next invoice.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item'>SoftLayer_Billing_Item[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#shipments" name=shipments>shipments</a>
            </span>
            <div class='views-field-body'>Shipments that belong to the customer's account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Shipment'>SoftLayer_Account_Shipment[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#sshKeys" name=sshKeys>sshKeys</a>
            </span>
            <div class='views-field-body'>Customer specified SSH keys that can be implemented onto a newly provisioned or reloaded server. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Security_Ssh_Key'>SoftLayer_Security_Ssh_Key[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#sslVpnUsers" name=sslVpnUsers>sslVpnUsers</a>
            </span>
            <div class='views-field-body'>An account's associated portal users with SSL VPN access. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_User_Customer'>SoftLayer_User_Customer[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#standardPoolVirtualGuests" name=standardPoolVirtualGuests>standardPoolVirtualGuests</a>
            </span>
            <div class='views-field-body'>An account's virtual guest objects that are hosted on a user provisioned hypervisor. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#subnetRegistrationDetails" name=subnetRegistrationDetails>subnetRegistrationDetails</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Account_Regional_Registry_Detail'>SoftLayer_Account_Regional_Registry_Detail[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#subnetRegistrations" name=subnetRegistrations>subnetRegistrations</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet_Registration'>SoftLayer_Network_Subnet_Registration[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#subnets" name=subnets>subnets</a>
            </span>
            <div class='views-field-body'>All network subnets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Subnet'>SoftLayer_Network_Subnet[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#supportRepresentatives" name=supportRepresentatives>supportRepresentatives</a>
            </span>
            <div class='views-field-body'>The SoftLayer employees that an account is assigned to. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_User_Employee'>SoftLayer_User_Employee[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#supportSubscriptions" name=supportSubscriptions>supportSubscriptions</a>
            </span>
            <div class='views-field-body'>The active support subscriptions for this account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Billing_Item'>SoftLayer_Billing_Item[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#supportTier" name=supportTier>supportTier</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>string</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#suppressInvoicesFlag" name=suppressInvoicesFlag>suppressInvoicesFlag</a>
            </span>
            <div class='views-field-body'>A flag indicating to suppress invoices. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#tags" name=tags>tags</a>
            </span>
            <div class='views-field-body'> </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Tag'>SoftLayer_Tag[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#tickets" name=tickets>tickets</a>
            </span>
            <div class='views-field-body'>An account's associated tickets. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Ticket'>SoftLayer_Ticket[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#ticketsClosedInTheLastThreeDays" name=ticketsClosedInTheLastThreeDays>ticketsClosedInTheLastThreeDays</a>
            </span>
            <div class='views-field-body'>Tickets closed within the last 72 hours or last 10 tickets, whichever is less, associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Ticket'>SoftLayer_Ticket[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#ticketsClosedToday" name=ticketsClosedToday>ticketsClosedToday</a>
            </span>
            <div class='views-field-body'>Tickets closed today associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Ticket'>SoftLayer_Ticket[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#transcodeAccounts" name=transcodeAccounts>transcodeAccounts</a>
            </span>
            <div class='views-field-body'>An account's associated Transcode account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Media_Transcode_Account'>SoftLayer_Network_Media_Transcode_Account[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#upgradeRequests" name=upgradeRequests>upgradeRequests</a>
            </span>
            <div class='views-field-body'>An account's associated upgrade requests. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Product_Upgrade_Request'>SoftLayer_Product_Upgrade_Request[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#users" name=users>users</a>
            </span>
            <div class='views-field-body'>An account's portal users. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_User_Customer'>SoftLayer_User_Customer[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#validSecurityCertificates" name=validSecurityCertificates>validSecurityCertificates</a>
            </span>
            <div class='views-field-body'>Stored security certificates that are not expired (ie. SSL) </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Security_Certificate'>SoftLayer_Security_Certificate[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#vdrUpdatesInProgressFlag" name=vdrUpdatesInProgressFlag>vdrUpdatesInProgressFlag</a>
            </span>
            <div class='views-field-body'>Return 0 if vpn updates are currently in progress on this account otherwise 1. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>boolean</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualDedicatedRacks" name=virtualDedicatedRacks>virtualDedicatedRacks</a>
            </span>
            <div class='views-field-body'>The bandwidth pooling for this account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Bandwidth_Version1_Allotment'>SoftLayer_Network_Bandwidth_Version1_Allotment[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualDiskImages" name=virtualDiskImages>virtualDiskImages</a>
            </span>
            <div class='views-field-body'>An account's associated virtual server virtual disk images. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Disk_Image'>SoftLayer_Virtual_Disk_Image[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuests" name=virtualGuests>virtualGuests</a>
            </span>
            <div class='views-field-body'>An account's associated virtual guest objects. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestsOverBandwidthAllocation" name=virtualGuestsOverBandwidthAllocation>virtualGuestsOverBandwidthAllocation</a>
            </span>
            <div class='views-field-body'>An account's associated virtual guest objects currently over bandwidth allocation. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestsProjectedOverBandwidthAllocation" name=virtualGuestsProjectedOverBandwidthAllocation>virtualGuestsProjectedOverBandwidthAllocation</a>
            </span>
            <div class='views-field-body'>An account's associated virtual guest objects currently over bandwidth allocation. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestsWithCpanel" name=virtualGuestsWithCpanel>virtualGuestsWithCpanel</a>
            </span>
            <div class='views-field-body'>All virtual guests associated with an account that has the cPanel web hosting control panel installed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestsWithMcafee" name=virtualGuestsWithMcafee>virtualGuestsWithMcafee</a>
            </span>
            <div class='views-field-body'>All virtual guests associated with an account that have McAfee Secure software components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestsWithMcafeeAntivirusRedhat" name=virtualGuestsWithMcafeeAntivirusRedhat>virtualGuestsWithMcafeeAntivirusRedhat</a>
            </span>
            <div class='views-field-body'>All virtual guests associated with an account that have McAfee Secure AntiVirus for Redhat software components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestsWithMcafeeAntivirusWindows" name=virtualGuestsWithMcafeeAntivirusWindows>virtualGuestsWithMcafeeAntivirusWindows</a>
            </span>
            <div class='views-field-body'>All virtual guests associated with an account that has McAfee Secure AntiVirus for Windows software components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestsWithMcafeeIntrusionDetectionSystem" name=virtualGuestsWithMcafeeIntrusionDetectionSystem>virtualGuestsWithMcafeeIntrusionDetectionSystem</a>
            </span>
            <div class='views-field-body'>All virtual guests associated with an account that has McAfee Secure Intrusion Detection System software components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestsWithPlesk" name=virtualGuestsWithPlesk>virtualGuestsWithPlesk</a>
            </span>
            <div class='views-field-body'>All virtual guests associated with an account that has the Plesk web hosting control panel installed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestsWithQuantastor" name=virtualGuestsWithQuantastor>virtualGuestsWithQuantastor</a>
            </span>
            <div class='views-field-body'>All virtual guests associated with an account that have the QuantaStor storage system installed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestsWithUrchin" name=virtualGuestsWithUrchin>virtualGuestsWithUrchin</a>
            </span>
            <div class='views-field-body'>All virtual guests associated with an account that has the Urchin web traffic analytics package installed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualPrivateRack" name=virtualPrivateRack>virtualPrivateRack</a>
            </span>
            <div class='views-field-body'>The bandwidth pooling for this account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Network_Bandwidth_Version1_Allotment'>SoftLayer_Network_Bandwidth_Version1_Allotment </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualStorageArchiveRepositories" name=virtualStorageArchiveRepositories>virtualStorageArchiveRepositories</a>
            </span>
            <div class='views-field-body'>An account's associated virtual server archived storage repositories. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Storage_Repository'>SoftLayer_Virtual_Storage_Repository[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualStoragePublicRepositories" name=virtualStoragePublicRepositories>virtualStoragePublicRepositories</a>
            </span>
            <div class='views-field-body'>An account's associated virtual server public storage repositories. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Storage_Repository'>SoftLayer_Virtual_Storage_Repository[] </a></p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#vpcVirtualGuests" name=vpcVirtualGuests>vpcVirtualGuests</a>
            </span>
            <div class='views-field-body'>An account's associated VPC configured virtual guest objects. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p><a href='/reference/datatypes/SoftLayer_Virtual_Guest'>SoftLayer_Virtual_Guest[] </a></p>
            </div>
        </div>
                <h2>Count</h2>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#abuseEmailCount" name=abuseEmailCount>abuseEmailCount</a>
            </span>
            <div class='views-field-body'>A count of email addresses that are responsible for abuse and legal inquiries on behalf of an account. For instance, new legal and abuse tickets are sent to these addresses. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#accountContactCount" name=accountContactCount>accountContactCount</a>
            </span>
            <div class='views-field-body'>A count of the account contacts on an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#accountLicenseCount" name=accountLicenseCount>accountLicenseCount</a>
            </span>
            <div class='views-field-body'>A count of the account software licenses owned by an account </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#accountLinkCount" name=accountLinkCount>accountLinkCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeAccountLicenseCount" name=activeAccountLicenseCount>activeAccountLicenseCount</a>
            </span>
            <div class='views-field-body'>A count of the active account software licenses owned by an account </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeAddressCount" name=activeAddressCount>activeAddressCount</a>
            </span>
            <div class='views-field-body'>A count of the active address(es) that belong to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeAgreementCount" name=activeAgreementCount>activeAgreementCount</a>
            </span>
            <div class='views-field-body'>A count of all active agreements for an account </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeBillingAgreementCount" name=activeBillingAgreementCount>activeBillingAgreementCount</a>
            </span>
            <div class='views-field-body'>A count of all billing agreements for an account </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeColocationContainerCount" name=activeColocationContainerCount>activeColocationContainerCount</a>
            </span>
            <div class='views-field-body'>A count of the account's active top level colocation containers. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeNotificationSubscriberCount" name=activeNotificationSubscriberCount>activeNotificationSubscriberCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeQuoteCount" name=activeQuoteCount>activeQuoteCount</a>
            </span>
            <div class='views-field-body'>A count of an account's non-expired quotes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeReservedCapacityAgreementCount" name=activeReservedCapacityAgreementCount>activeReservedCapacityAgreementCount</a>
            </span>
            <div class='views-field-body'>A count of active reserved capacity agreements for an account </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#activeVirtualLicenseCount" name=activeVirtualLicenseCount>activeVirtualLicenseCount</a>
            </span>
            <div class='views-field-body'>A count of the virtual software licenses controlled by an account </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#adcLoadBalancerCount" name=adcLoadBalancerCount>adcLoadBalancerCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated load balancers. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#addressCount" name=addressCount>addressCount</a>
            </span>
            <div class='views-field-body'>A count of all the address(es) that belong to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allCommissionBillingItemCount" name=allCommissionBillingItemCount>allCommissionBillingItemCount</a>
            </span>
            <div class='views-field-body'>A count of the billing items that will be on an account's next invoice. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allRecurringTopLevelBillingItemCount" name=allRecurringTopLevelBillingItemCount>allRecurringTopLevelBillingItemCount</a>
            </span>
            <div class='views-field-body'>A count of the billing items that will be on an account's next invoice. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allRecurringTopLevelBillingItemsUnfilteredCount" name=allRecurringTopLevelBillingItemsUnfilteredCount>allRecurringTopLevelBillingItemsUnfilteredCount</a>
            </span>
            <div class='views-field-body'>A count of the billing items that will be on an account's next invoice. Does not consider associated items. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allSubnetBillingItemCount" name=allSubnetBillingItemCount>allSubnetBillingItemCount</a>
            </span>
            <div class='views-field-body'>A count of the billing items that will be on an account's next invoice. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allTopLevelBillingItemCount" name=allTopLevelBillingItemCount>allTopLevelBillingItemCount</a>
            </span>
            <div class='views-field-body'>A count of all billing items of an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#allTopLevelBillingItemsUnfilteredCount" name=allTopLevelBillingItemsUnfilteredCount>allTopLevelBillingItemsUnfilteredCount</a>
            </span>
            <div class='views-field-body'>A count of the billing items that will be on an account's next invoice. Does not consider associated items. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#applicationDeliveryControllerCount" name=applicationDeliveryControllerCount>applicationDeliveryControllerCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated application delivery controller records. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#attributeCount" name=attributeCount>attributeCount</a>
            </span>
            <div class='views-field-body'>A count of the account attribute values for a SoftLayer customer account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#availablePublicNetworkVlanCount" name=availablePublicNetworkVlanCount>availablePublicNetworkVlanCount</a>
            </span>
            <div class='views-field-body'>A count of the public network VLANs assigned to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#bandwidthAllotmentCount" name=bandwidthAllotmentCount>bandwidthAllotmentCount</a>
            </span>
            <div class='views-field-body'>A count of the bandwidth allotments for an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#bandwidthAllotmentsOverAllocationCount" name=bandwidthAllotmentsOverAllocationCount>bandwidthAllotmentsOverAllocationCount</a>
            </span>
            <div class='views-field-body'>A count of the bandwidth allotments for an account currently over allocation. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#bandwidthAllotmentsProjectedOverAllocationCount" name=bandwidthAllotmentsProjectedOverAllocationCount>bandwidthAllotmentsProjectedOverAllocationCount</a>
            </span>
            <div class='views-field-body'>A count of the bandwidth allotments for an account projected to go over allocation. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#bareMetalInstanceCount" name=bareMetalInstanceCount>bareMetalInstanceCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated bare metal server objects. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#billingAgreementCount" name=billingAgreementCount>billingAgreementCount</a>
            </span>
            <div class='views-field-body'>A count of all billing agreements for an account </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#blockDeviceTemplateGroupCount" name=blockDeviceTemplateGroupCount>blockDeviceTemplateGroupCount</a>
            </span>
            <div class='views-field-body'>A count of private template group objects (parent and children) and the shared template group objects (parent only) for an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#cartCount" name=cartCount>cartCount</a>
            </span>
            <div class='views-field-body'>A count of an account's active carts. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#catalystEnrollmentCount" name=catalystEnrollmentCount>catalystEnrollmentCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#closedTicketCount" name=closedTicketCount>closedTicketCount</a>
            </span>
            <div class='views-field-body'>A count of all closed tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#datacentersWithSubnetAllocationCount" name=datacentersWithSubnetAllocationCount>datacentersWithSubnetAllocationCount</a>
            </span>
            <div class='views-field-body'>A count of datacenters which contain subnets that the account has access to route. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#dedicatedHostCount" name=dedicatedHostCount>dedicatedHostCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated virtual dedicated host objects. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#displaySupportRepresentativeAssignmentCount" name=displaySupportRepresentativeAssignmentCount>displaySupportRepresentativeAssignmentCount</a>
            </span>
            <div class='views-field-body'>A count of the SoftLayer employees that an account is assigned to. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#domainCount" name=domainCount>domainCount</a>
            </span>
            <div class='views-field-body'>A count of the DNS domains associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#domainRegistrationCount" name=domainRegistrationCount>domainRegistrationCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#domainsWithoutSecondaryDnsRecordCount" name=domainsWithoutSecondaryDnsRecordCount>domainsWithoutSecondaryDnsRecordCount</a>
            </span>
            <div class='views-field-body'>A count of the DNS domains associated with an account that were not created as a result of a secondary DNS zone transfer. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#evaultMasterUserCount" name=evaultMasterUserCount>evaultMasterUserCount</a>
            </span>
            <div class='views-field-body'>A count of an account's master EVault user. This is only used when an account has EVault service. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#evaultNetworkStorageCount" name=evaultNetworkStorageCount>evaultNetworkStorageCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated EVault storage volumes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#expiredSecurityCertificateCount" name=expiredSecurityCertificateCount>expiredSecurityCertificateCount</a>
            </span>
            <div class='views-field-body'>A count of stored security certificates that are expired (ie. SSL) </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#facilityLogCount" name=facilityLogCount>facilityLogCount</a>
            </span>
            <div class='views-field-body'>A count of logs of who entered a colocation area which is assigned to this account, or when a user under this account enters a datacenter. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#flexibleCreditEnrollmentCount" name=flexibleCreditEnrollmentCount>flexibleCreditEnrollmentCount</a>
            </span>
            <div class='views-field-body'>A count of all of the account's current and former Flexible Credit enrollments. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#globalIpRecordCount" name=globalIpRecordCount>globalIpRecordCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#globalIpv4RecordCount" name=globalIpv4RecordCount>globalIpv4RecordCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#globalIpv6RecordCount" name=globalIpv6RecordCount>globalIpv6RecordCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#globalLoadBalancerAccountCount" name=globalLoadBalancerAccountCount>globalLoadBalancerAccountCount</a>
            </span>
            <div class='views-field-body'>A count of the global load balancer accounts for a softlayer customer account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareCount" name=hardwareCount>hardwareCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated hardware objects. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareOverBandwidthAllocationCount" name=hardwareOverBandwidthAllocationCount>hardwareOverBandwidthAllocationCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated hardware objects currently over bandwidth allocation. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareProjectedOverBandwidthAllocationCount" name=hardwareProjectedOverBandwidthAllocationCount>hardwareProjectedOverBandwidthAllocationCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated hardware objects projected to go over bandwidth allocation. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareWithCpanelCount" name=hardwareWithCpanelCount>hardwareWithCpanelCount</a>
            </span>
            <div class='views-field-body'>A count of all hardware associated with an account that has the cPanel web hosting control panel installed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareWithHelmCount" name=hardwareWithHelmCount>hardwareWithHelmCount</a>
            </span>
            <div class='views-field-body'>A count of all hardware associated with an account that has the Helm web hosting control panel installed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareWithMcafeeAntivirusRedhatCount" name=hardwareWithMcafeeAntivirusRedhatCount>hardwareWithMcafeeAntivirusRedhatCount</a>
            </span>
            <div class='views-field-body'>A count of all hardware associated with an account that has McAfee Secure AntiVirus for Redhat software components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareWithMcafeeAntivirusWindowCount" name=hardwareWithMcafeeAntivirusWindowCount>hardwareWithMcafeeAntivirusWindowCount</a>
            </span>
            <div class='views-field-body'>A count of all hardware associated with an account that has McAfee Secure AntiVirus for Windows software components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareWithMcafeeCount" name=hardwareWithMcafeeCount>hardwareWithMcafeeCount</a>
            </span>
            <div class='views-field-body'>A count of all hardware associated with an account that has McAfee Secure software components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareWithMcafeeIntrusionDetectionSystemCount" name=hardwareWithMcafeeIntrusionDetectionSystemCount>hardwareWithMcafeeIntrusionDetectionSystemCount</a>
            </span>
            <div class='views-field-body'>A count of all hardware associated with an account that has McAfee Secure Intrusion Detection System software components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareWithPleskCount" name=hardwareWithPleskCount>hardwareWithPleskCount</a>
            </span>
            <div class='views-field-body'>A count of all hardware associated with an account that has the Plesk web hosting control panel installed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareWithQuantastorCount" name=hardwareWithQuantastorCount>hardwareWithQuantastorCount</a>
            </span>
            <div class='views-field-body'>A count of all hardware associated with an account that has the QuantaStor storage system installed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareWithUrchinCount" name=hardwareWithUrchinCount>hardwareWithUrchinCount</a>
            </span>
            <div class='views-field-body'>A count of all hardware associated with an account that has the Urchin web traffic analytics package installed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hardwareWithWindowCount" name=hardwareWithWindowCount>hardwareWithWindowCount</a>
            </span>
            <div class='views-field-body'>A count of all hardware associated with an account that is running a version of the Microsoft Windows operating system. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hourlyBareMetalInstanceCount" name=hourlyBareMetalInstanceCount>hourlyBareMetalInstanceCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated hourly bare metal server objects. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hourlyServiceBillingItemCount" name=hourlyServiceBillingItemCount>hourlyServiceBillingItemCount</a>
            </span>
            <div class='views-field-body'>A count of hourly service billing items that will be on an account's next invoice. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hourlyVirtualGuestCount" name=hourlyVirtualGuestCount>hourlyVirtualGuestCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated hourly virtual guest objects. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#hubNetworkStorageCount" name=hubNetworkStorageCount>hubNetworkStorageCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated Virtual Storage volumes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#internalNoteCount" name=internalNoteCount>internalNoteCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#invoiceCount" name=invoiceCount>invoiceCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated billing invoices. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#ipAddressCount" name=ipAddressCount>ipAddressCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#iscsiNetworkStorageCount" name=iscsiNetworkStorageCount>iscsiNetworkStorageCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated iSCSI storage volumes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lastFiveClosedAbuseTicketCount" name=lastFiveClosedAbuseTicketCount>lastFiveClosedAbuseTicketCount</a>
            </span>
            <div class='views-field-body'>A count of the five most recently closed abuse tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lastFiveClosedAccountingTicketCount" name=lastFiveClosedAccountingTicketCount>lastFiveClosedAccountingTicketCount</a>
            </span>
            <div class='views-field-body'>A count of the five most recently closed accounting tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lastFiveClosedOtherTicketCount" name=lastFiveClosedOtherTicketCount>lastFiveClosedOtherTicketCount</a>
            </span>
            <div class='views-field-body'>A count of the five most recently closed tickets that do not belong to the abuse, accounting, sales, or support groups associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lastFiveClosedSalesTicketCount" name=lastFiveClosedSalesTicketCount>lastFiveClosedSalesTicketCount</a>
            </span>
            <div class='views-field-body'>A count of the five most recently closed sales tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lastFiveClosedSupportTicketCount" name=lastFiveClosedSupportTicketCount>lastFiveClosedSupportTicketCount</a>
            </span>
            <div class='views-field-body'>A count of the five most recently closed support tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lastFiveClosedTicketCount" name=lastFiveClosedTicketCount>lastFiveClosedTicketCount</a>
            </span>
            <div class='views-field-body'>A count of the five most recently closed tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#legacyBandwidthAllotmentCount" name=legacyBandwidthAllotmentCount>legacyBandwidthAllotmentCount</a>
            </span>
            <div class='views-field-body'>A count of the legacy bandwidth allotments for an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#loadBalancerCount" name=loadBalancerCount>loadBalancerCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated load balancers. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#lockboxNetworkStorageCount" name=lockboxNetworkStorageCount>lockboxNetworkStorageCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated Lockbox storage volumes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#manualPaymentsUnderReviewCount" name=manualPaymentsUnderReviewCount>manualPaymentsUnderReviewCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#mediaDataTransferRequestCount" name=mediaDataTransferRequestCount>mediaDataTransferRequestCount</a>
            </span>
            <div class='views-field-body'>A count of an account's media transfer service requests. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#monthlyBareMetalInstanceCount" name=monthlyBareMetalInstanceCount>monthlyBareMetalInstanceCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated monthly bare metal server objects. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#monthlyVirtualGuestCount" name=monthlyVirtualGuestCount>monthlyVirtualGuestCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated monthly virtual guest objects. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#nasNetworkStorageCount" name=nasNetworkStorageCount>nasNetworkStorageCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated NAS storage volumes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkGatewayCount" name=networkGatewayCount>networkGatewayCount</a>
            </span>
            <div class='views-field-body'>A count of all network gateway devices on this account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkHardwareCount" name=networkHardwareCount>networkHardwareCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated network hardware. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMessageDeliveryAccountCount" name=networkMessageDeliveryAccountCount>networkMessageDeliveryAccountCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMonitorDownHardwareCount" name=networkMonitorDownHardwareCount>networkMonitorDownHardwareCount</a>
            </span>
            <div class='views-field-body'>A count of hardware which is currently experiencing a service failure. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMonitorDownVirtualGuestCount" name=networkMonitorDownVirtualGuestCount>networkMonitorDownVirtualGuestCount</a>
            </span>
            <div class='views-field-body'>A count of virtual guest which is currently experiencing a service failure. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMonitorRecoveringHardwareCount" name=networkMonitorRecoveringHardwareCount>networkMonitorRecoveringHardwareCount</a>
            </span>
            <div class='views-field-body'>A count of hardware which is currently recovering from a service failure. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMonitorRecoveringVirtualGuestCount" name=networkMonitorRecoveringVirtualGuestCount>networkMonitorRecoveringVirtualGuestCount</a>
            </span>
            <div class='views-field-body'>A count of virtual guest which is currently recovering from a service failure. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMonitorUpHardwareCount" name=networkMonitorUpHardwareCount>networkMonitorUpHardwareCount</a>
            </span>
            <div class='views-field-body'>A count of hardware which is currently online. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkMonitorUpVirtualGuestCount" name=networkMonitorUpVirtualGuestCount>networkMonitorUpVirtualGuestCount</a>
            </span>
            <div class='views-field-body'>A count of virtual guest which is currently online. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkStorageCount" name=networkStorageCount>networkStorageCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated storage volumes. This includes Lockbox, NAS, EVault, and iSCSI volumes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkStorageGroupCount" name=networkStorageGroupCount>networkStorageGroupCount</a>
            </span>
            <div class='views-field-body'>A count of an account's Network Storage groups. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkTunnelContextCount" name=networkTunnelContextCount>networkTunnelContextCount</a>
            </span>
            <div class='views-field-body'>A count of iPSec network tunnels for an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#networkVlanCount" name=networkVlanCount>networkVlanCount</a>
            </span>
            <div class='views-field-body'>A count of all network VLANs assigned to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#nextBillingPublicAllotmentHardwareBandwidthDetailCount" name=nextBillingPublicAllotmentHardwareBandwidthDetailCount>nextBillingPublicAllotmentHardwareBandwidthDetailCount</a>
            </span>
            <div class='views-field-body'>A count of dEPRECATED - This information can be pulled directly through tapping keys now - DEPRECATED. The allotments for this account and their servers for the next billing cycle. The public inbound and outbound bandwidth is calculated for each server in addition to the daily average network traffic since the last billing date. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#nextInvoiceTopLevelBillingItemCount" name=nextInvoiceTopLevelBillingItemCount>nextInvoiceTopLevelBillingItemCount</a>
            </span>
            <div class='views-field-body'>A count of the billing items that will be on an account's next invoice. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#notificationSubscriberCount" name=notificationSubscriberCount>notificationSubscriberCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openAbuseTicketCount" name=openAbuseTicketCount>openAbuseTicketCount</a>
            </span>
            <div class='views-field-body'>A count of the open abuse tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openAccountingTicketCount" name=openAccountingTicketCount>openAccountingTicketCount</a>
            </span>
            <div class='views-field-body'>A count of the open accounting tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openBillingTicketCount" name=openBillingTicketCount>openBillingTicketCount</a>
            </span>
            <div class='views-field-body'>A count of the open billing tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openCancellationRequestCount" name=openCancellationRequestCount>openCancellationRequestCount</a>
            </span>
            <div class='views-field-body'>A count of an open ticket requesting cancellation of this server, if one exists. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openOtherTicketCount" name=openOtherTicketCount>openOtherTicketCount</a>
            </span>
            <div class='views-field-body'>A count of the open tickets that do not belong to the abuse, accounting, sales, or support groups associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openRecurringInvoiceCount" name=openRecurringInvoiceCount>openRecurringInvoiceCount</a>
            </span>
            <div class='views-field-body'>A count of an account's recurring invoices. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openSalesTicketCount" name=openSalesTicketCount>openSalesTicketCount</a>
            </span>
            <div class='views-field-body'>A count of the open sales tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openStackAccountLinkCount" name=openStackAccountLinkCount>openStackAccountLinkCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openStackObjectStorageCount" name=openStackObjectStorageCount>openStackObjectStorageCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated Openstack related Object Storage accounts. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openSupportTicketCount" name=openSupportTicketCount>openSupportTicketCount</a>
            </span>
            <div class='views-field-body'>A count of the open support tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openTicketCount" name=openTicketCount>openTicketCount</a>
            </span>
            <div class='views-field-body'>A count of all open tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#openTicketsWaitingOnCustomerCount" name=openTicketsWaitingOnCustomerCount>openTicketsWaitingOnCustomerCount</a>
            </span>
            <div class='views-field-body'>A count of all open tickets associated with an account last edited by an employee. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#orderCount" name=orderCount>orderCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated billing orders excluding upgrades. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#orphanBillingItemCount" name=orphanBillingItemCount>orphanBillingItemCount</a>
            </span>
            <div class='views-field-body'>A count of the billing items that have no parent billing item. These are items that don't necessarily belong to a single server. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#ownedBrandCount" name=ownedBrandCount>ownedBrandCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#ownedHardwareGenericComponentModelCount" name=ownedHardwareGenericComponentModelCount>ownedHardwareGenericComponentModelCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#paymentProcessorCount" name=paymentProcessorCount>paymentProcessorCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#pendingEventCount" name=pendingEventCount>pendingEventCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#pendingInvoiceTopLevelItemCount" name=pendingInvoiceTopLevelItemCount>pendingInvoiceTopLevelItemCount</a>
            </span>
            <div class='views-field-body'>A count of a list of top-level invoice items that are on an account's currently pending invoice. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#permissionGroupCount" name=permissionGroupCount>permissionGroupCount</a>
            </span>
            <div class='views-field-body'>A count of an account's permission groups. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#permissionRoleCount" name=permissionRoleCount>permissionRoleCount</a>
            </span>
            <div class='views-field-body'>A count of an account's user roles. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#placementGroupCount" name=placementGroupCount>placementGroupCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated virtual placement groups. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#portableStorageVolumeCount" name=portableStorageVolumeCount>portableStorageVolumeCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#postProvisioningHookCount" name=postProvisioningHookCount>postProvisioningHookCount</a>
            </span>
            <div class='views-field-body'>A count of customer specified URIs that are downloaded onto a newly provisioned or reloaded server. If the URI is sent over https it will be executed directly on the server. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#pptpVpnUserCount" name=pptpVpnUserCount>pptpVpnUserCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated portal users with PPTP VPN access. (Deprecated) </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#priceRestrictionCount" name=priceRestrictionCount>priceRestrictionCount</a>
            </span>
            <div class='views-field-body'>A count of the item price that an account is restricted to. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#priorityOneTicketCount" name=priorityOneTicketCount>priorityOneTicketCount</a>
            </span>
            <div class='views-field-body'>A count of all priority one tickets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#privateAllotmentHardwareBandwidthDetailCount" name=privateAllotmentHardwareBandwidthDetailCount>privateAllotmentHardwareBandwidthDetailCount</a>
            </span>
            <div class='views-field-body'>A count of dEPRECATED - This information can be pulled directly through tapping keys now - DEPRECATED. The allotments for this account and their servers. The private inbound and outbound bandwidth is calculated for each server in addition to the daily average network traffic since the last billing date. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#privateBlockDeviceTemplateGroupCount" name=privateBlockDeviceTemplateGroupCount>privateBlockDeviceTemplateGroupCount</a>
            </span>
            <div class='views-field-body'>A count of private and shared template group objects (parent only) for an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#privateIpAddressCount" name=privateIpAddressCount>privateIpAddressCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#privateNetworkVlanCount" name=privateNetworkVlanCount>privateNetworkVlanCount</a>
            </span>
            <div class='views-field-body'>A count of the private network VLANs assigned to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#privateSubnetCount" name=privateSubnetCount>privateSubnetCount</a>
            </span>
            <div class='views-field-body'>A count of all private subnets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#publicAllotmentHardwareBandwidthDetailCount" name=publicAllotmentHardwareBandwidthDetailCount>publicAllotmentHardwareBandwidthDetailCount</a>
            </span>
            <div class='views-field-body'>A count of dEPRECATED - This information can be pulled directly through tapping keys now - DEPRECATED. The allotments for this account and their servers. The public inbound and outbound bandwidth is calculated for each server in addition to the daily average network traffic since the last billing date. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#publicIpAddressCount" name=publicIpAddressCount>publicIpAddressCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#publicNetworkVlanCount" name=publicNetworkVlanCount>publicNetworkVlanCount</a>
            </span>
            <div class='views-field-body'>A count of the public network VLANs assigned to an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#publicSubnetCount" name=publicSubnetCount>publicSubnetCount</a>
            </span>
            <div class='views-field-body'>A count of all public network subnets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#quoteCount" name=quoteCount>quoteCount</a>
            </span>
            <div class='views-field-body'>A count of an account's quotes. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#recentEventCount" name=recentEventCount>recentEventCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#referredAccountCount" name=referredAccountCount>referredAccountCount</a>
            </span>
            <div class='views-field-body'>A count of if this is a account is a referral partner, the accounts this referral partner has referred </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#regulatedWorkloadCount" name=regulatedWorkloadCount>regulatedWorkloadCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#remoteManagementCommandRequestCount" name=remoteManagementCommandRequestCount>remoteManagementCommandRequestCount</a>
            </span>
            <div class='views-field-body'>A count of remote management command requests for an account </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#replicationEventCount" name=replicationEventCount>replicationEventCount</a>
            </span>
            <div class='views-field-body'>A count of the Replication events for all Network Storage volumes on an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#reservedCapacityAgreementCount" name=reservedCapacityAgreementCount>reservedCapacityAgreementCount</a>
            </span>
            <div class='views-field-body'>A count of all reserved capacity agreements for an account </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#reservedCapacityGroupCount" name=reservedCapacityGroupCount>reservedCapacityGroupCount</a>
            </span>
            <div class='views-field-body'>A count of the reserved capacity groups owned by this account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#resourceGroupCount" name=resourceGroupCount>resourceGroupCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated top-level resource groups. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#routerCount" name=routerCount>routerCount</a>
            </span>
            <div class='views-field-body'>A count of all Routers that an accounts VLANs reside on </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#scaleGroupCount" name=scaleGroupCount>scaleGroupCount</a>
            </span>
            <div class='views-field-body'>A count of all scale groups on this account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#secondaryDomainCount" name=secondaryDomainCount>secondaryDomainCount</a>
            </span>
            <div class='views-field-body'>A count of the secondary DNS records for a SoftLayer customer account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#securityCertificateCount" name=securityCertificateCount>securityCertificateCount</a>
            </span>
            <div class='views-field-body'>A count of stored security certificates (ie. SSL) </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#securityGroupCount" name=securityGroupCount>securityGroupCount</a>
            </span>
            <div class='views-field-body'>A count of the security groups belonging to this account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#securityScanRequestCount" name=securityScanRequestCount>securityScanRequestCount</a>
            </span>
            <div class='views-field-body'>A count of an account's vulnerability scan requests. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#serviceBillingItemCount" name=serviceBillingItemCount>serviceBillingItemCount</a>
            </span>
            <div class='views-field-body'>A count of the service billing items that will be on an account's next invoice.  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#shipmentCount" name=shipmentCount>shipmentCount</a>
            </span>
            <div class='views-field-body'>A count of shipments that belong to the customer's account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#sshKeyCount" name=sshKeyCount>sshKeyCount</a>
            </span>
            <div class='views-field-body'>A count of customer specified SSH keys that can be implemented onto a newly provisioned or reloaded server. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#sslVpnUserCount" name=sslVpnUserCount>sslVpnUserCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated portal users with SSL VPN access. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#standardPoolVirtualGuestCount" name=standardPoolVirtualGuestCount>standardPoolVirtualGuestCount</a>
            </span>
            <div class='views-field-body'>A count of an account's virtual guest objects that are hosted on a user provisioned hypervisor. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#subnetCount" name=subnetCount>subnetCount</a>
            </span>
            <div class='views-field-body'>A count of all network subnets associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#subnetRegistrationCount" name=subnetRegistrationCount>subnetRegistrationCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#subnetRegistrationDetailCount" name=subnetRegistrationDetailCount>subnetRegistrationDetailCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#supportRepresentativeCount" name=supportRepresentativeCount>supportRepresentativeCount</a>
            </span>
            <div class='views-field-body'>A count of the SoftLayer employees that an account is assigned to. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#supportSubscriptionCount" name=supportSubscriptionCount>supportSubscriptionCount</a>
            </span>
            <div class='views-field-body'>A count of the active support subscriptions for this account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#tagCount" name=tagCount>tagCount</a>
            </span>
            <div class='views-field-body'>A count of  </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#ticketCount" name=ticketCount>ticketCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated tickets. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#ticketsClosedInTheLastThreeDaysCount" name=ticketsClosedInTheLastThreeDaysCount>ticketsClosedInTheLastThreeDaysCount</a>
            </span>
            <div class='views-field-body'>A count of tickets closed within the last 72 hours or last 10 tickets, whichever is less, associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#ticketsClosedTodayCount" name=ticketsClosedTodayCount>ticketsClosedTodayCount</a>
            </span>
            <div class='views-field-body'>A count of tickets closed today associated with an account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#transcodeAccountCount" name=transcodeAccountCount>transcodeAccountCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated Transcode account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#upgradeRequestCount" name=upgradeRequestCount>upgradeRequestCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated upgrade requests. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#userCount" name=userCount>userCount</a>
            </span>
            <div class='views-field-body'>A count of an account's portal users. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#validSecurityCertificateCount" name=validSecurityCertificateCount>validSecurityCertificateCount</a>
            </span>
            <div class='views-field-body'>A count of stored security certificates that are not expired (ie. SSL) </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualDedicatedRackCount" name=virtualDedicatedRackCount>virtualDedicatedRackCount</a>
            </span>
            <div class='views-field-body'>A count of the bandwidth pooling for this account. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualDiskImageCount" name=virtualDiskImageCount>virtualDiskImageCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated virtual server virtual disk images. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestCount" name=virtualGuestCount>virtualGuestCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated virtual guest objects. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestsOverBandwidthAllocationCount" name=virtualGuestsOverBandwidthAllocationCount>virtualGuestsOverBandwidthAllocationCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated virtual guest objects currently over bandwidth allocation. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestsProjectedOverBandwidthAllocationCount" name=virtualGuestsProjectedOverBandwidthAllocationCount>virtualGuestsProjectedOverBandwidthAllocationCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated virtual guest objects currently over bandwidth allocation. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestsWithCpanelCount" name=virtualGuestsWithCpanelCount>virtualGuestsWithCpanelCount</a>
            </span>
            <div class='views-field-body'>A count of all virtual guests associated with an account that has the cPanel web hosting control panel installed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestsWithMcafeeAntivirusRedhatCount" name=virtualGuestsWithMcafeeAntivirusRedhatCount>virtualGuestsWithMcafeeAntivirusRedhatCount</a>
            </span>
            <div class='views-field-body'>A count of all virtual guests associated with an account that have McAfee Secure AntiVirus for Redhat software components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestsWithMcafeeAntivirusWindowCount" name=virtualGuestsWithMcafeeAntivirusWindowCount>virtualGuestsWithMcafeeAntivirusWindowCount</a>
            </span>
            <div class='views-field-body'>A count of all virtual guests associated with an account that has McAfee Secure AntiVirus for Windows software components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestsWithMcafeeCount" name=virtualGuestsWithMcafeeCount>virtualGuestsWithMcafeeCount</a>
            </span>
            <div class='views-field-body'>A count of all virtual guests associated with an account that have McAfee Secure software components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestsWithMcafeeIntrusionDetectionSystemCount" name=virtualGuestsWithMcafeeIntrusionDetectionSystemCount>virtualGuestsWithMcafeeIntrusionDetectionSystemCount</a>
            </span>
            <div class='views-field-body'>A count of all virtual guests associated with an account that has McAfee Secure Intrusion Detection System software components. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestsWithPleskCount" name=virtualGuestsWithPleskCount>virtualGuestsWithPleskCount</a>
            </span>
            <div class='views-field-body'>A count of all virtual guests associated with an account that has the Plesk web hosting control panel installed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestsWithQuantastorCount" name=virtualGuestsWithQuantastorCount>virtualGuestsWithQuantastorCount</a>
            </span>
            <div class='views-field-body'>A count of all virtual guests associated with an account that have the QuantaStor storage system installed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualGuestsWithUrchinCount" name=virtualGuestsWithUrchinCount>virtualGuestsWithUrchinCount</a>
            </span>
            <div class='views-field-body'>A count of all virtual guests associated with an account that has the Urchin web traffic analytics package installed. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualStorageArchiveRepositoryCount" name=virtualStorageArchiveRepositoryCount>virtualStorageArchiveRepositoryCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated virtual server archived storage repositories. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#virtualStoragePublicRepositoryCount" name=virtualStoragePublicRepositoryCount>virtualStoragePublicRepositoryCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated virtual server public storage repositories. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
                <div class='prop-row views-row'>
            <span class='views-field-title'>
                <a href="#vpcVirtualGuestCount" name=vpcVirtualGuestCount>vpcVirtualGuestCount</a>
            </span>
            <div class='views-field-body'>A count of an account's associated VPC configured virtual guest objects. </div>
            <span class="type-label">Type:</span> 
            <div class='type-content'>
                <p>unsignedLong</p>
            </div>
        </div>
            </div>
</div>


