---
    title: How to Set Up Multiple Interest Rates
    description: You can calculate finance charges with multiple interest rates for a specific period. The interest calculation is similar for all financial charges, with variation only in the rate of interest for a specific period.

    documentationcenter: ''
    author: SorenGP

    ms.prod: "dynamics-nav-2018"
    ms.topic: article
    ms.devlang: na
    ms.tgt_pltfrm: na
    ms.workload: na
    ms.search.keywords:
    ms.date: 12/21/2017
    ms.author: edupont

---
# How to: Set Up Multiple Interest Rates
Multiple interest rates are used for different periods for delayed payments in trade transactions. For example, a government specifies the maximum interest to be levied for a consumer. This interest rate can be changed twice a year on 01 January and 01 July. The interest rate between businesses (B2B) is agreed by the parties and there is no limit to that customer group. The announced rate is usually four percent more than the normal bank interest.

When you create finance charge terms and reminder terms, for delayed payment penalty, you can specify multiple interest rates so that the penalty fee is calculated from different interest rates in different periods. For more information, see How to: Collect Outstanding Balances. For more information, see [How to: Collect Outstanding Balances](receivables-collect-outstanding-balances.md).

## To set up multiple interest rates  
1.  Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Finance Charge Terms**, and then choose the related link.  
2.  In the **Finance Charge Terms** window, select the required finance term, and then choose the **Interest Rates** action.  
3.  Fill in the fields as necessary. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4.  Choose the **OK** button.  
5.  Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Reminder Terms**, and then choose the related link.  
6.  In the **Reminder Terms** window, select the required reminder term, and then choose the **Levels** action.  
7.  In the **Reminder Levels** window, select the **Calculate Interest** field.  

When you issue a finance charge memo, the memo shows the finance charges with multiple interest rates for a specific time period. The memo also contains the contact details of the customer, the company issuing the memo, the additional amount, and the total amount. The opening entry on the memo is displayed in bold. The finance charges are calculated with multiple interest rates for a specific time period and are printed after the opening entry of the memo.  

## See Also
[Dynamics 365 Business Central](https://docs.microsoft.com/dynamics365/business-central/)  
[How to: Collect Outstanding Balances](receivables-collect-outstanding-balances.md)  
[Setting Up Finance](finance-setup-finance.md)
