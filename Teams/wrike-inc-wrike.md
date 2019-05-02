---
title: Application Information for Wrike by Wrike Inc.
ms.author: 
ms.date: 05/02/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for Wrike, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data-mcas-csa
---
# Wrike

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: April 25, 2019</p>

* <a href="https://teams.microsoft.com/l/app/05274a45-7312-4c23-8f64-d57fe4a28d6d" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381390" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by Wrike Inc. to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | Wrike |
| ID | 05274a45-7312-4c23-8f64-d57fe4a28d6d |
| Capabilities | Bot, Tab, Messaging Extension, Connector |
| Partner company name | Wrike Inc. |
| Physical address | 70 N 2nd Street San Jose, CA 95113 |
| Contact information for this app | N/A |
| URL of partner website | <https://www.wrike.com> |
| URL of Teams application info page | <https://help.wrike.com/hc/en-us/articles/115001825869-Microsoft-Teams> |
| URL of Privacy Policy | <https://www.wrike.com/security/privacy/> |
| URL of Terms of Use | <https://www.wrike.com/security/terms/> |
| Main telephone number | 1 (877)779-7453 |
| Description of available licensing options, if any | Free, Pro, Business, Enterprise, Wrike for Marketers. Licensing plans described here: https://www.wrike.com/price/ Wrike for Teams does&#x27;n require a paid plan to be used |
| Licensing contact | N/A |
| Licensing telephone number | 1 (877)-779-7453 |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by Wrike Inc. on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

This application does not use Microsoft Graph.

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Does this app make use of this capability?

>Our app creates data only on our side

>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>|  |  |  |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>1. We&#x27;re logging invalid attempts to login. Such information is archived in 1 month.
2. Looks like that&#x27;s the only case when we&#x27;re logging anything similar to EUII/OII.

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>Data is partially incrypted (we encrypt information like labels/titles/descriptions/usernmes/etc. Channel ids/user ids/account ids/etc are not encrupted). - Access by Wrike Support team: in case of troubleshooting or verifying the issue requires Support to access to your account; that access can only be granted by you only. This is enabled by a system generated security token that you provide out of band to our Support team, allowing Support to delve deeper into solving your problem for a limited amount of time. This systemic approach ensures additional confidentiality for your data stored in Wrike.
- Access by Wrike Operational team: Wrike Operational team is responsible to maintenance and support production environment including monitoring, patching and updating, delivery the new builds to production, etc. This access in this case is strictly prohibited from both procedural and technical aspects, and strong authorisation controls including but not limited VPN, 2FA and personal certificate are in place, moreover it is monitored in details using HIDS (Host-based Intrusion Detection System) and reviewed by Wrike Operational Security team. Moreover, in case of Amazon KMS (Wrike Lock functionality), the customer data is stored encrypted in Wrike database, so the data is not directly or indirectly available by Wrike Operational team, because the data can be decrypted using access to customer�s Amazon KMS, that is managed and controlled by the customer only.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>Our customers&#x27; administrators could control all data in their accounts, including deletion/retention/auditing/etc. 

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Information from the [Microsoft Cloud App Security](https://www.microsoft.com/en-us/enterprise-mobility-security/cloud-app-security) catalog:

<iframe height='1020' title='Microsoft Cloud App Security Information' src='https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/21522' frameborder='no'  style='width: 100%;'></iframe>

<a href="https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/21522" target="_blank">View in a new tab</a>

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="csa"

### CSA STAR information

[Cloud Security Alliance](https://cloudsecurityalliance.org/about/) is a not-for-profit organization dedicated to defining and raising awareness of best practices to help ensure a secure cloud computing environment. The CSA maintains the [Security, Trust & Assurance Registry (STAR)](https://cloudsecurityalliance.org/star/), a free, publicly-accessible registry where cloud-based providers can publish information on security, privacy, and compliance practices. The STAR registry contains three levels of assurance: self-assessment, 3rd-party audit, and continuous monitoring. More information on assurance levels can be found [here](https://cloudsecurityalliance.org/star/#_overview).

> [!NOTE]
> This information is self-reported by Wrike Inc. and directly submitted to and retrieved from CSA STAR. Microsoft is not responsible for the accuracy of this information.

<iframe height='798' scrolling='yes' title='Microsoft Teams App Information: CSA STAR' src='https://66eac45ba2a0418f9cfa290fcad4072b.codepen.website/#/details/347/Wrike' frameborder='no' style='width: 100%;'></iframe>

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end
