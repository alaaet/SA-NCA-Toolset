دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

(ECC – 2: 2024)



Document Classification: Public

Disclaimer: Please refer to the National Cybersecurity Authority’s website (https://nca.gov.sa),
to obtain the latest version of this document.

 دوﺪحﻣ

 ﺪﻴﻘﻣ

 دوﺪحﻣ

 ﺪﻴﻘﻣ

In the Name of Allah,
 The Most Gracious,
 The Most Merciful

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Disclaimer: The following controls will be governed by and
implemented in accordance with the laws of the Kingdom of Saudi
Arabia, and must be subject to the exclusive jurisdiction of the
courts of the Kingdom of Saudi Arabia. Therefore, the Arabic
version will be the binding language for all matters relating to the
meaning or interoperation of this document.

Document classification: Public



1

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

Traffic Light Protocol (TLP):

This marking protocol is widely used around the world to share sensitive data. It has four
colors (traffic lights):

Red – Personal and Confidential to the Recipient Only

The recipient has no rights to share information classified in red with any person
outside the defined range of recipients, either inside or outside the entity.

Amber – Restricted Sharing

The recipient may share information marked in amber with the concerned personnel
only within the same entity, and with those required to take action with regard to the
information.

Green – Sharing within the Same Community

The recipient may share information marked in green with other recipients inside the
same entity or with others in a related entity or in an entity within the same sector.
However, sharing or publishing this information on public platforms is not permitted.

White – No Restrictions

Document classification: Public



2

Essential Cybersecurity Controls

Update and Review

 دوﺪحﻣ

 ﺪﻴﻘﻣ

NCA will periodically review and update the ECC as per the cybersecurity requirements and
related industry updates. NCA will communicate and publish the updated version of ECC for
implementation and compliance. NCA has updated the previous version of the ECC
(i.e., ECC-1:2018).

Version

ECC – 1
ECC – 2

Year of Issuance

Updates

2018
2024

Appendix (C) illustrates the updates on the previous version

Document classification: Public



3

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

Table of Contents

Update and Review ................................................................................................................................... 3

Introduction ................................................................................................................................................ 7

Objectives ................................................................................................................................................... 8

Scope of Work and Applicability ............................................................................................................. 9

ECC Scope of Work ................................................................................................................................... 9

ECC Statement of Applicability ............................................................................................................... 9

Implementation and Compliance ........................................................................................................... 9

Assessment and Compliance Tool ......................................................................................................... 9

ECC Domains and Structure .................................................................................................................. 10

Main Domains .......................................................................................................................................... 10

Subdomains ............................................................................................................................................. 11

Structure .................................................................................................................................................. 12

The Essential Cybersecurity Controls (ECC) ....................................................................................... 13

Details of the Essential Cybersecurity Controls (ECC) ...................................................................... 13

Cybersecurity Governance .................................................................................................................... 13

Cybersecurity Defense ........................................................................................................................... 19

Cybersecurity Resilience ....................................................................................................................... 29

Third-Party and Cloud Computing Cybersecurity .............................................................................. 30

Appendices ............................................................................................................................................... 32

Appendix (A): Terms and Definitions ................................................................................................... 32

Appendix (B): List of the Abbreviations ............................................................................................... 41

Appendix (C): List of Updates ................................................................................................................ 42

Document classification: Public



4

Essential Cybersecurity Controls

List of Tables

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Table 1 Document Versions .................................................................................................................. 13

Table 2: ECC Structure .......................................................................................................................... 16

table 3 Terms and Definition ................................................................................................................ 53

Table 4 List of Abbreviations ................................................................................................................ 54

List of Figures

Figure 1: Main Domains of ECC ............................................................................................................ 14

Figure 2: ECC Subdomains ................................................................................................................... 15

Figure 3: Controls Coding scheme ...................................................................................................... 16

Figure 4: ECC Structure ........................................................................................................................ 16

Document classification: Public



5

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

Executive Summary

The Kingdom of Saudi Arabia’s Vision 2030 aims for a comprehensive improvement of the
nation and its security, economy, and citizens’ well-being and decent life. Naturally, one of the
essential goals of Vision 2030 is the transformation towards digitalization and the improvement
of digital infrastructure, in order to keep up with the accelerated global progress in digital
services, renewable global networks, IT systems, and OT systems, align with growing computer
processing and massive data storage and exchange capabilities, and be prepared for handling
artificial intelligence and the fourth 4th industrial revolution transformations.

This transformation requires streamlining the flow of information, securing it, and
preserving the integration of all systems. It also requires maintaining and supporting the
cybersecurity of the Kingdom, in order to protect the State’s vital interests, national security,
critical infrastructures, high priority sectors, and governmental services and activities. To this
end, the National Cybersecurity Authority (NCA) was established, and the NCA’s Statute was
approved by Royal Order No. 6801, dated 11/02/1439H., making the NCA the national and
specialized cybersecurity reference in the Kingdom.

NCA’s powers and duties fulfill the strategic cybersecurity needs and the need to develop
cybersecurity policies, governance mechanisms, frameworks, standards, controls, and guidelines,
and disseminate them across entities.

NCA’s powers and duties also fulfil the needs of updating and continuously monitoring the
compliance of government agencies and non-government entities, as the role and significance of
cybersecurity have significantly increased more than ever with the rise of security risks in the
cyberspace.

NCA’s Statute states that no public agency, private entity, or any other entity shall be relieved
from their responsibility towards their own cybersecurity, as confirmed by High Order No.
57231, dated 10/11/1439H., which states that “all government agencies must raise the level of
their cybersecurity to protect their electronic networks, systems and data, and to abide by the
NCA’s policies, frameworks, standards, controls, and guidelines in this regard”.

From this perspective, the NCA has developed the Essential Cybersecurity Controls (ECC-1:
2018) to set the minimum cybersecurity requirements for national entities falling within the ECC
scope of work. This document outlines the details, goals, scope of work, applicability, and
compliance and monitoring mechanism of the ECC.

All national entities shall take the necessary measures to ensure ongoing and continuous
compliance with the ECC, as per Article 10(3) of the NCA’s Statute and High Order No. 57231,
dated 10/11/1439H.

Document classification: Public



6

Essential Cybersecurity Controls

Introduction

 دوﺪحﻣ

 ﺪﻴﻘﻣ

The National Cybersecurity Authority (Hereinafter referred to as the “NCA”) developed the
Essential Cybersecurity Controls (ECC–1:2018) after conducting a study on multiple
cybersecurity standards, frameworks, and controls that have previously been developed by
(national and international) entities and organizations, considering the requirements of relevant
national legislations, regulations, and decisions, as well as reviewing and leveraging cybersecurity
best practices, analyzing previous cybersecurity incidents and attacks against government
agencies and other critical entities, and surveying and considering opinions of multiple national
entities.
The Essential Cybersecurity Controls consist of the following:

 4 Cybersecurity Main Domains.
 28 Cybersecurity Subdomains.
 108 Cybersecurity Main Controls.
 92 Cybersecurity Subcontrols.

Moreover, these Controls are linked to relevant national and international legislative and
regulatory requirements.

Document classification: Public



7

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

Objectives

These Controls aim to provide the minimum cybersecurity requirements based on the best
practices and standards to minimize the internal and external cybersecurity threats against the
entities’ information and technology assets. The protection of the entity’s information and
technology assets requires focusing on the key protection goals, which are as follows:







Confidentiality

Integrity

Availability

These Controls take into account the following four main cybersecurity pillars:

 Strategy
 People
 Process
 Technology

Document classification: Public



8

Essential Cybersecurity Controls

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Scope of Work and Applicability

ECC Scope of Work

These Controls are applicable to government agencies in the Kingdom of Saudi Arabia
(including ministries, authorities, establishments and others) and their affiliated companies and
entities (inside and outside the kingdom), as well as all private sector entities owning, operating,
or hosting Critical National Infrastructures (CNIs) (Hereinafter referred to collectively as the
"entity"). The NCA strongly encourages all other entities in the Kingdom to leverage these
Controls to implement best practices to improve and enhance their cybersecurity.

ECC Statement of Applicability

These Controls have been developed to fulfill the cybersecurity needs of all entities and
sectors in the Kingdom, taking into account the diverse nature of their businesses. Each entity
shall comply with all controls applicable thereto.

Here are some examples of controls the applicability of which varies from one entity to

another based on the entity’s business and use of certain technologies:

 Controls under the Subdomain (4-2) relating to Cloud Computing and Hosting
Cybersecurity are applicable and binding on entities currently using or planning to use
cloud computing and hosting services.

Implementation and Compliance

As per Article 10(3) of the NCA's Statute and High Order No. 57231, dated 10/11/1439H.,
all entities within the scope of these Controls shall take all necessary measures to ensure ongoing
and continuous compliance with these Controls.

The NCA shall evaluate the entities’ compliance with the ECC through multiple means,
such as self-assessment by the entities, periodic reports of the compliance tool, and/or field
auditing visits, in accordance with the mechanism deemed appropriate by the NCA.

Assessment and Compliance Tool

The NCA will issue a tool (ECC-2:2024 Assessment and Compliance Tool) to organize the

process of assessment and measurement of compliance by entities in applying the ECC.

Document classification: Public



9

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

ECC Domains and Structure

Main Domains

Figure (1) below shows the main domains of the ECC.

FIGURE 1: MAIN DOMAINS OF ECC

Document classification: Public



10

Essential Cybersecurity Controls

Subdomains

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Figure (2) below shows the ECC subdomains

1. Cybersecurity
Governance

2- Cybersecurity
Defense

3- Cybersecurity
Resilience

4- Third-Party and
Cloud Computing
Cybersecurity

1-1

1-3

1-5

1-7

1-9

2-1

2-3

2-5

2-7

2-9

Cybersecurity Strategy

Cybersecurity Policies and
Procedures

Cybersecurity Risk
Management

Compliance with
Cybersecurity Standards,
Laws and Regulations

1-2

1-4

1-6

1-8

Cybersecurity Management

Cybersecurity Roles and
Responsibilities

Cybersecurity in Information and
Technology Project Management

Periodical Cybersecurity Review
and Audit

Cybersecurity in Human
Resources

1-10

Cybersecurity Awareness and
Training Program

Asset Management

2-2

Identity and Access Management

Information Systems and
Information Processing
Facilities Protection

Network Security
Management

Data and Information
Protection

Backup and Recovery
Management

2-4

2-6

2-8

Email Protection

Mobile Devices Security

Cryptography

2-10

Vulnerability Management

2-11

Penetration Testing

2-12

Cybersecurity Event Logs and
Monitoring Management

2-13

2-15

3-1

Cybersecurity Incident
and Threat Management

2-14

Physical Security

Web Application Security

Cybersecurity Resilience Aspects of Business Continuity Management
(BCM)

4-1

Third-Party Cybersecurity

4-2

Cloud Computing and Hosting
Cybersecurity

FIGURE 2: ECC SUBDOMAIN

11

Document classification: Public



 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

Structure

Figures (3) and (4) below show the meaning of controls codes.

ECC

2

2024

Essential Cybersecurity Controls

Version No.

Year of Issuance

FIGURE 3: CONTROLS CODING SCHEME

2

3

2

6

Sub-Control No.

Main Control No.

Subdomain No.

Main domain No.

Table (1) below shows the ECC methodological structure.

FIGURE 4: ECC STRUCTURE

TABLE 1: ECC STRUCTURE

Reference Number of Main Domain

Reference Number of Subdomain

Name of Subdomain

Name of Main Domain

Objective

Controls

Control Reference Number

Control Clauses

Document classification: Public



12

Essential Cybersecurity Controls

 دوﺪحﻣ

 ﺪﻴﻘﻣ

The Essential Cybersecurity Controls (ECC)

Details of the Essential Cybersecurity Controls (ECC)

1

1-1

Objective

Controls

1-1-1

1-1-2

1-1-3

1-2

Objective

Controls

1-2-1

1-2-2

1-2-3

Cybersecurity Governance

Cybersecurity Strategy
To ensure that the action plans, objectives, initiatives, and projects of the entity
contribute to compliance with the relevant legislative and regulatory requirements.

The cybersecurity strategy of the entity shall be identified, documented, and approved,
and it shall be supported by the head of the entity or his/her delegate (Hereinafter
referred to as the “Authorized Official”). The strategy goals shall be in line with the
relevant legislative and regulatory requirements.
The entity shall execute an action plan to apply the cybersecurity strategy.
The cybersecurity strategy shall be reviewed at planned intervals (or in case of changes
to the relevant legislative and regulatory requirements).
Cybersecurity Management
To ensure that the Authorized Official of the entity complies with and supports the
implementation and management of cybersecurity programs within the entity, as per
the relevant legislative and regulatory requirements.

A department for cybersecurity shall be established within the entity. This department
shall be independent from the Information Technology and Communications
Department (As per High Order No. 37140, dated 14/08/1438H.). It is recommended
that the Cybersecurity Department reports directly to the head of the entity or his/her
delegate while ensuring that this does not result in a conflict of interests.
All cybersecurity positions shall be filled out with full-time and qualified Saudi
cybersecurity professionals.
A cybersecurity supervisory committee shall be established pursuant to the instruction
of the entity’s Authorized Official to ensure compliance with, support for, and
monitoring of the implementation of the cybersecurity programs and regulations. The
committee’s members, responsibilities, and governance framework shall be identified,
documented, and approved. The committee shall include the head of the cybersecurity

13

Document classification: Public



 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

department as a member. It is recommended that the committee reports directly to the
head of the entity or his/her delegate while ensuring that this does not result in a
conflict of interests.
Cybersecurity Policies and Procedures
To ensure that the cybersecurity requirements and the entity’s compliance therewith
are documented and communicated, as per the entity’s regulatory requirements and
the relevant legislative and regulatory requirements.

The cybersecurity department of the entity shall identify and document cybersecurity
policies and procedures, including the cybersecurity controls and requirements, and
have them approved by the entity’s Authorized Official, and communicate them to the
relevant personnel and parties inside the entity.
The cybersecurity department shall ensure that the cybersecurity policies and
procedures, including the relevant controls and requirements, are implemented at the
entity.
The cybersecurity policies and procedures shall be supported by technical security
standards (e.g. technical security standards for firewall, databases, operating systems,
etc.).
The cybersecurity policies and procedures shall be reviewed and updated at planned
intervals (or in case of changes to the relevant legislative and regulatory requirements
and standards). Changes shall be documented and approved.
Cybersecurity Roles and Responsibilities
To ensure that roles and responsibilities are clearly defined for all parties participating
in implementing the cybersecurity controls within the entity.

The Authorized Official shall identify, document, and approve the governance
organizational structure, roles, and responsibilities of the entity’s cybersecurity, and
assign the persons concerned therewith. The necessary support shall be provided for
the implementation thereof while ensuring that this does not result in a conflict of
interests.
The cybersecurity roles and responsibilities within the entity shall be reviewed and
updated at planned intervals (or in case of changes to the relevant legislative and
regulatory requirements).

1-3

Objective

Controls

1-3-1

1-3-2

1-3-3

1-3-4

1-4

Objective

Controls

1-4-1

1-4-2

Document classification: Public



14

Essential Cybersecurity Controls

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Cybersecurity Risk Management

1-5
Objective To ensure managing cybersecurity risks in a methodological approach, in order to
protect the entity’s information and technology assets, as per the entity’s regulatory
policies and procedures and the relevant legislative and regulatory requirements.

Controls
1-5-1

1-5-2

1-5-3

1-5-4

1-6

Objective

Controls

1-6-1

The cybersecurity department of the entity shall identify, document, and approve the
cybersecurity risk management methodology and procedures within the entity, in
accordance with considerations of confidentiality, and the integrity and availability of
information and technology assets.
The cybersecurity department shall implement the cybersecurity risk management
methodology and procedures within the entity.
The cybersecurity risk assessment procedures shall be implemented at least in the
following cases:
1.5.3.1 At early stage of technology projects.
1.5.3.2 Before making major changes to technology infrastructure.
1.5.3.3 During planning to obtain third party services.
1.5.3.4 During planning and before the release of new technology services and products.
The cybersecurity risk management methodology and procedures shall be reviewed and
updated at planned intervals (or in case of changes to the relevant legislative and
regulatory requirements and standards). Changes shall be documented and approved.
Cybersecurity in Information and Technology Project Management
To ensure that cybersecurity requirements are included in the methodology and
procedures of the entity’s project management, in order to protect the confidentiality,
integrity, accuracy, and availability of the entity’s information and technology assets,
as per the entity’s regulatory policies and procedures and the relevant legislative and
regulatory requirements.

Cybersecurity requirements shall be included in the project management methodology
and procedures and in the information and technology asset change management
within the entity to ensure identifying and managing cybersecurity risks as part of the
technology project lifecycle. The cybersecurity requirements shall be a key part of the
requirements for technology projects.

Document classification: Public



15

1-6-2

1-6-3

1-6-4

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

The cybersecurity requirements for project management and information and
technology asset changes within the entity shall include the following as a minimum:
1.6.2.1 Vulnerability assessment and remediation.
1.6.2.2 Reviewing secure configuration and hardening and updates packages before
launching projects and changes.

The cybersecurity requirements for software and application development projects
within the entity shall include the following as a minimum:
1.6.3.1 Using the secure coding standards.
1.6.3.2 Using trusted and licensed sources for software development tools and libraries.
1.6.3.3 Conducting compliance test for software against the cybersecurity requirements
within the entity.
1.6.3.4 Secure integration between applications.
1.6.3.5 Reviewing secure configuration and hardening and updates packages before
launching software products
The cybersecurity requirements for project management within the entity shall be
periodically reviewed.
Compliance with Cybersecurity Standards, Laws and Regulations

1.7
Objective To ensure that the entity’s cybersecurity program complies with the relevant legislative

and regulatory requirements.

Controls

1-7-1

1-8

Objective

Controls

1-8-1

If there are nationally approved international agreements or commitments that include
cybersecurity requirements, the entity shall identify and comply with these
requirements.
Periodical Cybersecurity Review and Audit
To ensure that the cybersecurity controls adopted by the entity are implemented and
applicable in accordance with the entity’s regulatory policies and procedures, relevant
national legislative and regulatory requirements, and international requirements
imposed on the entity by law.

The cybersecurity department of
implementation of cybersecurity controls by the entity.

the entity shall periodically review

the

Document classification: Public



16

Essential Cybersecurity Controls

 دوﺪحﻣ

 ﺪﻴﻘﻣ

1-8-2

1-8-3

1-9

Objective

Controls

1-9-1

1-9-2

1-9-3

1-9-4

1-9-5

1-9-6

The implementation of cybersecurity controls by the entity shall be reviewed and
audited by parties other than the cybersecurity department at the entity, provided that
the audit and review are to be conducted independently while considering the principle
of conflict of interest, as per the Generally Accepted Auditing Standards (GAAS) and
the relevant legislative and regulatory requirements.
The results of cybersecurity audits and reviews shall be documented and presented to
the cybersecurity supervisory committee and the Authorized Official. Results shall
include the audit and review scope, observations, recommendations, corrective actions,
and remediation plans.
Cybersecurity in Human Resources
To ensure that cybersecurity risks and requirements for personnel (employees and
contractors) of the entity are managed efficiently prior to, during, and upon the end or
termination of their employment, as per the entity’s regulatory policies and procedures
and the relevant legislative and regulatory requirements.

Cybersecurity requirements for personnel of the entity shall be identified, documented,
and approved prior to, during, and upon the end or termination of their employment.
Cybersecurity requirements for personnel of the entity shall be implemented.
Cybersecurity requirements prior to the commencement of the employment
relationship between personnel and the entity shall include the following as a
minimum:
1.9.3.1 Incorporating the personnel’s cybersecurity responsibilities clauses and non-
disclosure clauses in their employment contracts with the entity (including during and
after employment end/termination with the entity).
1.9.3.2 Conducting screening or vetting for personnel in cybersecurity positions and
technical positions with critical and privileged powers.
Cybersecurity requirements for personnel during their employment relationship with
the entity shall include the following as a minimum:
1.9.4.1 Cybersecurity awareness (during on-boarding and during employment).
1.9.4.2 Implementation and compliance with cybersecurity requirements, as per the
entity’s cybersecurity policies, procedures, and operations.
The personnel’s powers shall be reviewed and revoked immediately upon the
end/termination of their employment with the entity.
Cybersecurity requirements for personnel of the entity shall be periodically reviewed.

17

Document classification: Public



 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

1-10

Objective

Controls

1-10-1

1-10-2

1-10-3

1-10-4

1-10-5

Cybersecurity Awareness and Training Program
To ensure that the entity’s personnel have the required security awareness, are aware
of their cybersecurity responsibilities, and are equipped with the required cybersecurity
skills, qualifications, and training courses in order to protect the entity’s information
and technology assets and fulfill their cybersecurity duties.

A cybersecurity awareness program, delivered through multiple channels, shall be
periodically developed and approved by the entity to strengthen the awareness about
cybersecurity, cyber threats, and risks, and to build a positive cybersecurity awareness
culture.
The approved cybersecurity awareness program shall be implemented within the entity.
The cybersecurity awareness program shall include how to protect the entity against
the most important and latest cyber risks and threats, including:
1.10.3.1 Secure handling of email services, especially phishing emails.
1.10.3.2 Secure handling of mobile devices and storage media.
1.10.3.3 Secure Internet browsing.
1.10.3.4 Secure usage of social media.
Specialized skills and necessary training shall be provided to personnel in positions that
are linked directly to cybersecurity within the entity. Such skills and training shall be
classified in line with their cybersecurity responsibilities, including:
1.10.4.1 Cybersecurity department personnel.
1.10.4.2 Personnel working on software/application development and those working
on information and technology assets of the entity.
1.10.4.3 Executive and supervisory positions.
The implementation of cybersecurity awareness program within the entity shall be
periodically reviewed.

Document classification: Public



18

Essential Cybersecurity Controls

 دوﺪحﻣ

 ﺪﻴﻘﻣ

 2
2

2-1

Objective

Controls

2-1-1

2-1-2

2-1-3

2-1-4

2-1-5

2-1-6

2-2

Objective

Controls

2-2-1

2-2-2

2-2-3

Cybersecurity Defense

Asset Management
To ensure that the entity has an accurate and updated inventory of assets, including
details of all information and technology assets of the entity, in order to support the
entity’s operations and cybersecurity requirements to maintain the confidentiality,
integrity, accuracy, and availability of information and technology assets of the entity.

Cybersecurity requirements for managing information and technology assets of the
entity shall be identified, documented, and approved.
Cybersecurity requirements for managing information and technology assets of the
entity shall be implemented.
The policy of acceptable use of information and technology assets of the entity shall be
identified, documented, approved, and communicated.
The policy of acceptable use of information and technology assets of the entity shall be
implemented.
Information and technology assets of the entity shall be classified, labeled, and handled
as per the relevant legislative and regulatory requirements.
Cybersecurity requirements for managing information and technology assets of the
entity shall be periodically reviewed.
Identity and Access Management
To ensure protecting cybersecurity of logical access to information and technology
assets of the entity, in order to prevent unauthorized access and restrict access to the
extent necessary for accomplishment of the assigned tasks of the entity.

Cybersecurity requirements for identity and access management of the entity shall be
identified, documented, and approved.
Cybersecurity requirements for identity and access management of the entity shall be
implemented.
Cybersecurity requirements for identity and access management of the entity shall
include the following as a minimum:
2.2.3.1 Single-factor authentication based on username and password.

Document classification: Public



19

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

2.2.3.2 Multi-factor authentication, and defining the suitable authentication factors and
their numbers as well as the suitable authentication techniques based on the result of
impact assessment of authentication failure and bypass for remote access and for
privileged accounts.
2.2.3.3 User authorization based on identity and access control principles (Need-to-
Know and Need-to-Use principle, Least Privilege principle, and Segregation of Duties
principle).
2.2.3.4 Privileged access management.
2.2.3.5 Periodic review of identities and access rights.
The implementation of cybersecurity requirements for identity and access management
of the entity shall be periodically reviewed.
Information System and Processing Facilities Protection
To ensure the protection of information systems and processing facilities, including
workstations and infrastructures of the entity, against cyber risks.

Cybersecurity requirements for protection of information system and processing
facilities of the entity shall be identified, documented, and approved.
Cybersecurity requirements for protection of information systems and processing
facilities of the entity shall be implemented.
Cybersecurity requirements for protection of information systems and processing
facilities of the entity shall include the following as a minimum:
2.3.3.1 Protection from viruses, suspicious programs and activities, and malware on
workstations and servers, using modern and advanced protection technologies and
mechanisms, and securely managing them.
2.3.3.2 Strict restriction on the use of external storage media and their security.
2.3.3.3 Patch management for systems, applications, and devices.
2.3.3.4 Centralized clock synchronization with an accurate and trusted source, such as
sources provided by the Saudi Standards, Metrology and Quality Organization (SASO).
The implementation of cybersecurity requirements for protection of the information
system and processing facilities of the entity shall be periodically reviewed.

2-2-4

2-3

Objective

Controls

2-3-1

2-3-2

2-3-3

2-3-4

Document classification: Public



20

Essential Cybersecurity Controls

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Email Protection

2-4
Objective To ensure the protection of the entity’s email service against cyber risks.
Controls

2-4-1

2-4-2

2-4-3

2-4-4

Cybersecurity requirements for protection of the email service of the entity shall be
identified, documented, and approved.
Cybersecurity requirements for protection of email service of the entity shall be
implemented.
Cybersecurity requirements for protection of the email service of the entity shall include
the following as a minimum:
2.4.3.1 Analyzing and filtering email messages (specifically phishing emails and spam
emails) using modern and advanced email protection techniques and mechanisms.
2.4.3.2 Multi-factor authentication, and defining the suitable authentication factors and
their numbers as well as the suitable authentication techniques based on the result of
impact assessment of authentication failure and bypass for remote and webmail access.
2.4.3.3 Email archiving and backup.
2.4.3.4 Secure management and protection against Advanced Persistent Threats (APT),
which normally utilize zero-day malware and viruses.
2.4.3.5 Validation of the entity’s email service domains by using Sender Policy
Framework (SPF), Domain Keys Identified Mail (DKIM), and Domain
Message Authentication Reporting and Conformance (DMARC).

The implementation of cybersecurity requirements for email service of the entity shall
be periodically reviewed .
Networks Security Management

2-5
Objective To ensure the protection of entity’s networks against cyber risks.
Controls

2-5-1

2-5-2

2-5-3

Cybersecurity requirements for the entity’s network security management shall be
identified, documented, and approved.
Cybersecurity requirements for the entity’s network security management shall be
implemented.
Cybersecurity requirements for the entity’s network security management shall include
the following as a minimum:

Document classification: Public



21

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

2.5.3.1 Logical or physical isolation and segmentation of network segments in a secure
manner which is required to control relevant cybersecurity risks, using firewall and
defense-in-depth principle.
2.5.3.2 Isolation of production network from testing and development environment
networks.
2.5.3.3 Secure browsing and internet connectivity, including strict restrictions on
suspicious websites, file storage/sharing websites, and remote access websites.
2.5.3.4 Wireless network security and protection using secure authentication and
encryption techniques and avoiding the connection of wireless networks to the entity’s
internal network, except after a comprehensive assessment of subsequent risks, with
handling them in a way that protects the technology assets of the entity.
2.5.3.5 Restricting and managing network services, protocols, and ports.
2.5.3.6 Intrusion Prevention Systems (IPS).
2.5.3.7 Security of Domain Name Service (DNS).
2.5.3.8 Secure management and protection of Internet browsing channel against
Advanced Persistent Threats (APT), which normally utilize zero-day malware
and viruses.

 2-5-3-9 Protecting against Distributed Denial of Service (DDoS) attacks to limit risks
arising from these attacks.
The implementation of cybersecurity requirements for the entity’s network security
management shall be periodically reviewed.
Mobile Devices Security
To ensure the protection of the entity’s mobile devices (including laptops, smartphones,
and tablets) against cyber risks, and ensure secure handling of the entity’s sensitive
information and business information and protecting them during transfer and storage
while using the devices of personnel of the entity (Bring Your Own Device "BYOD”
policy).

Cybersecurity requirements for mobile devices and BYOD security when connected to
the entity’s network shall be identified, documented, and approved.
Cybersecurity requirements for mobile devices and BYOD security of the entity shall be
implemented.
Cybersecurity requirements for mobile devices and BYOD security of the entity shall
include the following as a minimum:

2-5-4

2-6

Objective

Controls

2-6-1

2-6-2

2-6-3

Document classification: Public



22

Essential Cybersecurity Controls

 دوﺪحﻣ

 ﺪﻴﻘﻣ

2.6.3.1 Separation and encryption of the entity’s data and information stored on mobile
devices and BYODs.
2.6.3.2 Controlled and restricted use based on the requirements of the interest of the
entity's business.
2.6.3.3 Deletion of the entity’s data and information stored on mobile devices and
BYOD in cases of device loss or after the ending/termination of employment with the
entity.
2.6.3.4 Security awareness for users.
The implementation of cybersecurity requirements for mobile devices and BYOD
security of the entity shall be periodically reviewed.
Data and Information Protection
To ensure confidentiality, integrity, accuracy, and availability of the entity’s data and
information, as per the entity’s regulatory policies and procedures and the relevant
legislative and regulatory requirements

Cybersecurity requirements for protecting and handling data and information of the
entity shall be identified, documented, and approved, as per the relevant legislative and
regulatory requirements.
Cybersecurity requirements for protecting data and information of the entity shall be
implemented, based on its classification level.
The implementation of cybersecurity requirements for protecting data and information
of the entity shall be periodically reviewed.
Cryptography
To ensure the proper and efficient use of cryptography to protect electronic
information assets of the entity, as per the entity’s regulatory policies and procedures
and the relevant legislative and regulatory requirements.

Cybersecurity requirements for cryptography within the entity shall be identified,
documented, and approved.
Cybersecurity requirements for cryptography within the entity shall be implemented.
Cybersecurity requirements for cryptography shall include at least the requirements in
the National Cryptographic Standards, published by NCA. The appropriate
cryptographic standard level shall be implemented based on the nature and sensitivity
of the data, systems, and networks to be protected as well as the entity’s risk assessment,

23

2-6-4

2-7

Objective

Controls

2-7-1

2-7-2

2-7-3

2-8

Objective

Controls

2-8-1

2-8-2

2-8-3

Document classification: Public



 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

legislative and regulatory requirements, as follows:
and as per the relevant
2.8.3.1 Approved cryptographic systems and solutions standards and their technical and
regulatory restrictions.
2.8.3.2 Secure management of cryptographic keys during their lifecycles.
2.8.3.3 Encryption of data in-transit and at-rest, as per their classification and the
relevant legislative and regulatory requirements.
The implementation of cybersecurity requirements for cryptography within the entity
shall be periodically reviewed.
Backup and Recovery Management
To ensure the protection of the entity’s data, information, and technical configurations
of systems and applications against cyber risks, as per the entity’s regulatory policies
and procedures and the relevant legislative and regulatory requirements.

Cybersecurity requirements for backup and recovery management within the entity
shall be identified, documented, and approved.
Cybersecurity requirements for backup and recovery management within the entity
shall be implemented.
Cybersecurity requirements for backup and recovery management shall include the
following as a minimum:
2.9.3.1 Scope of backups to cover critical technology and information assets.
2.9.3.2 Ability to perform quick recovery of data and systems after cybersecurity
incidents.
2.9.3.3 Periodic testing for the effectiveness of backup recovery.
The
management within the entity shall be periodically reviewed.
Vulnerabilities Management
To ensure timely detection and effective remediation of technical vulnerabilities to
prevent or minimize the probability of exploitation of these vulnerabilities by cyber-
attacks and to reduce any impacts on the entity’s business.

implementation of cybersecurity requirements for backup and recovery

Cybersecurity requirements for technical vulnerabilities management within the entity
shall be identified, documented, and approved.
Cybersecurity requirements for technical vulnerabilities management within the entity
shall be implemented.

2-8-4

2-9

Objective

Controls

2-9-1

2-9-2

2-9-3

2-9-4

2-10

Objective

Controls

2-10-1

2-10-2

Document classification: Public



24

Essential Cybersecurity Controls

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Cybersecurity requirements for technical vulnerabilities management shall include the
following as a minimum:
2.10.3.1 Periodic vulnerabilities assessment and detection.
2.10.3.2 Vulnerabilities classification based on their severities.
2.10.3.3 Vulnerabilities remediation based on their classification and the associated
cyber risks.
2.10.3.4 Patch management to remediate vulnerabilities, and ensuring the integrity and
effectiveness of these updates and fixes are verified using a non-production environment
before being applied.
2.10.3.5 Communication and subscription with trusted resources for new and up-to-
date vulnerabilities.
The implementation of cybersecurity requirements for technical vulnerabilities
management within the entity shall be periodically reviewed.
Penetration Testing
To assess and test the efficiency of the entity’s cybersecurity defense capabilities through
simulation of actual cyber-attack methods and technologies to discover unknown
weaknesses that may lead to cyber penetration of the entity, as per the relevant legislative
and regulatory requirements.

Cybersecurity requirements for penetration testing within the entity shall be identified,
documented, and approved.
Cybersecurity requirements for penetration testing within the entity shall be
implemented.
Cybersecurity requirements for penetration testing shall include the following as a
minimum:
2.11.3.1 Scope of penetration testing to include all externally provided services (via the
Internet) and their technical components, including infrastructure, websites, web
applications, smartphone and tablet applications, email, and remote access.
2.11.3.2 Conducting penetration tests periodically.
The implementation of cybersecurity requirements for penetration testing shall be
periodically reviewed.

2-10-3

2-10-4

2-11

Objective

Controls

2-11-1

2-11-2

2-11-3

2-11-4

Document classification: Public



25

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

2-12

Objective

Controls

2-12-1

2-12-2

2-12-3

2-12-4

2-13

Objective

Controls

2-13-1

2-13-2

Cybersecurity Event Logs and Monitoring Management
To ensure timely collection, analysis, and monitoring of cybersecurity event logs for
proactive detection and effective management of cyber-attacks to prevent or minimize
negative impacts on the entity’s business.

Cybersecurity requirements for cybersecurity event logs and monitoring management
within the entity shall be identified, documented, and approved.
Cybersecurity requirements for cybersecurity event logs and monitoring management
within the entity shall be implemented.
Cybersecurity requirements for cybersecurity event logs and monitoring management
shall include the following as a minimum:
2.12.3.1 Activation of cybersecurity event logs for critical information assets within the
entity.
2.12.3.2 Activation of cybersecurity event logs for critical and privileged accounts
accessing information assets as well as for remote access events within the entity.
2.12.3.3 Identification of Security Information and Event Management (SIEM)
techniques required for cybersecurity event logs collection.
2.12.3.4 Continuous monitoring of cybersecurity event logs.
2.12.3.5 Retention period of cybersecurity event logs (shall be at least 12 months).
The implementation of cybersecurity requirements for cybersecurity event logs and
monitoring management within the entity shall be periodically reviewed.
Cybersecurity Incident and Threat Management
To ensure timely identification, detection, and effective management of cybersecurity
incidents and proactive response to cybersecurity threats to prevent or minimize
impacts on the entity’s business, as per High Order No. 37140, dated 14/08/1438H.

Requirements for cybersecurity incident and threat management within the entity shall
be identified, documented, and approved.
Requirements for cybersecurity incident and threat management within the entity shall
be implemented.

26

Document classification: Public



Essential Cybersecurity Controls

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Requirements for cybersecurity incident and threat management shall include the
following as a minimum:
2.13.3.1 Cybersecurity incident response plans and escalation procedures.
2.13.3.2 Cybersecurity incident classification.
2.13.3.3 Reporting cybersecurity incidents to the NCA.
2.13.3.4 Sharing cybersecurity incident notifications, threat intelligence, penetration
indicators, and incident reports with the NCA.
2.13.3.5 Collecting and handling threat intelligence feeds.
The implementation of cybersecurity requirements for incident and threat management
within the entity shall be periodically reviewed.
Physical Security
To ensure the protection of information and technology assets of the entity against
unauthorized physical access, loss, theft, and damage.

Cybersecurity requirements for protection of information and technology assets of the
entity against unauthorized physical access, loss, theft, and damage shall be identified,
documented, and approved.
Cybersecurity requirements for protection of information and technology assets of the
entity against unauthorized physical access, loss, theft, and damage shall be
implemented.
Cybersecurity requirements for protection of information and technology assets of the
entity against unauthorized physical access, loss, theft, and damage shall include the
following as a minimum:
2.14.3.1 Authorized access to critical areas within the entity (e.g. the entity’s data center,
disaster recovery center, critical information processing facilities, security surveillance
center, network connection rooms, technical device and equipment supply areas, etc.).
2.14.3.2 Access and monitoring logs (CCTV).
2.14.3.3 Protection of access and monitoring log information.
2.14.3.4 Security of the destruction and re-use of physical assets that hold classified
information (including paper documents and storage media).
2.14.3.5 Security of devices and equipment inside and outside the entity’s facilities.
Cybersecurity requirements for protection of information and technology assets of the
entity against unauthorized physical access, loss, theft, and damage shall be periodically
reviewed.

27

2-13-3

2-13-4

2-14

Objective

Controls

2-14-1

2-14-2

2-14-3

2-14-4

Document classification: Public



 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

Web Application Security

2-15
Objective To ensure the protection of external web applications of the entity against cyber risks.
Controls

2-15-1

2-15-2

2-15-3

2-15-4

Cybersecurity requirements for protection of external web applications of the entity
shall be identified, documented, and approved.
Cybersecurity requirements for protection of external web applications of the entity
shall be implemented.
Cybersecurity requirements for protection of external web applications of the entity
shall include the following as a minimum:
2.15.3.1 Use of web application firewall.
2.15.3.2 Adoption of the multi-tier architecture principle.
2.15.3.3 Use of secure protocols (e.g. HTTPS).
2.15.3.4 Clarification of the secure usage policy for users.
2.15.3.5 User authentication, and the suitable authentication factors and their numbers
as well as the authentication techniques shall be defined based on the result of impact
assessment of authentication failure and bypass for users’ access.
Cybersecurity requirements for protection of web applications of the entity shall be
periodically reviewed.

Document classification: Public



28

Essential Cybersecurity Controls

 دوﺪحﻣ

 ﺪﻴﻘﻣ

3

3-1

Objective

Controls

3-1-1

3-1-2

3-1-3

3-1-4

Cybersecurity Resilience

Cybersecurity Resilience Aspects of Business Continuity Management
(BCM)
To ensure the inclusion of cybersecurity resilience requirements in the
entity’s business continuity management and remediate and minimize the
impacts of disruptions on the entity’s critical e-services and information
processing systems and facilities caused by cyber risks.

Cybersecurity requirements for business continuity management within the
entity shall be identified, documented, and approved.
Cybersecurity requirements for business continuity management within the
entity shall be implemented.
Cybersecurity requirements for business continuity management within the
entity shall include the following as a minimum:
3.1.3.1 Ensuring the continuity of cybersecurity systems and procedures.
3.1.3.2 Developing plans for response to cybersecurity incidents that may
affect the entity’s business continuity.
3.1.3.3 Developing disaster recovery plans.
Cybersecurity requirements for business continuity management within the
entity shall be periodically reviewed.

Document classification: Public



29

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

4

4-1

Objective

Controls

4-1-1

4-1-2

4-1-3

4-1-4

Third-Party and Cloud Computing Cybersecurity

Third-Party Cybersecurity
To ensure the protection of the entity’s assets against third-party
cybersecurity risks (including Information Technology (IT) outsourcing,
cybersecurity outsourcing, and managed services), as per the entity’s
regulatory policies and procedures and the relevant legislative and regulatory
requirements.

Cybersecurity requirements for the entity’s contracts and agreements with
third parties shall be identified, documented, and approved.
Cybersecurity requirements for contracts and agreements with third parties,
e.g. Service Level Agreement (SLA), which, if impaired, may affect the entity's
data or services shall include the following as a minimum:
4.1.2.1 Clauses of non-disclosure and the secure removal of the entity’s data
by the third party upon the end of service.
4.1.2.2 Communication procedures in case of the occurrence of a
cybersecurity incident.
4.1.2.3 Obligating the third party to apply the entity’s cybersecurity
requirements and policies and the relevant legislative and regulatory
requirements.
Cybersecurity requirements for contracts and agreements with third parties
providing IT or cybersecurity outsourcing or managed services shall include
the following as a minimum:
4.1.3.1 Conducting a cybersecurity risk assessment and ensuring the
availability of risk mitigation controls before signing contracts and
agreements or upon making changes to the relevant legislative and regulatory
requirements.
4.1.3.2 Cybersecurity managed service centers for monitoring and operations
which use remote access shall be fully located in the Kingdom of Saudi
Arabia.
Cybersecurity requirements for third parties shall be periodically reviewed.

Document classification: Public



30

Essential Cybersecurity Controls

 دوﺪحﻣ

 ﺪﻴﻘﻣ

4-2

Objective

Controls

4-2-1

4-2-2

4-2-3

Cloud Computing and Hosting Cybersecurity
To ensure proper and efficient remediation of cyber risks and
implementation of cybersecurity requirements for cloud computing and
hosting, as per the entity’s regulatory policies and procedures, relevant
legislative and regulatory requirements, orders, and decisions, and to ensure
the protection of the entity’s information and technology assets on cloud
computing services hosted, processed, or managed by third parties.

Cybersecurity requirements for use of cloud computing and hosting services
shall be identified, documented, and approved.
Cybersecurity requirements for the cloud computing and hosting services
within the entity shall be implemented.
In accordance with the relevant legislative and regulatory requirements, and
in addition to the applicable controls in the Main Domains (1), (2), and (3)
and Subdomain (4.1) that are necessary to protect the entity’s data or services
provided thereto, cybersecurity requirements for use of cloud computing and
hosting services shall include the following as a minimum:
4.2.3.1 Protection of entity’s data by cloud and hosting service providers in
accordance with its classification level and returning data (in a usable format)
upon service completion.
4.2.3.2 Separation of the entity’s environment (especially virtual servers)
from environments of other entities within the cloud computing service
provider.

4-2-4

Cybersecurity requirements for cloud computing and hosting services shall
be periodically reviewed.

Document classification: Public



31

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

Appendices

Appendix (A): Terms and Definitions

Table (2) below highlights some of the terms and their definitions which were used in
this document.

TABLE 2 TERMS AND DEFINITION

Term
Advanced Persistent
Threats (APT)
Protection

Asset

Attack

Audit

Authentication

Authorization

Availability

include

less obvious

things, such as

Definition
Protection against advanced threats that use invisible techniques to
gain unauthorized access to technology systems and networks and stay
as long as possible by circumventing detection and protection tools.
To accomplish this, zero-day malware are usually used in these
techniques.
Any tangible or intangible thing of value to the entity. There are many
types of assets, and some of which are obvious, such as persons,
machinery, facilities, patents, software, and services. The term could
also
information and
characteristics (such as the entity’s reputation and public image, as
well as skills and knowledge).
Any kind of malicious activity aimed at gaining unauthorized access
to, collecting, disabling, preventing, destroying, or sabotaging
information system resources or the information itself.
Independent review and examination of records and activities, in
order to assess the effectiveness of cybersecurity controls and to ensure
compliance with policies, operational procedures, standards, and
relevant legislative and regulatory requirements.
Verification of the user's identity, process, or device, which is often a
prerequisite for allowing access to resources on the system.
The property of identifying and verifying the rights/licenses of the user
to access the information and technology assets and resources of the
entity and allowing access based on the user’s rights/licenses
previously defined.
Ensuring timely access and use of information, data, systems, and
applications.

Document classification: Public



32

Essential Cybersecurity Controls

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Backup

Bring Your Own
Device (BYOD)

Change
Management

Closed-Circuit
Television (CCTV)

Cloud Computing

Compromise

Files, devices, data, and procedures available for use in case of failure
or loss, or in case of deletion or suspension of their original copies.
This term refers to an entity's policy that allows (in whole or in part)
its personnel to bring their personal devices (laptops, tablets, and
smartphones) to their workplace within the entity and use such
devices to access the entity’s networks, information, applications, and
systems to which access is restricted.
A service management system that ensures a systematic and proactive
approach using effective standard methods and procedures (for
example, change in the entity’s infrastructure and networks, etc.).
Change management helps all stakeholders, including individuals and
teams alike, move from their current state to the next desired state. It
also helps reduce the impact of relevant incidents on service.
CCTV, also known as video surveillance, uses video cameras to
transmit a signal to a specific location on a limited set of screens. This
term is often used to refer to the surveillance technique employed in
areas that require monitoring due to the importance of physical
security.
A model to enable on-demand access to a shared pool of information
technology resources (e.g. networks, servers, storage, applications, and
services) that can be rapidly provided and launched with minimal
operational
setup
effort
intervention/interaction from the service provider. Cloud computing
allows users to access technology-based services over a cloud computing
network without needing to know or control the technology
infrastructure that supports them.
Cloud computing models are composed of five essential characteristics:
on-demand self-service, broad network access, resource pooling, rapid
elasticity, and measured service.
There are three models of cloud computing services: Software as a Service
(SaaS), Platform as a Service (PaaS), and Infrastructure as a Service (IaaS).
Moreover, according to the nature of access, there are four cloud
computing models: Public Cloud Computing, Community Cloud
Computing, Private Cloud Computing, and Hybrid Cloud Computing.
Disclosure or acquisition of information not authorized to be leaked
to or obtained by third parties, or violation of the entity's cybersecurity

management

service

and

Document classification: Public



33

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

the disclosure, acquisition,

policy through the disclosure, alteration, sabotage, or loss of anything,
either intentionally or unintentionally.
Compromise also means
leakage,
alteration, or use of sensitive data without authorization (including
cryptographic keys and other critical cybersecurity standards).
Information (or data) that is highly sensitive and important, as
classified by the entity, and intended for their use. One of the methods
that can be used to classify this type of information is to measure the
extent of damage when it is disclosed, accessed in an unauthorized
manner, lost, or sabotaged, as this may result in material or moral
damage to the entity or its clients, affecting the lives of persons
associated with that information, or affecting and damaging the State
security, national economy, or national capacities.
Sensitive information includes all information whose unauthorized
disclosure, loss, or sabotage results in accountability or statutory
penalties.
Maintaining authorized restrictions on access to and disclosure of
information,
information
including means of privacy/personal
protection.
Essential elements of infrastructure (i.e. assets, facilities, systems,
networks, processes, and key personnel who operate and process them)
whose loss or compromise may result in:
 Significant negative impact on the availability, integration, or delivery
of basic services, including services whose integrity could, if
compromised, result in serious loss of property, lives, and/or injuries,
taking into account significant national-level economic and/or social
impacts.

 Significant impact on national security, national defense, and/or State

economy or national capacities.

It is also called (cryptology). It refers to rules that include the principles,
methods, and means of storing and transmitting data or information in
a particular form, in order to conceal its semantic content and prevent
unauthorized use or prevent undetected modification, so that only the
concerned persons can read and process them.
An intentional attempt to impact cybersecurity negatively, whether
successful or not.
Risks that harm the entity’s business operations (including the entity’s
vision, mission, management, image, or reputation), assets, individuals,

34

Sensitive
Data/Information

Confidentiality

Critical National
Infrastructure
(CNI)

Cryptography

Cyber-Attack

Cyber Risks

Document classification: Public



Essential Cybersecurity Controls

 دوﺪحﻣ

 ﺪﻴﻘﻣ

other entities, or the State due to unauthorized access, use, disclosure,
disruption, modification, or damage of information and/or information
systems.
Pursuant to the provisions of the NCA's Statute issued by Royal Order
No. 6801, dated 11/02/1439H., cybersecurity is the protection of
networks, IT systems, operational technologies systems, their hardware
and software components, services, and the data they contain, from any
unauthorized penetration, disruption, modification, access, use, or
exploitation. The concept of cybersecurity also encompasses information
security, digital security, and the like.
The overall ability of entities to withstand cyber events and, where harm
is caused, recover from them.
The interconnected network of IT infrastructure, including the Internet,
communication networks, computer systems, Internet-connected
devices, and associated processors and control devices. The term can also
refer to a virtual world or domain, such as experimental phenomenon or
abstract concept.
Determining the sensitivity level of data and information which gives rise
to security controls for each classification level. Data and information
sensitivity levels are set according to predefined categories, where data
and information is created, modified, improved, stored, or transmitted.
The classification level is an indicator of the value or significance of data
and information to the entity.
The process of transferring data that is no longer actively used to a
separate storage device for long-term retention. Archive data consists of
older data that is still important to the entity and may be needed for
future reference, as well as data that shall be retained for legal and
regulatory compliance purposes.
A concept of information assurance where multiple levels of security
controls are used (as a defense) in the IT/OT system.
Programs, activities, and plans designed to restore the entity’s critical
business functions and services to an acceptable state, following exposure
to cyber-attacks or disruption of such functions or services.
A technical system that uses a database distributed over the network
and/or the Internet to allow the translation of domain names into IP
addresses and vice versa, in order to identify service addresses, such as
web and e-mail servers.

Cybersecurity

Cybersecurity
Resilience
Cyberspace

Data and
Information
Classification

Data Archiving

Defense-in-Depth

Disaster Recovery

Domain Name
System (DNS)

Document classification: Public



35

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

Effectiveness

Efficiency

Event

Hyper Text
Transfer Protocol
Secure (HTTPS)

Identification

Incident

Integrity

International
Requirements
Intrusion
Prevention System
(IPS)
Key Performance
Indicator (KPI)

Labeling

Least Privilege

Malware

A degree whereby a planned impact is achieved. Planned activities are
considered effective if they are already implemented, and planned results
are considered effective if they are already achieved. The Key
Performance Indicators (KPIs) can be used to measure and evaluate the
effectiveness level.
Relationship between the results achieved (outputs) and the resources
used (inputs). The efficiency of a process or system can be enhanced by
achieving more results using the same resources (inputs) or even less.
An event related to the cybersecurity state of a network, a system, a
service, data, or any other digital device.
A protocol that uses encryption to secure the web pages and data when
they are transmitted over the network. It is a secure version of the Hyper
Text Transfer Protocol (HTTP).
A means for verifying the user’s identity, process, or device, which is
usually a prerequisite for granting access to system resources.
An event that occurred and negatively impacted cybersecurity, whether
intentional or unintentional.
Protection against unauthorized modification or destruction of
information, including ensuring information non-repudiation and
reliability.
International requirements are those developed by an international entity
or organization for regulatory use worldwide (e.g. SWIFT, PCI, etc.).
A system with intrusion detection capabilities, as well as capabilities to
prevent and stop suspicious or potential activities and incidents.

A type of performance measurement tools that evaluate the success of an
activity or an entity in achieving specific objectives.
Display of information (with specific and standard naming and coding)
on the entity’s assets (such as devices, applications, documents, etc.) to
refer to some information on the classification, ownership, and type of
the asset and other asset management information.
A basic principle in cybersecurity that aims at granting users only access
privileges they need to fulfill their official responsibilities.
A program that infects systems, usually covertly, with the intent of
compromising the confidentiality, integrity, accuracy, or availability of
data, applications, or operating system.

36

Document classification: Public



Essential Cybersecurity Controls

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Multi-Factor
Authentication
(MFA)

Multi-tier
Architecture

Need-to-Know and
Need-to-Use

Offline/Offsite
Backup

Online Backup

Organization Staff

Outsourcing

Patch

Penetration Testing

that verifies user
through

A security system
authentication
Authentication factors are:
 Knowledge (something only the user knows “like using password

identity, using several
technique.

authentication

factors

technique”).

 Possession (something only owned by the user “such as using
technique like a program, device generating random numbers or
SMSs” for login records, which are called: One-Time-Password).
 Inherent characteristics (characteristics of the user only, such as

using fingerprint or face recognition techniques).

An architecture or structure that applies a client-server approach in
which the functional process logic, data access, data storage, and user
interface are developed and maintained as separate units on separate
platforms.
Restrictions on data, which is considered confidential, unless a person
has a specific need to know for official business duties.
A backup of databases, and settings of systems, applications, and devices
when the copy is offline and cannot be updated. Typically, backup tapes
are utilized for offsite backup.
A storage method whereby the backup is regularly taken on a remote
server over a network (either within the entity’s network or hosted by a
service provider).
Individuals who work for the entity (including official employees,
temporary employees, and contractors).
Obtaining goods or services by contracting with a supplier or a service
provider.
Supporting data packages used to upgrade, fix, or improve computer
operating system, software, or applications. This includes fixing security
vulnerabilities and other bugs. Such patches are usually called fixes, bug
fixes, and usability or performance improvements.
Testing a computer system, network, web application, or mobile
application to find vulnerabilities that can be exploited by an attacker.

Document classification: Public



37

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

Phishing Emails

Physical Security

Policy

Privileged Access
Management

Procedure

Process

Recovery

Retention

Secure Coding
Standards

An attempt to obtain confidential information, such as usernames,
passwords, or credit card details, often for malicious reasons and
intentions, by disguising as a trustworthy entity in emails.
Physical security describes security measures designed to prevent
unauthorized access to the entity’s facilities, equipment, and resources,
and to protect individuals and property against damage or harm (such as
espionage, theft, or terrorist attacks).
Physical security involves the use of multiple tiers of interconnected
systems, including CCTV, security guards, security limits, locks, access
control systems, and many other technologies.
A document with clauses specifying a general obligation, direction, or
intent as formally expressed by the Authorized Official of the entity .
Cybersecurity policy is a document with clauses reflecting official
commitment of the senior management of the entity to implement and
improve the cybersecurity program within the entity. Such policy
includes the entity’s objectives relating to the cybersecurity program, as
well as its controls, requirements, and improvement and development
mechanisms.
The process of managing high-risk authorizations on the entity’s systems,
which often need special handling to minimize risks that may arise from
the misuse thereof.
A document with a detailed description of the steps necessary to perform
specific operations or activities in compliance with relevant standards and
policies. Procedures are defined as part of operations.
A set of interrelated or interactive activities that translates inputs into
outputs. Such activities are influenced by the entity’s policies.
A procedure or process to restore or control something that is suspended,
damaged, stolen, or lost.
The time period during which information, data, event logs, or backups
shall be retained, regardless of the form (e.g. paper, electronic, etc.).
A practice for the development of computer software and applications in
a way that protects against exposure to cybersecurity vulnerabilities in
software and applications.

Document classification: Public



38

Essential Cybersecurity Controls

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Secure
Configuration and
Hardening

Security
Information and
Event Management
(SIEM)

Security Testing

Security-by-Design

Protecting, hardening, and configuring the settings of computers,
systems, applications, network devices, and security devices to resist
cyber-attacks, such as disabling or changing manufacturing and default
accounts, disabling unused services, and disabling unused network ports.
A system that manages and analyzes security event logs in real time, in
order to monitor threats and analyze the results of interrelated rules for
event logs and reports on logs data, and incident response.

A process intended to ensure that a modified or new system or
application, has the appropriate security controls and protection, is free
from any security vulnerabilities that might compromise other systems
and applications or lead to misusing the system or application or
information thereon, and to maintain the functionality of the system or
application as intended.

A methodology for developing systems and software and designing
networks to free them from cybersecurity vulnerabilities and weaknesses
and make them impervious to cyber-attack as much as possible through
several measures, such as continuous testing, authentication safeguards,
and adherence to best programming and design practices.

Segregation of
Duties

A key cybersecurity principle that aims at minimizing errors and fraud
during the stages of processing specific tasks, by ensuring the presence of
more than one individual to complete a task with different privileges.

Sender Policy
Framework

A method to verify that the email server used for sending emails belongs
to the sender's domain.

Third-Party

Any entity that serves as a party to contractual relationship to provide
goods or services (including suppliers and service providers).

Threat

Anything with the potential to impact cybersecurity negatively.

Threat Intelligence

It provides and analyzes organized information on recent, current, and
potential attacks that could pose a cyber threat to the entity.

Vulnerability

A weakness in any information technology asset (such as software and
systems) or a process, control, or anything, that could be exploited to
negatively impact cybersecurity.

Document classification: Public



39

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

Web Application
Firewall

Zero-Day Malware

A protection system that is installed before web applications to minimize
risks that may arise from attack attempts against web applications.
Previously unknown malware that has been produced or disseminated
recently and is normally hard to be detected by prior knowledge of
malware (Signature-based Protection).

Document classification: Public



40

Essential Cybersecurity Controls

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Appendix (B): List of the Abbreviations

Table (3) below shows some of the abbreviations and their meanings which are used in this
document.

TABLE 3 LIST OF ABBREVIATIONS

Abbreviation Full Term

APT

BCM

BYOD

CCTV

CNI

DDoS

DKIM

Advanced Persistent Threat

Business Continuity Management

Bring Your Own Device

Closed-Circuit Television

Critical National Infrastructure

Distributed Denial of Service Attack

Domain Keys Identified Mail

DMARC

Domain Message Authentication Reporting and Conformance

DNS

ECC

Domain Name System

Essential Cybersecurity Controls

HTTPS

Hyper Text Transfer Protocol Secure

ICT

IT

MFA

OT

SIEM

SLA

SPF

Information and Communication Technology

Information Technology

Multi-Factor Authentication

Operational Technology

Security Information and Event Management

Service Level Agreement

Sender Policy Framework

Document classification: Public



41

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

Appendix (C): List of Updates

Table (4) below illustrates the updates on the previous version (i.e., ECC-1:2018).

TABLE 4 LIST OF UPDATES

Version

ECC – 2 : 2024

Date

2024

Update type

Section

Previous text

Updated text

Modification ECC Scope of

Work

Deletion

ECC Statement
of Applicability

Modification Control

1-2-2

These
are
controls
applicable to government
entities in the Kingdom of
(including
Saudi Arabia
authorities,
ministries,
establishments and others)
and
its companies and
entities.

Controls in main domain 5
(Industrial Control Systems
Cybersecurity)
are
applicable and must be
implemented by entities
currently using or planning
to use industrial control
systems.

of
position
The
cybersecurity function head
(e.g., CISO), and related
critical
supervisory
positions
the
function, must be filled with
full-time and experienced

and
within

42

These
are
Controls
applicable to government
agencies in the Kingdom of
(including
Saudi Arabia
authorities,
ministries,
establishments and others)
affiliated
and
entities
companies
(inside and outside
the
kingdom)

their

and

All cybersecurity positions
shall be filled out with full-
time and qualified Saudi
cybersecurity professionals.

Rationale

Clarification

Deletion of main
domain 5. Controls in
domain 5 moved to
OTCC
the
(Operational
Technology
Cybersecurity
Controls)

Cybersecurity
enhancement

Document classification: Public



Essential Cybersecurity Controls

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Date

2024

Previous text

Saudi
professionals.

Updated text

Rationale

cybersecurity

Version

ECC – 2 : 2024

Update type

Section

Deletion

Control
1-7-1

Modification Control

1-7-2

related

The entity must comply
national
with
cybersecurity
and
regulations.

laws

any

The entity must comply
nationally-
with
international
approved
and
agreements
commitments
to
cybersecurity.

related

Modification Sub-control

2-2-3-1

User authentication based
on username and password.

Modification Sub-control

2-2-3-2

Multi-factor authentication
for remote access.

Cybersecurity
regulatory maturity,
and
supporting
entities’ compliance

Clarification

Clarification

Clarification

there are nationally
If
international
approved
agreements
or
commitments that include
cybersecurity requirements,
the entity shall identify and
these
with
comply
requirements.

Single-factor authentication
based on username and
password.

Multi-factor authentication,
and defining the suitable
authentication factors and
their numbers as well as the
suitable
authentication
techniques based on the
result of impact assessment
failure
of authentication
and bypass
remote
for
access and for privileged
accounts.

Document classification: Public



43

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

Version

ECC – 2 : 2024

Date

2024

Update type

Section

Previous text

Updated text

Modification Sub-control

2-4-3-2

Multi-factor authentication
for remote and webmail
access to email service.

Modification Sub-control

2-4-3-5

Validation of the entity’s
email service domains (e.g.,
Policy
Sender
using
Framework (SPF)).

Addition

Sub-control
2-5-3-9

N/A

Modification Control

2-7-2

Deletion

Control
2-7-3

cybersecurity
The
requirements for protecting
and handling data and
be
information must
implemented.
The
cybersecurity
requirements for protecting
and handling data and
44

Multi-factor authentication,
and defining the suitable
authentication factors and
their numbers as well as the
authentication
suitable
techniques based on the
result of impact assessment
failure
of authentication
and bypass for remote and
webmail access.

Validation of the entity’s
email service domains by
Policy
Sender
using
Framework (SPF), Domain
Identified Mail
Keys
and Domain
(DKIM),
Authentication
Message
Reporting
and
Conformance (DMARC).
against
Protecting
Distributed Denial
of
Service (DDoS) attacks to
limit risks arising
from
these attacks.
Cybersecurity requirements
for protecting data and
information of the entity
shall be implemented, based
on its classification level.

Rationale

Clarification

Clarification

Cybersecurity
enhancement

Clarification

For the National Data
Management Office
(NDMO) at the Saudi

Document classification: Public



Essential Cybersecurity Controls

Version

ECC – 2 : 2024

Date

2024

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Update type

Section

Previous text

Updated text

Rationale

Data and Artificial
Intelligence
Authority mandates,
entities must refer to
the National Data
Management Office
regarding
data
privacy before taking
any action
this
regard.
Clarification

in

and

information must include at
least the following:
2-7-3-1
Data
information ownership.
and
2-7-3-2
information
classification
and labeling mechanisms.
2-7-3-3
and
information privacy.

Data

Data

Modification Control

2-8-3

cybersecurity
The
requirements
for
cryptography must include
at least the following:
Approved
2-8-3-1
cryptographic
solutions
standards and its technical
and regulatory limitations.
2-8-3-2 Secure management
keys
cryptographic
of
during their lifecycles.
2-8-3-3 Encryption of data
in-transit and at-rest as per
classification and related
laws and regulations.

Cybersecurity requirements
for cryptography shall
include at least the
requirements in the
National Cryptographic
Standards, published by
NCA. The appropriate
cryptographic standard
level shall be implemented
based on the nature and
sensitivity of the data,
systems, and networks to
be protected as well as the
entity’s risk assessment,
and as per the relevant
legislative and regulatory
requirements, as follows:
2.8.3.1 Approved
cryptographic systems and
solutions standards and
their technical and
regulatory restrictions.

Document classification: Public



45

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

Version

ECC – 2 : 2024

Date

2024

Update type

Section

Previous text

Updated text

Rationale

assessment

2.8.3.2 Secure management
of cryptographic keys
during their lifecycles.
2.8.3.3 Encryption of data
in-transit and at-rest, as per
their classification and the
relevant legislative and
regulatory requirements.
User authentication, and
the suitable authentication
factors and their numbers as
well as the authentication
techniques shall be defined
the result of
based on
impact
of
authentication failure and
bypass for users’ access.
To ensure the protection of
the entity’s assets against
cybersecurity
third-party
(including
risks
Information
Technology
outsourcing,
(IT)
cybersecurity outsourcing,
and managed services), as
per the entity’s regulatory
policies and procedures and
the relevant legislative and
regulatory requirements.
Cybersecurity requirements
and
contracts
for
third
agreements with

Clarification

Clarification

Clarification

Modification Sub-control

2-15-3-5

Multi-factor authentication
for users’ access.

Modification Objective of
Sub-domain
4-1

Modification Control

4-1-3

To ensure the protection of
assets
the
against
cybersecurity risks related
to third-parties including
outsourcing and managed
per
services
organizational policies and
procedures, and related laws
and regulations.

as

The
cybersecurity
requirements for contracts
and agreements with IT

46

Document classification: Public



Essential Cybersecurity Controls

Version

ECC – 2 : 2024

Date

2024

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Update type

Section

Previous text

Updated text

Rationale

outsourcing and managed
services third-parties must
include
the
following:

least

at

Modification Control
4-2-3-1

Deletion

Sub-control
4-2-3-3

Classification of data prior
to hosting on cloud or
and
hosting
returning data (in a usable
format)
service
upon
completion.

services

information
Entity’s
hosting and storage must be
inside
the Kingdom of
Saudi Arabia.

Deletion

Main domain
5

Industrial Control Systems
Cybersecurity

47

parties providing IT or
cybersecurity outsourcing
or managed services shall
include the following as a
minimum:
Protection of entity’s data
by cloud and hosting service
in accordance
providers
with its classification level
and returning data (in a
usable format) upon service
completion.

Cybersecurity
enhancement

Controls related to
data localization have
been transferred from
the document to the
Data
National
Management Office
(NDMO) at the Saudi
Data and Artificial
Intelligence
Authority for as per
the mandates, and
entities must refer to
the National Data
Management Office
data
regarding
localization
before
taking any action in
this regard.
Controls in domain 5
moved to the OTCC

Document classification: Public



 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

Version

ECC – 2 : 2024

Date

2024

Update type

Section

Previous text

Updated text

Rationale

(Operational
Technology
Cybersecurity
Controls)
Translation update

Clarification

Modification Terms and
Definitions
Modification Terms and
Definitions

National

Confidential
Data/Information
Critical
Infrastructure (CNI)
These are the assets (i.e.,
facilities, systems, networks,
processes and key operators
who operate and process
loss
them), whose
or
security
to
vulnerability
breaches may result in:
 Significant
negative
the
on
impact
availability,
integration
or delivery of basic
including
services,
services that could result
in
of
loss
serious
lives
property and/or
and/or injuries, alongside
observance of significant
economic and/or social
impacts.
 Significant

impact on
national security and/or
national defense and/or
state
or
economy
national capacities.

loss

National

Sensitive
Data/Information
Critical
Infrastructure (CNI)
of
Essential
elements
infrastructure
(i.e. assets,
facilities, systems, networks,
processes, and key personnel
who operate and process
or
them) whose
compromise may result in:
 Significant
negative
the
on
impact
availability,
integration,
or delivery of basic
including
services,
services whose integrity
could, if compromised,
result in serious loss of
lives, and/or
property,
injuries,
into
taking
significant
account
national-level economic
and/or social impacts.

 Significant
impact on
national
security,
national defense, and/or

Document classification: Public



48

Essential Cybersecurity Controls

Version

ECC – 2 : 2024

Date

2024

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Update type

Section

Previous text

Updated text

Rationale

Modification Terms and
Definitions

Modification Terms and
Definitions

Modification Terms and
Definitions

Modification Terms and
Definitions

Clarification

Clarification

Clarification

Clarification

State
economy
national capacities.

or

Cyber Attack
An intentional attempt to
cybersecurity
impact
negatively;
whether
succeeded or not.

Event
An event related to the
cybersecurity state of a
network, or a system, or a
service, or data, or any other
digital device.

Incident
An event that occurred and
impacted
negatively
whether
cybersecurity,
or
intentional
unintentional.

International
Requirements

International requirements
are those developed by an
international
or
organization for regulatory
use worldwide (e.g. SWIFT,
PCI, etc.).

entity

Cyber Attack
Intentional exploitation of
computer systems, networks,
and entities whose work
depends on digital ICT, in
order to cause damage.
Event
Something that happens in
a specific place (such as
network,
system,
application) at a specific
time.

compromise

Incident
through
A
violation of cybersecurity
acceptable use
policies,
or
practices
policies,
cybersecurity controls or
requirements.
(Inter)National
Requirements

National requirements are
those developed by
a
regulatory entity or body in
Saudi Arabia for regulatory
use (e.g., NCA’s Essential
Cybersecurity
Controls
(ECC-1:2018)

49

Document classification: Public



 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

Version

ECC – 2 : 2024

Date

2024

Update type

Section

Previous text

Updated text

Rationale

Modification Terms and
Definitions

system

security

elements

International requirements
are those developed by a
global entity for worldwide
regulatory or best practices
use (e.g., SWIFT, PCI-DSS,
etc.).
Multi-Factor
Authentication (MFA)
A
that
verifies user identity, which
requires the use of several
separate
of
identity
verification
mechanisms. Verification
mechanisms include several
elements:
 Knowledge (something
only the user knows
“like password”).
 Possession (something
only owned by the user
“such as a program,
device
generating
random numbers or
SMSs” for login records,
which are called: One-
Time-Password).
 Inherent characteristics
(characteristics of the
user only,
as
fingerprint).

such

Clarification

Multi-Factor
Authentication (MFA)
A security system that
verifies user identity, using
several authentication
factors through user
authentication techniques.
Authentication factors are:
 Knowledge (something
only the user knows
“such as using a
password technique”).
 Possession (something
only owned by the user
“such as using
techniques like a
program or a device
generating random
numbers or SMSs” for
login records, which are
called One-Time-
Password).

 Inherent characteristics
(characteristics of the
user only, such as using

Document classification: Public



50

Essential Cybersecurity Controls

Version

ECC – 2 : 2024

Date

2024

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Update type

Section

Previous text

Updated text

Rationale

fingerprint or face
recognition
techniques).

For the National Data
Management Office
(NDMO) at the Saudi
Data and Artificial
Intelligence
Authority mandates,
entities must refer to
the National Data
Management Office
regarding
data
privacy before taking
any action
this
regard.
Clarification

in

Deletion

Terms and
Definitions

Privacy
from
Freedom
unauthorized
interference
or disclosure of personal
an
information
individual.

about

Modification Terms and
Definitions

Threat
Anything with the potential
cybersecurity
impact
to
negatively.

image,

Threat
Any circumstance or event
with
to
the potential
impact
adversely
organizational operations
(including
mission,
or
functions,
reputation), organizational
assets,
individuals
or
information
through an
system via unauthorized
access,
destruction,
disclosure, modification of
information, and/or denial
of
the
service. Also,
potential for a threat-source
to successfully exploit a
51

Document classification: Public



 دوﺪحﻣ

 ﺪﻴﻘﻣ

Essential Cybersecurity Controls

Version

ECC – 2 : 2024

Date

2024

Update type

Section

Previous text

Updated text

Rationale

information

particular
system vulnerability.
Vulnerability
Any type of weakness in a
computer system, software,
application,
of
procedures, or in anything
leaves cybersecurity
that
exposed to a threat.

set

a

Modification Terms and
Definitions

Addition

List of the
Abbreviations

Deletion

List of the
Abbreviations

Industrial Control

ICS:
System
SIS: Safety Instrumented
System

exploited

Vulnerability
A weakness
in
any
technology
information
asset (such as software and
systems) or a process,
control, or anything, that
could be
to
negatively
impact
cybersecurity.
DDoS: Distributed Denial
of Service Attack
DKIM: Domain Keys
Identified Mail
DMARC: Domain Message
Authentication Reporting
and Conformance
SPF:
Framework

Sender

Policy

Clarification

Addition
abbreviations

of

Controls in domain 5
moved to the OTCC
(Operational
Technology
Cybersecurity
Controls)

Document classification: Public



52

Essential Cybersecurity Controls

 دوﺪحﻣ

 ﺪﻴﻘﻣ

Document classification: Public



53
