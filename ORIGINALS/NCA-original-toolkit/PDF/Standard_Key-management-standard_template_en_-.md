This is a guidance box. Remove all guidance boxes
after filling out the template. Items highlighted in
turquoise should be edited appropriately. Items
highlighted in green are examples and should be
removed. After all edits have been made, all
highlights should be cleared.

Insert organization logo by clicking
on the placeholder to the left.

Key Management Standard
Template

Choose Classification

DATE
VERSION
REF

Click here to add date
Click here to add text
Click here to add text

Replace <organization name> with the
name of the organization for the entire
document. To do so, perform the following:
keys
“Ctrl”

● Press

“H”

+

simultaneously.

● Enter “<organization name>” in

the Find text box.

● Enter your organization’s

full

name in the “Replace” text box.

● Click “More”, and make sure

“Match case” is ticked.

● Click “Replace All”.
● Close the dialog box.

Key Management standard

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

Key Management standard

Document Approval

Role

Job Title

Name

Date

Signature

Choose Role

<Insert job title>

<Insert individual’s full
personnel name>

Click here to add
date

<Insert
signature>

Version Control

Version

Date

Updated by

Version Details

<Insert version
number>

Click here to
add date

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

Key Management standard

Table of Contents

Purpose ............................................................................................................. 4

Scope ................................................................................................................ 4

Standards .......................................................................................................... 4

Roles and Responsibilities .............................................................................. 18

Update and Review ......................................................................................... 18

Compliance ..................................................................................................... 18

Choose

Classification

VERSION <1.0>

3

Key Management standard

Purpose

This standard aims to define the detailed cybersecurity requirements

related to the Key Management process for <organization name>.

The requirements in this standard are aligned with the cybersecurity
requirements issued by the National Cybersecurity Authority (NCA) including
but not limited to )ECC-1:2018( and NCS-1:2020, in addition to other related
cybersecurity legal and regulatory requirements.

Scope

This standard covers all information and technology assets in the
<organization name> and applies to all personnel (employees and contractors)
in the <organization name>.

Standards

1

General requirements

Objective

General requirements for the Key Management process must
be defined to ensure appropriate secure management of
cryptographic keys used by <organization name> during their
lifecycle.

Risk
Implication

Requirements

1-1

1-2

If cryptographic keys are not used properly and
its
management process is not conducted in line with general
cryptographic standards, this can impact the communication
and data exchange process which may result in information
theft, unauthorized access, and information disclosure.

Cryptographic key management must be in line with the 2-8-3
control of the Essential Cybersecurity Controls (ECC-1:2018).

Keys must be managed through the activities that involve
handling keys and related security parameters such as

Choose

Classification

VERSION <1.0>

4

Key Management standard

initialization vectors during the key cycle, including generation,
storage, establishment, insertion, output, use, and destruction.

Keys must be categorized according to their classification
(public, private, shared or symmetric) and use.

Keys and their association must be protected according to their
type and the required protection.

Using Hardware cryptographic modules must follow the below
requirements:

● Private keys should not be valid for more than 5 years
for

(this does not
MODERATE level of Cryptographic Standards.

limit CA certificates'

lifetime)

1-3

1-4

1-5

● Private keys should not be valid for more than 3 years
for

(this does not
ADVANCED level of Cryptographic Standards.

limit CA certificates’

lifetime)

Using Software cryptographic modules must follow the below
requirements:

1-6

● Private keys must not be valid longer than 2 years for

MODERATE level of Cryptographic Standards.

● Not accepted for ADVANCED level of Cryptographic

Standards.

2

Key Generation

Objective

Define requirements for the Key Generation process to ensure
proper key generation according to security rules.

If cryptographic keys are not generated properly and in line
with the defined process, this may result in the generation of
weak keys which can have severe implications that could lead
to information theft, unauthorized access, and information
disclosure.

Risk
Implication

Requirements

Choose

Classification

VERSION <1.0>

5

Key Management standard

2-1

2-2

2-3

2-4

2-5

Key generation must be performed based on:

● the generation of a key using the output of a Random Bit
Generator (approved RBGs are specified in NIST SP
800-90ar1).

● the derivation of a key from another key.

● the derivation of a key from a password key agreement
performed by two parties using an approved key-
agreement scheme.

Certificate Authority key generation must be undertaken in a
physically secured environment by personnel (employees and
contractors) in trusted roles under, at least, dual control,
defined as requiring two or more persons to control the
generation process to be parts of the key ceremony.

The asymmetric key pairs generating methods must be
approved, listed and complied with the National Cryptographic
Standards document.

An asymmetric static key pair must be generated by either:

● the party that owns the key pair (i.e., the party that uses
the private key in the cryptographic computations).

● a facility that distributes the key pair.

● the owner and facility in a cooperative process.

Symmetric keys must be either:

● generated by an approved, listed and complied with the
National Cryptographic Standards document method,

● derived from a master key/key-derivation key using an
approved and complied with the National Cryptographic
Standards document key-derivation function.

Choose

Classification

VERSION <1.0>

6

Key Management standard

A symmetric secret key used to apply cryptographic protection
to information and to remove or verify the protection must be
generated by:

● One or more of the organizations that will share the key,

2-6

or

● A trusted party that provides the key to the intended
sharing organizations in a secure manner. The trusted
party must be trusted by all organizations that will share
the key not to disclose the key to unauthorized parties
or otherwise misuse the key.

Key lengths used in symmetric key algorithms must be
complied with
the National Cryptographic Standards
document.

All symmetric keys and key shares must be generated within
the National
a cryptographic module specified
Cryptographic Standards document.

in

For critical systems, it is mandatory to employ symmetric key
lengths that are at least 256 bits, and asymmetric Elliptic Curve
Cryptography ECC key lengths that are at least 512 bits.

2-7

2-8

2-9

3

Key Registration/Certification

Objective

Define requirements for the Key Registration/Certification
process
registration/certification
according to security rules.

to ensure proper key

If cryptographic keys are not registered in line with the defined
requirements, this may result in e.g., the key registration in
untrusted and unauthorized Certification Authority which can
have severe implications that could lead to information theft,
unauthorized access, and information disclosure.

Risk
Implication

Requirements

Choose

Classification

VERSION <1.0>

7

Key Management standard

3-1

3-2

Keys must be associated with their owner (user) with a
certificate.

Root certificates must be distributed to relying parties and
signatories.

3-3

A trusted Certificate Authority must be used.

3-4

3-5

3-6

3-7

3-8

Key registration must result in the binding of keying material to
information associated with a particular organization. Keys that
would be registered include the public key of an asymmetric
key pair and the symmetric key used to bootstrap an
organization into a system.

The binding must be performed by a trusted third party.
Examples of a trusted third party include a Kerberos realm
server or a PKI Certification Authority.

If a Kerberos realm server performs the binding, a symmetric
key must be stored on that server with the corresponding
metadata.

If a Certificate Authority performs the binding, the public key
and associated information must be placed in a public-key
certificate that is digitally signed by the Certificate Authority.

If a Certificate Authority provides a certificate for a public key,
the public key must be verified to ensure that it is associated
with the private key known by the purported owner of the public
key.

4

Key Distribution and Installation

Objective

Define requirements for the Key Distribution and Installation
process to ensure proper key distribution and installation
according to security rules.

Risk
Implication

If cryptographic keys are not distributed and installed in line
with the defined requirements, this may result in e.g. a key

Choose

Classification

VERSION <1.0>

8

Key Management standard

breach and compromise or key distribution to an unauthorized
third party which can have severe implications that could lead
to information theft, unauthorized access, and information
disclosure.

The integrity and authenticity of the CA signature verification
(public key) and any associated parameters must be
maintained during its distribution to relying parties.

Keys must be distributed to their users securely and must be
under the users control.

Keys must be transported securely by protecting their
confidentiality and authenticity in a way complied with and
defined in the National Cryptographic Standards document.

Private and secret keys must not be distributed in plain text.

All copies of keys must be securely installed and stored.

Public keys must be kept secure to prevent interception and
manipulation until they are distributed.

Public keys must be transported, and authenticity (but not
privacy) must be protected by using certificates.

Private keys must be protected and authorized by the
owner/third party or CA.

The generated keys must be transported (when transportation
is necessary) using only secured channels.

Requirements

4-1

4-2

4-3

4-4

4-5

4-6

4-7

4-8

4-9

4-10

Keys must not be shared or distributed beyond those specific
organizations or devices requiring the use of the key for
approved purposes.

4-11

Keys that are manually distributed must either:

Choose

Classification

VERSION <1.0>

9

Key Management standard

● be cryptographically protected in the same manner as

those intended for electronic distribution.

● receive physical protection and be subject to controlled
distribution using approved and secure method between
the key processing facility and the end organization.

4-12

4-13

4-14

4-15

Keys used only for the storage of information must not be
to other authorized
distributed except
the stored
organizations
information protected by the keys.

for backup or
that may require access

to

The private key of an asymmetric key pair must be kept secret.
If the key is transferred, it must be taken out and transferred in
a form and manner that provides appropriate assurance of its
confidentiality, integrity and authenticity.

The method used for symmetric key transport or key wrapping
must support the desired security strength needed to protect
the target data.

The encrypted data and the key used for it must not be
transmitted together unless the encryption key is protected via
a secondary encryption, e.g., public key encryption.

5

Key Use

Objective

Define requirements for the Key Use process to ensure proper
key use according to security rules.

If cryptographic keys are not used in line with the define
requirement, this may result in e.g. the key misuse or its
unauthorized usage which can have severe implications that
could lead to information theft, unauthorized access, and
information disclosure.

Risk
Implication

Requirements

Choose

Classification

VERSION <1.0>

10

Key Management standard

5-1

5-2

5-3

5-4

5-5

5-6

Keys must be protected against unauthorized use during their
lifetimes.

 Keys must implement authorization check mechanisms to
protect against misuse from the owners.

A single key must be used for only one purpose (e.g.,
encryption, integrity authentication, key wrapping, random bit
generation, or digital signatures).

The keys and their intended usage must be connected in a
reliable way (key wrapping). Key usage information tells the
system what the key can (and cannot) be used for.

For asymmetric key pairs, each key of the pair must have its
own crypto period defined.

The key change may be done when:

● The key may have been compromised.

● The key’s cryptoperiod may be nearing expiration.

● It may be desirable to limit the amount of data protected
with any given key (re-keying – defined as a process of
changing the session key of an ongoing communication
in order to limit the amount of data encrypted with the
same key).

6

Key Storage

Objective

Define requirements for the Key Storage process to ensure
proper key storage according to security rules.

Risk
Implication

If cryptographic keys are not stored in line with the defined
requirements, this may result in e.g. the key leak and its
compromise and as result data leak which can have severe
implications that could lead to information theft, unauthorized
access, and information disclosure.

Choose

Classification

VERSION <1.0>

11

Key Management standard

Requirements

6-1

6-2

6-3

6-4

6-5

6-6

6-7

Organizations must require secure backups of keys (for
internal or
is
supported.

law enforcement use) when encryption

Storage rules and retention time for key information must be
defined by <organization name>.

Keys used for non-repudiation must be under the sole control
of the user.

Key identifiers or distinguished naming must be used for
proper key identification.

<organization name> must address how the cryptographic
device or application stores and protects key information
including how long it is to be stored.

<organization name> must indicate how the key information
(key identifier, distinguished name, ownership, key users,
generation date, expiration date, associated CA) is identified
during its storage life (e.g., using a Distinguished Name or key
identifier). The storage capacity requirements for storing the
key information must be included.

Asymmetric private keys must be stored in one of the following
ways:

● Inside one piece of Hardware Security Modules in

plaintext (or even encrypted under a Master key).

● Outside HSMs but encrypted with a key wrap function in

accordance with the NCS-1:2020.

● Inside many HSMs pieces of hardware but in plaintext
fragments (or even encrypted under a Master key).

6-8

Symmetric keys must be stored inside the Hardware Security
Modules. In case of exception, where a key is stored outside a

Choose

Classification

VERSION <1.0>

12

Key Management standard

cryptographic module, the method of protection must depend
on the impact level associated with the data protected by a
key.

6-9

The database that is used to store the keys must be encrypted
using validated and complied with the National Security
Standards document module.

7

Key Revocation/Validation

Objective

Define requirements
the Key Revocation/Validation
process to ensure proper key destruction according to security
rules.

for

If cryptographic keys are not revoked and validated in line with
the defined requirements, this may result in e.g. data
encrypted by the compromised key decryption and leak or
expired key usage which can have severe implications that
could lead to information theft, unauthorized access, and
information disclosure.

Risk
Implication

Requirements

A key must be revoked in case where:

● the authorized use of a key needs to be terminated prior
to the end of the established cryptoperiod of that key.

● a key whose usage period has expired.

● a key has been compromised.

A key may be revoked for administrative reasons (e.g., the
key’s owner has left <organization name>, or a device
containing the key has been removed from service).

A key must be revoked on an emergency basis if there is
reason to believe that it may have been disclosed to or
otherwise accessed by an unauthorized organization.

7-1

7-2

7-3

Choose

Classification

VERSION <1.0>

13

Key Management standard

7-4

7-5

7-6

7-7

7-8

A key must be revoked as soon as feasible after the need for
revocation has been determined.

The Certificate Revocation List (CRL) and
the Online
Certificate Status Protocol (OCSP) must be implemented to
avoid relying on keys that have expired.

Relying parties must be notified about key revocation using,
for example, Certificate Revocation Lists (CRLs) or the Online
Certificate Status Protocol (OCSP).

When a key is compromised, all organizations sharing the key
need to be notified (e.g., using a Compromised Key List
(CKL)).

<organization name> must validate used keys by checking the
CRL or OCSP lists/servers.

An assurance of public-key validity must be obtained to ensure
that the key is arithmetically correct, through one of the
following methods:

7-9

● Assurance from the key owner, key verifier, or trusted

third party.

● Explicit public key validation by encrypting a message
using one key and decrypting using the other one.

8

Key Archive

Objective

Define requirements for the Key Archive process to ensure
proper key archive according to security rules.

If cryptographic keys are not archived in line with the defined
requirements, this may result in e.g., the key leak and its
compromise and as a result data leak which can have severe
implications that could lead to information theft, unauthorized
access, and information disclosure.

Risk
Implication

Requirements

Choose

Classification

VERSION <1.0>

14

Key Management standard

8-1

8-2

8-3

8-4

8-5

8-6

The archival process must be secured and confidentiality must
be ensured to preserve the secrecy of information encrypted
with archived keys.

Expired keys must be archived to keep old data accessible as
long as the original encryption is supported.

Archival systems must follow the retention periods as per
relevant regulations and internal <organization name>’s
policies and standards.

(i.e., key

A key archive must contain keys and their associated
information
identifier,
distinguished name, ownership, key users, generation date,
expiration date, associated CA) for recovery beyond the
cryptoperiod of the keys.

information

like key

The key archive must continue to provide the appropriate
protections in line with requirements included in the National
Cryptographic Standards document for each key and any
other related information in the archive. The archive must
require a strong access-control mechanism to limit access to
only authorized organizations.

The archive must be maintained by <organization name> or
trusted third party.

9

Key Destruction

Objective

Define requirements for the Key Destruction process to ensure
proper key destruction according to security rules.

Risk
Implication

If cryptographic keys are not destructed in line with the defined
requirements, this may result in e.g., the possibility to decrypt
data by compromised key and data leak which can have
severe implications that could lead to information theft,
unauthorized access, and information disclosure.

Choose

Classification

VERSION <1.0>

15

Key Management standard

Requirements

9-1

9-2

9-3

Keys must be removed when key lifetime expires and there is
no need for it to be archived or stored via a secure deletion
process complied with the National Security Standards
document in order to minimize the risk of a compromise. The
key must be completely removed with all its instances and
make the recovery of that key impossible.

All copies of secret
(symmetric), public and private
(asymmetric) keys must be destroyed as soon as they are no
longer required (e.g., for archival or reconstruction activity) in
order to minimize the risk of a compromise.

Secret (symmetric), public and private (asymmetric) keys must
be destroyed in a manner that removes all traces and records
of the keys so that they cannot be recovered by either physical
or electronic means.

9-4

A compromised key must be revoked as soon as possible.

9-5

9-6

Public keys must be retained or destroyed depending on their
future needs associated with archiving,
restoring or
accountability.

Media storage systems storing keys must be sanitized before
disposal using a process compliant with NIST SP 800-88r1 or
NSA/CSS Storage Device Sanitization Manual.

10

Key Accounting

Objective

Define requirements for the Key Accounting process to ensure
proper key accounting according to security rules.

Risk
Implication

If cryptographic keys are not accounted in line with the defined
requirements, this may result in e.g. the impossibility of calling
to account the person responsible for key misuse or key
compromise which can have severe implications that could

Choose

Classification

VERSION <1.0>

16

Key Management standard

lead to information theft, unauthorized access, and information
disclosure.

Requirements

10-1

10-2

10-3

Use of asymmetric keys must be monitored by <organization
function> or nominated by
name>'s <cybersecurity
<cybersecurity function> key owners/administrator through
dedicated tools.

Key usage must be accounted for. Accountability process must
involve the identification of those that have access to, or
control of, cryptographic keys throughout their lifecycles.

Each <organization name>’s personal involved with key
their
informed about
management must be clearly
responsibilities and held accountable for fulfilling them.

11

Other Standards

Objective

The key management process must be securely configured
and performed and meet other associated standards.

Risk
Implication

Requirements

11-1

If <organization name> is not compliant with all applicable and
mandatory standards and requirements, it could be exposed
to severe threat rise specific for areas covers by below
mentioned standards.

The following standards must be implemented in relevance to
key management process:

● The National Cryptographic Standards.

● Cryptography standard.

Choose

Classification

VERSION <1.0>

17

Key Management standard

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

18
