---
title: Application Information for LawToolBox by LawToolBox.com,Inc.
ms.author: 
ms.date: 05/01/2019
ms.topic: article
ms.service: msteams
ms.collection: Teams_ITAdmin_PracticalGuidance
description: All available security and compliance information information for LawToolBox, its data handling policies, its Microsoft Cloud App Security app catalog information, and security/compliance information in the CSA STAR registry.
localization_priority: Normal
MS.collection: Teams_ITAdmin_PracticalGuidance
appliesto:
- Microsoft Teams
zone_pivot_groups: app-info-data
---
# LawToolBox

<p></p><img alt="Self-attestation logo" src="./images/attested.png" width="650"/>
<p>Last updated by the developer on: —</p>

* <a href="https://teams.microsoft.com/l/app/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d" target="_blank">View in Teams store</a>
* <a href="https://appsource.microsoft.com/en-us/product/office/WA104381656" target="_blank">View in AppSource</a>

::: zone pivot="general"

### General information

Information provided by LawToolBox.com,Inc. to Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| App name | LawToolBox |
| ID | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
| Capabilities | Bot, Tab, Messaging Extension |
| Partner company name | LawToolBox.com,Inc. |
| URL of partner website | <https://www.lawtoolbox.com> |
| URL of Teams application info page | <https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid&#x3D;718> |
| URL of Privacy Policy | <https://www.lawtoolbox.com/privacy-policy/> |
| URL of Terms of Use | <https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid&#x3D;661> |

 [!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### How the app handles data

Information provided by LawToolBox.com,Inc. on how this app collects and stores organizational data, and what control an organization has over this data.

#### Data access using Microsoft Graph

List any [Microsoft Graph permissions](https://docs.microsoft.com/en-us/graph/permissions-reference) this app requires, and for each, whether they are delegate or application permissions, the justification and purpose for this permission (what does the app use this information for?), and whether the app stores any of this information in its databases.

>| **Permission**  | **Delegated/Application** | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:----------------|:--------------------------|:--------------------------|:---------------------------------------------------|
>| Calendars.Read | Delegated | [Optional] Read user&#x27;s calendar  |  |
>| Calendars.ReadWrite | Delegated | To create calendar invite in to user&#x27;s calendar |  |
>| Calendars.ReadWrite.Shared | Delegated | To create calendar invite in to shared calendar |  |
>| Contacts.ReadWrite | Delegated | [Optional]- to read user Contacts and connect users from contact list to group |  |
>| Contacts.ReadWrite.Shared | Delegated | [Optional]- to read users shared contacts to serve the list of contacts relevant to the case |  |
>| Files.Read | Delegated | [Optional]-Read user&#x27;s OneDrive |  |
>| Files.Read.All | Delegated | [Optional]-Read user&#x27;s OneDrive |  |
>| Files.ReadWrite | Delegated | [Optional]-Read and modify files in a user&#x27;s OneDrive |  |
>| Files.ReadWrite.All | Delegated | [Optional]-Read/write user&#x27;s OneDrive file associated with the Matter |  |
>| Group.ReadWrite.All | Delegated | We create a Group for each matter created in our system. This help user stores matter-related information into the Group, which in turn saves their data into their own tenant. | GroupID, GroupName, GroupEmail |
>| Mail.Read | Delegated | [Optional]-[InProgress]Read users email for Matters |  |
>| Mail.ReadWrite | Delegated | [Optional]-[InProgress] Read/Write Email for users |  |
>| Mail.ReadWrite.Shared | Delegated | [Optional]-[InProgress] Read/Write Email for users |  |
>| Mail.Send | Delegated | [Optional]-[InProgress]Send Deadlines on email as user |  |
>| Directory.AccessAsUser.All | Delegated | [Optional]-to read Groups and Users information as a user |  |
>| Directory.ReadWrite.All | Delegated | [Optional]-to read Groups and Users information as a user |  |
>| Files.Read | Delegated | Read user&#x27;s Files |  |
>| Files.ReadWrite | Delegated | [Optional]-[InProgress]Read/Write user&#x27;s file |  |
>| Tasks.ReadWrite.Shared | Delegated | [Optional]-[InProgress]Read Write Deadlines as Task for users |  |
>| User.Read  | Delegated | Read user&#x27;s Information |  |
>| User.ReadWrite | Delegated | Read/Write user&#x27;s Information |  |
>| User.ReadWrite.All | Delegated | Read/Write user&#x27;s Information |  |
>| profile | Delegated | Read user profile information |  |
>| email | Delegated | Read user&#x27;s email address | email, Office365 UserID, ObjectID, TenantID |

#### Data access via bots

If this app contains a bot or a messaging extension, it can access the roster (first name, last name, display name, email address) of any team member in a team or chat it's added to. Do this app make use of this capability?


>| **Access team/chat roster?**  | **Justification/Purpose** | **Is any of this data stored in app database(s)?** |
>|:--------------------------------|:---------------------|:--------------------------|
>|  |  |  |

#### Telemetry data

Does any organizational information, including EUII (end-user identifiable information) and OII (organizational identifiable information), appears in this application's telemetry/logs? If yes, describe what data is present and what controls/processes an organization has in place to archive and/or delete it. If no, describe the controls/processes in place to prevent EUII and OII from appearing in telemetry/logs.

>

#### Storing and securing organizational data

Describe where/how is this application's data is stored and how access to it is controlled. Is it encrypted? Who can access it? How do you ensure that only authorized systems/individuals can access it? Examples: 2FA for all admins, Privileged Access Management (PMA), partitioning service admin accounts from Azure AD/corporate user accounts, protected IP ranges between systems, etc.

>

#### Organizational controls for data stored by partner

Describe any capabilities an organization's administrators have to control their information residing in partner systems, e.g. deletion, retention, auditing, archiving, end-user policy, etc.

>

[!INCLUDE [Corrections or suggestions contact information](./includes/corrections-or-suggestions.md)]

::: zone-end


