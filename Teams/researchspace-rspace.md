---
title: Application Information for RSpace by ResearchSpace
ms.author: 
ms.date: 05/01/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for RSpace, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data
---
# RSpace

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: —</p>

* <a href="https://teams.microsoft.com/l/app/f2cc0584-bb0c-448f-a175-2c9725f0bb87" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381671" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by ResearchSpace to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | RSpace |
| ID | f2cc0584-bb0c-448f-a175-2c9725f0bb87 |
| Capabilities | Tab |
| Partner company name | ResearchSpace |
| Physical address | 24 Fountainhall Road, Edinburgh EH9 2LW, UK |
| Contact information for this app | info@researchspace.com |
| URL of partner website | <https://www.researchspace.com> |
| URL of Teams application info page | <https://www.researchspace.com/enterprise/help-and-support-resources-enterprise/> |
| URL of Privacy Policy | <https://www.researchspace.com/terms-conditions/#privacy> |
| URL of Terms of Use | <https://www.researchspace.com/terms-conditions> |
| Main telephone number | (44)7875 336302 |
| Description of available licensing options, if any | There is a one time set up and training fee of $1,500, and an annual subscription charge of $200/user commercial and $100/user academic with volume discounts. |
| Licensing contact | support@researchspace.com |
| Licensing telephone number | (44)7875 336302 |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by ResearchSpace on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

This application does not use Microsoft Graph.


#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>Username appears in logs. Access to logs is restricted to named staff

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>Data is stored on AWS EBS volumes, or internally on customer systems if they host the application themselves. EBS volumes are encrypted. Only named operations staff can access data from restricted IP addresses.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>Admins can delete or retain data as they see fit and in accordance with local or organisational data protection policies.

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end


