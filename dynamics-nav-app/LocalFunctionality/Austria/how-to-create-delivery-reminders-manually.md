---
    title: How to Create Delivery Reminders Manually
    description: In [!INCLUDE[navnow](../../includes/navnow_md.md)], you can create delivery reminders when a purchase has not been delivered as expected.

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
# How to: Create Delivery Reminders Manually
In [!INCLUDE[navnow](../../includes/navnow_md.md)], you can create delivery reminders when a purchase has not been delivered as expected. You can create a single delivery reminder manually, or you can generate delivery reminders for all overdue deliveries. For more information, see [How to: Generate Delivery Reminders](how-to-generate-delivery-reminders.md).

> [!NOTE]
> To create delivery reminders, you must set up the delivery reminder properties. For more information, see [How to: Set Up Delivery Reminders](how-to-set-up-delivery-reminders.md).

## To create a delivery reminder manually  

1.  Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Delivery Reminder**, and then choose the related link.  
2.  Choose the **New** action.  
3.  In the **Delivery Reminder** window, on the **General** FastTab, fill in the fields as described in the following table.  

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**No.**|The unique identification number for the delivery reminder.|  
    |**Vendor No.**|The number of the vendor for whom you want to post the delivery reminder.<br /><br /> When you select the vendor number, the **Name**, **Address**, **Post Code/City**, and **Contact** fields are filled in automatically.|  
    |**Posting Date**|The posting date for the delivery reminder. This date is copied to all of the delivery reminder ledger entries.|  
    |**Document Date**|The document date for the delivery reminder. This date is also used to calculate the due date for the delivery reminder. You can modify the posting date if required.|  
    |**Reminder Level**|The delivery reminder level. This value is based on the number of delivery reminders that have already been sent. For more information, see [How to: Set Up Delivery Reminder Terms, Levels, and Text](how-to-set-up-delivery-reminder-terms-levels-and-text.md).|  
    |**Reminder Terms Code**|Specify the delivery reminder terms code that is set up for the vendor.|  
    |**Due Date**|The due date for the delivery reminder.|  

4.  Choose the **Suggest Reminder Lines** action  

    If there are overdue deliveries from the specified vendor, these are added to the deliver reminder.  

5.  Choose the **OK** button.  

    The delivery reminder is created. You can now issue and print the delivery reminder.  

## See Also
[Dynamics 365 Business Central](https://docs.microsoft.com/dynamics365/business-central/)  
[Delivery Reminders](delivery-reminders.md)   
 [How to: Generate Delivery Reminders](how-to-generate-delivery-reminders.md)   
 [How to: Set Up Delivery Reminders](how-to-set-up-delivery-reminders.md)   
 [How to: Set Up Delivery Reminder Terms, Levels, and Text](how-to-set-up-delivery-reminder-terms-levels-and-text.md)   
 [How to: Assign Delivery Reminder Codes to Vendors](how-to-assign-delivery-reminder-codes-to-vendors.md)   
 [How to: Issue Delivery Reminders](how-to-issue-delivery-reminders.md)   
 [How to: Print Test Reports for Delivery Reminders](how-to-print-test-reports-for-delivery-reminders.md)
