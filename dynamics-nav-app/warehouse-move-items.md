---
    title: Move Items 
    description: While in inventory, items may need to be moved between bins to support the daily warehouse activities involved in keeping items flowing through the warehouse. Some movements happen in direct relation to internal operations, such as a production order that needs components delivered or end items put away. Other movements happen as mere warehouse space optimization or as ad-hoc movements to and from operations.
    
    documentationcenter: ''
    author: SorenGP

    ms.prod: "dynamics-nav-2018"
    ms.topic: article
    ms.devlang: na
    ms.tgt_pltfrm: na
    ms.workload: na
    ms.search.keywords:
    ms.date: 08/22/2017
    ms.author: edupont

---
# Moving Items
The warehouse activity of moving items within the warehouse is performed in different ways depending on how warehouse management features are configured. The complexity can rank from no warehouse features, through basic warehouse configurations for order-by order handling in one or more activities only, to advanced configurations where all warehouse activities must be performed in a directed workflow. For more information, see [Setting Up Warehouse Management](warehouse-setup-warehouse.md).

While in one warehouse location, items may need to be moved between bins to support the daily warehouse activities involved in keeping items flowing through the warehouse. Some movements happen in direct relation to internal operations, such as a production order that needs components delivered or end items put away. Other movements happen as mere warehouse space optimization or as ad-hoc movements to and from operations.

Moving items to other locations affects the item ledger entries and must therefore be done by transfer order. For more information, see [How to: Transfer Inventory Between Locations](inventory-how-transfer-between-locations.md).  

Additional movement tasks are to periodically replenish picking bins or shop floor bins and to modify bin content information.  

 The following table describes a sequence of tasks, with links to the topics that describe them.   

|**To**|**See**|  
|------------|-------------|  
|Move items between bins in basic warehouse configurations at any time and without source documents.|[How to: Move Items in Basic Warehouse Configurations](warehouse-how-to-move-items-ad-hoc-in-basic-warehousing.md)|
|Use the warehouse movement worksheet to move items in advanced warehouse configurations, both for source documents and ad hoc.|[How to: Move Items in Advanced Warehouse Configurations](warehouse-how-to-move-items-in-advanced-warehousing.md)|  
|Bring component items to internal operations in basic warehouse configurations as requested by source documents for those operations.|[How to: Move Components to an Operation Area in Basic Warehouse Configurations](warehouse-how-to-move-components-to-an-operation-area-in-basic-warehousing.md)|
|Plan which bins to fill or empty to maintain an efficient flow, such as emptying a bulk storage area before a large receipt.|[How to: Plan Warehouse Movements in Worksheets](warehouse-how-to-plan-warehouse-movements-in-worksheets.md)|
|Update the frequency at which bins, such as picking bins, must be replenished as a result of demand fluctuations.|[How to: Calculate Bin Replenishment](warehouse-how-to-calculate-bin-replenishment.md)|
|Restructure your warehouse with new bin codes and new bin characteristics and potentially move them around.|[How to: Restructure Warehouses](warehouse-how-to-restructure-warehouses.md)|  

## See Also
[Dynamics 365 Business Central](https://docs.microsoft.com/dynamics365/business-central/)  
[Warehouse Management](warehouse-manage-warehouse.md)  
[Inventory](inventory-manage-inventory.md)  
[Setting Up Warehouse Management](warehouse-setup-warehouse.md)     
[Assembly Management](assembly-assemble-items.md)    
[Design Details: Warehouse Management](design-details-warehouse-management.md)  
[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)
