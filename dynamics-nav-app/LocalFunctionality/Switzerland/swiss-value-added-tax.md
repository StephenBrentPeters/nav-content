---
    title: Swiss Value Added Tax
    description: Swiss enhancements include special VAT reporting features.

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
# Swiss Value Added Tax
[!INCLUDE[navnow](../../includes/navnow_md.md)] includes the following enhancements to Swiss VAT reporting:  

- Automatic adjustment of VAT amounts for invoices, according to payment discounts.  
- Additional VAT exchange rates for invoices in foreign currencies.  
- VAT percentages and amounts included in journals.  

For more information about Swiss VAT reporting and coding requirements, see [Swiss VAT Information](http://www.estv.admin.ch/mwst/dokumentation/00130/00947/00948/index.html?lang=fr), in particular, document 605.525.01. The information is available in French, German, and Italian.  

## VAT Amounts and VAT Exchange Rates  
According to local VAT laws, the VAT base amount for an invoice can be reduced by the payment discount if a discount is granted. To allow automatic VAT adjustment for a payment discount on an invoice, the **Adjust for Payment Discount** field is activated by default in the **General Ledger Setup** window. You can also activate this function in the VAT posting setup. For more information, see the General Ledger Setup table and the VAT Posting Setup table.  

### Currency Exchange Rates for VAT Reporting  
For invoices in foreign currency, you must use the official exchange rate provided by the government for the VAT calculation itself. You can also set up additional exchange rates for VAT, which you can use for aspects of the invoice other than the VAT calculation. You can provide the correct government VAT exchange rate for each relevant foreign currency in the exchange rate setup for invoices. For more information, see the Currency Exchange Rate table.  

You can also adjust all VAT amounts in VAT entries that result from foreign currency transactions. When you activate the adjust VAT exchange rate function, VAT exchange rates are adjusted automatically. The positive differences that result from exchange rates are posted to exchange rate gain accounts. The negative differences that result from exchange rates are posted to exchange rate loss accounts. For more information, see the Adjust Exchange Rates batch job.  

Additional information, such as VAT rate and original currency amount, is transferred to the VAT entries. For more information, see the VAT Entry table.  

## VAT Information in Journals  
When you enter a new line in a journal, the VAT percentages and VAT amounts for the account and balance account for the selected journal line are populated in the journal status area. For more information, see the General Journal window, Sales Journal window, and the Purchase Journal.  

## See Also
[Dynamics 365 Business Central](https://docs.microsoft.com/dynamics365/business-central/)  
[VAT Rates for Switzerland](vat-rates-for-switzerland.md)   
 [How to: Create and Print a Swiss VAT Statement](how-to-create-and-print-a-swiss-vat-statement.md)   
 [Switzerland Local Functionality](switzerland-local-functionality.md)   
