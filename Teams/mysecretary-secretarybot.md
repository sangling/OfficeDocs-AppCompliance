---
title: Application Information for SecretaryBot by MySecretary
ms.author: 
ms.date: 05/01/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for SecretaryBot, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data
---
# SecretaryBot

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: —</p>

* <a href="https://teams.microsoft.com/l/app/256ff1bc-fd16-4f82-aeb3-8a6977ff2ec4" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381085" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by MySecretary to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | SecretaryBot |
| ID | 256ff1bc-fd16-4f82-aeb3-8a6977ff2ec4 |
| Capabilities | Bot, Tab |
| Partner company name | MySecretary |
| Physical address | N/A |
| Contact information for this app | masota@morehour.com |
| URL of partner website | <https://secretarybot.wordpress.com/> |
| URL of Teams application info page | <https://secretarybot.wordpress.com/support/> |
| URL of Privacy Policy | <https://secretarybot.wordpress.com/privacy-policy/> |
| URL of Terms of Use | <https://secretarybot.wordpress.com/terms-of-use/> |
| Main telephone number | N/A |
| Description of available licensing options, if any | Free |
| Licensing contact | Support@morehour.com |
| Licensing telephone number | N/A |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by MySecretary on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/en-us/graph/permissions-reference) this app requires, and for each, whether they are delegate or application permissions, the justification and purpose for this permission (what does the app use this information for?), and whether the app stores any of this information in its databases.

>| **Permission**  | **Delegated/Application** | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:----------------|:--------------------------|:--------------------------|:---------------------------------------------------|
>| Calendars.Read.Shared | Delegated | Fetch user&#x27;s and their colleagues&#x27; free time information |  |
>| Calendars.ReadWrite | Delegated | Send meeting request instead of user |  |
>| MailboxSettings.Read | Delegated | Fetch user&#x27;s language and timezone setting | Stora language for showing correct langage. Save timezone to call MS Graph calendar API correctly |
>| People.Read | Delegated | Try to find colleagues who have strong relathionship with user |  |
>| User.Read | Delegated | Try to find user&#x27;s country and preferred language. It&#x27;s used for backup for MailboxSettings.Read. | Store username, city, country and langauge for user analytics. Store email for contacting customer. We have never used email address, but may use for support. |
>| email | Delegated | For storing email | Save above |
>| openid | Delegated | For OpenID authentication |  |
>| profile | Delegated | Getting user name and OID. Try to use OID for connecting Outlook Addin in the future. | Save OID for identifying user&#x27;s unique id in the MS identity system |

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Does this app make use of this capability?


>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Team | Use this infromation to schedule team meeting |  |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>Not specified.

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>We store users&#x27; data in  Microsoft Azure SQL Database. It is encrypted by SQL Database Transparent data encryption. Limited engineers can access it with Azure AD authentication.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>We don&#x27;t provide adminstrative control to end users yet, but if end users request us to delete data, we can follow their request.

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end


