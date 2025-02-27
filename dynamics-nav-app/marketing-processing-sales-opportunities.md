---
title: Process Sales Opportunities in Sales Cycles
description: You can view, close, or delete sales opportunities, and you can also create quotes and sales orders for opportunities, and move an opportunity through the stages of a sales cycle.

documentationcenter: ''
author: jswymer

ms.prod: "dynamics-nav-2018"
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: relationship, prospect
ms.date: 06/06/2017
ms.author: jswymer

---
# How to: Process Sales Opportunities
After you create an opportunity, there are several features for managing the opportunity and moving it through to completion.

## To view opportunities
The existing sale opportunities are available from the **Opportunity List** window. There are different ways to access this window for processing sales opportunities:

| To view opportunities for | Then |
| --- | --- |
| All salespeople and contacts |Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Opportunity List**, and then choose the related link. |
| A specific sales person |Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Salespeople**, and then choose the related link. Select the salesperson, choose the **Opportunities** action, and then choose the **List** action. |
| A specific contact |Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Contacts**, and then choose the related link. Select the contact from the list, and then choose the **Opportunities** action. |

Each of these tasks opens the **Opportunity List** window.

## To close opportunities
You can close opportunities when the negotiations are over. When closing an opportunity, you can specify whether it was won or lost, and the reasons for closing it. To specify a reason, you must set up closed opportunity codes.

1. In the **Opportunity List** window, select the opportunity, and the choose the **Close** action. The **Close Opportunity** window opens.
2. Fill in the relevant fields, and then choose the **OK** button.

   The **Close Opportunity Code** and **Date Closed** fields are required fields and must be filled in before you can choose the **OK** button.

   In the **Close Opportunity Code** field, you can choose from one of the existing close opportunity codes or add a new code. To add a new code, from the drop-down list, choose **Select from full list**, and then choose **new**. On the new blank line, fill in the **Code**, **Type**, and **Description** fields, and then choose the **OK** button.

## To create quotes for opportunities
You can create sales quotes for contacts that are not recorded as customers.

1. In the **Opportunity List** window, select the opportunity, and then choose the **Assign Sales Quote** action. The **Sales Quote** window opens.
2. Fill in the relevant fields.

## To create sales orders for opportunities
You can make sales orders from the sales quotes that you have created for your opportunities. Before you can create sales orders for your contacts, you must create the contact as a customer. For more information, see [Create a Customer, Vendor, or Bank Account From a Contact](marketing-how-create-contacts-new-customers-vendors-bank-accounts.md).

1. In the **Opportunity List** window, find the opportunity that you have created a sales quote for.
2. Choose the **Assign Sales Quote** action. The **Sales Quote** window opens to show the sales quote that you have assigned to the opportunity.
3. Fill in the additional fields, and then choose the **Make Order** action.

When handling sales opportunities, you may need to create a quote for the contact that the opportunity is linked to.

## To delete opportunities
You can delete opportunities, for example, after you have concluded a deal. However, you can only delete closed opportunities. There are two ways to delete closed opportunities. You can delete individual closed opportunities from the **Opportunity List** window or you can run the **Delete Closed Opportunities** batch job to delete multiple opportunities based on a specified criteria.

To delete closed opportunities from the **Opportunity List** window, select the opportunity, and then choose the **Delete** action.

To delete closed opportunities by using the **Delete Closed Opportunities** batch job, follow these steps:

1. Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Delete Opportunities**, and then choose the related link.
2. In the **Opportunity** section, set up the filters that specify the closed opportunities to delete.
3. Choose the **OK** button.

After you have deleted an opportunity, it is removed it from the **Opportunity List** window.

## To move an opportunity through sales cycle stages
If an opportunity follows a sales cycle, you can move it forward or back through the different stages, such as moving the next or previous stage, and even skipping a stage.

1. In the **Opportunity List** window, choose the **Update** action. The **Update Opportunity** opens,
2. Use the **Action Type** field to move the opportunity through the sales cycle stages:
   * **Next** moves the opportunity forward one stage.
   * **Skip** moves the opportunity forward one or several stages in the sales cycle, which you specify in the **Presentation** field. You can only skip stages that have been set up to allow skipping.
   * **Previous** moves the opportunity back one stage.
   * **Jump** moves the opportunity back one or several stages in the sales cycle, which you specify in the **Presentation** field.
   * **Update** enables you to change information (such as to modify your evaluation of their chances of success and estimated values) without moving to another stage.
3. Fill in the other fields as needed, and then choose the **OK** button.

## See Also
[Dynamics 365 Business Central](https://docs.microsoft.com/dynamics365/business-central/)  
[Sales](sales-manage-sales.md)  
[Creating and Managing Contacts](marketing-contacts.md)  
[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)
