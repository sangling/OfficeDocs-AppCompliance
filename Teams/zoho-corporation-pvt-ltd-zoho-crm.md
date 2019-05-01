---
title: Application Information for Zoho CRM by Zoho Corporation Pvt Ltd
ms.author: 
ms.date: 05/01/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for Zoho CRM, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data
---
# Zoho CRM

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: —</p>

* <a href="https://teams.microsoft.com/l/app/003a8a54-9d27-41cd-9c28-aec5875a3497" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104382094" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by Zoho Corporation Pvt Ltd to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | Zoho CRM |
| ID | 003a8a54-9d27-41cd-9c28-aec5875a3497 |
| Capabilities | Bot, Tab, Messaging Extension |
| Partner company name | Zoho Corporation Pvt Ltd |
| Physical address | ZOHO Corporation Pvt. Ltd., 4141 Hacienda Dr,, Pleasanton,CA 94588 |
| Contact information for this app | support@zohocrm.com |
| URL of partner website | <https://www.zoho.com/> |
| URL of Teams application info page | <https://www.zoho.com/crm/help/microsoft-teams-integration.html> |
| URL of Privacy Policy | <https://www.zoho.com/privacy.html> |
| URL of Terms of Use | <https://www.zoho.com/crm/zohocrm-terms.html> |
| Main telephone number | N/A |
| Description of available licensing options, if any | Available licensing option in Zoho CRM is Free,Standard,Professional,Enterprise,Ultimate,CRM Plus . For more information on licensing , please refer the link https://www.zoho.com/crm/zohocrm-pricing.html. |
| Licensing contact | support@zohocrm.com |
| Licensing telephone number | https://www.zoho.com/contactus.html |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by Zoho Corporation Pvt Ltd on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

List any Microsoft Graph permissions this app requires, and for each, whether they are delegate or application permissions, the justification and purpose for this permission (what does the app use this information for?), and whether the app stores any of this information in its databases.

>| **Permission**  | **Delegated/Application** | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:----------------|:--------------------------|:--------------------------|:---------------------------------------------------|
>| offline_access | Delegated | Maintain access to data you have given it access to |  |
>| Files.Read.Selected | Delegated | Read files that the user selects | UserPrincipaName is stored for user indentification |
>| User.Read | Delegated | Sign in and read user profile |  |
>| User.ReadBasic.All | Delegated | Read all users&#x27; basic profiles |  |
>| Calendars.ReadWrite | Delegated | Have full access to user calendars | Calendar Folder Id is stored to sync the contacts from Zoho CRM to Microsoft &amp; vice-versa |
>| Contacts.ReadWrite | Delegated | Have full access to user contacts | Contacts Folder Id is stored to sync the contacts from Zoho CRM to Microsoft &amp; vice-versa |
>| Files.Read.All | Delegated | Read all files that user can access |  |
>| email | Delegated | View users&#x27; email address | UserPrincipaName is stored for user indentification |
>| profile | Delegated | View users&#x27; basic profile |  |
>| Files.Read | Delegated | Read user Files |  |

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

>Customer can select the data that needs to be encrypted via EAR (Encryption At Rest)with certaat restrictions.Passwords will be hashed by default. Logical access to the servers is provided through an isolated & dedicated network and is highly secured and monitored. This network is protected with Firewall, 2- Factor Authentication and Kerberos Authentication Protocol. The accessing machines are securely hardened so that no data can be copied or transferred from the data center. Physical Access to the data centers are protected with Biometric+PIN. No visitors are allowed inside the dedicated cages of Zoho in the data centers. Only a very restricted number of employees have the access to the servers to carry out any emergency works.

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>Audit logs are available for all create, update delete operations to the customer�s administrators. Regarding deletion and retention, please refer to the respective sections in our privacy policy.

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end


