---
ms.service: azure-monitor
ms.topic: include
ms.date: 10/18/2023
ms.author: edbaynash
author: EdB-MSFT
ms.custom: Microsoft.NetworkFunction/azureTrafficCollectors, naam
---
<!--
NOTE:  This content is automatically generated using API calls to Azure. 
Any edits made on these files will be overwritten in the next run of the script. 
There is no benefit in editing these files directly.  
-->
  
  
|Metric|Name in REST API|Unit|Aggregation|Dimensions|Time Grains|DS Export|
|---|---|---|---|---|---|---|
|**Flow Records**<p><p>Flow Records Processed by ATC. |`count` |Count |Average, Total |`RoleInstance`, `Circuit`|PT1M |Yes|
|**CPU Usage**<p><p>CPU Usage Percentage. |`usage_active` |Percent |Average, Minimum, Maximum |`Hostname`|PT5M, PT15M, PT30M, PT1H, PT6H, PT12H, P1D |Yes|
|**Memory Usage**<p><p>Memory Usage Percentage. |`used_percent` |Percent |Average |`Hostname`|PT1M |Yes|