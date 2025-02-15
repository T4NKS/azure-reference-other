---
ms.service: azure-monitor
ms.topic: include
ms.date: 08/28/2023
ms.author: edbaynash
author: EdB-MSFT
ms.custom: DeviceEtw
---


| Column | Type | Description |
|---|---|---|
| ActivityId | string |   |
| appName | string |   |
| _BilledSize | real | The record size in bytes |
| Computer | string |   |
| DeviceType | string |   |
| EventId | int |   |
| EventName | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| period | int |   |
| ProcessId | string |   |
| ProviderId | string |   |
| SerialNumber | string |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| status | int |   |
| tags | string |   |
| ThreadId | int |   |
| TimeGenerated | datetime |   |
| type | int |   |
| Type | string | The name of the table |
| wakeEnabled | bool |   |
