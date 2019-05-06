---
title: Application Information for Priority Matrix by Appfluence Inc
ms.author: 
ms.date: 05/06/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for Priority Matrix, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data-mcas
---
# Priority Matrix

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: April 18, 2019</p>

* <a href="https://teams.microsoft.com/l/app/5be2b320-a5b7-4221-893c-dee506e4e365" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104382005" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by Appfluence Inc to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | Priority Matrix |
| ID | 5be2b320-a5b7-4221-893c-dee506e4e365 |
| Capabilities | Bot, Tab, Messaging Extension, Connector |
| Partner company name | Appfluence Inc |
| Physical address | 2627 Hanover st, Palo Alto, CA 94304, United States |
| Contact information for this app | support@appfluence.com |
| URL of partner website | <https://appfluence.com> |
| URL of Teams application info page | <https://appfluence.com/help/> |
| URL of Privacy Policy | <https://appfluence.com/privacy> |
| URL of Terms of Use | <https://appfluence.com/eula> |
| Main telephone number | 1 (800) 551-3274 |
| Description of available licensing options, if any | Pro subscription at $12/user/month (billed annually), Business subscription at $24/u/m (billed annually), and Enterprise site-license at negotiated price. A basic free plan is available at no cost. |
| Licensing contact | sales@appfluence.com |
| Licensing telephone number | 1 (800) 551-3274 |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by Appfluence Inc on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/en-us/graph/permissions-reference) this app requires, and for each, whether they are delegate or application permissions, the justification and purpose for this permission (what does the app use this information for?), and whether the app stores any of this information in its databases.

>| **Permission**  | **Delegated/Application** | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:----------------|:--------------------------|:--------------------------|:---------------------------------------------------|
>| openid | Delegated | In order to sign in users via single-sign-on | We store the SSO connection to indicate the login mode for the user. |
>| offline_access | Delegated | Refresh token without bothering the user. | We store the login token in order to perform requests on behalf of the user |
>| User.Read | Delegated | Get the user&#x27;s name, email, avatar, to personalize their account with us | Basic user profile information (name, email, avatar) is stored by us. |
>| Mail.Read | Delegated | Used in our Outlook add-in to turn emails into tasks | We store tasks created in our system, with a link to the original message. |
>| Tasks.Read | Delegated | We bootstrap new user accounts with their Graph tasks | Some Outlook/Planner tasks are replicated in our system to help new users. |
>| User.ReadBasic.All | Delegated | On new account creation, we use this to suggest other team members. | Only when a new user is added to the account, do we store their email. |
>| Contacts.Read | Delegated | On new account creation, we use this to suggest other team members. | Only when a new user is added to the account, do we store their email. |
>| Calendars.Read | Delegated | We bootstrap new user accounts with their calendar events | A small number of calendar events are turned into tasks stored in our system. |

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Does this app make use of this capability?

>Priority Matrix manages project/task data created by the user, or by the app automatically in response to events.

>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Team, Chat | Our one-on-one tab shows users tasks shared with another user. We use the roster to constrain that filter. | No |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>We capture the user email in our crash reports, so we can help users who report issues. We also include unique EUII in our telemetry to track popular features and allocate our effort to improve the features our users use more often.

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>Only our executive team has access to application/personal data, which is encrypted both at rest and on transit. 2FA and rotating admin keys enforced by our system. Restricted, redacted access is available to our support staff for customer service tasks.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>Users are allowed full review/export to their personal and application data via our management dashboard. Deletion requests are handled manually by our support staff, and typically complied with within 48h. 

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Information from the [Microsoft Cloud App Security](https://www.microsoft.com/en-us/enterprise-mobility-security/cloud-app-security) catalog appears below.

> [!NOTE]
> Information from the Microsoft Cloud App Security catalog is based on a variety of sources. Microsoft works to keep the information current but makes no guarantees of the accuracy of all the data sources. Contact us if you believe information about an app is outdated.

<iframe height='1020' title='Microsoft Cloud App Security Information' src='https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/35667' frameborder='no'  style='width: 100%;'></iframe>

<a href="https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/35667" target="_blank">View in a new tab</a>

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

