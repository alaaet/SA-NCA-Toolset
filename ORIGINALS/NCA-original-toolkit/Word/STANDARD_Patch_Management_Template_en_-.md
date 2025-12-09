This is a guidance box. Remove all guidance boxes after filling out the template. Items highlighted in turquoise should be edited appropriately. Items highlighted in green are examples and should be removed. After all edits have been made, all highlights should be cleared.

Insert organization logo by clicking on the placeholder to the left.

Patch Management Standard Template

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

[Purpose 4](#_Toc110846035)

[Scope 4](#_Toc110846036)

[Standards 4](#_Toc110846037)

[Roles and Responsibilities 14](#_Toc110846038)

[Update and Review 14](#_Toc110846039)

[Compliance 14](#_Toc110846040)

# [Purpose](#_heading=h.30j0zll)

This standard aims to define the cybersecurity requirements related to the patch management for <organization name>’s technology solutions and assets. The ability of <organization name> to manage patches in accordance with this standard will assist in reducing the cybersecurity risks, in ensuring protection from related internal and external threats, and in preservation of the availability, integrity and confidentiality of <organization name>’s assets and information.

The requirements in this standard are aligned with the cybersecurity requirements issued by the National Cybersecurity Authority (NCA), including but not limited to ECC-1:2018, DCC-1:2022, CSCC-1:2019 and CCC-1:2020, in addition to other related cybersecurity legal and regulatory requirements.

# [Scope](#_heading=h.1fob9te)

This standard covers all <organization name>’s information and technology assets and applies to all personnel (employees and contractors) in <organization name>.

# Standards

|  |  |  |
| --- | --- | --- |
| 1 | Plan risk response | |
| Objective | The objective of this section is to ensure that the organization is managing the patching in accordance with the assessment of the incoming cybersecurity risks and vulnerabilities. | |
| Risk Implication | Without patching is being done in consequence of the <organization name>’s overall risk and vulnerability management processes (e.g., only being done as an operational duty), the chance of letting potential vulnerabilities unthreated is higher. | |
| Requirements | | |
|  | <organization name> must consider every new software vulnerability affecting <organization name>’s assets, including applications, operating systems, and firmware. | |
|  | <organization name> must avoid the cybersecurity risk of unavailable or not introduced patches, ensuring that the likelihood of risk is reduced by eliminating the attack surface:   * uninstalling the vulnerable software; * disconnecting vulnerable asset from network; * decommissioning devices with the vulnerabilities; * disabling computing capabilities in devices that can function without them. | |
|  | <organization name> must mitigate cybersecurity risks by performing patches to eliminate the vulnerabilities, e.g.:   * patching the vulnerable software; * disabling a vulnerable feature; or * upgrading to a newer software version without the vulnerabilities. | |
|  | <organization name> must deploy additional security controls to reduce vulnerability exploitation, e.g.:   * using firewalls and network segmentation to isolate vulnerable devices, thus reducing the attack surface. | |
|  | <organization name> must define at least the following software vulnerability risk response scenarios they need to be prepared to handle:   * Routine patching (standard procedure for patches that are on a regular release cycle) * Emergency patching (to address patching emergencies in a crisis situation) * Emergency workaround (to temporarily mitigate vulnerabilities before a patch is available) * Unpatchable assets (isolation or other methods to mitigate the risk of systems that cannot be easily patched) | |
|  | <organization name> must define maintenance groups and develop maintenance plan for each maintenance group for each applicable risk response scenario, e.g.:   * <Maintenance Plans for Scenario 1, Routine Patching>   + <organization name> must adopt phased deployments for routine patching in which a small subset of the assets to be patched receive the patch first. * <Maintenance Plans for Scenario 2, Emergency Patching>   + <organization name> must use the same general approach for emergency patching as for routine patching, except with a highly accelerated schedule. * <Maintenance Plans for Scenario 3, Emergency Workarounds>   + <organization name> must plan for the quick implementation of multiple types of emergency workarounds to protect vulnerable assets. * <Maintenance Plans for Scenario 4, Un-patchable Assets>   + <organization name> must plan to implement multiple types of long-term risk mitigation methods besides patching to protect vulnerable assets. | |
| 2 | Execute risk response | |
| Objective | The objective of this section is to ensure that patching is being done by following logically structured risk response execution. | |
| Risk Implication | Without a well-designed and structured risk response execution, the assessment of risks can fail on several occasions, leaving vulnerabilities unpatched, or untreated. | |
| Requirements | | |
|  | The execution of risk response must be composed of the following steps:   * Prepare risk response * Implement risk response * Verify risk response * Continuously monitor risk response | |
|  | Preparing risk response must cover the following activities:   * Acquiring patches * Validating patches * Testing patches | |
|  | Implementing risk response must cover the following activities:   * Applying change management processes * Determine method of installing * Prioritize and schedule installing patches | |
|  | Verifying risk response must cover the following activities:   * Confirmation of installed patch * Checking the effectiveness of patching   + Vulnerability scan   + Using metrics (KPI) | |
|  | Continuous monitoring of risk response must cover the following activities:   * Making sure no one uninstalls patches * Making sure, that an older version of the patched software has not been restored * Periodic vulnerability assessment for installed patches | |
| 3 | Prepare risk response | |
| Objective | The objective of this section is acquiring, validating, and testing patches for the vulnerable software or deploying additional security controls to safeguard the vulnerable software. | |
| Risk Implication | Validation: The patch could have been acquired from a rogue source or tampered with in transit or after acquisition.  Testing: Operational risk by identifying problems with a patch before placing it into production. | |
| Requirements | | |
|  | Patches must be acquired only from legitimate sources. This includes acquiring it though secure sites provided by the vendor/manufacturer or developing it internally. | |
|  | Available patches must be monitored by the asset owner and be installed if it is technically feasible, in accordance with the patched asset’s criticality level, and after the patch has been tested. | |
|  | File integrity must be confirmed before the patch is being tested or installed, using hashing algorithms if it is technically feasible (e.g., network device firmware). | |
|  | Virus scan must always be performed on the downloaded patches, to avoid the possibility of a malware being installed. | |
|  | Patches must be tested prior deployment or live implementation. | |
|  | In case of software patches, a separate test environment must be used in order to avoid virus infection and software compatibility issues. | |
|  | Upcoming issues must be documented and resolved in the testing phase before live implementation of the patches. | |
|  | Processes with an option of rollback must be implemented in case there is an unforeseen incompatibility, so systems can be restored to their pre-patched state. | |
|  | Backup and restore functions must be implemented in case there is an unforeseen incompatibility, so system availability can be ensured in such cases. | |
| 4 | Implement risk response | |
| Objective | The objective of this section is to ensure the safety and continuity of the information system through distributing and installing patches and changing asset configurations and state. | |
| Risk Implication | Change management: Applying patches without the proper change management process can lead to the halt of business processes, or even data loss.  Prioritize and schedule: Without the prioritization of patches there is a chance that some of the critical or high severity patches are not being installed on an important asset. | |
| Requirements | | |
|  | Patch deployments must be scheduled as part of the <organization name>’s change management activity. | |
|  | <organization name> must implement only those changes in the <organization name>’s live environment that has been approved through the <organization name>’s change management procedure. | |
|  | The application procedure of a patch being installed must be documented in order to be traceable (e.g., approvement and testing is already done) | |
|  | The following installation methods must be used to install patches:   * Distributing patches through a centralized solution   + Using automatic installation   + Scheduling the installation of patches   + Installing it manually (forced installation) * Installing patches as a single installation | |
|  | Patches must be prioritized in order to install higher priority patches first, in accordance with the results of <organization name>’s risk assessment. | |
|  | Patch prioritization must be based on asset criticality, in accordance with the vulnerability management policy and standard.  <organization name> must introduce a Vulnerability Mitigation Time Summary Matrix (Table 1 appendix) and provide mitigation metrics based on   * relative importance of the assets (low, moderate, or high) according to the classification of <organization name> and the legislative and regulatory requirements issued; * vulnerabilities (low, medium, high, or critical), according to the classification of <organization name> and the legislative and regulatory requirements issued. | |
| 5 | Verify and monitor risk response | |
| Objective | The objective of this section is to ensure that the implementation has been completed successfully. For patching, this means confirming that the patch is installed and has taken effect. For deploying additional security controls, ensure they are functioning as intended. | |
| Risk Implication | In case the installation of patches is not monitored or confirmed, there is a risk that an information asset will be still vulnerable and open for attack. | |
| Requirements | | |
|  | The effectiveness of the patching must be checked in order to verify its success. The following techniques must be used for verification:   * Performing vulnerability scan on the patched asset * Using metrics (Key Performance Indicators) provided by the information systems being used to install patches (WSUS, HPSA, SCCM) | |
|  | The risk response must be continuously monitored, taking into consideration the following:   * Patches must be installed only by appropriate personnel (IT operations). Any other means of installing patches must be disabled by the system administrator. * <organization name> must ensure no one uninstalls the patch, deactivates the additional security controls, lets the cybersecurity insurance lapse, or restarts the decommissioned device. | |
| 6 | Other Standards | |
| Objective | Patch Management must be securely deployed and used appropriately when required. | |
| Risk Implication | If <organization name> is not compliant with all of standards and requirements, it could be exposed to severe threat rise. | |
| Requirements | | |
|  | | The following standards must be implemented in relevance to Patch management:  1- Vulnerability Management Policy  2- Vulnerability Management Standard  3- Cybersecurity Risk Management Policy | |

Table 1 – Vulnerability Mitigation Time Summary Matrix <with data example>

|  |  |  |  |
| --- | --- | --- | --- |
| Vulnerability importance | Asset importance | | |
| Low | Moderate | High |
| Low | By deadline: 64.7 %  Average time: 80.4 days  Median time: 75.2 days | By deadline: 72.4 %  Average time: 34.7 days  Median time: 33.7 days | By deadline: 85.0 %  Average time: 14.6 days  Median time: 8.1 days |
| Medium | By deadline: 66.5 %  Average time: 75.1 days  Median time: 70.7 days | By deadline: 68.7 %  Average time: 33.2 days  Median time: 31.6 days | By deadline: 71.4 %  Average time: 12.9 days  Median time: 10.5 days |
| High | By deadline: 68.6 %  Average time: 62.1 days  Median time: 58.0 days | By deadline: 78.8 %  Average time: 26.8 days  Median time: 22.1 days | By deadline: 85.5 %  Average time: 8.8 days  Median time: 8.1 days |
| Critical | By deadline: 81.4 %  Average time: 44.4 days  Median time: 41.3 days | By deadline: 92.3 %  Average time: 21.2 days  Median time: 23.9 days | By deadline: 95.2 %  Average time: 5.2 days  Median time: 5.1 days |

The metrics in each cell reflect the percentage of assets that were patched by the corresponding maintenance plans’ deadlines, as well as the average (mean) time and median time for patching.

# [Roles and Responsibilities](#_heading=h.3dy6vkm)

1. **Standard Owner:** <head of the cybersecurity function>
2. **Standard Review and Update:** <cybersecurity function>
3. **Standard Implementation and Execution:** <information technology function>
4. **Standard Compliance Measurement:** <cybersecurity function>

# [Update](#_heading=h.2et92p0) and Review

<cybersecurity function> must review the standard at least once a year or in case any changes happen to the policy or the regulatory procedures in <organization name> or the relevant regulatory requirements.

# [Compliance](#_heading=h.1t3h5sf)

1. The <head of the cybersecurity function> will ensure compliance of <organization name> with this standard on a regular basis.
2. All personnel at <organization name> must comply with this standard.
3. Any violation of this standard may be subject to disciplinary action according to <organization name>’s procedures.
