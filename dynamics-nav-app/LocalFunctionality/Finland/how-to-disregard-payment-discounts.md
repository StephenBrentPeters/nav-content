---
    title: How to Disregard Payment Discounts
    description: Use the disregard payment discount at full payment feature to accept payments when certain conditions are true.

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
# How to: Disregard Payment Discounts
Use the disregard payment discount at full payment feature to accept payments when the following conditions are true:  

- Payment discount date < payment date <= payment tolerance date  
- Full amount >= payment amount >= full amount - payment discount  

## To disregard a payment discount  

1.  Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Terms**, and then choose the related link.  
2.  Select the line with the payment term for which you want to activate or deactivate payment discounts.  
3.  Select the **Disreg. Pmt. Disc. at Full Pmt** check box to initiate activation for this feature. To deactivate, clear the check box.  

> [!NOTE]  
>  When you apply one payment to multiple invoices, the feature to ignore payment discount at full payment is not supported.  

## See Also
[Dynamics 365 Business Central](https://docs.microsoft.com/dynamics365/business-central/)  
[Electronic Banking in Finland](electronic-banking-in-finland.md)   
[How to: Generate Payment Files](how-to-generate-payment-files.md)   
[Defining Payment Methods](../../finance-payment-methods.md)  
[How to: Work with Payment Tolerances and Payment Discount Tolerances](../../finance-payment-tolerance-and-payment-discount-tolerance.md)     
[How to: Set Up Bank Reference Files](how-to-set-up-bank-reference-files.md)
