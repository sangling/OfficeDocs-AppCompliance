---
title: Application Information for Calendar BOT by Approved Contact
ms.author: 
ms.date: 05/02/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for Calendar BOT, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data-mcas
---
# Calendar BOT

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: April 11, 2019</p>

* <a href="https://teams.microsoft.com/l/app/f02fddc9-159a-4d58-9800-d94c4f64bfe8" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381271" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by Approved Contact to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | Calendar BOT |
| ID | f02fddc9-159a-4d58-9800-d94c4f64bfe8 |
| Capabilities | Bot, Tab |
| Partner company name | Approved Contact |
| URL of partner website | <https://approvedcontact.com> |
| URL of Teams application info page | <https://approvedcontact.com/Help.aspx> |
| URL of Privacy Policy | <https://approvedcontact.com/Privacy%20Policy%20Bot.pdf> |
| URL of Terms of Use | <https://approvedcontact.com/Terms%20of%20use.pdf> |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by Approved Contact on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/en-us/graph/permissions-reference) this app requires, and for each, whether they are delegate or application permissions, the justification and purpose for this permission (what does the app use this information for?), and whether the app stores any of this information in its databases.

>| **Permission**  | **Delegated/Application** | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:----------------|:--------------------------|:--------------------------|:---------------------------------------------------|
>| openid | Delegated | Office 365 SSO | No |
>| offline_access | Delegated | Call Graph when user isn&#x27;t actively using our site | Yes, free/busy times for offline users. |
>| User.Read | Delegated | Basic profile information | Yes |
>| Calendars.ReadWrite | Delegated | We read free/busy time and schedule meetings | Yes, we store free/busy time for all users. |
>| Contacts.Read | Delegated | Importing contacts | Yes, we store contact information. |
>| User.ReadBasic.All | Delegated | Conference room scheduling | No |


#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>Not specified.

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>Not specified.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>Not specified.

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Information from the [Microsoft Cloud App Security](https://www.microsoft.com/en-us/enterprise-mobility-security/cloud-app-security) catalog:

<iframe height='1020' title='Microsoft Cloud App Security Information' src='https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/20445' frameborder='no'  style='width: 100%;'></iframe>

<a href="https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/20445" target="_blank">View in a new tab</a>

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

