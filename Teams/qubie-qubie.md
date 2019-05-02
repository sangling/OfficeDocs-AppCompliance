---
title: Application Information for Qubie by Qubie
ms.author: 
ms.date: 05/01/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for Qubie, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data
---
# Qubie

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: —</p>

* <a href="https://teams.microsoft.com/l/app/a4b9907d-cff2-4771-91d5-30cb794f00c5" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381933" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by Qubie to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | Qubie |
| ID | a4b9907d-cff2-4771-91d5-30cb794f00c5 |
| Capabilities | Bot, Tab |
| Partner company name | Qubie |
| Physical address | 295 Madison Avenue, 45th Floor, New York, NY 10017, United States |
| Contact information for this app | info@questback.com |
| URL of partner website | <https://www.questback.com/our-products/performance-suite/teams-triumph-with-qubie/> |
| URL of Teams application info page | <http://www.questback.com/qubie-ms-teams> |
| URL of Privacy Policy | <https://www.questback.com/qubie-privacy-policy/> |
| URL of Terms of Use | <https://www.questback.com/qubie-terms-and-conditions/> |
| Main telephone number | 1 (800) 974-8784 |
| Description of available licensing options, if any | Freemium version - Free for all with limited functionality - Premium paid version with added functionality |
| Licensing contact | info@questback.com |
| Licensing telephone number | 1 (800) 974-8784 |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by Qubie on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

This application does not use Microsoft Graph.

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Does this app make use of this capability?


>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Team/Chat Roster | Show name when deleting comments in team chat, and to respond to user that files a bug or sends questions. Respond to user that files a bug or has a question. Displayed when showing team performance questions so user knows the context of the question. Display team name when showing reports and Graphs. | Display Name, Email Address, Team Name  |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>Display name and User email - Used to communicate with users who sends in bugs/questions

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>Data storied in Azure SQL database in Azure hosting environment.  This is encrypted at rest by default. Access: a role inside IT Operations in Questback is the only users with access to the environment. Requires 2FA.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>They can contact Questback to modify/delete, audit data.

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end


