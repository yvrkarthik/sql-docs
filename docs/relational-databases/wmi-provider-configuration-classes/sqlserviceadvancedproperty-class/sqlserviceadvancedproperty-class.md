---
title: "SqlServiceAdvancedProperty Class | Microsoft Docs"
ms.custom: ""
ms.date: "03/03/2017"
ms.prod: "sql"
ms.prod_service: "database-engine"
ms.service: ""
ms.component: "wmi"
ms.reviewer: ""
ms.suite: "sql"
ms.technology: 

ms.tgt_pltfrm: ""
ms.topic: "reference"
apiname: 
  - "SqlServiceAdvancedProperty Class"
apilocation: 
  - "sqlmgmproviderxpsp2up.mof"
apitype: "MOFDef"
helpviewer_keywords: 
  - "SqlServiceAdvancedProperty class"
ms.assetid: a5d06bde-6058-464c-a4aa-444d83f2331f
caps.latest.revision: 32
author: "CarlRabeler"
ms.author: "carlrab"
manager: "craigg"
ms.workload: "Inactive"
---
# SqlServiceAdvancedProperty Class
[!INCLUDE[tsql-appliesto-ss2008-xxxx-xxxx-xxx-md](../../../includes/tsql-appliesto-ss2008-xxxx-xxxx-xxx-md.md)]
  The [SqlServiceAdvancedProperty Class](../../../relational-databases/wmi-provider-configuration-classes/sqlserviceadvancedproperty-class/sqlserviceadvancedproperty-class.md) represents an advanced property of the service that is referenced by the [SqlService Class](../../../relational-databases/wmi-provider-configuration-classes/sqlservice-class/sqlservice-class.md) object.  
  
 The [AdvancedProperties Property (SqlService Class)](../../../relational-databases/wmi-provider-configuration-classes/sqlservice-class/advancedproperties-property-sqlservice-class.md) references an array of [SqlServiceAdvancedProperty Class](../../../relational-databases/wmi-provider-configuration-classes/sqlserviceadvancedproperty-class/sqlserviceadvancedproperty-class.md) objects.  
  
 The [Starting and Stopping Services](http://technet.microsoft.com/library/ms174886\(v=sql.105\).aspx) class represents properties that are unique to the service. These properties are not in the list of properties that is associated with the [SqlService Class](http://technet.microsoft.com/library/ms186497.aspx) class. The [SqlServiceAdvancedProperty Class](http://technet.microsoft.com/library/ms182447.aspx) class allows representation of string, numeric, or Boolean properties. You can use this class to view the unique properties of the specified service.  
  
## See Also  
 [Starting, Stopping, and Pausing Services](http://technet.microsoft.com/library/ms174886\(v=sql.105\).aspx)  
  
  
