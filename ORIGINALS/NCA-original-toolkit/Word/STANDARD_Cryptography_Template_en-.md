This is a guidance box. Remove all guidance boxes after filling out the template. Items highlighted in turquoise should be edited appropriately. After all edits have been made, all highlights should be cleared.

Insert organization logo by clicking on the outlined image.

Cryptography Standard Template

Replace <organization name> with the name of the entity for the entire document. To do so, perform the following:

* Press “Ctrl” + “H” keys simultaneously
* Enter “<organization name>” in the Find text box
* Enter your organization’s full name in the “Replace” text box
* Click “More”, and make sure “Match case” is ticked
* Click “Replace All”
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
| Version Details | Updated by | Date | Version |
| <Insert description of the version> | <Insert individual’s full personnel name> | Click here to add date | <Insert version number> |
|  |  |  |  |

Review Table

|  |  |  |
| --- | --- | --- |
| Upcoming Review Date | Last Review Date | Periodical Review Rate |
| Click here to add date | Click here to add date | <Once a year> |
|  |  |  |

Table of Contents

[Purpose 4](#_Toc120212596)

[Scope 4](#_Toc120212597)

[Standards 4](#_Toc120212598)

[Roles and Responsibilities 12](#_Toc120212599)

[Update and Review 12](#_Toc120212600)

[Compliance 12](#_Toc120212601)

# [Purpose](#_heading=h.1fob9te)

This standard aims to define the detailed cybersecurity requirements related to the cryptography of‏ <organization name> to achieve the main objective which is minimizing cybersecurity risks resulting from internal and external threats.

The requirements in this standard are aligned with the Cryptography Policy and the cybersecurity requirements issued by the National Cybersecurity Authority (NCA) in addition to other related cybersecurity legal and regulatory requirements.

# [Scope](#_heading=h.3znysh7)

This standard covers all <organization name>’s systems, applications and processing devices and applies to all personnel (personnel and contractors) in the <organization name>.

# [Standards](#_heading=h.2et92p0)

|  |  |
| --- | --- |
| 1 | Use of Cryptography |
| Objective | To ensure that the use of cryptography is securely managed and used appropriately when required. |
| Risk Implication | If cryptography is not used properly and as necessary, this can have severe implications that could lead to information theft, unauthorized access, and information disclosure. |
| Requirements | |
|  | Valid Transport Layer Security (TLS) certificates must be used for all sensitive information in transit between the client, server and other servers |
|  | TLS certificates must be obtained from a recognized Certificate Authority (CA) for all production services at <organization name>. |
|  | Internet browsers must be configured to avoid insecure and weak protocols (e.g., SSLv3 or SSLv2), and weak ciphers (e.g., DES or MD5) while ensuring to use protocols with alignment with the National Cryptography Standards (NCS-1:2020). |
|  | Encrypted channels must be used for all authentications. |
|  | It must be ensured that backups are properly protected via physical security and encryption when they are stored and moved across the network. Such backups must include remote backups and cloud services. |
|  | All network devices must be managed using encrypted sessions. |
|  | During a cryptographic process, if an error is detected in the received information, and the receiver requires that the information be entirely correct (e.g., the receiver cannot proceed when the information is in error), then the following must be performed:   * The information must not be used. * The recipient may request that the information be resent (retransmissions must be limited to a predetermined maximum number of times). * Information related to the incident must be stored in an audit log to later identify the source of the error. |
|  | The strength levels must be designed to target a 128-bit security level for the basic level and a 256-bit security level for the advanced level as per the National Cryptographic Standard (NCS-1:2020). |
| 2 | Data and Information Encryption |
| Objective | To ensure that data and information is encrypted when necessary. |
| Risk Implication | Unencrypted data and information has severe implications that could lead to information theft, unauthorized access, and information disclosure. |
| Requirements | |
|  | Approved whole disk encryption software must be used to encrypt the hard drive of all mobile devices. |
|  | All encrypted network traffic must be decrypted at the boundary proxy prior to analyzing the content. However, <organization name> may use whitelists of allowed sites that can be accessed through the proxy without decrypting the traffic. |
|  | All remote login access to <organization name>’s network must be required to encrypt data in transit. |
|  | All traffic leaving <organization name> must be monitored, and any unauthorized use of encryption must be detected. |
|  | If USB storage devices are used, data stored on such devices must be encrypted while at rest, based on the data classification. |
|  | All protected information in transit must be encrypted. |
|  | All protected information at rest must be encrypted using a tool that requires a secondary authentication mechanism not integrated into the operating system, in order to access the information. |
|  | All wireless data in transit must be encrypted. |
|  | All authentication credentials must be encrypted or hashed with a salt when stored |
|  | It must be ensured that all account usernames and authentication credentials are transmitted across networks using encrypted channels. |
|  | Servers storage media must be encrypted, including hard disks, Network Attached Storage (NAS), Storage Area Network (SAN) connected storage, or any other type of connected storage. |
|  | Databases must be encrypted to prevent unauthorized access to data classified as confidential, secret, and top secret. |
|  | Data must be transmitted over the network and between systems using encryption mechanisms strong enough to minimize the risk of data exposure. |
|  | Database files, on the database-level or field-level, must be encrypted as per <organization name>’s relevant policies and procedures. |
|  | Backup tapes that store backups must be encrypted, and the key must not be stored in the same tapes in plain text. |
|  | All administrator, user or application traffic to and from the DBMS must be encrypted. |
|  | End-to-end encryption for web applications client/server communications must be implemented. |
| 3 | Other Cryptographic Related Information |
| Objective | To ensure that data and information used in conjunction with keys is securely managed. |
| Risk Implication | Insecure management of data and information used in conjunction with cryptographic keys has severe implications that could lead to information theft, unauthorized access, and information disclosure. |
| Requirements | |
|  | All information used in conjunction with cryptographic algorithms and keys must be protected. |
|  | Associations for cryptographic information must be protected according to their type. |
|  | An assurance of domain parameter validity must be obtained for all discrete log public key algorithms to ensure that the domain parameters are arithmetically correct, using one of the following methods:   * Assurance from the key owner, key verifier, or trusted third party * Explicit validation depending on the algorithm used |
|  | Non-cryptographic mechanisms must be incorporated in communication systems to ensure the availability of transmitted cryptographic information after it has been successfully received, rather than relying on retransmission by the original sender for future availability. |
| 4 | Cryptographic algorithms and schemes |
| Objective | To ensure that approved and secure cryptographic algorithms and schemes are used when using cryptography. |
| Risk Implication | Use of insecure or unapproved cryptographic algorithms and schemes has severe implications that could lead to information theft, unauthorized access, and information disclosure. |
| Requirements | |
|  | Only cryptographic hash functions must be used to ensure that it is not feasible to find a message that produces a given hash value (Pre-image Resistance) or find two messages that produce the same hash value (Collision Resistance). |
|  | Accepted cryptographic hash functions should be used based on national cryptographic standards (NCS-1:2020). |
|  | Key lengths that are at least 128 bits must be used in all symmetric key algorithms. |
|  | Message Authentication Codes (MACs) must be used to provide assurance of the data’s integrity, and that the MAC was computed by the expected organization. |
|  | Only MAC algorithms must be used based on block cipher algorithms (CMAC) or based on hash functions (HMAC). |
|  | The same key must not be used if the same block cipher algorithm is used for both encryption and MAC computation. |
|  | Approved digital signature algorithms must be used to provide source authentication, integrity authentication, and support for non-repudiation. |
|  | Only the following digital signature algorithms must be used with the approved key sizes for each of the following:  • Digital Signature Algorithm (DSA)  • RSA Algorithm  • ECDSA Algorithm  • Merkle |
|  | Digital signatures must be generated using keys that meet or exceed the approved key sizes of the algorithm. |
|  | Only the following approved key-exchange scheme types must be used to set up keys between communicating entities:  • Key Transport: The keying material must be transported from one organization to another using a symmetric algorithm (i.e., using a key-wrapping key), or using an asymmetric algorithm.  • Key Agreement: Entities must co-create shared keying material using symmetric or asymmetric algorithms. |
|  | Approved key-exchange schemes with approved key sizes must be used. These schemes include Diffie-Hellman (DH) and RSA algorithms and Elliptic Curve Diffie-Hellman (ECDH) for the advance level. |
|  | Security strengths of at least 256 bits must be employed for cryptographic algorithms used for critical systems as per the National Cryptographic Standard (NCS-1:2020). |
|  | Security strengths of at least 256 bits must be employed for hash functions used for critical systems. |
|  | Authenticated Encryption with Associated Data (AEAD) and the accepted schemes must be used such as:   * Galois Counter Mode (GCM) * Counter with CBC-MAC (CCM) |
|  | When using Hybrid Encryption Schemes the accepted schemes must be used such as:   * Elliptic Curve Integrated Encryption Scheme (ECIES) * Discrete Logarithm Integrated Encryption Scheme (DLIES) * RSA with Optimal Asymmetric Encryption Padding (RSA-OAEP) |
| 5 | Commonly Used Cryptographic Protocols |
| Objective | To ensure that approved and secure cryptographic protocols are used when using cryptography. |
| Risk Implication | Use of insecure or unapproved cryptographic protocols has severe implications that could lead to information theft, unauthorized access, and information disclosure. |
| Requirements | |
|  | IP Security algorithms must be used for authentication, and must use the Authentication Header (AH) and encapsulation security payload (ESP) with authentication designs of (MAC) such as but not limited to: HMAC-SHA2-384, HMAC-SHA3-256. |
|  | Acceptable versions of the Transport Layer Security (TLS) protocol must be used such as TLS 1.2 and TLS 1.3 |
|  | Domain Name System Security (DNSSEC) must be used and the accepted requirements for both zone data signing and message authentication such as ECDSA\_P384\_SHA-384 and HMAC\_SHA- 384. |
|  | Acceptable secure remote connection protocol versions and requirements must be used such as SSH-2 and AEAD\_AES\_128\_GCM. |
|  | Acceptable version and requirements must be used for Bluetooth such as Bluetooth 4.1, Security Mode 4 and AES-CCM. |
|  | Acceptable requirements of the UMTS / 4G (LTE) / 5G system must be used such as:  • For Universal Mobile Telecommunications System (UMTS), UEA1-128 must be used with UA1-128.  • For 4G (LTE), must use 128-EEA2 with 128-EIA2.  • For the fifth generation (5G),must use OR 128-NEA2 with 128-NIA2. |
|  | Acceptable versions of Wi-Fi Protected Access (WPA) must be used such as WPA3-Enterprise. |
|  | Kerberos Protocol must use the accepted requirements for both basic and advance level such as:   * (CAMELLIA128-CTS-CMAC) * (AES256-CTS-HMAC-SHA3) |
|  | Server management protocol that supports encryption or configures encryption for server management protocols, such as LDAP over TLS, SNMPv3 with authentication and privacy, Kerberos with TLS, encrypted syslog, etc., must be used. |
|  | Encryption for server application and database communication protocols, such as HTTPS, Secure API, TDE or SQL with TLS, SFTP, SSHv2, etc., must be configured. |
|  | Unencrypted protocols or non-secure services (such as HTTP, FTP, etc.), must not be used, and HTTPS, SFTP, etc. must be used instead. |
|  | Encryption technologies, such as Transport Layer Security (TLS) and Virtual Private Networks (VPN), must be implemented to protect authentication mechanisms during transmission. |
|  | Web application protocols must be configured to use encryption wherever applicable (e.g., HTTPS, SFTP over TLS, etc.). |
|  | The use of secure encrypted management protocols such as Secure Shell (SSH) v2 and Remote Desktop Protocol (RDP) over TLS must be restricted. |

# [Roles and Responsibilities](#_heading=h.tyjcwt)

1. **Standard Owner:** <head of the cybersecurity function>
2. **Standard Review and Update:** <cybersecurity function>
3. **Standard Implementation and Execution:** <information technology organization>
4. **Standard Compliance Measurement**: <cybersecurity function>

# [Update](#heading=h.3dy6vkm) and Review

<cybersecurity function> must review the standard at least once a year or in case any changes occur in the infrastructure or changes happen to the policy or the regulatory procedures in <organization name> or the relevant regulatory requirements.

# [Compliance](#_heading=h.3dy6vkm)

1. The <head of the cybersecurity function> will ensure compliance of <organization name> with this standard on a regular basis.
2. All personnel at <organization name> must comply with this standard.
3. Any violation of this standard may be subject to disciplinary action according to <organization name>’s procedures.
