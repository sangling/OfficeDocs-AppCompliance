---
title: Application Information for MailClark by MailClark
ms.author: 
ms.date: 05/01/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for MailClark, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data
---
# MailClark

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: —</p>

* <a href="https://teams.microsoft.com/l/app/64f174e8-7e14-4b48-871e-2fb7b17be302" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381679" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by MailClark to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | MailClark |
| ID | 64f174e8-7e14-4b48-871e-2fb7b17be302 |
| Capabilities | Bot, Tab, Messaging Extension |
| Partner company name | MailClark |
| Physical address | WeReso, 18-20 rue Tronchet, 69006 Lyon, France |
| URL of partner website | <https://mailclark.ai/msteams> |
| URL of Teams application info page | <https://mailclark.ai/support> |
| URL of Privacy Policy | <https://mailclark.ai/privacy> |
| URL of Terms of Use | <https://mailclark.ai/tos> |
| Main telephone number | (33) 767 796 960 |
| Description of available licensing options, if any | Free plan limited to 1 user &amp; 3 connected accounts. Premium plan at $5/m per active user (billed yearly) |
| Licensing contact | sales@mailclark.ai |
| Licensing telephone number | (33) 767 796 960 |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by MailClark on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/en-us/graph/permissions-reference) this app requires, and for each, whether they are delegate or application permissions, the justification and purpose for this permission (what does the app use this information for?), and whether the app stores any of this information in its databases.

>| **Permission**  | **Delegated/Application** | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:----------------|:--------------------------|:--------------------------|:---------------------------------------------------|
>| openid | Application | Required to authenticate |  |
>| profile | Application | To authenticate the user |  |
>| openid | Application | Required to authenticate |  |
>| profile | Application | To authenticate the account |  |
>| offline_access | Application | To renew authentication until the account is disconnected | Refresh token |
>| User.Read | Application | To identify the account | Account details e.g. email address |
>| Mail.ReadWrite | Application | Read: To subscribe push notifications for incoming emails—Write: To create drafts |  |
>| Mail.Send | Application | To send out drafts |  |

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Do this app make use of this capability?


>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Team Roster | To assign people to conversations | First name, last name, display name, email address |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>Tenant ID, user ID (email address)

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>Data stored in AWS Ireland. Not encrypted. Only accessed by two privileged IT managers with individual SSH keys.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>As part of GDPR compliance, admins can request deletions, data access and more (see Legal tab for details).

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end


