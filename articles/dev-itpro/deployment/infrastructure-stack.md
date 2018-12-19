---
# required metadata

title: Self-service deployment
description: This topic provides an overview self-service deployment for Finance and Operations.
author: sarvanisathish
manager: AnnBe
ms.date: 12/18/2018
ms.topic: article
ms.prod: 
ms.service: dynamics-ax-applications
ms.technology: 

# optional metadata

# ms.search.form:  [Operations AOT form name to tie this topic to]
audience: IT Pro
# ms.devlang: 
ms.reviewer: sericks
ms.search.scope: Operations
# ms.custom: [used by loc for topics migrated from the wiki]
ms.search.region: Global 
# ms.search.industry: 
ms.author: sarvanis
ms.search.validFrom: 2018-12-31
ms.dyn365.ops.version: 8.1.1

---

# Self-service deployment

[!include[banner](../includes/banner.md)]
[!include [banner](../includes/limited-availability.md)]

Self-service deployment is available for Dynamics 365 for Finance and Operations **Tier 2 through 5** cloud environments. Self-service deployment enables easier deployment and significantly reduced deployment times.

> [!Important]
> This update will be released incrementally, based on your Azure country/region. However at this time, this experience is only available for **new customers** signing up for Finance and Operations. There is no change to the experience current customers have with existing environments.  
>
> Note that not all new customers signing up for Finance and Operations will see the experience. We will gradually increase the number of new customers seeing this experience.

## What’s new or changed

Customers using the self-service capabilities will see the following changes in their LCS experience. 

- Deployment is self-service and can be completed within an average time of 30 minutes. There are no longer lead times and wait times for deployment. You can control when you deploy, and verify that the environment is deployed. This experience is the same as the current experience. Please see the [self-service deployment FAQ](https://docs.microsoft.com/en-us/dynamics365/unified-operations/dev-itpro/deployment/deploymentfaq) for additional questions.

   ![Deployment settings](media/deployment-settings.png)

- You will no longer have remote desktop access to the Tier 2+ sandbox environments. All operations that need remote desktop access are now available as self-service actions. The following image shows some of the operations in the environment’s **Maintain** \> **Move database menu option**. The [Maintenance Operations](https://docs.microsoft.com/en-us/dynamics365/unified-operations/dev-itpro/deployment/maintenanceoperationsguide-newinfrastructure) article has additional details.

   > [!Important]
   > Remote desktop access will be restricted only to environments deployed using the self-service deployment. There is no change to existing environments or existing customers.

   ![Self-service actions](media/Self-service-actions.png)

- The diagnostics capabilities will remain the same, which enables troubleshooting without remote desktop access. Additional details on [diagnostics](https://docs.microsoft.com/en-us/dynamics365/unified-operations/dev-itpro/deployment/troubleshoot-newinfrastructure) is available in the help topic.

   ![Environment monitoring](media/environment-monitoring.png)

- You will not have SQL Server access on Tier 2+. You will continue to have SQL database access using just-in-time access.

- You will need to provide a combined deployable package for customizations. Delta packages will not be supported. This was always a recommended best practice and is now enforced.
