---
title: Application Information for RememberThis by Tom Morgan
ms.author: 
ms.date: 05/01/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for RememberThis, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data
---
# RememberThis

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: —</p>

* <a href="https://teams.microsoft.com/l/app/d58f3268-9fe3-44f5-8a4c-abef78b77134" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381607" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by Tom Morgan to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | RememberThis |
| ID | d58f3268-9fe3-44f5-8a4c-abef78b77134 |
| Capabilities | Bot |
| Partner company name | Tom Morgan |
| Physical address | N/A |
| Contact information for this app | tom@thoughtstuff.co.uk |
| URL of partner website | <https://www.thoughtstuff.co.uk/free-products/rememberthis> |
| URL of Teams application info page | <https://www.thoughtstuff.co.uk/free-products/rememberthis> |
| URL of Privacy Policy | <https://www.thoughtstuff.co.uk/rememberthis/privacy-policy> |
| URL of Terms of Use | <https://www.thoughtstuff.co.uk/rememberthis/terms-of-service> |
| Main telephone number | (44)7812 986876 |
| Description of available licensing options, if any | Free |
| Licensing contact | N/A |
| Licensing telephone number | N/A |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by Tom Morgan on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

This application does not use Microsoft Graph.

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Does this app make use of this capability?

>Time of reminder event

>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Team Roster (messageTeamMembers permission) | To reminder users at the specified time | Yes - ConversationID, ActivityID, ServiceURL, DateTime to be reminded. None of this data is PII or OII. |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>Not specified.

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>Data stored in Azure Storage Queue. Encrypted AES 256. Access restricted by storage access key.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>None

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end


