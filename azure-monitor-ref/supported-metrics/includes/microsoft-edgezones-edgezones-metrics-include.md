---
ms.service: azure-monitor
ms.topic: include
ms.date: 09/19/2023
ms.author: edbaynash
author: EdB-MSFT
ms.custom: microsoft.edgezones/edgezones, naam
---
  
  
|Metric|Name|Unit|Aggregation|Dimensions|Time Grains|DS Export|
|---|---|---|---|---|---|---|
|Disk IOPS<p><p>The total IOPS generated by Managed Disks in Azure Edge Zone Enterprise site. |`DiskStorageIOPSUsage` |CountPerSecond |Average |No Dimensions|PT1M |No|
|Disk Usage Percentage<p><p>The utilization of the Managed Disk capacity in Azure Edge Zone Enterprise site. |`DiskStorageUsedSizeUsage` |Percent |Average |No Dimensions|PT1H |Yes|
|Region Site Connectivity<p><p>The status of an Edge Zone Enterprise link connection to its Azure region |`RegionSiteConnectivity` |Count |Average, Maximum, Minimum |No Dimensions|PT1M |Yes|
|Total Disk Capacity<p><p>The total capacity of Managed Disk in Azure Edge Zone Enterprise site. |`TotalDiskStorageSizeCapacity` |Bytes |Average |No Dimensions|PT1H |Yes|
|Total VCore Capacity<p><p>The total capacity of the General-Purpose Compute vcore in Edge Zone Enterprise site.  |`TotalVcoreCapacity` |Count |Average |No Dimensions|PT1M |Yes|
|Vcore Usage Percentage<p><p>The utilization of the General-Purpose Compute vcores in Edge Zone Enterprise site  |`VcoresUsage` |Percent |Average |No Dimensions|PT1M |Yes|