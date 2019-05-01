---
title: Application Information for Talla by Talla Inc.
ms.author: 
ms.date: 05/01/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for Talla, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data
---
# Talla

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: —</p>

* <a href="https://teams.microsoft.com/l/app/bcb050bd-ad7e-4e0e-94a7-e38d7fa098c9" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381253" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by Talla Inc. to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | Talla |
| ID | bcb050bd-ad7e-4e0e-94a7-e38d7fa098c9 |
| Capabilities | Bot, Tab |
| Partner company name | Talla Inc. |
| Physical address | 2 Park Plaza, Floor 7, Boston, MA 02116  |
| Contact information for this app | hello@talla.com |
| URL of partner website | <https://www.talla.com> |
| URL of Teams application info page | <http://help.talla.com/> |
| URL of Privacy Policy | <https://www.talla.com/privacy> |
| URL of Terms of Use | <https://www.talla.com/terms> |
| Main telephone number | 1 (617) 517-4156 |
| Description of available licensing options, if any | We offer monthly and annual subscriptions for our products.  More information can be found at https://talla.com/pricing/. |
| Licensing contact | services@talla.com |
| Licensing telephone number | 1 (617) 517-4156 |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by Talla Inc. on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

This application does not use Microsoft Graph.

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Do this app make use of this capability?


>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Chat Roster | Talla stores the Microsoft user ID, the users email address, first and last name and display name. These are used to indenify the user and communicate with the user.  | Talla stores a user profile that includes: Microsoft user ID, frist and last name, display name and email address in it&#x27;s database |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>Yes; the exposure is minimal because the logs are rotated

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>All data stored in Talla databases is encrypted with industry standard AES-256 encryption. Talla production systems operate on the Amazon Web Services Virtual Private Cloud (VPC) Network.The data will be encrypted during transmission until it reaches the secure Talla VPC, which exists on Amazon Web Services. Once it is within the VPC, the data is secured within the Amazon Web Services Virtual Private Cloud (VPC) Network. 

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>Talla provides adminstrators to enable and disable access to the service on a per-user basis. A privledged base model is used to restrict access to content.  The service, also provides the ability see what questions a user is asking and the answers provided via the training protal

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end


