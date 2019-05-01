---
title: Application Information for Droplr by Droplr
ms.author: 
ms.date: 05/01/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for Droplr, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data-mcas
---
# Droplr

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: —</p>

* <a href="https://teams.microsoft.com/l/app/3763b495-45c3-4fd4-a64c-944aa8aabf53" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381718" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by Droplr to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | Droplr |
| ID | 3763b495-45c3-4fd4-a64c-944aa8aabf53 |
| Capabilities | Bot, Tab, Messaging Extension |
| Partner company name | Droplr |
| Physical address | 1001 SW Emkay Dr, Bend, OR 97702 USA |
| Contact information for this app | levi@droplr.com |
| URL of partner website | <https://droplr.com> |
| URL of Teams application info page | <http://droplr.com/contact> |
| URL of Privacy Policy | <https://droplr.com/privacy> |
| URL of Terms of Use | <https://droplr.com/terms> |
| Main telephone number | 1-866-310-2315 |
| Description of available licensing options, if any | Droplr is Free for Microsoft Teams users. Pro and Enterprise accounts are available for purchase directly through Droplr. |
| Licensing contact | sales@droplr.com |
| Licensing telephone number | 1-866-310-2315 |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by Droplr on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

List any Microsoft Graph permissions this app requires, and for each, whether they are delegate or application permissions, the justification and purpose for this permission (what does the app use this information for?), and whether the app stores any of this information in its databases.

>| **Permission**  | **Delegated/Application** | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:----------------|:--------------------------|:--------------------------|:---------------------------------------------------|
>| User.Read | 42949682128 | We use this permission to identify the authenticated user and link it with their Droplr account | We store the &#x60;user_id&#x60; value in our database |

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Do this app make use of this capability?


>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>|  |  |  |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>No. It is against our policy to log user data.

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>Our application data is stored within our own virtual private cloud with network access control lists that prevent unauthorized requests going to our internal network. User data can only be accessed via 2FA. Direct access to database servers is protected behind 2FA and a jump box. All backups are encrypted at rest and deleted after 30 days.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>Users can delete their data at any time by logging into their Droplr account. Team administrators can additionally delete and archive data at any time (requires an Enterprise subscription).

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Information from the [Microsoft Cloud App Security](https://www.microsoft.com/en-us/enterprise-mobility-security/cloud-app-security) catalog:

<iframe height='1020' title='Microsoft Cloud App Security Information' src='https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/23296' frameborder='no'  style='width: 100%;'></iframe>

<a href="https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/23296" target="_blank">View in a new tab</a>

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

