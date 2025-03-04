---
title: Overview of Tasks to Manage Sales 
description: Describes how to manage sales activities.
author: SorenGP

ms.prod: "dynamics-nav-2018"
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: trade, sell
ms.date: 09/08/2017
ms.author: edupont

---
# Sales
You create a sales invoice or sales order to record your agreement with a customer to sell certain products on certain delivery and payment terms.

You must use sales orders if your sales process requires that you can ship parts of an order quantity, for example, because the full quantity is not available at once. If you sell items by delivering directly from your vendor to your customer, as a drop shipment, then you must also use sales orders. In all other aspects, sales orders work the same way as sales invoices. With sales orders, you can also use the Order Promising functionality to communicate certain delivery dates to your customers.  

You can negotiate with the customer by first creating a sales quote, which you can convert to a sales invoice or sales order when you agree on the sale. After the customer has confirmed the agreement, you can send an order confirmation to record your obligation to deliver the products as agreed.

You can easily correct or cancel a posted sales invoice before it is paid. This is useful if you want to correct a typing mistake or if the customer requests a change early in the order process. If the posted sales invoice is paid, then you must create a sales credit memo or a sales return order to reverse the sale.

Good sales and marketing practices are all about how to make the best decisions at the right time. Marketing functionality in [!INCLUDE[d365fin](includes/d365fin_md.md)] provides precise and timely overview of your contact information so that you can serve your prospective customers more efficiently and increase customer satisfaction. For more information, see [Relationship Management](marketing-relationship-management.md).

In business environments where the customer must pay before products are delivered, such as in retail, you must wait for the receipt of payment before you deliver the products. In most cases, you process incoming payments some weeks after delivery by applying the payments to their related posted, unpaid sales invoices. For more information, see [How to: Reconcile Payments Using Automatic Application](receivables-how-reconcile-payments-auto-application.md).

Sales documents can be sent as PDF files attached to email. The email body will contain an extract of the sales document, such as products, total amount, and a link to the PayPal site. For more information, see [How to: Send Documents by Email](ui-how-send-documents-email.md).

For all sales processes, you can incorporate an approval workflow, for example, to require that large sales to certain customers are approved by the accounting manager. For more information, see [Using Workflows](across-use-workflows.md).

The following table describes a sequence of tasks, with links to the topics that describe them.

| To | See |
| --- | --- |
| Create a sales quote where you offer products on negotiable terms before converting the quote to a sales invoice. |[How to: Make Offers](sales-how-make-offers.md) |
| Create a sales invoice to record your agreement with a customer to sell products on certain delivery and payment terms. |[How to: Invoice Sales](sales-how-invoice-sales.md) |
| Process a sales order that involves partial shipping or drop shipment. |[How to: Sell Products](sales-how-sell-products.md) |
|Set up standard sales or purchase lines that you can quickly insert on documents, for example, for recurring replenishment orders.|[How to: Create Recurring Sales and Purchase Lines](sales-how-work-standard-lines.md)|  
| Link a sales order to a purchase order to sell a drop-shipment item that will be delivered directly from your vendor to your customer. |[How to: Make Drop Shipments](sales-how-drop-shipment.md) |
|Have a nonstock item shipped from a vendor to your warehouse so that you can ship the item on to your customer.|[How to: Create Special Orders](sales-how-to-create-special-orders.md)|
| Perform an action on an unpaid posted sales invoice to automatically create a credit memo and either cancel the sales invoice or recreate it so you can make corrections. |[How to: Correct or Cancel Unpaid Sales Invoices](sales-how-correct-cancel-sales-invoice.md) |
| Create a sales credit memo to revert a specific posted sales invoice to reflect which products the customer returns and which payment amount you will refund. |[How to: Process Sales Returns or Cancellations](sales-how-process-sales-returns-cancellations.md) |
|Manage your customer's commitment to purchase large quantities delivered in several shipments over time.|[How to: Work with Blanket Sales Orders](sales-how-to-create-blanket-sales-orders.md)|
|Sell assembly items that are not currently available by creating a linked assembly order to supply the full or partial sales order quantity.|[How to: Sell Items Assembled to Order](assembly-how-to-sell-items-assembled-to-order.md)|
|Invoice a customer once for multiple shipments by combining the shipments on one invoice.|[How to: Combine Shipments on a Single Invoice](sales-how-to-combine-shipments-on-a-single-invoice.md)|
|Inform your customers of order delivery dates by calculating either the capable-to-promise date or the available-to-promise date.|[How to: Calculate Order Promising Dates](sales-how-to-calculate-order-promising-dates.md)|

## See Also
[Dynamics 365 Business Central](https://docs.microsoft.com/dynamics365/business-central/)  
[Setting Up Sales](sales-setup-sales.md)  
[How to: Register New Customers](sales-how-register-new-customers.md)  
[Managing Receivables](receivables-manage-receivables.md)  
[Managing Payables](payables-manage-payables.md)  
[Project Management](projects-manage-projects.md)    
[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
[General Business Functionality](ui-across-business-areas.md)

## 
