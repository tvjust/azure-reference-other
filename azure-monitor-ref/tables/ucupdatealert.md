---
title: Azure Monitor Logs reference - UCUpdateAlert
description: Reference for UCUpdateAlert table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: edbaynash
author: EdB-MSFT
ms.date: 08/28/2023
---

# UCUpdateAlert

Update Compliance - Alert for both Client and Service Update, will contain information that needs attention, relative to one device (client), one update, and one deployment (if relevant). Certain fields may be blank depending on the UpdateAlert's AlertType field; for example, ServiceUpdateAlert will not necessarily contain client-side statuses. 

## Solutions

- LogManagement
- WaaSUpdateInsights

            


## Columns
  
[!INCLUDE [ucupdatealert](../includes/ucupdatealert-include.md)]
