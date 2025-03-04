---
    title: How to Set Up Customers for OIOUBL
    description: To create Offentlig Information Online UBL (OIOUBL) documents for customers in the public sector, you must add OIOUBL information to the relevant customers.
    author: SorenGP

    ms.prod: "dynamics-nav-2018"
    ms.topic: article
    ms.devlang: na
    ms.tgt_pltfrm: na
    ms.workload: na
    ms.search.keywords:
    ms.date: 09/17/2019
    ms.author: edupont

---
# How to: Set Up Customers for OIOUBL
To create Offentlig Information Online UBL (OIOUBL) documents for customers in the public sector, you must add OIOUBL information to the relevant customers.  

 This topic only describes fields that apply to OIOUBL. For more information, see [How to: Register New Customers](../../sales-how-register-new-customers.md).  

### To set up customers for OIOUBL  

1. Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Customers**, and then choose the related link.  
2. Open the customer that you want to enable for OIOUBL.  
3. On the **Invoicing** FastTab, fill in the fields as described in the following table.  

   |Field|Description|  
   |---------------------------------|---------------------------------------|  
   |**EAN No.**|Enter the European Article Numbering (EAN) location number for the customer. For more information, see [EAN Location Number](ean-location-number.md).|  
   |**Account Code**|Enter the account code for the customer.<br /><br /> Customers in the public sector provide an account code when they place an order or requisition. Based on the value of this field, the account code is included in the OIOUBL documents that you create in [!INCLUDE[navnow](../../includes/navnow_md.md)]. In accordance with **Lov om Offentlige Betalinger** and related statutes, the customer is entitled to withhold payment until they receive an invoice with the relevant account code. For more information, see Account Code.|  
   |**OIOUBL Profile Code**|Specifies the profile that this customer requires for electronic documents if this is different from the default profile that you specified in the **Sales & Receivables Setup** window.|  
   |**OIOUBL Profile Code Required**|Specifies if this customer requires a profile code for electronic documents. **Tip:**  If the **OIOUBL Profile Code Required** field is selected, you cannot post a sales document for this customer unless you have specified a profile.|  

   These fields are specific to OIOUBL. The values are used in all OIOUBL documents that you create for this customer. For more information, see [OIOUBL Electronic Invoicing Overview](oioubl-electronic-invoicing-overview.md).  

## See Also
[Dynamics 365 Business Central](https://docs.microsoft.com/dynamics365/business-central/)  
[Denmark Local Functionality](denmark-local-functionality.md)  
 [How to: Register New Customers](../../sales-how-register-new-customers.md)   
 [How to: Set Up OIOUBL](how-to-set-up-oioubl.md)   
 [How to: Create Electronic Documents by Using OIOUBL](how-to-create-electronic-documents-by-using-oioubl.md)   
 [OIOUBL Electronic Invoicing Overview](oioubl-electronic-invoicing-overview.md)   
 [EAN Location Number](ean-location-number.md)
