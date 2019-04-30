---
title: Application Information for SurveyMonkey by SurveyMonkey
ms.author: 
ms.date: 04/30/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for SurveyMonkey, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data-mcas
---
# SurveyMonkey

<p></p><img alt="Non-attested image" src="./images/unattested.png" width="650"/>

* <a href="https://teams.microsoft.com/l/app/0fd925a0-357f-4d25-8456-b3022aaa41a9" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381088" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by SurveyMonkey to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | SurveyMonkey |
| ID | 0fd925a0-357f-4d25-8456-b3022aaa41a9 |
| Capabilities | Bot, Tab, Connector |
| Partner company name | SurveyMonkey |
| Physical address | 1 Curiosity Way, San Mateo, CA 94403 |
| Contact information for this app | support@surveymonkey.com |
| URL of partner website | <https://www.surveymonkey.com> |
| URL of Teams application info page | <https://help.surveymonkey.com/articles/en_US/kb/Microsoft-Teams-Integration> |
| URL of Privacy Policy | <https://www.surveymonkey.com/privacy> |
| URL of Terms of Use | <https://www.surveymonkey.com/mp/policy/terms-of-use/> |
| Main telephone number | N/A |
| Description of available licensing options, if any | SurveyMonkey is as online SaaS provider with a number of self-serve and sales-assisted licensing options as follows: Basic Standard Advantage Premier Enterprise (sales-assisted) Please refer to our Plans and Pricing page for more information: https://www.surveymonkey.com/pricing/teams |
| Licensing contact | api-admin@surveymonkey.com |
| Licensing telephone number | �(650) 543-8400� |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by SurveyMonkey on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

List any Microsoft Graph permissions this app requires, and for each, whether they are delegate or application permissions, the justification and purpose for this permission (what does the app use this information for?), and whether the app stores any of this information in its databases.

>| **Permission**  | **Delegated/Application** | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:----------------|:--------------------------|:--------------------------|:---------------------------------------------------|
>| group.readwrite.all | Delegated | To provide a list of groups/channels to share a survey with | no |

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Do this app make use of this capability?

>N/A

>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Access Chat roster | Internal tracking of usage, we only look at the size of the chat roster, other info is ignored | Yes, the size of the chat is stored (a single integer) |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>EUII - A success/fail log is created whenever a survey gets a response, and we try to send that response to Teams via the connector, this log includes user_id, survey_id, integration_id (which in the database can be used to look up MS Team ID, MS User ID)

Team Size, MS User ID, SM User ID, MS tenant ID are logged when a person first initiates contact with our integration

All of these logs are protected and only accessible via our company intranet, and only accessible by people who have the relevant permissions

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>Our primary data center is located in Las Vegas, NV and our secondary data center is located in Santa Clara, CA. SurveyMonkey owns and operates all of its servers and infrastructure at these locations. We also have Canadian data residency available for certain SurveyMonkey Enterprise customers located in Canada. All data is encrypted at rest using TDE with AES256 and data in transit is encrypted using TLS 1.2.

SurveyMonkey uses central user authentication to maintain identity and access management. This system manages all authentication and authorization to any and all corporate, and production infrastructure, systems and services. Strict access policies are maintained and reviewed on a quarterly basis. The reviews include but are not limited to: user access lists, policy groups and 3rd party access reviews. To access our production environment (i.e. to get a privileged account), one needs to obtain manager approval, complete a number of required trainings, and obtain approval from our security team. At that time, an additional VPN account is provisioned, which differentiates the �normal� account from a �privileged� account.

Only company-issued devices are allowed to access our production network. All wireless vendor defaults are changed prior to installation, including but not limited to default wireless encryption keys, passwords, and SNMP community strings. 2FA and VPN are required to do so remotely. We have a separate wifi network for guest access at our corporate offices.

All services, protocols, and allowed ports must have a documented business justification and approval, including the use of security features implemented for those protocols considered insecure. Routers and firewalls are configured to limit the IP disclosure to unauthorized or unintended parties and limit inbound internet access to IP addresses within the DMZ Firewall and router rulesets are reviewed at least every six months.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>Our customers own and control all of the data that they collect via our platform. They have full control to edit/delete their data at any time via either UI or API. Deleted data may reside on our backup servers for up to 90 days before being overwritten.

SurveyMonkey does not delete customer data associated with active accounts. If an account has been inactive for a period of three years SurveyMonkey will attempt to contact the account holder. If the account holder does not respond or take action within a reasonable amount of time we will delete the account and associated data.

Our Terms of Use are available here: https://www.surveymonkey.com/mp/legal/terms-of-use/
Our Privacy Policy is available here: https://www.surveymonkey.com/mp/legal/privacy-policy/

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Information from the [Microsoft Cloud App Security](https://www.microsoft.com/en-us/enterprise-mobility-security/cloud-app-security) catalog:

<iframe height='1020' title='Microsoft Cloud App Security Information' src='https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/12024' frameborder='no'  style='width: 100%;'></iframe>

<a href="https://3ca685143b5b46b4b0e5266dadf2e97c.codepen.website/#/dashboard/12024" target="_blank">View in a new tab</a>

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

