---
title: Application Information for MURAL by MURAL
ms.author: 
ms.date: 04/30/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for MURAL, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data-csa
---
# MURAL

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: —</p>

* <a href="https://teams.microsoft.com/l/app/c738b607-88dd-4f16-aefe-6a824c65d25d" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381626" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by MURAL to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | MURAL |
| ID | c738b607-88dd-4f16-aefe-6a824c65d25d |
| Capabilities | Bot, Tab, Messaging Extension |
| Partner company name | MURAL |
| Physical address | 650 California St. 7th floor suite 105. San Francisco , CA. 94108 |
| Contact information for this app | info@mural.co |
| URL of partner website | <https://mural.co/> |
| URL of Teams application info page | <https://support.mural.co/> |
| URL of Privacy Policy | <https://mural.co/terms/privacy-policy> |
| URL of Terms of Use | <https://mural.co/terms> |
| Main telephone number | 1 415 687 2501 Staffed during support hours |
| Description of available licensing options, if any | Pricing options are: https://mural.co/pricing |
| Licensing contact | info@mural.co |
| Licensing telephone number | info@mural.co |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by MURAL on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

List any Microsoft Graph permissions this app requires, and for each, whether they are delegate or application permissions, the justification and purpose for this permission (what does the app use this information for?), and whether the app stores any of this information in its databases.

>| **Permission**  | **Delegated/Application** | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:----------------|:--------------------------|:--------------------------|:---------------------------------------------------|
>| N/A | N/A | N/A | N/A |

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Do this app make use of this capability?

>We are only getting and storing the user&#x27;s name.

>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>|  |  |  |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>Yes, we log personal information (username, email, etc.) to build our audit log. The information is stored in our database encrypted and can only be accessed when consulting the audit api.

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>Data is stored in our Microsoft Azure Cloud service. The data is stored encrypted at rest with AES-256. Our infrastructure and devops team has access to the database management, but not to the data itself. Users login to the system with MFA and there's an audit trail of every action taken by them once in the infra.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>Administrators can manage users, delete them, delete murals, etc. The user policy is here: https://mural.co/terms

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="csa"

### CSA STAR information

[Cloud Security Alliance](https://cloudsecurityalliance.org/about/) is a not-for-profit organization dedicated to defining and raising awareness of best practices to help ensure a secure cloud computing environment. The CSA maintains the [Security, Trust & Assurance Registry (STAR)](https://cloudsecurityalliance.org/star/), a free, publicly-accessible registry where cloud-based providers can publish information on security, privacy, and compliance practices. The STAR registry contains three levels of assurance: self-assessment, 3rd-party audit, and continuous monitoring. More information on assurance levels can be found [here](https://cloudsecurityalliance.org/star/#_overview).

> [!NOTE]
> This information is self-reported by MURAL and directly submitted to and retrieved from CSA STAR. Microsoft is not responsible for the accuracy of this information.

<iframe height='798' scrolling='yes' title='Microsoft Teams App Information: CSA STAR' src='https://66eac45ba2a0418f9cfa290fcad4072b.codepen.website/#/details/385/MURAL' frameborder='no' style='width: 100%;'></iframe>

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end
