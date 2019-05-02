---
title: Application Information for MeisterTask by MeisterLabs GmbH
ms.author: 
ms.date: 05/02/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for MeisterTask, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data-mcas
---
# MeisterTask

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: April 29, 2019</p>

* <a href="https://teams.microsoft.com/l/app/4d0f0848-3fdd-4046-9976-d5568c8b71f4" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381349" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by MeisterLabs GmbH to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | MeisterTask |
| ID | 4d0f0848-3fdd-4046-9976-d5568c8b71f4 |
| Capabilities | Tab |
| Partner company name | MeisterLabs GmbH |
| Physical address | Zugspitzstrasse 2, 85591 Vaterstetten, Germany |
| Contact information for this app | info@meistertask.com |
| URL of partner website | <https://www.meistertask.com> |
| URL of Teams application info page | <https://support.meistertask.com/> |
| URL of Privacy Policy | <https://www.meistertask.com/privacy> |
| URL of Terms of Use | <https://www.meistertask.com/legal> |
| Main telephone number | (49) 89 1213 5359 |
| Description of available licensing options, if any | free basic plan as well as pro, business and enterprise plans with monthly or annual payments |
| Licensing contact | support@meistertask.com |
| Licensing telephone number | (49) 89 1213 5359 |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by MeisterLabs GmbH on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/en-us/graph/permissions-reference) this app requires, and for each, whether they are delegate or application permissions, the justification and purpose for this permission (what does the app use this information for?), and whether the app stores any of this information in its databases.

>| **Permission**  | **Delegated/Application** | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:----------------|:--------------------------|:--------------------------|:---------------------------------------------------|
>| User.Read | Delegated | For authentication and sign-up | id, displayName, mail |

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Does this app make use of this capability?

>Organization ID for Azure Marketplace license managment

>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>|  |  |  |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>All of the EUII and OII mentioned above can potentially end up in log files used for debugging purposes. All log data is automatically deleted after 6 months at the latest.

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>All application data is encrypted in transit and at rest. It can only be accessed by select roles. A thorough permission system according to the principle of least privilege is implemented, and all employees are using 2FA.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>Customer&#x27;s administrators can delete their data and close their accounts. The retention perios is not customizable. Auditing is currently not available. User-generated data can be archived manually or accessed through the public API (https://developers.meistertask.com/). The end-user policies are available at https://www.meistertask.com/privacy and https://www.meistertask.com/terms.

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Information from the [Microsoft Cloud App Security](https://www.microsoft.com/en-us/enterprise-mobility-security/cloud-app-security) catalog:

<iframe height='1020' title='Microsoft Cloud App Security Information' src='https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/35426' frameborder='no'  style='width: 100%;'></iframe>

<a href="https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/35426" target="_blank">View in a new tab</a>

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

