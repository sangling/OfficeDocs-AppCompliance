---
title: Application Information for Assistant @ Zoom.ai by Zoom.ai Inc
ms.author: 
ms.date: 05/02/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for Assistant @ Zoom.ai, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data-mcas
---
# Assistant @ Zoom.ai

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: April 14, 2019</p>

* <a href="https://teams.microsoft.com/l/app/cac7469b-37cc-44f5-bf08-ff6654d35819" target="_blank">View in Teams store</a>

::: zone pivot="general"

### General information

Information provided by Zoom.ai Inc to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | Assistant @ Zoom.ai |
| ID | cac7469b-37cc-44f5-bf08-ff6654d35819 |
| Capabilities | Bot, Tab |
| Partner company name | Zoom.ai Inc |
| Physical address | 325 Front Street West, 4th floor, Toronto, Ontario, Canada |
| Contact information for this app | hello@zoom.ai |
| URL of partner website | <https://zoom.ai> |
| URL of Privacy Policy | <https://zoom.ai/privacy> |
| URL of Terms of Use | <https://zoom.ai/privacy> |
| Main telephone number | N/A |
| Description of available licensing options, if any | free 7 day trial, $25/user/month afterwards |
| Licensing contact | sales@zoom.ai |
| Licensing telephone number | N/A |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by Zoom.ai Inc on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/en-us/graph/permissions-reference) this app requires, and for each, whether they are delegate or application permissions, the justification and purpose for this permission (what does the app use this information for?), and whether the app stores any of this information in its databases.

>| **Permission**  | **Delegated/Application** | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:----------------|:--------------------------|:--------------------------|:---------------------------------------------------|
>| Calendars.ReadWrite | Both | Access to user&#x27;s calendar events | meetings are cached in our mongoDB on Azure, but descriptions are encrypted |
>| MailboxSettings.ReadWrite | Both | User&#x27;s timezone | user&#x27;s timezone |
>| Contacts.ReadWrite | Both | Read the user&#x27;s contacts (so that we can invite them to a meeting) | contact&#x27;s name &amp; email |
>| Mail.Read | Both | (Optional) is used to read email meta data to under who the user&#x27;s most important contacts are (via Machine Learning) | contact email/name, frequency/recency of interactions |
>| offline_access | Application | We need to read and write through our back-end anytime, without the user being present | No |
>| Group.Read.All | Both | (optional) read corporate user groups (for scheduling with groups) | group name and members |
>| User.Read.All | Both | (Optional) read corporate users (for scheduling with coworkers) | user&#x27;s name &amp; email (stored as a contact) |

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Does this app make use of this capability?


>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Yes, we load the entire roster  | So that the users can schedule meetings with anyone on their team. | Team name/email are stored as contacts. |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>We log user IDs (from zoom.ai) in our logs.

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>MS Azure in Quebec Canada.  All sensitive information is encrypted in MongoDB using AES256 and a static key.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>Admins, end-users and their contacts can delete all information pertaining to their records.

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Information from the [Microsoft Cloud App Security](https://www.microsoft.com/en-us/enterprise-mobility-security/cloud-app-security) catalog:

<iframe height='1020' title='Microsoft Cloud App Security Information' src='https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/35668' frameborder='no'  style='width: 100%;'></iframe>

<a href="https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/35668" target="_blank">View in a new tab</a>

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

