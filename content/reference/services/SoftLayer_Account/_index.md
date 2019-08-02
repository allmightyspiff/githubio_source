---
title: "SoftLayer_Account"
description: "Every SoftLayer customer has an account which is defined in the SoftLayer_Account service. SoftLayer accounts have users... "
date: "2018-02-12"
layout: "service"
tags:
    - "service"
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
Every SoftLayer customer has an account which is defined in the SoftLayer_Account service. SoftLayer accounts have users, hardware, and services such as storage and domains associated with them. The SoftLayer_Account service is a convenient way to obtain general information about your SoftLayer account. Use the data returned by these methods with other API services to get more detailed information about your services and to make changes to your servers and services. 

SoftLayer customers are unable to change their company account information in the portal or the API. If you need to change this information please open a sales ticket in our customer portal and our account management staff will assist you. 



        
<div id="properties" class="content">
    <h2>Methods</h2>
    <div class="view-filters">
        <div class="clearfix">
            <div class="search-input-box">
                <input placeholder="Datatype Filter" onkeyup="titleSearch(inputId='edit-combine', divId='method-div', elementClass='method-row')" 
                    type="text" id="edit-combine" value="" size="30" maxlength="128" class="form-text">
            </div>
        </div>
    </div>
    <div id="method-div">
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/activatePartner'> activatePartner</a> </span>
            <div class='views-field-body'>This service enables a partner account that has been created but is currently inactive. This restricted service is only available for certain accounts. Please contact support for questions. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/addAchInformation'> addAchInformation</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/addReferralPartnerPaymentOption'> addReferralPartnerPaymentOption</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/areVdrUpdatesBlockedForBilling'> areVdrUpdatesBlockedForBilling</a> </span>
            <div class='views-field-body'>This method returns true if Bandwidth Pooling updates are blocked so billing can run for this account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/cancelPayPalTransaction'> cancelPayPalTransaction</a> </span>
            <div class='views-field-body'>Cancel the PayPal Payment Request process.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/completePayPalTransaction'> completePayPalTransaction</a> </span>
            <div class='views-field-body'>Complete the PayPal Payment Request process and receive confirmation message.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/countHourlyInstances'> countHourlyInstances</a> </span>
            <div class='views-field-body'>Retrieve the number of hourly services on an account that are active, plus any pending orders with hourly services attached. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/createUser'> createUser</a> </span>
            <div class='views-field-body'>Create a new user record, optionally skipping the IBMid email ("silently").</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/disableEuSupport'> disableEuSupport</a> </span>
            <div class='views-field-body'>Turn off the EU Supported account flag.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/editAccount'> editAccount</a> </span>
            <div class='views-field-body'>Edit an account's information.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/enableEuSupport'> enableEuSupport</a> </span>
            <div class='views-field-body'>Turn on the EU Supported account flag.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAbuseEmail'> getAbuseEmail</a> </span>
            <div class='views-field-body'>Retrieve an email address that is responsible for abuse and legal inquiries on behalf of an account. For instance, new legal and abuse tickets are sent to this address.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAbuseEmails'> getAbuseEmails</a> </span>
            <div class='views-field-body'>Retrieve email addresses that are responsible for abuse and legal inquiries on behalf of an account. For instance, new legal and abuse tickets are sent to these addresses.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAccountBackupHistory'> getAccountBackupHistory</a> </span>
            <div class='views-field-body'>This method provides a history of account backups.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAccountContacts'> getAccountContacts</a> </span>
            <div class='views-field-body'>Retrieve the account contacts on an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAccountLicenses'> getAccountLicenses</a> </span>
            <div class='views-field-body'>Retrieve the account software licenses owned by an account</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAccountLinks'> getAccountLinks</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAccountStatus'> getAccountStatus</a> </span>
            <div class='views-field-body'>Retrieve an account's status presented in a more detailed data type.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAccountTraitValue'> getAccountTraitValue</a> </span>
            <div class='views-field-body'>Get the specific trait by its key</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getActiveAccountDiscountBillingItem'> getActiveAccountDiscountBillingItem</a> </span>
            <div class='views-field-body'>Retrieve the billing item associated with an account's monthly discount.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getActiveAccountLicenses'> getActiveAccountLicenses</a> </span>
            <div class='views-field-body'>Retrieve the active account software licenses owned by an account</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getActiveAddresses'> getActiveAddresses</a> </span>
            <div class='views-field-body'>Retrieve the active address(es) that belong to an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getActiveAgreements'> getActiveAgreements</a> </span>
            <div class='views-field-body'>Retrieve all active agreements for an account</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getActiveAlarms'> getActiveAlarms</a> </span>
            <div class='views-field-body'>Get all active alarms on this account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getActiveBillingAgreements'> getActiveBillingAgreements</a> </span>
            <div class='views-field-body'>Retrieve all billing agreements for an account</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getActiveCatalystEnrollment'> getActiveCatalystEnrollment</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getActiveColocationContainers'> getActiveColocationContainers</a> </span>
            <div class='views-field-body'>Retrieve the account's active top level colocation containers.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getActiveFlexibleCreditEnrollment'> getActiveFlexibleCreditEnrollment</a> </span>
            <div class='views-field-body'>Retrieve account's currently active Flexible Credit enrollment.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getActiveNotificationSubscribers'> getActiveNotificationSubscribers</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getActiveOutletPackages'> getActiveOutletPackages</a> </span>
            <div class='views-field-body'>DEPRECATED. This method will return nothing.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getActivePackages'> getActivePackages</a> </span>
            <div class='views-field-body'>Retrieve the active [[SoftLayer_Product_Package]] objects from which you can order a server, service or software. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getActivePackagesByAttribute'> getActivePackagesByAttribute</a> </span>
            <div class='views-field-body'>[<strong>DEPRECATED</strong>] Retrieve the active [[SoftLayer_Product_Package]] objects from which you can order a server, service or software filtered by an attribute type ([[SoftLayer_Product_Package_Attribute_Type]]) on the package. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getActivePrivateHostedCloudPackages'> getActivePrivateHostedCloudPackages</a> </span>
            <div class='views-field-body'>Get the Active SoftLayer_Product_Packages from which one can order private hosted cloud configurations.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getActiveQuotes'> getActiveQuotes</a> </span>
            <div class='views-field-body'>Retrieve an account's non-expired quotes.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getActiveReservedCapacityAgreements'> getActiveReservedCapacityAgreements</a> </span>
            <div class='views-field-body'>Retrieve active reserved capacity agreements for an account</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getActiveVirtualLicenses'> getActiveVirtualLicenses</a> </span>
            <div class='views-field-body'>Retrieve the virtual software licenses controlled by an account</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAdcLoadBalancers'> getAdcLoadBalancers</a> </span>
            <div class='views-field-body'>Retrieve an account's associated load balancers.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAddresses'> getAddresses</a> </span>
            <div class='views-field-body'>Retrieve all the address(es) that belong to an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAffiliateId'> getAffiliateId</a> </span>
            <div class='views-field-body'>Retrieve an affiliate identifier associated with the customer account. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAggregatedUptimeGraph'> getAggregatedUptimeGraph</a> </span>
            <div class='views-field-body'>Returns URL uptime data for your account</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAllBillingItems'> getAllBillingItems</a> </span>
            <div class='views-field-body'>Retrieve the billing items that will be on an account's next invoice.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAllCommissionBillingItems'> getAllCommissionBillingItems</a> </span>
            <div class='views-field-body'>Retrieve the billing items that will be on an account's next invoice.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAllRecurringTopLevelBillingItems'> getAllRecurringTopLevelBillingItems</a> </span>
            <div class='views-field-body'>Retrieve the billing items that will be on an account's next invoice.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAllRecurringTopLevelBillingItemsUnfiltered'> getAllRecurringTopLevelBillingItemsUnfiltered</a> </span>
            <div class='views-field-body'>Retrieve the billing items that will be on an account's next invoice. Does not consider associated items.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAllSubnetBillingItems'> getAllSubnetBillingItems</a> </span>
            <div class='views-field-body'>Retrieve the billing items that will be on an account's next invoice.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAllTopLevelBillingItems'> getAllTopLevelBillingItems</a> </span>
            <div class='views-field-body'>Retrieve all billing items of an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAllTopLevelBillingItemsUnfiltered'> getAllTopLevelBillingItemsUnfiltered</a> </span>
            <div class='views-field-body'>Retrieve the billing items that will be on an account's next invoice. Does not consider associated items.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAllowIbmIdSilentMigrationFlag'> getAllowIbmIdSilentMigrationFlag</a> </span>
            <div class='views-field-body'>Retrieve indicates whether this account is allowed to silently migrate to use IBMid Authentication.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAllowsBluemixAccountLinkingFlag'> getAllowsBluemixAccountLinkingFlag</a> </span>
            <div class='views-field-body'>Retrieve flag indicating if this account can be linked with Bluemix.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAlternateCreditCardData'> getAlternateCreditCardData</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getApplicationDeliveryControllers'> getApplicationDeliveryControllers</a> </span>
            <div class='views-field-body'>Retrieve an account's associated application delivery controller records.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAttributeByType'> getAttributeByType</a> </span>
            <div class='views-field-body'>Retrieve an account attribute by type key name.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAttributes'> getAttributes</a> </span>
            <div class='views-field-body'>Retrieve the account attribute values for a SoftLayer customer account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAuxiliaryNotifications'> getAuxiliaryNotifications</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAvailablePublicNetworkVlans'> getAvailablePublicNetworkVlans</a> </span>
            <div class='views-field-body'>Retrieve the public network VLANs assigned to an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAverageArchiveUsageMetricDataByDate'> getAverageArchiveUsageMetricDataByDate</a> </span>
            <div class='views-field-body'>Returns the average disk usage for all archive repositories for the timeframe based on the parameters provided. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getAveragePublicUsageMetricDataByDate'> getAveragePublicUsageMetricDataByDate</a> </span>
            <div class='views-field-body'>Returns the average disk usage for all public repositories for the timeframe based on the parameters provided. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getBalance'> getBalance</a> </span>
            <div class='views-field-body'>Retrieve the account balance of a SoftLayer customer account. An account's balance is the amount of money owed to SoftLayer by the account holder, returned as a floating point number with two decimal places, measured in US Dollars ($USD). A negative account balance means the account holder has overpaid and is owed money by SoftLayer.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getBandwidthAllotments'> getBandwidthAllotments</a> </span>
            <div class='views-field-body'>Retrieve the bandwidth allotments for an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getBandwidthAllotmentsOverAllocation'> getBandwidthAllotmentsOverAllocation</a> </span>
            <div class='views-field-body'>Retrieve the bandwidth allotments for an account currently over allocation.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getBandwidthAllotmentsProjectedOverAllocation'> getBandwidthAllotmentsProjectedOverAllocation</a> </span>
            <div class='views-field-body'>Retrieve the bandwidth allotments for an account projected to go over allocation.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getBareMetalInstances'> getBareMetalInstances</a> </span>
            <div class='views-field-body'>Retrieve an account's associated bare metal server objects.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getBillingAgreements'> getBillingAgreements</a> </span>
            <div class='views-field-body'>Retrieve all billing agreements for an account</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getBillingInfo'> getBillingInfo</a> </span>
            <div class='views-field-body'>Retrieve an account's billing information.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getBlockDeviceTemplateGroups'> getBlockDeviceTemplateGroups</a> </span>
            <div class='views-field-body'>Retrieve private template group objects (parent and children) and the shared template group objects (parent only) for an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getBluemixAccountLink'> getBluemixAccountLink</a> </span>
            <div class='views-field-body'>Retrieve the Bluemix account link associated with this SoftLayer account, if one exists.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getBluemixLinkedFlag'> getBluemixLinkedFlag</a> </span>
            <div class='views-field-body'>Retrieve returns true if this account is linked to IBM Bluemix, false if not.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getBrand'> getBrand</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getBrandAccountFlag'> getBrandAccountFlag</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getBrandKeyName'> getBrandKeyName</a> </span>
            <div class='views-field-body'>Retrieve the brand keyName.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getBusinessPartner'> getBusinessPartner</a> </span>
            <div class='views-field-body'>Retrieve the Business Partner details for the account. Country Enterprise Code, Channel, Segment, Reseller Level.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getCanOrderAdditionalVlansFlag'> getCanOrderAdditionalVlansFlag</a> </span>
            <div class='views-field-body'>Retrieve [DEPRECATED] All accounts may order VLANs.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getCarts'> getCarts</a> </span>
            <div class='views-field-body'>Retrieve an account's active carts.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getCatalystEnrollments'> getCatalystEnrollments</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getClosedTickets'> getClosedTickets</a> </span>
            <div class='views-field-body'>Retrieve all closed tickets associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getCurrentBackupStatisticsGraph'> getCurrentBackupStatisticsGraph</a> </span>
            <div class='views-field-body'>This method retrieves a pie chart for today's backup statistics.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getCurrentTicketStatisticsGraph'> getCurrentTicketStatisticsGraph</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getCurrentUser'> getCurrentUser</a> </span>
            <div class='views-field-body'>Retrieve the current API user's record.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getDatacentersWithSubnetAllocations'> getDatacentersWithSubnetAllocations</a> </span>
            <div class='views-field-body'>Retrieve datacenters which contain subnets that the account has access to route.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getDedicatedHosts'> getDedicatedHosts</a> </span>
            <div class='views-field-body'>Retrieve an account's associated virtual dedicated host objects.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getDedicatedHostsForImageTemplate'> getDedicatedHostsForImageTemplate</a> </span>
            <div class='views-field-body'>Get a collection of dedicated hosts that are valid for a given image template. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getDisablePaymentProcessingFlag'> getDisablePaymentProcessingFlag</a> </span>
            <div class='views-field-body'>Retrieve a flag indicating whether payments are processed for this account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getDiskUsageMetricDataByDate'> getDiskUsageMetricDataByDate</a> </span>
            <div class='views-field-body'>Retrieve the metric data for disk space usage for a storage repository from the Metric Tracking Object System and the Legacy Data Warehouse. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getDiskUsageMetricDataFromLegacyByDate'> getDiskUsageMetricDataFromLegacyByDate</a> </span>
            <div class='views-field-body'>Retrieve the metric data for disk space usage for a storage repository from the Legacy Data Warehouse. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getDiskUsageMetricDataFromMetricTrackingObjectSystemByDate'> getDiskUsageMetricDataFromMetricTrackingObjectSystemByDate</a> </span>
            <div class='views-field-body'>Retrieve the metric data for disk space usage for a storage repository from the Metric Tracking Object System. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getDiskUsageMetricImageByDate'> getDiskUsageMetricImageByDate</a> </span>
            <div class='views-field-body'>Retrieve an image of the disk usage data on a [[SoftLayer_Virtual_Guest|Cloud Computing Instance]] image for the time range you provide. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getDisplaySupportRepresentativeAssignments'> getDisplaySupportRepresentativeAssignments</a> </span>
            <div class='views-field-body'>Retrieve the SoftLayer employees that an account is assigned to.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getDomainRegistrations'> getDomainRegistrations</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getDomains'> getDomains</a> </span>
            <div class='views-field-body'>Retrieve the DNS domains associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getDomainsWithoutSecondaryDnsRecords'> getDomainsWithoutSecondaryDnsRecords</a> </span>
            <div class='views-field-body'>Retrieve the DNS domains associated with an account that were not created as a result of a secondary DNS zone transfer.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getEuSupportedFlag'> getEuSupportedFlag</a> </span>
            <div class='views-field-body'>Retrieve boolean flag dictating whether or not this account has the EU Supported flag. This flag indicates that this account uses IBM Cloud services to process EU citizen's personal data.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getEvaultCapacityGB'> getEvaultCapacityGB</a> </span>
            <div class='views-field-body'>Retrieve the total capacity of Legacy EVault Volumes on an account, in GB.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getEvaultMasterUsers'> getEvaultMasterUsers</a> </span>
            <div class='views-field-body'>Retrieve an account's master EVault user. This is only used when an account has EVault service.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getEvaultNetworkStorage'> getEvaultNetworkStorage</a> </span>
            <div class='views-field-body'>Retrieve an account's associated EVault storage volumes.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getExecutiveSummaryPdf'> getExecutiveSummaryPdf</a> </span>
            <div class='views-field-body'>This method provides an executive summary PDF for managed hosting services. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getExpiredSecurityCertificates'> getExpiredSecurityCertificates</a> </span>
            <div class='views-field-body'>Retrieve stored security certificates that are expired (ie. SSL)</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getFacilityLogs'> getFacilityLogs</a> </span>
            <div class='views-field-body'>Retrieve logs of who entered a colocation area which is assigned to this account, or when a user under this account enters a datacenter.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getFileBlockBetaAccessFlag'> getFileBlockBetaAccessFlag</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getFlexibleCreditEnrollments'> getFlexibleCreditEnrollments</a> </span>
            <div class='views-field-body'>Retrieve all of the account's current and former Flexible Credit enrollments.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getFlexibleCreditProgramInfo'> getFlexibleCreditProgramInfo</a> </span>
            <div class='views-field-body'>This method retrieves the Flexible Credit Program information for your account. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getForcePaasAccountLinkDate'> getForcePaasAccountLinkDate</a> </span>
            <div class='views-field-body'>Retrieve timestamp representing the point in time when an account is required to link with PaaS.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getGlobalIpRecords'> getGlobalIpRecords</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getGlobalIpv4Records'> getGlobalIpv4Records</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getGlobalIpv6Records'> getGlobalIpv6Records</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getGlobalLoadBalancerAccounts'> getGlobalLoadBalancerAccounts</a> </span>
            <div class='views-field-body'>Retrieve the global load balancer accounts for a softlayer customer account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHardware'> getHardware</a> </span>
            <div class='views-field-body'>Retrieve an account's associated hardware objects.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHardwareOverBandwidthAllocation'> getHardwareOverBandwidthAllocation</a> </span>
            <div class='views-field-body'>Retrieve an account's associated hardware objects currently over bandwidth allocation.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHardwarePools'> getHardwarePools</a> </span>
            <div class='views-field-body'>Get a collection of managed hardware pools.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHardwareProjectedOverBandwidthAllocation'> getHardwareProjectedOverBandwidthAllocation</a> </span>
            <div class='views-field-body'>Retrieve an account's associated hardware objects projected to go over bandwidth allocation.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHardwareWithCpanel'> getHardwareWithCpanel</a> </span>
            <div class='views-field-body'>Retrieve all hardware associated with an account that has the cPanel web hosting control panel installed.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHardwareWithHelm'> getHardwareWithHelm</a> </span>
            <div class='views-field-body'>Retrieve all hardware associated with an account that has the Helm web hosting control panel installed.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHardwareWithMcafee'> getHardwareWithMcafee</a> </span>
            <div class='views-field-body'>Retrieve all hardware associated with an account that has McAfee Secure software components.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHardwareWithMcafeeAntivirusRedhat'> getHardwareWithMcafeeAntivirusRedhat</a> </span>
            <div class='views-field-body'>Retrieve all hardware associated with an account that has McAfee Secure AntiVirus for Redhat software components.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHardwareWithMcafeeAntivirusWindows'> getHardwareWithMcafeeAntivirusWindows</a> </span>
            <div class='views-field-body'>Retrieve all hardware associated with an account that has McAfee Secure AntiVirus for Windows software components.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHardwareWithMcafeeIntrusionDetectionSystem'> getHardwareWithMcafeeIntrusionDetectionSystem</a> </span>
            <div class='views-field-body'>Retrieve all hardware associated with an account that has McAfee Secure Intrusion Detection System software components.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHardwareWithPlesk'> getHardwareWithPlesk</a> </span>
            <div class='views-field-body'>Retrieve all hardware associated with an account that has the Plesk web hosting control panel installed.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHardwareWithQuantastor'> getHardwareWithQuantastor</a> </span>
            <div class='views-field-body'>Retrieve all hardware associated with an account that has the QuantaStor storage system installed.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHardwareWithUrchin'> getHardwareWithUrchin</a> </span>
            <div class='views-field-body'>Retrieve all hardware associated with an account that has the Urchin web traffic analytics package installed.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHardwareWithWindows'> getHardwareWithWindows</a> </span>
            <div class='views-field-body'>Retrieve all hardware associated with an account that is running a version of the Microsoft Windows operating system.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHasEvaultBareMetalRestorePluginFlag'> getHasEvaultBareMetalRestorePluginFlag</a> </span>
            <div class='views-field-body'>Retrieve return 1 if one of the account's hardware has the EVault Bare Metal Server Restore Plugin otherwise 0.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHasIderaBareMetalRestorePluginFlag'> getHasIderaBareMetalRestorePluginFlag</a> </span>
            <div class='views-field-body'>Retrieve return 1 if one of the account's hardware has an installation of Idera Server Backup otherwise 0.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHasPendingOrder'> getHasPendingOrder</a> </span>
            <div class='views-field-body'>Retrieve the number of orders in a PENDING status for a SoftLayer customer account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHasR1softBareMetalRestorePluginFlag'> getHasR1softBareMetalRestorePluginFlag</a> </span>
            <div class='views-field-body'>Retrieve return 1 if one of the account's hardware has an installation of R1Soft CDP otherwise 0.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHistoricalBackupGraph'> getHistoricalBackupGraph</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHistoricalBandwidthGraph'> getHistoricalBandwidthGraph</a> </span>
            <div class='views-field-body'>This method returns a line graph of bandwidth statistics.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHistoricalTicketGraph'> getHistoricalTicketGraph</a> </span>
            <div class='views-field-body'>This method returns a pie chart of ticket statistics for the given dates.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHistoricalUptimeGraph'> getHistoricalUptimeGraph</a> </span>
            <div class='views-field-body'>This method returns a SoftLayer_Container_Account_Graph_Outputs object for the specified date range. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHourlyBareMetalInstances'> getHourlyBareMetalInstances</a> </span>
            <div class='views-field-body'>Retrieve an account's associated hourly bare metal server objects.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHourlyServiceBillingItems'> getHourlyServiceBillingItems</a> </span>
            <div class='views-field-body'>Retrieve hourly service billing items that will be on an account's next invoice.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHourlyVirtualGuests'> getHourlyVirtualGuests</a> </span>
            <div class='views-field-body'>Retrieve an account's associated hourly virtual guest objects.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getHubNetworkStorage'> getHubNetworkStorage</a> </span>
            <div class='views-field-body'>Retrieve an account's associated Virtual Storage volumes.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getIbmCustomerNumber'> getIbmCustomerNumber</a> </span>
            <div class='views-field-body'>Retrieve unique identifier for a customer used throughout IBM.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getIbmIdAuthenticationRequiredFlag'> getIbmIdAuthenticationRequiredFlag</a> </span>
            <div class='views-field-body'>Retrieve indicates whether this account requires IBMid authentication.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getIbmIdMigrationExpirationTimestamp'> getIbmIdMigrationExpirationTimestamp</a> </span>
            <div class='views-field-body'>Retrieve this key is deprecated and should not be used.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getInProgressExternalAccountSetup'> getInProgressExternalAccountSetup</a> </span>
            <div class='views-field-body'>Retrieve an in progress request to switch billing systems.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getInternalNotes'> getInternalNotes</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getInvoices'> getInvoices</a> </span>
            <div class='views-field-body'>Retrieve an account's associated billing invoices.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getIpAddresses'> getIpAddresses</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getIscsiIsolationDisabled'> getIscsiIsolationDisabled</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getIscsiNetworkStorage'> getIscsiNetworkStorage</a> </span>
            <div class='views-field-body'>Retrieve an account's associated iSCSI storage volumes.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getLargestAllowedSubnetCidr'> getLargestAllowedSubnetCidr</a> </span>
            <div class='views-field-body'>Computes the number of available public secondary IP addresses, augmented by the provided number of hosts, before overflow of the allowed host to IP address ratio occurs. The result is aligned to the nearest subnet size that could be accommodated in full. 

0 is returned if an overflow is detected. 

The use of $locationId has been deprecated. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getLastCanceledBillingItem'> getLastCanceledBillingItem</a> </span>
            <div class='views-field-body'>Retrieve the most recently canceled billing item.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getLastCancelledServerBillingItem'> getLastCancelledServerBillingItem</a> </span>
            <div class='views-field-body'>Retrieve the most recent cancelled server billing item.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getLastFiveClosedAbuseTickets'> getLastFiveClosedAbuseTickets</a> </span>
            <div class='views-field-body'>Retrieve the five most recently closed abuse tickets associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getLastFiveClosedAccountingTickets'> getLastFiveClosedAccountingTickets</a> </span>
            <div class='views-field-body'>Retrieve the five most recently closed accounting tickets associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getLastFiveClosedOtherTickets'> getLastFiveClosedOtherTickets</a> </span>
            <div class='views-field-body'>Retrieve the five most recently closed tickets that do not belong to the abuse, accounting, sales, or support groups associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getLastFiveClosedSalesTickets'> getLastFiveClosedSalesTickets</a> </span>
            <div class='views-field-body'>Retrieve the five most recently closed sales tickets associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getLastFiveClosedSupportTickets'> getLastFiveClosedSupportTickets</a> </span>
            <div class='views-field-body'>Retrieve the five most recently closed support tickets associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getLastFiveClosedTickets'> getLastFiveClosedTickets</a> </span>
            <div class='views-field-body'>Retrieve the five most recently closed tickets associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getLatestBillDate'> getLatestBillDate</a> </span>
            <div class='views-field-body'>Retrieve an account's most recent billing date.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getLatestRecurringInvoice'> getLatestRecurringInvoice</a> </span>
            <div class='views-field-body'>Retrieve an account's latest recurring invoice.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getLatestRecurringPendingInvoice'> getLatestRecurringPendingInvoice</a> </span>
            <div class='views-field-body'>Retrieve an account's latest recurring pending invoice.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getLegacyBandwidthAllotments'> getLegacyBandwidthAllotments</a> </span>
            <div class='views-field-body'>Retrieve the legacy bandwidth allotments for an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getLegacyIscsiCapacityGB'> getLegacyIscsiCapacityGB</a> </span>
            <div class='views-field-body'>Retrieve the total capacity of Legacy iSCSI Volumes on an account, in GB.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getLoadBalancers'> getLoadBalancers</a> </span>
            <div class='views-field-body'>Retrieve an account's associated load balancers.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getLockboxCapacityGB'> getLockboxCapacityGB</a> </span>
            <div class='views-field-body'>Retrieve the total capacity of Legacy lockbox Volumes on an account, in GB.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getLockboxNetworkStorage'> getLockboxNetworkStorage</a> </span>
            <div class='views-field-body'>Retrieve an account's associated Lockbox storage volumes.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getManualPaymentsUnderReview'> getManualPaymentsUnderReview</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getMasterUser'> getMasterUser</a> </span>
            <div class='views-field-body'>Retrieve an account's master user.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getMediaDataTransferRequests'> getMediaDataTransferRequests</a> </span>
            <div class='views-field-body'>Retrieve an account's media transfer service requests.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getMigratedToIbmCloudPortalFlag'> getMigratedToIbmCloudPortalFlag</a> </span>
            <div class='views-field-body'>Retrieve flag indicating whether this account is restricted to the IBM Cloud portal.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getMonthlyBareMetalInstances'> getMonthlyBareMetalInstances</a> </span>
            <div class='views-field-body'>Retrieve an account's associated monthly bare metal server objects.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getMonthlyVirtualGuests'> getMonthlyVirtualGuests</a> </span>
            <div class='views-field-body'>Retrieve an account's associated monthly virtual guest objects.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNasNetworkStorage'> getNasNetworkStorage</a> </span>
            <div class='views-field-body'>Retrieve an account's associated NAS storage volumes.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNetAppActiveAccountLicenseKeys'> getNetAppActiveAccountLicenseKeys</a> </span>
            <div class='views-field-body'>Get a collection of active NetApp software account license keys.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNetworkCreationFlag'> getNetworkCreationFlag</a> </span>
            <div class='views-field-body'>Retrieve whether or not this account can define their own networks.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNetworkGateways'> getNetworkGateways</a> </span>
            <div class='views-field-body'>Retrieve all network gateway devices on this account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNetworkHardware'> getNetworkHardware</a> </span>
            <div class='views-field-body'>Retrieve an account's associated network hardware.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNetworkMessageDeliveryAccounts'> getNetworkMessageDeliveryAccounts</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNetworkMonitorDownHardware'> getNetworkMonitorDownHardware</a> </span>
            <div class='views-field-body'>Retrieve hardware which is currently experiencing a service failure.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNetworkMonitorDownVirtualGuests'> getNetworkMonitorDownVirtualGuests</a> </span>
            <div class='views-field-body'>Retrieve virtual guest which is currently experiencing a service failure.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNetworkMonitorRecoveringHardware'> getNetworkMonitorRecoveringHardware</a> </span>
            <div class='views-field-body'>Retrieve hardware which is currently recovering from a service failure.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNetworkMonitorRecoveringVirtualGuests'> getNetworkMonitorRecoveringVirtualGuests</a> </span>
            <div class='views-field-body'>Retrieve virtual guest which is currently recovering from a service failure.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNetworkMonitorUpHardware'> getNetworkMonitorUpHardware</a> </span>
            <div class='views-field-body'>Retrieve hardware which is currently online.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNetworkMonitorUpVirtualGuests'> getNetworkMonitorUpVirtualGuests</a> </span>
            <div class='views-field-body'>Retrieve virtual guest which is currently online.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNetworkStorage'> getNetworkStorage</a> </span>
            <div class='views-field-body'>Retrieve an account's associated storage volumes. This includes Lockbox, NAS, EVault, and iSCSI volumes.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNetworkStorageGroups'> getNetworkStorageGroups</a> </span>
            <div class='views-field-body'>Retrieve an account's Network Storage groups.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNetworkTunnelContexts'> getNetworkTunnelContexts</a> </span>
            <div class='views-field-body'>Retrieve iPSec network tunnels for an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNetworkVlanSpan'> getNetworkVlanSpan</a> </span>
            <div class='views-field-body'>Retrieve whether or not an account has automatic private VLAN spanning enabled.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNetworkVlans'> getNetworkVlans</a> </span>
            <div class='views-field-body'>Retrieve all network VLANs assigned to an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNextBillingPublicAllotmentHardwareBandwidthDetails'> getNextBillingPublicAllotmentHardwareBandwidthDetails</a> </span>
            <div class='views-field-body'>Retrieval: DEPRECATED - This information can be pulled directly through tapping keys now - DEPRECATED. The allotments for this account and their servers for the next billing cycle. The public inbound and outbound bandwidth is calculated for each server in addition to the daily average network traffic since the last billing date.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNextInvoiceExcel'> getNextInvoiceExcel</a> </span>
            <div class='views-field-body'>Retrieve the next billing period's invoice. Note, this should be considered preliminary as you may add, remove, change billing items on your account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNextInvoiceIncubatorExemptTotal'> getNextInvoiceIncubatorExemptTotal</a> </span>
            <div class='views-field-body'>Retrieve the pre-tax total amount exempt from incubator credit for the account's next invoice. This field is now deprecated and will soon be removed. Please update all references to instead use nextInvoiceTotalAmount</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNextInvoicePdf'> getNextInvoicePdf</a> </span>
            <div class='views-field-body'>Retrieve the next billing period's invoice. Note, this should be considered preliminary as you may add, remove, change billing items on your account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNextInvoicePdfDetailed'> getNextInvoicePdfDetailed</a> </span>
            <div class='views-field-body'>Retrieve the next billing period's detailed invoice. Note, this should be considered preliminary as you may add, remove, change billing items on your account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNextInvoiceRecurringAmountEligibleForAccountDiscount'> getNextInvoiceRecurringAmountEligibleForAccountDiscount</a> </span>
            <div class='views-field-body'>Retrieve the total recurring charge amount of an account's next invoice eligible for account discount measured in US Dollars ($USD), assuming no changes or charges occur between now and time of billing.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNextInvoiceTopLevelBillingItems'> getNextInvoiceTopLevelBillingItems</a> </span>
            <div class='views-field-body'>Retrieve the billing items that will be on an account's next invoice.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNextInvoiceTotalAmount'> getNextInvoiceTotalAmount</a> </span>
            <div class='views-field-body'>Retrieve the pre-tax total amount of an account's next invoice measured in US Dollars ($USD), assuming no changes or charges occur between now and time of billing.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNextInvoiceTotalOneTimeAmount'> getNextInvoiceTotalOneTimeAmount</a> </span>
            <div class='views-field-body'>Retrieve the total one-time charge amount of an account's next invoice measured in US Dollars ($USD), assuming no changes or charges occur between now and time of billing.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNextInvoiceTotalOneTimeTaxAmount'> getNextInvoiceTotalOneTimeTaxAmount</a> </span>
            <div class='views-field-body'>Retrieve the total one-time tax amount of an account's next invoice measured in US Dollars ($USD), assuming no changes or charges occur between now and time of billing.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNextInvoiceTotalRecurringAmount'> getNextInvoiceTotalRecurringAmount</a> </span>
            <div class='views-field-body'>Retrieve the total recurring charge amount of an account's next invoice measured in US Dollars ($USD), assuming no changes or charges occur between now and time of billing.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNextInvoiceTotalRecurringAmountBeforeAccountDiscount'> getNextInvoiceTotalRecurringAmountBeforeAccountDiscount</a> </span>
            <div class='views-field-body'>Retrieve the total recurring charge amount of an account's next invoice measured in US Dollars ($USD), assuming no changes or charges occur between now and time of billing.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNextInvoiceTotalRecurringTaxAmount'> getNextInvoiceTotalRecurringTaxAmount</a> </span>
            <div class='views-field-body'>Retrieve the total recurring tax amount of an account's next invoice measured in US Dollars ($USD), assuming no changes or charges occur between now and time of billing.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNextInvoiceTotalTaxableRecurringAmount'> getNextInvoiceTotalTaxableRecurringAmount</a> </span>
            <div class='views-field-body'>Retrieve the total recurring charge amount of an account's next invoice measured in US Dollars ($USD), assuming no changes or charges occur between now and time of billing.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNextInvoiceZeroFeeItemCounts'> getNextInvoiceZeroFeeItemCounts</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getNotificationSubscribers'> getNotificationSubscribers</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getObject'> getObject</a> </span>
            <div class='views-field-body'>Retrieve a SoftLayer_Account record.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getOpenAbuseTickets'> getOpenAbuseTickets</a> </span>
            <div class='views-field-body'>Retrieve the open abuse tickets associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getOpenAccountingTickets'> getOpenAccountingTickets</a> </span>
            <div class='views-field-body'>Retrieve the open accounting tickets associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getOpenBillingTickets'> getOpenBillingTickets</a> </span>
            <div class='views-field-body'>Retrieve the open billing tickets associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getOpenCancellationRequests'> getOpenCancellationRequests</a> </span>
            <div class='views-field-body'>Retrieve an open ticket requesting cancellation of this server, if one exists.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getOpenOtherTickets'> getOpenOtherTickets</a> </span>
            <div class='views-field-body'>Retrieve the open tickets that do not belong to the abuse, accounting, sales, or support groups associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getOpenRecurringInvoices'> getOpenRecurringInvoices</a> </span>
            <div class='views-field-body'>Retrieve an account's recurring invoices.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getOpenSalesTickets'> getOpenSalesTickets</a> </span>
            <div class='views-field-body'>Retrieve the open sales tickets associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getOpenStackAccountLinks'> getOpenStackAccountLinks</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getOpenStackObjectStorage'> getOpenStackObjectStorage</a> </span>
            <div class='views-field-body'>Retrieve an account's associated Openstack related Object Storage accounts.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getOpenSupportTickets'> getOpenSupportTickets</a> </span>
            <div class='views-field-body'>Retrieve the open support tickets associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getOpenTickets'> getOpenTickets</a> </span>
            <div class='views-field-body'>Retrieve all open tickets associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getOpenTicketsWaitingOnCustomer'> getOpenTicketsWaitingOnCustomer</a> </span>
            <div class='views-field-body'>Retrieve all open tickets associated with an account last edited by an employee.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getOrders'> getOrders</a> </span>
            <div class='views-field-body'>Retrieve an account's associated billing orders excluding upgrades.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getOrphanBillingItems'> getOrphanBillingItems</a> </span>
            <div class='views-field-body'>Retrieve the billing items that have no parent billing item. These are items that don't necessarily belong to a single server.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getOwnedBrands'> getOwnedBrands</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getOwnedHardwareGenericComponentModels'> getOwnedHardwareGenericComponentModels</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPaymentProcessors'> getPaymentProcessors</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPendingCreditCardChangeRequestData'> getPendingCreditCardChangeRequestData</a> </span>
            <div class='views-field-body'>Retrieve details of all credit card change requests which have not been processed by a SoftLayer agent.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPendingEvents'> getPendingEvents</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPendingInvoice'> getPendingInvoice</a> </span>
            <div class='views-field-body'>Retrieve an account's latest open (pending) invoice.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPendingInvoiceTopLevelItems'> getPendingInvoiceTopLevelItems</a> </span>
            <div class='views-field-body'>Retrieve a list of top-level invoice items that are on an account's currently pending invoice.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPendingInvoiceTotalAmount'> getPendingInvoiceTotalAmount</a> </span>
            <div class='views-field-body'>Retrieve the total amount of an account's pending invoice, if one exists.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPendingInvoiceTotalOneTimeAmount'> getPendingInvoiceTotalOneTimeAmount</a> </span>
            <div class='views-field-body'>Retrieve the total one-time charges for an account's pending invoice, if one exists. In other words, it is the sum of one-time charges, setup fees, and labor fees. It does not include taxes.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPendingInvoiceTotalOneTimeTaxAmount'> getPendingInvoiceTotalOneTimeTaxAmount</a> </span>
            <div class='views-field-body'>Retrieve the sum of all the taxes related to one time charges for an account's pending invoice, if one exists.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPendingInvoiceTotalRecurringAmount'> getPendingInvoiceTotalRecurringAmount</a> </span>
            <div class='views-field-body'>Retrieve the total recurring amount of an account's pending invoice, if one exists.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPendingInvoiceTotalRecurringTaxAmount'> getPendingInvoiceTotalRecurringTaxAmount</a> </span>
            <div class='views-field-body'>Retrieve the total amount of the recurring taxes on an account's pending invoice, if one exists.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPermissionGroups'> getPermissionGroups</a> </span>
            <div class='views-field-body'>Retrieve an account's permission groups.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPermissionRoles'> getPermissionRoles</a> </span>
            <div class='views-field-body'>Retrieve an account's user roles.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPlacementGroups'> getPlacementGroups</a> </span>
            <div class='views-field-body'>Retrieve an account's associated virtual placement groups.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPortableStorageVolumes'> getPortableStorageVolumes</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPostProvisioningHooks'> getPostProvisioningHooks</a> </span>
            <div class='views-field-body'>Retrieve customer specified URIs that are downloaded onto a newly provisioned or reloaded server. If the URI is sent over https it will be executed directly on the server.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPptpVpnAllowedFlag'> getPptpVpnAllowedFlag</a> </span>
            <div class='views-field-body'>Retrieve boolean flag dictating whether or not this account supports PPTP VPN Access.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPptpVpnUsers'> getPptpVpnUsers</a> </span>
            <div class='views-field-body'>Retrieve an account's associated portal users with PPTP VPN access. (Deprecated)</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPreviousRecurringRevenue'> getPreviousRecurringRevenue</a> </span>
            <div class='views-field-body'>Retrieve the total recurring amount for an accounts previous revenue.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPriceRestrictions'> getPriceRestrictions</a> </span>
            <div class='views-field-body'>Retrieve the item price that an account is restricted to.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPriorityOneTickets'> getPriorityOneTickets</a> </span>
            <div class='views-field-body'>Retrieve all priority one tickets associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPrivateAllotmentHardwareBandwidthDetails'> getPrivateAllotmentHardwareBandwidthDetails</a> </span>
            <div class='views-field-body'>Retrieval: DEPRECATED - This information can be pulled directly through tapping keys now - DEPRECATED. The allotments for this account and their servers. The private inbound and outbound bandwidth is calculated for each server in addition to the daily average network traffic since the last billing date.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPrivateBlockDeviceTemplateGroups'> getPrivateBlockDeviceTemplateGroups</a> </span>
            <div class='views-field-body'>Retrieve private and shared template group objects (parent only) for an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPrivateIpAddresses'> getPrivateIpAddresses</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPrivateNetworkVlans'> getPrivateNetworkVlans</a> </span>
            <div class='views-field-body'>Retrieve the private network VLANs assigned to an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPrivateSubnets'> getPrivateSubnets</a> </span>
            <div class='views-field-body'>Retrieve all private subnets associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getProofOfConceptAccountFlag'> getProofOfConceptAccountFlag</a> </span>
            <div class='views-field-body'>Retrieve boolean flag indicating whether or not this account is a Proof of Concept account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPublicAllotmentHardwareBandwidthDetails'> getPublicAllotmentHardwareBandwidthDetails</a> </span>
            <div class='views-field-body'>Retrieval: DEPRECATED - This information can be pulled directly through tapping keys now - DEPRECATED. The allotments for this account and their servers. The public inbound and outbound bandwidth is calculated for each server in addition to the daily average network traffic since the last billing date.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPublicIpAddresses'> getPublicIpAddresses</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPublicNetworkVlans'> getPublicNetworkVlans</a> </span>
            <div class='views-field-body'>Retrieve the public network VLANs assigned to an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getPublicSubnets'> getPublicSubnets</a> </span>
            <div class='views-field-body'>Retrieve all public network subnets associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getQuotes'> getQuotes</a> </span>
            <div class='views-field-body'>Retrieve an account's quotes.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getRecentEvents'> getRecentEvents</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getReferralPartner'> getReferralPartner</a> </span>
            <div class='views-field-body'>Retrieve the Referral Partner for this account, if any.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getReferralPartnerCommissionForecast'> getReferralPartnerCommissionForecast</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getReferralPartnerCommissionHistory'> getReferralPartnerCommissionHistory</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getReferralPartnerCommissionPending'> getReferralPartnerCommissionPending</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getReferredAccounts'> getReferredAccounts</a> </span>
            <div class='views-field-body'>Retrieve if this is a account is a referral partner, the accounts this referral partner has referred</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getRegulatedWorkloads'> getRegulatedWorkloads</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getRemoteManagementCommandRequests'> getRemoteManagementCommandRequests</a> </span>
            <div class='views-field-body'>Retrieve remote management command requests for an account</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getReplicationEvents'> getReplicationEvents</a> </span>
            <div class='views-field-body'>Retrieve the Replication events for all Network Storage volumes on an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getRequireSilentIBMidUserCreation'> getRequireSilentIBMidUserCreation</a> </span>
            <div class='views-field-body'>Retrieve indicates whether newly created users under this account will be associated with IBMid via an email requiring a response, or not.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getReservedCapacityAgreements'> getReservedCapacityAgreements</a> </span>
            <div class='views-field-body'>Retrieve all reserved capacity agreements for an account</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getReservedCapacityGroups'> getReservedCapacityGroups</a> </span>
            <div class='views-field-body'>Retrieve the reserved capacity groups owned by this account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getResourceGroups'> getResourceGroups</a> </span>
            <div class='views-field-body'>Retrieve an account's associated top-level resource groups.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getRouters'> getRouters</a> </span>
            <div class='views-field-body'>Retrieve all Routers that an accounts VLANs reside on</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getRwhoisData'> getRwhoisData</a> </span>
            <div class='views-field-body'>Retrieve an account's reverse WHOIS data. This data is used when making SWIP requests.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getSamlAuthentication'> getSamlAuthentication</a> </span>
            <div class='views-field-body'>Retrieve the SAML configuration for this account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getScaleGroups'> getScaleGroups</a> </span>
            <div class='views-field-body'>Retrieve all scale groups on this account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getSecondaryDomains'> getSecondaryDomains</a> </span>
            <div class='views-field-body'>Retrieve the secondary DNS records for a SoftLayer customer account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getSecurityCertificates'> getSecurityCertificates</a> </span>
            <div class='views-field-body'>Retrieve stored security certificates (ie. SSL)</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getSecurityGroups'> getSecurityGroups</a> </span>
            <div class='views-field-body'>Retrieve the security groups belonging to this account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getSecurityLevel'> getSecurityLevel</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getSecurityScanRequests'> getSecurityScanRequests</a> </span>
            <div class='views-field-body'>Retrieve an account's vulnerability scan requests.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getServiceBillingItems'> getServiceBillingItems</a> </span>
            <div class='views-field-body'>Retrieve the service billing items that will be on an account's next invoice. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getSharedBlockDeviceTemplateGroups'> getSharedBlockDeviceTemplateGroups</a> </span>
            <div class='views-field-body'>Get the collection of template group objects that have been shared with this account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getShipments'> getShipments</a> </span>
            <div class='views-field-body'>Retrieve shipments that belong to the customer's account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getSshKeys'> getSshKeys</a> </span>
            <div class='views-field-body'>Retrieve customer specified SSH keys that can be implemented onto a newly provisioned or reloaded server.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getSslVpnUsers'> getSslVpnUsers</a> </span>
            <div class='views-field-body'>Retrieve an account's associated portal users with SSL VPN access.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getStandardPoolVirtualGuests'> getStandardPoolVirtualGuests</a> </span>
            <div class='views-field-body'>Retrieve an account's virtual guest objects that are hosted on a user provisioned hypervisor.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getSubnetRegistrationDetails'> getSubnetRegistrationDetails</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getSubnetRegistrations'> getSubnetRegistrations</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getSubnets'> getSubnets</a> </span>
            <div class='views-field-body'>Retrieve all network subnets associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getSupportRepresentatives'> getSupportRepresentatives</a> </span>
            <div class='views-field-body'>Retrieve the SoftLayer employees that an account is assigned to.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getSupportSubscriptions'> getSupportSubscriptions</a> </span>
            <div class='views-field-body'>Retrieve the active support subscriptions for this account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getSupportTier'> getSupportTier</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getSuppressInvoicesFlag'> getSuppressInvoicesFlag</a> </span>
            <div class='views-field-body'>Retrieve a flag indicating to suppress invoices.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getTags'> getTags</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getTechIncubatorProgramInfo'> getTechIncubatorProgramInfo</a> </span>
            <div class='views-field-body'>This method retrieves the Technology Incubator Program information for your account. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getThirdPartyPoliciesAcceptanceStatus'> getThirdPartyPoliciesAcceptanceStatus</a> </span>
            <div class='views-field-body'>Get the acceptance status of the applicable third-party policies.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getTickets'> getTickets</a> </span>
            <div class='views-field-body'>Retrieve an account's associated tickets.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getTicketsClosedInTheLastThreeDays'> getTicketsClosedInTheLastThreeDays</a> </span>
            <div class='views-field-body'>Retrieve tickets closed within the last 72 hours or last 10 tickets, whichever is less, associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getTicketsClosedToday'> getTicketsClosedToday</a> </span>
            <div class='views-field-body'>Retrieve tickets closed today associated with an account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getTranscodeAccounts'> getTranscodeAccounts</a> </span>
            <div class='views-field-body'>Retrieve an account's associated Transcode account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getUpgradeRequests'> getUpgradeRequests</a> </span>
            <div class='views-field-body'>Retrieve an account's associated upgrade requests.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getUsers'> getUsers</a> </span>
            <div class='views-field-body'>Retrieve an account's portal users.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getValidSecurityCertificateEntries'> getValidSecurityCertificateEntries</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getValidSecurityCertificates'> getValidSecurityCertificates</a> </span>
            <div class='views-field-body'>Retrieve stored security certificates that are not expired (ie. SSL)</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getVdrUpdatesInProgressFlag'> getVdrUpdatesInProgressFlag</a> </span>
            <div class='views-field-body'>Retrieve return 0 if vpn updates are currently in progress on this account otherwise 1.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getVirtualDedicatedRacks'> getVirtualDedicatedRacks</a> </span>
            <div class='views-field-body'>Retrieve the bandwidth pooling for this account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getVirtualDiskImages'> getVirtualDiskImages</a> </span>
            <div class='views-field-body'>Retrieve an account's associated virtual server virtual disk images.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getVirtualGuests'> getVirtualGuests</a> </span>
            <div class='views-field-body'>Retrieve an account's associated virtual guest objects.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getVirtualGuestsOverBandwidthAllocation'> getVirtualGuestsOverBandwidthAllocation</a> </span>
            <div class='views-field-body'>Retrieve an account's associated virtual guest objects currently over bandwidth allocation.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getVirtualGuestsProjectedOverBandwidthAllocation'> getVirtualGuestsProjectedOverBandwidthAllocation</a> </span>
            <div class='views-field-body'>Retrieve an account's associated virtual guest objects currently over bandwidth allocation.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getVirtualGuestsWithCpanel'> getVirtualGuestsWithCpanel</a> </span>
            <div class='views-field-body'>Retrieve all virtual guests associated with an account that has the cPanel web hosting control panel installed.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getVirtualGuestsWithMcafee'> getVirtualGuestsWithMcafee</a> </span>
            <div class='views-field-body'>Retrieve all virtual guests associated with an account that have McAfee Secure software components.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getVirtualGuestsWithMcafeeAntivirusRedhat'> getVirtualGuestsWithMcafeeAntivirusRedhat</a> </span>
            <div class='views-field-body'>Retrieve all virtual guests associated with an account that have McAfee Secure AntiVirus for Redhat software components.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getVirtualGuestsWithMcafeeAntivirusWindows'> getVirtualGuestsWithMcafeeAntivirusWindows</a> </span>
            <div class='views-field-body'>Retrieve all virtual guests associated with an account that has McAfee Secure AntiVirus for Windows software components.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getVirtualGuestsWithMcafeeIntrusionDetectionSystem'> getVirtualGuestsWithMcafeeIntrusionDetectionSystem</a> </span>
            <div class='views-field-body'>Retrieve all virtual guests associated with an account that has McAfee Secure Intrusion Detection System software components.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getVirtualGuestsWithPlesk'> getVirtualGuestsWithPlesk</a> </span>
            <div class='views-field-body'>Retrieve all virtual guests associated with an account that has the Plesk web hosting control panel installed.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getVirtualGuestsWithQuantastor'> getVirtualGuestsWithQuantastor</a> </span>
            <div class='views-field-body'>Retrieve all virtual guests associated with an account that have the QuantaStor storage system installed.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getVirtualGuestsWithUrchin'> getVirtualGuestsWithUrchin</a> </span>
            <div class='views-field-body'>Retrieve all virtual guests associated with an account that has the Urchin web traffic analytics package installed.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getVirtualPrivateRack'> getVirtualPrivateRack</a> </span>
            <div class='views-field-body'>Retrieve the bandwidth pooling for this account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getVirtualStorageArchiveRepositories'> getVirtualStorageArchiveRepositories</a> </span>
            <div class='views-field-body'>Retrieve an account's associated virtual server archived storage repositories.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getVirtualStoragePublicRepositories'> getVirtualStoragePublicRepositories</a> </span>
            <div class='views-field-body'>Retrieve an account's associated virtual server public storage repositories.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getVmWareActiveAccountLicenseKeys'> getVmWareActiveAccountLicenseKeys</a> </span>
            <div class='views-field-body'>Get a collection of active VMware software account license keys.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getVpcVirtualGuests'> getVpcVirtualGuests</a> </span>
            <div class='views-field-body'>Retrieve an account's associated VPC configured virtual guest objects.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/getWindowsUpdateStatus'> getWindowsUpdateStatus</a> </span>
            <div class='views-field-body'>Retrieve a list of an account's hardware's Windows Update status.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/hasAttribute'> hasAttribute</a> </span>
            <div class='views-field-body'>Determine if an account has a given attribute.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/hourlyInstanceLimit'> hourlyInstanceLimit</a> </span>
            <div class='views-field-body'>Retrieve the number of hourly services that an account is allowed to have </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/hourlyServerLimit'> hourlyServerLimit</a> </span>
            <div class='views-field-body'>Retrieve the number of hourly bare metal servers that an account is allowed to have </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/isActiveVmwareCustomer'> isActiveVmwareCustomer</a> </span>
            <div class='views-field-body'>Determines if the account is considered an active VMware customer and as such eligible to order VMware restricted products. This result is cached for up to 60 seconds. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/isEligibleForLocalCurrencyProgram'> isEligibleForLocalCurrencyProgram</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/isEligibleToLinkWithPaas'> isEligibleToLinkWithPaas</a> </span>
            <div class='views-field-body'>Returns true if this account is eligible to link with PaaS. False otherwise. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/linkExternalAccount'> linkExternalAccount</a> </span>
            <div class='views-field-body'>This method will link this SoftLayer account with the provided external account. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/removeAlternateCreditCard'> removeAlternateCreditCard</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/requestCreditCardChange'> requestCreditCardChange</a> </span>
            <div class='views-field-body'>Retrieve the record data associated with the submission of a Credit Card Change Request.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/requestManualPayment'> requestManualPayment</a> </span>
            <div class='views-field-body'>Retrieve the record data associated with the submission of a Manual Payment Request.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/requestManualPaymentUsingCreditCardOnFile'> requestManualPaymentUsingCreditCardOnFile</a> </span>
            <div class='views-field-body'>Retrieve the record data associated with the submission of a Manual Payment Request which charges the manual payment to a credit card already on file. </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/setAbuseEmails'> setAbuseEmails</a> </span>
            <div class='views-field-body'>Set this account's abuse emails.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/setManagedPoolQuantity'> setManagedPoolQuantity</a> </span>
            <div class='views-field-body'>Set the number of desired servers in the pool</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/setVlanSpan'> setVlanSpan</a> </span>
            <div class='views-field-body'>Set the flag that enables or disables automatic private network VLAN spanning for a SoftLayer customer account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/swapCreditCards'> swapCreditCards</a> </span>
            <div class='views-field-body'></div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/syncCurrentUserPopulationWithPaas'> syncCurrentUserPopulationWithPaas</a> </span>
            <div class='views-field-body'>This method manually starts a synchronize operation for the current IBMid-authenticated user population of a linked account pair. "Manually" means "independent of an account link operation". </div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/updateVpnUsersForResource'> updateVpnUsersForResource</a> </span>
            <div class='views-field-body'>Creates or updates a user VPN access privileges for a server on account.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/validate'> validate</a> </span>
            <div class='views-field-body'>Validates SoftLayer account information. Will return an error if any field is not valid.</div>
        </div>
            <div class="method-row">
                        <span class='view-field-title'><a href='/reference/services/SoftLayer_Account/validateManualPaymentAmount'> validateManualPaymentAmount</a> </span>
            <div class='views-field-body'>Ensure the amount requested for a manual payment is valid.</div>
        </div>
        </div>
</div>

