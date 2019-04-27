---
title: Application Information for Now Virtual Agent by ServiceNow
ms.author: 
ms.date: 04/26/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for Now Virtual Agent, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data-mcas-csa
---
# Now Virtual Agent

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>

* <a href="https://teams.microsoft.com/l/app/49471a10-fdbc-4ffb-b0b8-944f3df985d9" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381816" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by ServiceNow to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | Now Virtual Agent |
| ID | 49471a10-fdbc-4ffb-b0b8-944f3df985d9 |
| Capabilities | Bot |
| Partner company name | ServiceNow |
| Physical address | 2225 Lawson Lane, Santa Clara, CA 95054 |
| Contact information for this app | https://www.servicenow.com/contact-us-request-info.html |
| URL of partner website | <https://www.servicenow.com/> |
| URL of Privacy Policy | <https://www.servicenow.com/service-privacy.html> |
| URL of Terms of Use | <https://www.servicenow.com/terms-of-use.html> |
| Main telephone number | +1 (408) 501?8550 |
| Description of available licensing options, if any | Customers need to be on a ServiceNow package that includes Virtual Agent access, starting with ServiceNow London release.  We encourage customers to reach out to their ServiceNow account team for more information. |
| Licensing contact | We encourage customers to reach out to their ServiceNow account team for more information. |
| Licensing telephone number | We encourage customers to reach out to their ServiceNow account team for more information. |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by ServiceNow on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

List any Microsoft Graph permissions this app requires, and for each, whether they are delegate or application permissions, the justification and purpose for this permission (what does the app use this information for?), and whether the app stores any of this information in its databases.

>| **Permission**  | **Delegated/Application** | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:----------------|:--------------------------|:--------------------------|:---------------------------------------------------|
>| User.Read | Delegated | When ServiceNow admin installs the integration with MS Teams, the admin needs to log into their MS Teams account. We read the domain from the email address (not full email address). | The domain is stored in our data center for future message routing purposes. |
>| User.ReadBasic | Delegated | Blah blah blah | Blah blah blah |

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Do this app make use of this capability?

>Our bot interacts with user 1:1. It cannot be added to a team (yet) and does not access team roster. User needs to log in their ServiceNow account once from within Microsoft Teams to establish a connection. This is initiated from within Teams and will require ServiceNow credentials.

>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| No | N/A | No |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>Not out of box by ServiceNow. Customers can leverage the Virtual Agent framework to build additional capabilities that can potentially access organization or end user information. Users may type in personal identifiable information during the interaction with the bot and have the information sent over to ServiceNow.

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>Refer to the [Cloud Security Alliance section](servicenow?pivots=csa) for details.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>Refer to the [Cloud Security Alliance section](servicenow?pivots=csa) for details.

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Information from the [Microsoft Cloud App Security](https://www.microsoft.com/en-us/enterprise-mobility-security/cloud-app-security) catalog:

<iframe height='1020' title='Microsoft Cloud App Security Information' src='https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/10638' frameborder='no'  style='width: 100%;'></iframe>

<a href="https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/10638" target="_blank">View in a new tab</a>

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="csa"

### CSA STAR information

[Cloud Security Alliance](https://cloudsecurityalliance.org/about/) is a not-for-profit organization dedicated to defining and raising awareness of best practices to help ensure a secure cloud computing environment. The CSA maintains the [Security, Trust & Assurance Registry (STAR)](https://cloudsecurityalliance.org/star/), a free, publicly-accessible registry where cloud-based providers can publish information on security, privacy, and compliance practices. The STAR registry contains three levels of assurance: self-assessment, 3rd-party audit, and continuous monitoring. More information on assurance levels can be found [here](https://cloudsecurityalliance.org/star/#_overview).

> [!NOTE]
> This information is self-reported by ServiceNow and directly submitted to and retrieved from CSA STAR. Microsoft is not responsible for the accuracy of this information.

<iframe height='798' scrolling='yes' title='Microsoft Teams App Information: CSA STAR' src='https://66eac45ba2a0418f9cfa290fcad4072b.codepen.website/#/details/281/ServiceNow' frameborder='no' style='width: 100%;'></iframe>

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end
