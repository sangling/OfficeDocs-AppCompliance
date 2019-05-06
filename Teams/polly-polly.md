---
title: Application Information for Polly by Polly
ms.author: 
ms.date: 05/06/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for Polly, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data
---
# Polly

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: —</p>

* <a href="https://teams.microsoft.com/l/app/1542629c-01b3-4a6d-8f76-1938b779e48d" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381060" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by Polly to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | Polly |
| ID | 1542629c-01b3-4a6d-8f76-1938b779e48d |
| Capabilities | Bot, Tab |
| Partner company name | Polly |
| Physical address | 100 S King Street, Suite 500, Seattle, WA |
| Contact information for this app | contact@polly.ai |
| URL of partner website | <https://www.polly.ai> |
| URL of Teams application info page | <https://www.polly.ai/help/msteams> |
| URL of Privacy Policy | <https://www.polly.ai/privacy> |
| URL of Terms of Use | <https://www.polly.ai/tos> |
| Main telephone number | 1 (206) 743-0987 |
| Description of available licensing options, if any | None |
| Licensing contact | contact@polly.ai |
| Licensing telephone number | 1 (206) 743-0987 |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by Polly on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

This application does not use Microsoft Graph.

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Does this app make use of this capability?


>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Team/Chat Roster | Providing list of users and channels | All |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>None

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>Polly uses a SAS database provided by Mongo Atlas for production.  Data is encrypted at rest using AES 256 encryption provided by the vendor.  Access to the database is restricted to support personel while doing customer support or maintenance work, and is protected by 2FA and IP Address white listing for all admin accounts.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>Customers are able to control data retention and perform auditing as part of the Polly Enterprise service plan.

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end


