---
ms.service: azure-monitor
ms.topic: include
ms.date: 08/28/2023
ms.author: edbaynash
author: EdB-MSFT
ms.custom: AddonAzureBackupProtectedInstance
---


| Column | Type | Description |
|---|---|---|
| ArchiveTierStorageConsumedInMBs | real |   |
| ArchiveTierStorageReplicationType | string |   |
| AzureDataCenter | string |   |
| BackupItemUniqueId | string |   |
| BackupManagementServerUniqueId | string |   |
| BackupManagementType | string |   |
| _BilledSize | real | The record size in bytes |
| BillingGroupFriendlyName | string |   |
| BillingGroupResourceGroupName | string |   |
| BillingGroupType | string |   |
| BillingGroupUniqueId | string |   |
| Category | string |   |
| DatasourceType | string |   |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| OperationName | string |   |
| ProtectedContainerUniqueId | string |   |
| ProtectedInstanceCount | int |   |
| ResourceGroupName | string |   |
| ResourceId | string |   |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SchemaVersion | string |   |
| SourceSizeInMBs | real |   |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| State | string |   |
| StorageConsumedInMBs | real |   |
| StorageReplicationType | string |   |
| SubscriptionId | string |   |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TimeGenerated | datetime |   |
| Type | string | The name of the table |
| VaultName | string |   |
| VaultTags | string |   |
| VaultType | string |   |
| VaultUniqueId | string |   |
