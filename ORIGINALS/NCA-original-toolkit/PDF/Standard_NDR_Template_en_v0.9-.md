This is a guidance box. Remove all guidance boxes
after filling out the template. Items highlighted in
turquoise should be edited appropriately. Items
highlighted in green are examples and should be
removed. After all edits have been made, all
highlights should be cleared.

Insert organization logo by clicking
on the placeholder to the left.

Network Detection and Response
Standard Template

Choose Classification

DATE
VERSION
REF

Click here to add date
Click here to add text
Click here to add text
Replace <organization name> with
the
name of the organization for the entire
document. To do so, perform the following:
keys
“Ctrl”
Press
simultaneously
Enter “<organization name>” in the
Find text box
Enter your organization’s full name
in the “Replace” text box

“H”

+
• Click “More”, and make sure

“Match case” is ticked

• Click “Replace All”
• Close the dialog box.

NDR Standard Template

Disclaimer

This template has been developed by the National Cybersecurity
Authority (NCA) as an illustrative example that can be used by organizations as
a reference and guide. This template must be customized and aligned with the
<organization name>’s business and relevant legislative and regulatory
requirements. This template must be approved by the head of the organization
(Authorizing official) or his/her delegate. The NCA is not responsible for any use
of this template as is, and it affirms that this template is solely an illustrative
example.

Choose

Classification

VERSION <1.0>

1

NDR Standard Template

Document Approval

Role

Job Title

Name

Date

Signature

Choose Role

<Insert job title>

<Insert individual’s
full personnel name>

Click here to add
date

<Insert
signature>

Version Control

Version

Date

Updated By

Version Details

<Insert version
number>

Click here to add
date

<Insert individual’s full
personnel name>

<Insert description of the
version>

Review Table

Periodical Review Rate

Last Review Date

Upcoming Review Date

<Once a year>

Click here to add date

Click here to add date

Choose

Classification

VERSION <1.0>

2

NDR Standard Template

Table of Contents

Purpose ............................................................................................................. 4

Scope ................................................................................................................ 4

Standards .......................................................................................................... 4

Roles and Responsibilities .............................................................................. 12

Update and Review ......................................................................................... 12

Compliance ..................................................................................................... 12

Choose

Classification

VERSION <1.0>

3

NDR Standard Template

Purpose

This standard aims to define the detailed cybersecurity requirements
related to the Network Detection and Response (NDR) for <organization
name>.

The requirements in this standard are aligned with the cybersecurity

requirements issued by the National Cybersecurity Authority (NCA) including
but not limited to ECC-1:2018 and CSCC-1:2019, in addition to other related
cybersecurity legal and regulatory requirements.

Scope

The standard covers <organization name>’s information and technology
in

to all personnel (employees and contractors)

assets and applies
<organization name> and related third parties.

Standards

1

General Requirements

Objective

The NDR solution must be securely designed and
appropriately used when required.

Risk
Implication

Requirements

1-1

Misconfiguration of the NDR solution may reduce the success
of
theft,
identification and result
unauthorized access, and information disclosure.

information

threat

in

NDR must combine data science, machine learning and
behavioral analysis with well-curated threat intelligence in
order to identify in real time or near real time the intent of
network traffic and reveal malicious behaviors, independent of
applications and even when traffic is encrypted and provide
assistance with manual incident and threat hunting response
through automation.

Choose

Classification

VERSION <1.0>

4

NDR Standard Template

1-2

1-3

1-4

1-5

1-6

1-7

1-8

1-9

NDR must correlate global threat intelligence to local threats
in order to prevent attackers from infecting many victims with
the same malware.

NDR must be deployed in various methodologies (in-line
sensors, passive sensors - Table A).

Physical access to the NDR solution must be restricted to
authorized employees only (least privilege assignment for
different administrators).

Administrative access to the management interface of the
NDR solution must be restricted
limited group of
administrators.

for

Unused Network Interface Cards must be disconnected from
any network.

NDR must support IPv4 and IPv6 stack for traffic processing
and security rules and traffic policy definition.

All security updates to the NDR solution must be installed as
they are released by the vendor and according to the change
management procedure.

Each management communication channel must be using a
dedicated management network or the management network
communications which is authenticated and encrypted using
validated cryptographic modules that are in line with the
National Cryptography Standard’s Key Lifecycle Management
requirements.

1-10

Time configuration on the NDR solution must be synchronized
with a trusted authoritative time server.

2

Traffic monitoring

Choose

Classification

VERSION <1.0>

5

NDR Standard Template

Objective

The NDR solution must be properly configured and securely
managed for proper cyber threat and anomalous behavior
detection in monitored networks.

Misconfiguration of the NDR solution may have severe
consequences like failing to analyze network traffic and
recognizing a threat, which could lead to data leakage, attack
on partner enterprises or even company clients.

Risk
Implication

Requirements

2-1

2-2

2-3

2-4

2-5

2-6

2-7

2-8

NDR must continually reveal the underlying purpose of traffic,
even when the payload is not visible. This allows for protection
without prying.

NDR must model a baseline of what normal network behavior
looks like and alert security teams on any suspicious traffic that
falls outside of that normal range.

NDR must attribute malicious behavior to a specific IP address
and perform forensic analyses to determine how threats have
moved laterally within an environment.

NDR must provide visibility to multiple public and private cloud
environments.

NDR must be able to analyze encrypted traffic without
decryption and detect threats that attempt to hide themselves
in encrypted traffic.

NDR must
signatures), IP addresses, TCP/UDP ports.

recognize URLs, applications

(based on

NDR must provide the ability to verify compliance to protocol
standards and prevent traffic that is not compliant.

Incident Response team must be able to query the database
list of “always available” or “always denied”
with

the

Choose

Classification

VERSION <1.0>

6

NDR Standard Template

resources/attacks which were verified by NDR solution during
traffic monitoring.

3

Traffic detection and logging

Objective

The NDR solution must monitor and process traffic in a secure
way to save any suspicious activity and notify the incident
response team in case of an unknown new possible incident.

Traffic detection without proper configuration may easily cause
malware propagation, phishing exposure and information leak.
Improperly configured NDR solution may result in not
sufficiently mitigating new possible security incidents in the
future.

Risk
Implication

Requirements

3-1

3-2

3-3

3-4

NDR must detect threats (e.g. unusual remote access, port
scanning, the use of restricted ports or protocols, etc.) in real-
time with the use of constantly learning behavioral models
derived from machine learning.

NDR must utilize advance threats detection and reduce
investigation time by capturing metadata and also recognize
the unique characteristics of malicious behaviors, which lead
to reliable identification of network intrusions, even if the tools,
malware or attack are completely unknown.

NDR must collect and enrich security metadata with deep
insights and context that allows it to detect and stop a wide
range of attack scenarios early and consistently.

NDR must apply algorithmic models directly to network traffic
in order to reveal underlying attack behaviors and then enrich
that data with secondary sources (e.g. authentication logs and
threat intelligence data) automatically.

Choose

Classification

VERSION <1.0>

7

NDR Standard Template

3-5

3-6

3-7

3-8

3-9

3-10

3-11

3-12

NDR must find signs of attackers who tunnel hidden
communications within an SSL/TLS-encrypted web session.
By analyzing tiny fluctuations in protocols like HTTPS and
DNS, NDR solution must reveal when additional layers of
communication are hidden within.

NDR must identify a wide range of command-and-control
behaviors, including attempts to imitate browser behavior, use
of hidden tunnels, peer-to-peer communication, malware
updating as well as a broad variety of anonymization
techniques such as TOR.

NDR must continuously monitor and alert for unusual
privileged access (the complexity of access management
makes it prone to misconfigurations).

NDR must divide gathered information into two sectors: user
for
information
administration section.

section and diagnostic

information

NDR must analyze previously captured incidents and draw
schemes to avoid them in the future with the use of machine
learning and artificial intelligence (ML and AI).

NDR must gather data about incidents in a dedicated
database. Each record must include information about
assigned categories of
like phishing emails,
malicious links, etc.

incidents,

The local threat intelligence database should be updated in
real-time to prepare for attacks happening in local enterprises.

NDR must filter all objects transferred through the network, for
instance phishing emails, malicious links, etc. It must be
consistent with the requirements of <organization name>’s
Malware Protection Standard.

Choose

Classification

VERSION <1.0>

8

NDR Standard Template

3-13

3-14

NDR must inform users about performed actions (in particular:
blocked requests or files) by configurable response web
pages.

NDR must use security feeds delivered by national trusted
organizations like national level CSIRT.

4

Automatic response and notification

Objective

The NDR solution must use data science and machine
learning in order to detect, analyze and protect the systems
against future security threats.

Risk
Implication

Without proper activity analysis and providing timely alerts for
incident response teams, the NDR solution may be ineffective
in preventing and mitigating future incidents.

Requirements

4-1

4-2

4-3

4-4

4-5

NDR must constantly detect network activity in order to detect
ongoing attacks, while security analysts have more time to
proactively hunt for threats and investigate incidents with
greater success.

NDR must accelerate response time by integrating and sharing
security insights with EDR, SIEMs and SOAR tools for
endpoint to cloud threat management and visibility.

NDR must deny unauthorized access to prevent access to
information which might progress attack and
essential
compromise sensitive data.

NDR must immediately inform about rejected or mitigated
attacks.

NDR must gather events and information about them in its
database with previously captured anomalies and prevented
attacks for future relevance.

Choose

Classification

VERSION <1.0>

9

NDR Standard Template

4-6

4-7

4-8

4-9

Organization should have runbook scenarios for NDR to
protect from adversary threats, for instance removing and
mitigation a threat by isolating affected systems, detecting and
blocking the spreading of malicious links or phishing emails
(detection based on local threat intelligence database with
ongoing incidents).

NDR must gather all log types from <organization name>’s
resources.

NDR must be consistent with
requirements of
<organization name>’s Event Log Management and
Monitoring Standard.

the

NDR must be configured to send only specific logs to the
central log system e.g. using syslog protocol and CEF, LEEF
or RFC 5425 specified log format.

NDR must include at least the following information:

● date and time of session

● source IP address

4-10

● user login

● destination IP

● action performed

● used traffic policy

Choose

Classification

VERSION <1.0>

10

NDR Standard Template

Table A – NDR deployment methodologies

There are two major methodologies of NDR deployment:

● in-line sensors - offer direct response capabilities.
● passive sensors - rely on integrations.

In-line sensors

Passive sensors

The method is based on placing the NDR
solution directly in the path of a network
segment, which allows for fast traffic inspection
and dropping anomalous or malicious traffic in
real-time.

inside

This option revolves around placing an NDR
(usually by
solution
integrating with SIEM, SOAR, public/private
clouds, etc.) and extracting metadata from
taken snapshots, which is then sent for analysis.

the network

Choose

Classification

VERSION <1.0>

11

NDR Standard Template

Roles and Responsibilities

1- Standard Owner: <head of the cybersecurity function>

2- Standard Review and Update: <cybersecurity function>

3- Standard Implementation and Execution: <information technology

function>

4- Standard Compliance Measurement: <cybersecurity function>

Update and Review

<cybersecurity function> must review the standard at least once a year
or in case any changes happen to the policy or the regulatory procedures in
<organization name> or the relevant regulatory requirements.

Compliance

1- The <head of the cybersecurity function> will ensure compliance of

<organization name> with this standard on a regular basis.

2- All personnel at <organization name> must comply with this standard.

3- Any violation of this standard may be subject to disciplinary action

according to <organization name>’s procedures.

Choose

Classification

VERSION <1.0>

12
