---
title: Alert policies in the Microsoft Defender portal
f1.keywords: 
  - NOCSH
ms.author: chrisda
author: chrisda
manager: deniseb
audience: ITPro
ms.topic: how-to
ms.collection: 
  - m365-security
  - tier2
ms.localizationpriority: medium
ms.assetid:
ms.custom: 
  - seo-marvel-apr2020
description: Admins can use the Alert policy page in the Microsoft Defender portal to view and create alert policies to trigger alerts when the specified actions occur.
ms.service: defender-office-365
search.appverid: met150
ms.date: 10/9/2023
appliesto:
  - ✅ <a href="https://learn.microsoft.com/defender-office-365/mdo-about#defender-for-office-365-plan-1-vs-plan-2-cheat-sheet" target="_blank">Microsoft Defender for Office 365 Plan 1 and Plan 2</a>
  - ✅ <a href="https://learn.microsoft.com/defender-xdr/microsoft-365-defender" target="_blank">Microsoft Defender XDR</a>
---

# Alert policies in the Microsoft Defender portal

[!INCLUDE [MDO Trial banner](../includes/mdo-trial-banner.md)]

In Microsoft 365 organizations with mailboxes in Exchange Online, alert policies generate alerts in the alert dashboard when users take actions that match the conditions of the policy. There are many default alert policies that help you monitor activities. For example, assigning admin privileges in Exchange Online, malware attacks, phishing campaigns, and unusual levels of file deletions and external sharing.

> [!TIP]
> Alert policies in the Microsoft Defender portal are identical to alert policies in the Microsoft Purview compliance portal at <https://compliance.microsoft.com/alertpolicies>.

## What do you need to know before you begin?

- You need to be assigned permissions before you can do the procedures in this article. You have the following options:
  - [Microsoft Defender XDR Unified role based access control (RBAC)](/defender-xdr/manage-rbac) (If **Email & collaboration** \> **Defender for Office 365** permissions is :::image type="icon" source="media/scc-toggle-on.png" border="false"::: **Active**. Affects the Defender portal only, not PowerShell):
    - _Read only access to the Alert policies page_: **Security operations / Security data / Security data basics (read)**.
    - _Manage alert policies_: **Authorization and settings / Security settings / Detection tuning (manage)**.
  - [Email & collaboration permissions in the Microsoft Defender portal](mdo-portal-permissions.md):
    - _Create and manage alert policies in the Threat management category_: Membership in the **Organization Management** or **Security Administrator** role groups.
    - _View alerts in the Threat management_ category: Membership in the **Security Reader** role group.
  - [Microsoft Entra permissions](/entra/identity/role-based-access-control/manage-roles-portal): Membership in the **Global Administrator**, **Security Administrator**, or **Security Reader** roles gives users the required permissions _and_ permissions for other features in Microsoft 365.

  For information about other alert policy categories, see [Permissions required to view alerts](/purview/alert-policies#rbac-permissions-required-to-view-alerts).

## Open alert policies

In the Microsoft Defender portal at <https://security.microsoft.com>, go to **Email & collaboration** \> **Policies & rules** \> **Alert policy**. Or, to go directly to the **Alert policy** page, use <https://security.microsoft.com/alertpoliciesv2>.

On the **Alert policy** page, you can view and create alert policies. For more information, see [Alert policies in Microsoft 365](/purview/alert-policies)
