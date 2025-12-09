This is a guidance box. Remove all guidance boxes after filling out the template. Items highlighted in turquoise should be edited appropriately. Items highlighted in green are examples and should be removed. After all edits have been made, all highlights should be cleared.

Insert organization logo by clicking on the outlined image.

Cybersecurity Policy for Operational Technology Template

Replace <organization name> with the name of the organization for the entire document. To do so, perform the following:

* Press “Ctrl” + “H” keys simultaneously.
* Enter “<organization name>” in the Find text box.
* Enter your organization's full name in the “Replace” text box.
* Click “More”, and make sure “Match case” is ticked.
* Click “Replace All”.
* Close the dialog box.

|  |  |
| --- | --- |
| Choose Classification | |
| DATE | Click here to add date |
| VERSION | Click here to add text |
| REF | Click here to add text |

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

[Purpose 4](#_Toc119909399)

[Scope 4](#_Toc119909400)

[Policy Statements 4](#_Toc119909401)

[Roles and Responsibilities 11](#_Toc119909402)

[Update and Review 11](#_Toc119909403)

[Compliance 11](#_Toc119909404)

# Purpose

This policy aims to define the cybersecurity requirements related to the <organization name>'s operational technology, including industrial control systems and devices to achieve the main objective of this policy which is minimizing cybersecurity risks resulting from internal and external threats at <organization name> in order to preserve confidentiality, integrity and availability.

The requirements in this policy are aligned with the cybersecurity requirements issued by the National Cybersecurity Authority (NCA) in addition to other related cybersecurity legal and regulatory requirements.

# [Scope](#_نطاق_العمل_وقابلية)

This policy covers all information and technology assets (industrial control devices and systems and operating systems and its components) in <organization name> and applies to all personnel (employees and contractors) in <organization name>.

# Policy Statements

1. **General Requirements**
 1. All approved <organization name> ‘s cybersecurity policies and requirements must be applied to <organization name>’s operational technology and industrial control systems (OT/ICS).
 2. Zones within the ICS environment must be logically or physically segmented according to the zone's appropriate level, and data flow must be isolated between zones so that they are connected through specific choke points.
 3. Strict restrictions and physical and logical segmentation must be implemented when connecting ICS networks to the internal network of the corporate zone and other networks in <organization name>, and access to business critical services on ICS networks from the internal network must be denied and restricted to authorized services.
 4. Strict restrictions and physical and logical segmentation must be implemented when connecting ICS and industrial control networks to external networks by using security control system such as the demilitarized zone (DMZ).
 5. Remote direct access to ICS networks must be prevented, and all connections must be routed to the jump hosts dedicated to such operations, secure, reinforced in the DMZ, and used only when needed while ensuring that Multi-Factor Authentication (MFA) principle and session recording are applied for a specified period of time.
 6. Safety Instrumented Systems (SISs) must be isolated either logically or physically from other ICS networks.
 7. Cybersecurity event logs must be activated on the OT/ICS network environment and related connections, and regularly monitored.
 8. Cybersecurity event logs and audit trails must be activated for all OT/ICS assets.
 9. Failed attempts to access the <organization name>’s monitoring systems must be detected and logged.
 10. Continuous, in-depth cybersecurity log review and monitoring, covering all logs and audit trails must be conducted for all OT/ICS assets.
 11. Monitoring, detecting, and analyzing User Behaviors Analytics (UBA) must be performed.
 12. Upload or download activities of OT/ICS assets including Safety Instrumented Systems (SIS) must be detected.
 13. All remote access sessions must be monitored.
 14. Malicious events must be detected and analyzed.
 15. Logging and monitoring of new alerts when new or unauthorized devices are connected to the OT/ICS networks must be performed.
 16. OT/ICS Threat Intelligence must be used and incorporated to regularly tune and refresh alerts of Security Information.
 17. All access control points between the network security boundaries and external connections must be monitored.
 18. The OT/ICS security configuration must undergo periodic review.
 19. Technical Security Standards for OT/ ICS must be defined, approved, and applied, taking into account the preferences of the manufacturers and developers of these systems in accordance with the Secure Configuration and Hardening Policy adopted in <organization name>.
 20. OT/ICS Vulnerability Management must be performed periodically, and vulnerabilities must be addressed based on their classification and their cybersecurity threats and in line with <organization name>'s Vulnerability Management Policy.
 21. Scope and activities of vulnerability assessments must be defined for OT/ICS environment as part of <organization name>’s formal vulnerability management while ensuring limited or no impact on the production environment.
 22. Remediation of newly discovered critical vulnerabilities presenting significant risks to the OT/ICS environment must be performed in a timely manner.
 23. The cybersecurity requirements for vulnerability management in OT/ICS environment must be reviewed, and their implementation effectiveness is measured and evaluated periodically
 24. OT/ICS Patch Management must be implemented periodically as per <organization name> Patch Management Policy.
 25. The automatic and default configuration of these systems must be reviewed to make sure that their settings do not facilitate third-party access or pre-defined access or pass rights.
 26. Access to OT/ICS locations within <organization name> must be restricted to authorized personnel only, as per the <organization name>’s Identity and Access Management and Physical Security Policy and in line with their operational requirements.
 27. Backup Recovery must be periodically tested, and Backup and Recovery Management cybersecurity requirements must be implemented as per <organization name> Backup and Recovery Management Policy.
 28. OT/ICS related CNI data and information must be identified, classified, protected, and handled based on their classification as per the <organization name> relevant legislations and laws.
 29. Electronic and physical data (at rest and in transit) must be protected at a level consistent with its classification.
 30. Data Leakage Prevention (DLP) mechanisms must be used to protect the classified data and information.
 31. Secure wiping mechanisms for configuration details and stored data from OT/ICS assets prior to decommissioning must be implemented.
 32. Transfer or usage of OT systems’ data in any environment other than production environment must be limited, except after applying strict controls for protecting that data.
 33. Cybersecurity awareness must be provided to <organization name>'s personnel along with the required cybersecurity training, skills, and capabilities.
 34. <organization name> must develop and accurate and up-to-date inventory of their OT/ICS assets.
 35. Automated solution to collect asset inventory information must be utilized.
 36. OT/ICS asset inventory records must be stored securely.
 37. Asset owners for OT/ICS assets must be identified and involved throughout the relevant asset inventory management lifecycle.
 38. Criticality rating for all assets must be assigned, documented, and approved by asset owners.
 39. Clear roles and responsibilities must be defined and assigned to all stakeholders involved in the application of OT/ICS cybersecurity controls at <organization name>.
 40. Cybersecurity requirements must be included in <organization name>'s project management methodology and procedures to protect the confidentiality, integrity, and availability of the operational and technical works of ICS in accordance with the general cybersecurity policy adopted by <organization name> and relevant legal and regulatory requirements.
 41. Cybersecurity levels must not be affected by the application of change requests in the environment containing ICS after analyzing and controlling vulnerabilities.
 42. <organization name> must conduct OT/ICS security awareness campaigns.
 43. Customized training, qualifications, knowledge, and professional skillsets must be provided to all personnel with access to the OT/ICS assets. The <organization name> is encouraged to utilize the reference material provided in the Saudi Cybersecurity Workforce Framework (SCyWF).
 44. Participation in OT/ICS authorized and/or specialized organizations and groups must be encouraged.
 45. OT/ ICS procedures and standards must be developed and approved based on business needs.
 46. Key performance indicators (KPI) must be used to ensure the continuous improvement and effective and efficient use of cybersecurity requirements related to the protection of industrial control systems and devices.
2. **OT Protection**
 1. Advanced and up-to-date antivirus and malware protection solutions for ICS must be implemented and configured according to the related malware protection policy and standards at <organization name>.
 2. ICS networks systems and devices (e.g., proxy servers, firewalls, and data diodes) must be configured to block or restrict unauthorized traffic.
 3. <organization name>'s external storage media and mobile devices (including laptops, mobile configuration devices, network test devices) must not be connected to OT/ICS or their technology components without <organization name>'s prior permission and after considering potential risks.
 4. OT/ICS data confidentiality, integrity, and availability must be ensured in accordance with <organization name> data protection policy, and related legal and regulatory requirements.
 5. Encryption must be used to protect data and information assets in accordance with the encryption policy adopted at <organization name> and related legal and regulatory requirements.
 6. The multi-tier architecture principle must be adopted for OT/ICS web applications.
 7. Threat Intelligence must be used to identify technologies and procedures (TTPs) used by Activity Groups targeting OT/ICS.
 8. Cybersecurity risks to OT/ICS must be assessed periodically in accordance with the <organization name> cybersecurity risk management policy and other related legislations. Such assessments must include the assessment of third-party cybersecurity risks, including OT/ICS manufacturers, and suppliers of ICS products and services.
 9. Cybersecurity risks and their OT/ICS requirements related to <organization name>'s workers must be effectively addressed before, during and upon the termination of their employment, as per the organizational policies or procedures by <organization name> and the relevant legal and regulatory requirements.
 10. Screening/vetting of all personnel (including employees and contractors) who have access or can utilize OT/ICS assets must be conducted prior to granting them access.
3. **Cybersecurity Incident and Threat Management and Disaster Recovery**
 1. Assessment and evaluation of the efficiency of cybersecurity enhancement capabilities for OT/ICS assets at <organization name> must be conducted through penetration tests.
 2. Scope and activities of penetration testing must be defined to ensure the coverage of OT/ICS environment and networks connected to the operational network by qualified team.
 3. Penetration testing must only be conducted with limited or no impact on the production environment, or on an identical separate environment.
 4. Penetration testing for OT/ICS systems must be conducted periodically.
 5. Alternative testing methods (such as passive testing mechanisms) must be defined and implemented to collect relevant information when a potential impact to operational production environment may occur.
 6. Redundancy must be implemented to critical networks, media, and devices in the OT/ICS assets in accordance with the periodic cybersecurity risk assessment.
 7. OT/ICS cybersecurity resilience requirements must be included in the Business Continuity Plan (BCP), including the Business Impact Analysis (BIA), Recovery Time Objective (RTO), and Recovery Point Objective (RPO).
 8. OT/ICS cybersecurity‏ ‏resilience requirements ‏ ‏must be included in the Disaster Recovery Plan (DRP).
 9. A contingency plan must be developed and approved to maintain or restore business operations from known valid backups in the event of cybersecurity incidents and ensure business continuity.
 10. OT/ICS cybersecurity incident response plans and escalation plans must be defined as per <organization name>'s Cybersecurity Incident and Threat Management Policy and other related legislations, and virtual plan exercises must be conducted periodically.
 11. Cybersecurity incident response plans must be integrated and aligned with organizational plans and its procedures.
 12. Formal incident response and root cause analysis for any detected cybersecurity incidents must be conducted.
 13. Sequence of incident response activities necessary to restore normal operations must be defined.
 14. Incident communications plan must be established.
 15. OT/ICS including Safety Instrumented Systems (SIS) recovery procedures must be included in the incident response, system recovery plans, and business continuity plans of <organization name>.
 16. Trainings and skillsets for the organization’s personnel (including employees and contractors) to respond to OT/ICS cybersecurity incidents must be provided.
 17. Cybersecurity incident response capabilities, readiness, and plan must be periodically tested by performing cyber-attack simulations exercises.
 18. Threat Intelligence information must be used to identify Tactics, Techniques, and Procedures (TTPs) of activity groups targeting OT/ICS systems.
 19. OT/ICS cybersecurity incident response plans must be aligned with the approved IT incident response plans, crisis management plans, and business continuity plans at <organization name>.
 20. Activities required to maintain a minimum level of OT/ICS operations must be identified, and systems must be able to operate at an acceptable level of security when an error occurs due to a cybersecurity incident.
 21. Incident analysis and Root Cause Analysis of cybersecurity incidents must be conducted systematically after incident detection.
 22. Incident Communications Plan must be developed when cybersecurity incidents occur.
 23. Owners and response teams must be aware of OT/ICS cybersecurity incident response plans by providing the organization employees with the required skills and training courses.
 24. A disaster recovery plan for OT/ICS must be documented and include the following:
 1. Develop the required response to events of varying durations and severity levels that would activate or deactivate the recovery plan.
 2. Determine the sequence of the cybersecurity incident response activities required to restore normal operations.
 3. Determine the procedures for restarting OT/ICS or operating them in manual mode.
 4. Define the roles and responsibilities of responders and personnel authorized for physical and cyber access to the ICS.
 5. Review processes and procedures for information asset backups and secure storage.
 6. Define complete and up-to-date logical network diagram and current configuration information for all ICS technology components.
 25. Cybersecurity incident response capabilities, readiness level, and approved plan must be tested periodically through Attack Simulation Exercises.

# Roles and Responsibilities

1. **Policy Owner:** <head of cybersecurity function>
2. **Policy Review and Update:** <cybersecurity function>
3. **Policy Implementation and Execution:** <information technology function> and <cybersecurity function>
4. **Policy Compliance Measurement:** <cybersecurity function>

# Update and Review

The <cybersecurity function> must review the policy at least once a year or in case any changes happen to the policy or the regulatory procedures in <organization name> or the relevant regulatory requirements.

# Compliance

1. <head of cybersecurity function> will ensure the compliance of <organization name> with this policy on a regular basis.
2. All personnel of <organization name> must comply with this policy.
3. Any violation of this policy may be subject to disciplinary action according to <organization name>’s procedures.
