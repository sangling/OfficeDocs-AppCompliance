---
title: Application Information for AtBot by H3 Solutions, Inc.
ms.author: 
ms.date: 05/01/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for AtBot, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data
---
# AtBot

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: —</p>

* <a href="https://teams.microsoft.com/l/app/7c01af81-ae7d-416e-98a3-c139cae8cfb0" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381219" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by H3 Solutions, Inc. to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | AtBot |
| ID | 7c01af81-ae7d-416e-98a3-c139cae8cfb0 |
| Capabilities | Bot |
| Partner company name | H3 Solutions, Inc. |
| Physical address | 10432 Balls Ford Rd. STE 230 Manassas, VA 20109 |
| Contact information for this app | hello@atbot.io |
| URL of partner website | <https://atbot.io> |
| URL of Teams application info page | <https://admin.atbot.io/Docs/GettingStarted> |
| URL of Privacy Policy | <https://admin.atbot.io/privacy> |
| URL of Terms of Use | <https://admin.atbot.io/terms> |
| Main telephone number | 1 (855) 464-5914 |
| Description of available licensing options, if any | Free, Pro, Enterprise \| https://admin.atbot.io/Docs/BizzyTiers |
| Licensing contact | support@atbot.io |
| Licensing telephone number | 1 (855) 464-5914 |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by H3 Solutions, Inc. on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

This application does not use Microsoft Graph.

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Do this app make use of this capability?


>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Yes | The creation of mentions in bot-generated chat messages | No |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>Tenant ID, UPN
We use Application Insights and our logs will last for 90 days before being automatically archived. (https://docs.microsoft.com/en-us/azure/azure-monitor/app/data-retention-privacy)

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>All AtBot Web Applications, Databases, Caching and Storage resources are located in a 	subscription that is not connected to our company AAD with only Administrators who 	have access to the resources.  2FA is required for these administrators.  All databases are 	encrypted and firewalled to only allow Azure IPs and our corporate office in Manassas, 	VA.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>Administrators have the ability to delete bot configurations that may contain AAD Group Names/GUIDs.
Upon cancellation of service, all UPNs will be removed from the licensing database.
See 'Azure Services' under Data Residency.  Much of the customer-specific data produced via the use of AtBot is stored in the customer's tenant and so admins of that tenant have full control of the data there.

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end


