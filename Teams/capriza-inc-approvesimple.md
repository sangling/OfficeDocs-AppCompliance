---
title: Application Information for ApproveSimple by Capriza, Inc
ms.author: 
ms.date: 05/01/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for ApproveSimple, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data-csa
---
# ApproveSimple

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: —</p>

* <a href="https://teams.microsoft.com/l/app/c920bd4d-3e2a-449a-b30a-26d2a73fa875" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381812" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by Capriza, Inc to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | ApproveSimple |
| ID | c920bd4d-3e2a-449a-b30a-26d2a73fa875 |
| Capabilities | Bot |
| Partner company name | Capriza, Inc |
| Physical address | 3000 El Camino real, Suite 800 Palo Alto 94301 |
| Contact information for this app | msdn@capriza.com |
| URL of partner website | <https://www.capriza.com/msteams-landing-page> |
| URL of Teams application info page | <https://support.capriza.com/> |
| URL of Privacy Policy | <https://www.capriza.com/privacy-policy/> |
| URL of Terms of Use | <https://www.capriza.com/mla/> |
| Main telephone number | 1 (650) 600-3661 |
| Description of available licensing options, if any | https://www.capriza.com/plans/ |
| Licensing contact | support@capriza.com |
| Licensing telephone number | 1(650) 720-4865 |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by Capriza, Inc on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

This application does not use Microsoft Graph.

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Does this app make use of this capability?


>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Team | Notify user of a new pending approval request | email address |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>Name, email and team name

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>Mete-data is stored encrypted on Postgres DB hosted by AWS. Attachmenst and log files are stored encrypted on AWS S3. Keys are managed in AWS-KMS. Production access is available only to selected company employees. Admin console login policy supports SAML login via a 2FA Identity Provider.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>The product provides an admin dashboard where the admininistrator can define which users will be serviced by ApproveSimple (including LDAP import) and control the user policy, including admin privileges and login policy. Auditing and archiving is built-into the adminstration. For data deletion the customer needs to issue a service ticket. 

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="csa"

### CSA STAR information

[Cloud Security Alliance](https://cloudsecurityalliance.org/about/) is a not-for-profit organization dedicated to defining and raising awareness of best practices to help ensure a secure cloud computing environment. The CSA maintains the [Security, Trust & Assurance Registry (STAR)](https://cloudsecurityalliance.org/star/), a free, publicly-accessible registry where cloud-based providers can publish information on security, privacy, and compliance practices. The STAR registry contains three levels of assurance: self-assessment, 3rd-party audit, and continuous monitoring. More information on assurance levels can be found [here](https://cloudsecurityalliance.org/star/#_overview).

> [!NOTE]
> This information is self-reported by Capriza, Inc and directly submitted to and retrieved from CSA STAR. Microsoft is not responsible for the accuracy of this information.

<iframe height='798' scrolling='yes' title='Microsoft Teams App Information: CSA STAR' src='https://66eac45ba2a0418f9cfa290fcad4072b.codepen.website/#/details/49/Capriza' frameborder='no' style='width: 100%;'></iframe>

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end
