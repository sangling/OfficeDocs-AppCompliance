---
title: Application Information for Woobot by Woobot.io
ms.author: 
ms.date: 05/06/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for Woobot, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data-mcas
---
# Woobot

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: April 10, 2019</p>

* <a href="https://teams.microsoft.com/l/app/da999ad2-6288-494d-99de-8e555f2688bb" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381664" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by Woobot.io to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | Woobot |
| ID | da999ad2-6288-494d-99de-8e555f2688bb |
| Capabilities | Bot, Tab, Messaging Extension |
| Partner company name | Woobot.io |
| Physical address | N/A |
| Contact information for this app | info@woobot.io |
| URL of partner website | <https://woobot.io> |
| URL of Teams application info page | <http://woobot.io/support> |
| URL of Privacy Policy | <https://woobot.io/privacy> |
| URL of Terms of Use | <https://woobot.io/terms> |
| Main telephone number | 1 (773) 451-9358 |
| Description of available licensing options, if any | Free trial and annual subscriptions. See https://woobot.io/pricing |
| Licensing contact | support@woobot.io |
| Licensing telephone number | 1 (773) 451-9358 |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by Woobot.io on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

This application does not use Microsoft Graph.

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Does this app make use of this capability?


>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Yes | In order to map Salesforce users to Teams Users we require a list of Team user id&#x27;s. We also store the Team and Channels names so that users can send notifications to these teams. Also, we store which team user id&#x27;s have been welcomed by the app, and which have not, so that when a new user joins a team, woobot can personally welcome that user. We also store the Team and Channels names so that users can send notifications to these teams. |  User Id, Team Id and Team Name, Channel Id and channel Name, and which users are members of which Teams. |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>No

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>Only privileged access is granted in a need to know basis. All privileged users make use of 2FA.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>Customer&#x27;s have full control of their configuration data that is created by them within our system. No other customer data is stored in our system.

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Information from the [Microsoft Cloud App Security](https://www.microsoft.com/en-us/enterprise-mobility-security/cloud-app-security) catalog appears below.

> [!NOTE]
> Information from the Microsoft Cloud App Security catalog is based on a variety of sources. Microsoft works to keep the information current but makes no guarantees of the accuracy of all the data sources. Contact us if you believe information about an app is outdated.

<iframe height='1020' title='Microsoft Cloud App Security Information' src='https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/35666' frameborder='no'  style='width: 100%;'></iframe>

<a href="https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/35666" target="_blank">View in a new tab</a>

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

