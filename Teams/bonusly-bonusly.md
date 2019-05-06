---
title: Application Information for Bonusly by Bonusly
ms.author: 
ms.date: 05/06/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for Bonusly, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data-mcas
---
# Bonusly

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: April 24, 2019</p>

* <a href="https://teams.microsoft.com/l/app/c06753b3-85de-4054-9a99-dcd869dc0836" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381622" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by Bonusly to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | Bonusly |
| ID | c06753b3-85de-4054-9a99-dcd869dc0836 |
| Capabilities | Bot |
| Partner company name | Bonusly |
| Physical address | 1928 Pearl Street, Boulder, CO |
| Contact information for this app | support@bonus.ly |
| URL of partner website | <https://bonus.ly/> |
| URL of Teams application info page | <http://help.bonus.ly/> |
| URL of Privacy Policy | <https://bonus.ly/privacy_policy> |
| URL of Terms of Use | <https://bonus.ly/terms_of_service> |
| Main telephone number | 1 (442) 222-8325 |
| Description of available licensing options, if any | N/A |
| Licensing contact | N/A |
| Licensing telephone number | N/A |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by Bonusly on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

This application does not use Microsoft Graph.

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Does this app make use of this capability?


>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Yes | We access user emails to find the associated users in our system. | User emails are stored in our system, but they are not entered into the system from Teams. |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>Yes, user emails appear in our logs when interacting with our Teams bot. Log data is stored for one year and then removed.

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>Application data is encrypted at rest, transmitted over TLS 1.2, and is accessible only by developers. Automated database snapshots are taken every 6 hours. Only a whitelisted set of IP addresses may communicate with the database servers.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>Customers can request to have data deleted at any time.

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Information from the [Microsoft Cloud App Security](https://www.microsoft.com/en-us/enterprise-mobility-security/cloud-app-security) catalog appears below.

> [!NOTE]
> Information from the Microsoft Cloud App Security catalog is based on a variety of sources. Microsoft works to keep the information current but makes no guarantees of the accuracy of all the data sources. Contact us if you believe information about an app is outdated.

<iframe height='1020' title='Microsoft Cloud App Security Information' src='https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/26579' frameborder='no'  style='width: 100%;'></iframe>

<a href="https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/26579" target="_blank">View in a new tab</a>

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

