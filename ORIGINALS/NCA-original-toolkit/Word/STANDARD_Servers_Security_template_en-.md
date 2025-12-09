This is a guidance box. Remove all guidance boxes after filling out the template. Items highlighted in turquoise should be edited appropriately. Items highlighted in green are examples and should be removed. After all edits have been made, all highlights should be cleared.

Insert organization logo by clicking on the placeholder to the left.

Server Security Standard Template

Replace <organization name> with the name of the organization for the entire document. To do so, perform the following:

* Press “Ctrl” + “H” keys simultaneously.
* Enter “<organization name>” in the Find text box.
* Enter your organization’s full name in the “Replace” text box.
* Click “More”, and make sure “Match case” is ticked.
* Click “Replace All”.
* Close the dialog box.

|  |  |  |
| --- | --- | --- |
| Choose Classification | |  |
| DATE | Click here to add date |  |
| VERSION | Click here to add text |  |
| REF | Click here to add text |  |

Disclaimer

This template has been developed by the National Cybersecurity Authority (NCA) as an illustrative example that can be used by organizations as a reference and guide. This template must be customized and aligned with the <organization name>’s business and relevant legislative and regulatory requirements. This template must be approved by the head of the organization (Authorizing official) or his/her delegate. The NCA is not responsible for any use of this template as is, and it affirms that this template is solely an illustrative example.

Document Approval

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| Signature | Date | Name | Job Title | Role |
| <Insert signature> | Click here to add date | <Insert individual’s full personnel name> | <Insert job title> | Choose Role |
|  |  |  |  |  |

Version Control

|  |  |  |  |
| --- | --- | --- | --- |
| Version Details | Updated By | Date | Version |
| <Insert description of the version> | <Insert individual’s full personnel name> | Click here to add date | <Insert version number> |
|  |  |  |  |

Review Table

|  |  |  |
| --- | --- | --- |
| Upcoming Review Date | Last Review Date | Periodical Review Rate |
| Click here to add date | Click here to add date | <Once a year> |
|  |  |  |

Table of Contents

[Purpose 4](#_Toc111036623)

[Scope 4](#_Toc111036624)

[Standards 4](#_Toc111036625)

[Roles and Responsibilities 9](#_Toc111036626)

[Update and Review 9](#_Toc111036627)

[Compliance 9](#_Toc111036628)

# [Purpose](#_Purpose" \o "This section clarifies the importance and reasons for the development and adoption of this standard. This section also describes the standard's relationship with the requirements of NCA ECC, and organizational, legal, and regulatory requirements)

This standard aims to define the detailed cybersecurity requirements related to the management and protection of <organization's name>'s servers in order to minimize cybersecurity risks resulting from internal and external threats.

The requirements in this standard are aligned with the Server Security Policy and the cybersecurity requirements issued by the National Cybersecurity Authority (NCA) in addition to other related cybersecurity legal and regulatory requirements.

# [Scope](#_Scope" \o "This section of the standard template aims to identify the assets, parties and persons to which this standard applies)

This standard covers all <organization name>’s information and technology assets (including servers) and applies to all personnel (employees and contractors) in <organization name>.

# Standards

|  |  |
| --- | --- |
| 1 | Secure Access |
| Objective | To ensure the protection of servers and their functions against unauthorized access. |
| Risk Implication | Unauthorized access to servers exposes <organization name> to severe risks that can lead to data leakage or theft, service interruption, or security compromises that attackers can use to carry out further cybersecurity attacks against <organization name> and its infrastructure. |
| Requirements | |
|  | Access on servers must be restricted to server administrators by only allowing access to administrators’ individual accounts and workstation IPs using network Access Control Lists (ACLs). |
|  | Default/non-interactive/unneeded accounts must be disabled or renamed. |
|  | Session timeout and session idle lockout must be configured in accordance with the <organization name>’s approved identity and access management standard. |
|  | BIOS bootloader passwords must be configured. |
|  | Access to critical servers must be restricted by administrators and operators to be provided through Privileged Access Workstations (PAW) only, and all administrative access must be encrypted. |
|  | Access to servers must be restricted by administrators and operators and must only be provided through a jump server or PAM.   * + 1. A separate jump server must be used for system administrators and users. 2. The use of Multi-Factor authentication must be required for the access of jump servers used by system administrators by implementing ACLs. 3. Access to jump servers must be restricted to the accounts of authorized administrators and operators only. 4. Network access must be restricted to jump servers by implementing ACLs. 5. Jump servers must be placed in the network management zone. 6. Internet access on jump servers must be disabled. 7. Unnecessary and risky services (such as sending and receiving emails) must be disabled on jump servers. 8. All levels of logging, as well as audit trail and security logs, must be enabled locally and to a centralized event logging system. |

|  |  |
| --- | --- |
| 2 | Server Protection |
| Objective | To ensure the protection of servers against viruses, malware, Advanced Persistent Threats (APTs), Zero-Day attacks, and any other types of malicious attacks. |
| Risk Implication | Successful malicious attacks on servers can expose <organization name> to a security breach, unauthorized access, or data disclosure if servers are left unprotected. |
| Requirements | |
|  | OS and application functionality lockout must be configured with the least privilege required to operate in normal conditions. For example, changing system time manually, shutting down/restarting, editing system files, creating/modifying/deleting files, etc., must be disabled. |
|  | Application whitelisting must be enabled on servers to allow only specific applications and software to run based on need. |
|  | Application whitelisting agents must be configured so that users cannot disable the agents with the exception of administrators when performing specific administrative tasks that would require disabling application whitelisting temporarily. |
|  | A list of approved executables (exe, com, pif, etc.), software libraries (dll, ocx, etc.), scripts (ps1, bat, vbs, etc.), and installers (msi, msp, etc.) must be defined and approved to be executed by certain users as per the needs. |
|  | Application whitelisting must be implemented to use cryptographic hash rules, publisher certificate rules or path rules to allow or restrict the use of applications. |
|  | Application folders must be configured with file system permissions to prevent unauthorized modification of folder and file permissions. |
|  | Exploit protection functionality must be enabled on servers with both operating system mitigation measures and application-specific mitigation measures. |
|  | Endpoint Detection and Response (EDR), Host-based Intrusion Detection System (HIDS) and Host-based Intrusion Prevention System (HIPS) must be implemented on all servers. |
|  | Software host firewall must be implemented on all servers. |
|  | Antivirus must be implemented on all servers. |
|  | End-point protection must be implemented on all servers. |
|  | Advanced Persistent Threat agents must be implemented on all servers. |
|  | End-point device control software must be implemented on all servers to prevent the use of unauthorized devices. |
|  | Data Leakage Prevention (DLP) must be implemented where required in accordance with <organization name>’s approved Data Leakage Prevention standard. |
|  | All requirements under <organization name>’s Malware Protection Policy must be implemented. |

|  |  |
| --- | --- |
| 3 | Central Management |
| Objective | To define security requirements for central management to ensure that servers are managed and operated securely and that all security requirements are implemented and enforced. |
| Risk implication | The lack of secure management and the non-implementation of security requirements on servers increases the probability of exposure to attacks and the existence of vulnerabilities and weaknesses in‏ <organization name>’s environment. Exploiting such vulnerabilities in malicious attacks or breaches can compromise the security of <organization name> 's ‏servers and data. ‏ |
| Requirements | |
|  | Central management server or domain server must be configured to enforce <organization name>‘s Configuration and Hardening policies on all servers. |
|  | System configuration management tools that automatically enforce and redeploy configuration settings to systems at regularly scheduled intervals must be deployed. |
|  | Configuration monitoring system compliant with Security Content Automation Protocol (SCAP) must be implemented to verify all security configuration elements, catalog approved exceptions, and alert when unauthorized changes occur. |
| 4 | Other Standards |
| Objective | To implement all server security standards and requirements to ensure the highest protection levels. |
| Risk implication | Failure to‏ implement all security standards and requirements exposes ‏ <organization name> to increased server security risks. |
| Requirements | |
|  | The following standards must be implemented:   1. Virtualization security standard 2. Disaster recovery and backup standard 3. Cryptography standard 4. Cybersecurity event and monitoring management standard 5. Physical security standard 6. Secure configuration and hardening standard |

# [Roles and Responsibilities](#_Roles_and_Responsibilities)

1. **Standard Owner:** <head of the cybersecurity function>
2. **Standard Review and Update:** <cybersecurity function>
3. **Standard Implementation and Execution:** <information technology organization>
4. **Standard Compliance Measurement:** <cybersecurity function>

# [Update](#_الالتزام_بالسياسة) and Review

<cybersecurity function> must review the standard at least once a year or in case any changes happen to the policy or the regulatory procedures in <organization name> or the relevant regulatory requirements.

# [Compliance](#_Compliance" \o "This section aims to identify the requirements for compliance with this standard and the consequences of incompliance)

1. The <head of the cybersecurity function> will ensure compliance of <organization name> with this standard on a regular basis.
2. All employees at <organization name> must comply with this standard.
3. Any violation of this standard may be subject to disciplinary action according to <organization name>’s procedures.
