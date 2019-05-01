---
title: Application Information for Zoho Sign by Zoho Corporation Pvt Ltd
ms.author: 
ms.date: 05/01/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for Zoho Sign, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data
---
# Zoho Sign

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: —</p>

* <a href="https://teams.microsoft.com/l/app/7a22873b-81e6-48ed-aee3-6f0e7dd5a104" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104382011" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by Zoho Corporation Pvt Ltd to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | Zoho Sign |
| ID | 7a22873b-81e6-48ed-aee3-6f0e7dd5a104 |
| Capabilities | Tab |
| Partner company name | Zoho Corporation Pvt Ltd |
| Physical address | ZOHO Corporation Pvt. Ltd., 4141 Hacienda Dr,, Pleasanton,CA 94588 |
| Contact information for this app | support@zohosign.com |
| URL of partner website | <https://zoho.com> |
| URL of Teams application info page | <https://www.zoho.com/sign/help/teams-extension.html> |
| URL of Privacy Policy | <https://www.zoho.com/privacy.html> |
| URL of Terms of Use | <https://www.zoho.com/terms.html> |
| Main telephone number | N/A |
| Description of available licensing options, if any | Zoho Sign users who have an account with Zoho Sign can access the app in Teams, irrespective of their license. They will have access to the features in ZohoSign which corresponds to their license. |
| Licensing contact | support@zohosign.com |
| Licensing telephone number | 1 877 834 4428 |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by Zoho Corporation Pvt Ltd on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

List any Microsoft Graph permissions this app requires, and for each, whether they are delegate or application permissions, the justification and purpose for this permission (what does the app use this information for?), and whether the app stores any of this information in its databases.

>| **Permission**  | **Delegated/Application** | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:----------------|:--------------------------|:--------------------------|:---------------------------------------------------|
>| Contacts.ReadWrite.Shared | Delegated | Read and write user and shared contacts |  |
>| Contacts.ReadWrite | Delegated | Have full access to user contacts |  |
>| Files.ReadWrite | Delegated | Have full access to user files |  |
>| Files.ReadWrite.All | Delegated | Have full access to all files user can access |  |
>| Files.ReadWrite.Selected | Delegated | Read and write files that the user selects |  |
>| User.ReadBasic.All | Delegated | Read all user&#x27;s basic profiles |  |
>| email | Delegated | View user&#x27;s email address |  |
>| offline_access | Delegated | Maintain access to data you have given it access to |  |
>| profile | Delegated | View user&#x27;basic profile |  |

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Do this app make use of this capability?


>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>|  |  |  |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>We don&#x27;t collect EUII / PII in telemetry and logs. We have scripts in place to look for and alert for fixing any such data being visible.

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>All the customer data is encrypted at rest. Logical access to the servers is provided through an isolated & dedicated network and is highly secured and monitored. This network is protected with Firewall, 2- Factor Authentication and Kerberos Authentication Protocol. The accessing machines are securely hardened so that no data can be copied or transferred from the data center. Physical Access to the data centers are protected with Biometric+PIN. No visitors are allowed inside the dedicated cages of Zoho in the data centers. Only a very restricted number of employees have the access to the servers to carry out any emergency works.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>Customers as the data controller have access to the data all the time. Admins can add or remove users from Zoho Sign. They will be able to view all information stored in the application, including complete audit trails, reports of usage. They can delete data and users, transfer control of data between users.

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end


