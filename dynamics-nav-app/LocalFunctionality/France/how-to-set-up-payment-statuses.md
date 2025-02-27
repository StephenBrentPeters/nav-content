---
    title: How to Set Up Payment Statuses
    description: To use payment management, you must set up payment statuses to define payment document progress levels. You must define a set of statuses for each payment class.

    documentationcenter: ''
    author: SorenGP

    ms.prod: "dynamics-nav-2018"
    ms.topic: article
    ms.devlang: na
    ms.tgt_pltfrm: na
    ms.workload: na
    ms.search.keywords:
    ms.date: 07/01/2017
    ms.author: edupont

---
# How to: Set Up Payment Statuses
To use payment management, you must set up payment statuses to define payment document progress levels. You must define a set of statuses for each payment class. For more information, see [How to: Set Up Payment Classes](how-to-set-up-payment-classes.md).  

## To set up payment statuses  

1.  Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Slip Setup**, and then choose the related link.  
2.  Select a payment class, and then choose the **Status** action.  
3.  In the **Payment Status** window, choose the **New** action.  
4.  Fill in the fields as described in the following table.  

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**Name**|The payment status description.|  
    |**RIB**|Select to indicate that information about the Relevé d Identité Bancaire (RIB) statement for the customer or vendor must be displayed in the payment lines. The RIB information includes the bank branch number, agency code, bank account number, bank name, RIB key, and key verification.|  
    |**Look**|Select to indicate that the payment document lines that have reached this payment status can be edited and viewed in the **View/Edit Payment Line** window.<br /><br /> For more information, see View-Edit Payment Line.|  
    |**ReportMenu**|Select to indicate that the documents that have reached this payment status can be printed.|  
    |**Amount**|Select to display the amount in the payment lines.|  
    |**Payment in Progress**|Select to indicate that all billing and payment lines with this status must be considered when calculating the payments in progress.|  
    |**Archiving Authorized**|Select to indicate that payment headers with this payment status can be archived.|  

5.  Choose the **OK** button.  

## See Also
[Dynamics 365 Business Central](https://docs.microsoft.com/dynamics365/business-central/)  
[Payment Management](payment-management.md)   
 [How to: Set Up Payment Classes](how-to-set-up-payment-classes.md)   
 [How to: Set Up Payment Steps](how-to-set-up-payment-steps.md)   
 [How to: Set Up Payment Addresses](how-to-set-up-payment-addresses.md)   
 [How to: Create Payment Slips](how-to-create-payment-slips.md)   
 [How to: Post Payment Slips](how-to-post-payment-slips.md)   
 [How to: Archive Payment Slips](how-to-archive-payment-slips.md)   
 [How to: Export or Import Payment Management Setup Parameters](how-to-export-or-import-payment-management-setup-parameters.md)
