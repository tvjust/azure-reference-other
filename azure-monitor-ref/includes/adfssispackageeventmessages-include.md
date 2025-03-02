---
ms.service: azure-monitor
ms.topic: include
ms.date: 08/28/2023
ms.author: edbaynash
author: EdB-MSFT
ms.custom: ADFSSISPackageEventMessages
---


| Column | Type | Description |
|---|---|---|
| _BilledSize | real | The record size in bytes |
| Category | string | The name of the log that belongs to |
| CorrelationId | string | correlation id |
| DataFactoryName | string | Data factory name |
| EventMessageGuid | string | Event message guid |
| EventName | string | Event name |
| ExecutionPath | string | Execution path |
| ExtendedInfoId | long | Extended info id |
| IntegrationRuntimeName | string | Integration runtime name |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| Level | string | Verbosity level of log |
| Message | string | Event message |
| MessageCode | int | Message code |
| MessageSourceId | string | Message source id |
| MessageSourceName | string | Message source name |
| MessageSourceType | int | Message source type |
| MessageTime | datetime | Message time |
| MessageType | int | Message type |
| OperationId | long | Operation id |
| OperationName | string | The name of the operation represented by this event |
| PackageName | string | Package name |
| PackagePath | string | Package path |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| SubcomponentName | string | Subcomponent name |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| ThreadId | int | Thread id |
| TimeGenerated | datetime | The timestamp (UTC) of the log |
| Type | string | The name of the table |
