---
ms.service: azure-monitor
ms.topic: include
ms.date: 08/28/2023
ms.author: edbaynash
author: EdB-MSFT
ms.custom: NWConnectionMonitorTestResult
---


| Column | Type | Description |
|---|---|---|
| AdditionalData | string | The additional data for the test |
| AvgRoundTripTimeMs | real | The average round trip time for the test |
| _BilledSize | real | The record size in bytes |
| ChecksFailed | int | The total number of checks failed under the test |
| ChecksFailedPercentThreshold | int | The checks failed percent threshold set for the test |
| ChecksTotal | int | The total number of checks done under the test |
| ConnectionMonitorResourceId | string | The connection monitor resource id of the test |
| DestinationAddress | string | The address of the destination configured for the test |
| DestinationAgentId | string | The destination agent id |
| DestinationIP | string | The IP address of the destination |
| DestinationName | string | The destination end point name |
| DestinationPort | int | The destination port configured for the test |
| DestinationResourceId | string | The resource id of the Destination machine |
| DestinationSubnet | string | If applicable, the subnet of the destination |
| DestinationType | string | The type of the destination machine configured for the test |
| _IsBillable | string | Specifies whether ingesting the data is billable. When _IsBillable is `false` ingestion isn't billed to your Azure account |
| JitterMs | real | The mean deviation round trip time for the test |
| MaxRoundTripTimeMs | real | The maximum round trip time for the test |
| MinRoundTripTimeMs | real | The minimum round trip time (ms) for the test |
| Protocol | string | The protocol of the test |
| RecordId | string | The record id for unique identification of test result record |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| RoundTripTimeMsThreshold | real | The round trip threshold (ms) set for the test |
| SourceAddress | string | The address of the source configured for the test |
| SourceAgentId | string | The source agent id |
| SourceIP | string | The IP address of the source |
| SourceName | string | The source end point name |
| SourceResourceId | string | The resource id of the source machine |
| SourceSubnet | string | The subnet of the source |
| SourceSystem | string | The type of agent the event was collected by. For example, `OpsManager` for Windows agent, either direct connect or Operations Manager, `Linux` for all Linux agents, or `Azure` for Azure Diagnostics |
| SourceType | string | The type of the source machine configured for the test |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string | The Log Analytics workspace ID |
| TestConfigurationName | string | The test configuration name to which the test belongs to |
| TestGroupName | string | The test group name to which the test belongs to |
| TestResult | string | The result of the test |
| TestResultCriterion | string | The result criterion of the test |
| TimeGenerated | datetime | The timestamp (UTC) of when the log was generated. |
| Type | string | The name of the table |
