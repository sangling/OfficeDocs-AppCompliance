---
title: Application Information for Evernote by Evernote
ms.author: 
ms.date: 05/06/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for Evernote, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data-mcas
---
# Evernote

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: April 25, 2019</p>

* <a href="https://teams.microsoft.com/l/app/4e1f8576-93d5-4c24-abb5-f02782e00a4e" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381639" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by Evernote to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | Evernote |
| ID | 4e1f8576-93d5-4c24-abb5-f02782e00a4e |
| Capabilities | Bot, Tab, Messaging Extension |
| Partner company name | Evernote |
| Physical address | 305 Walnut Street, Redwood City, CA 94063 |
| Contact information for this app | help.evernote.com |
| URL of partner website | <https://evernote.com/> |
| URL of Teams application info page | <https://help.evernote.com/hc/en-us/articles/360001244667> |
| URL of Privacy Policy | <https://evernote.com/privacy> |
| URL of Terms of Use | <https://evernote.com/legal/terms-of-service> |
| Main telephone number | N/A |
| Description of available licensing options, if any | Evernote Basic, Premium and Business https://evernote.com/basic ; https://evernote.com/premium ; https://evernote.com/business |
| Licensing contact | help.evernote.com |
| Licensing telephone number | N/A |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by Evernote on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

This application does not use Microsoft Graph.


#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>Not specified.

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>Customer data that we store in GCP will be protected using Google�s built-in encryption-at-rest features. 
User generated content access is 
- restricted based on business need 
- requires customer approval, and internal manager approval prior to accessing user generated content 
Access is granted following least privilege principles: role based access control in the service admin tool and access to systems within production environment is based on business needs. Both 2FA and IP whitelisting are used for customer service team members.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>The admin console is where account admins can manage Evernote Business account information, users, and content. Some of things account admins can do in admin console:
- View account summary
- Add and manage users
- View and manage spaces, notebooks, notes, tags, and trash
- View and manage account billing, security, and integrations
https://help.evernote.com/hc/en-us/articles/209005497-Evernote-Business-Admin-Console-Overview

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Information from the [Microsoft Cloud App Security](https://www.microsoft.com/en-us/enterprise-mobility-security/cloud-app-security) catalog appears below.

> [!NOTE]
> Information from the Microsoft Cloud App Security catalog is based on a variety of sources. Microsoft works to keep the information current but makes no guarantees of the accuracy of all the data sources. Contact us if you believe information about an app is outdated.

<iframe height='1020' title='Microsoft Cloud App Security Information' src='https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/11693' frameborder='no'  style='width: 100%;'></iframe>

<a href="https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/11693" target="_blank">View in a new tab</a>

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

