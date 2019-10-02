---
title: "System Settings Mobile Client tab  | MicrosoftDocs"
description: System Settings Mobile Client tab 
author: jimholtz
manager: kvivek
ms.service: power-platform
ms.component: pa-admin
ms.topic: conceptual
ms.date: 04/20/2018
ms.author: jimholtz
search.audienceType: 
  - admin
search.app: 
  - D365CE
  - PowerApps
  - Powerplatform
---
# System Settings Mobile Client tab

Use the settings on this page to manage mobile settings.

[!INCLUDE [cc-settings-moving](../includes/cc-settings-moving.md)] 

## Open the System Settings dialog box (if it’s not already open)  

1. [!INCLUDE[proc_permissions_system_admin_and_customizer](../includes/proc-permissions-system-admin-and-customizer.md)]  

    Check your security role  

   - [!INCLUDE[proc_follow_steps_in_link](../includes/proc-follow-steps-in-link.md)]  

   - [!INCLUDE[proc_dont_have_correct_permissions](../includes/proc-dont-have-correct-permissions.md)]  

2. [!INCLUDE[proc_settings_administration](../includes/proc-settings-administration.md)]  

3. Choose the **System Settings** > **Mobile Client** tab.  


|                           Settings                            |                                                                                                                                                                                                                                         Description                                                                                                                                                                                                                                          |
|---------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Set conflict detection for mobile offline synchronization** |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|      Enable conflict for mobile offline synchronization       | If Yes, sync conflict detection will be enabled during the play back of actions after an offline device comes back online. If No, the default, no conflict detection is done while playing back actions after an offline device comes back online. The changes done offline will overwrite any changes done in model-driven apps in Dynamics 365, such as Dynamics 365 Sales and Customer Service.<br/>For more information, see "Sync conflict resolution" in [Work offline with Dynamics 365 for phones and tablets](/dynamics365/customer-engagement/mobile-app/v8/go-mobile/work-offline.md) |
