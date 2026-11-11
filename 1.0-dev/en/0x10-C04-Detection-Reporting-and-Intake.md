# C4 Detection, Reporting & Intake

## Control Objective

This chapter addresses ensuring that suspected incidents from any source, whether automated detection, the workforce, customers, suppliers, researchers, or authorities, reach the incident response function quickly and reliably.

IRSVS does not define how to build a detection program. It covers the points where detection hands over to response, and the detection assurance that a high-assurance response capability depends on.

---

## C4.1 Internal Reporting

Anyone in the organization who notices something wrong must know how to report it and must feel safe doing so.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **4.1.1** | **Verify that** a documented mechanism for the workforce to report suspected incidents is communicated to all workforce members, covering what to report, how, and to whom. | 1 |
| **4.1.2** | **Verify that** at least one incident reporting channel remains usable when the reporter's device or account is suspected to be compromised. | 1 |
| **4.1.3** | **Verify that** IT service desk personnel have documented criteria for recognizing potential security incidents and a procedure for escalating them. | 2 |
| **4.1.4** | **Verify that** workforce reports of suspected incidents are acknowledged within a defined time. | 2 |
| **4.1.5** | **Verify that** policy protects workforce members who report suspected incidents in good faith, including their own mistakes, from retaliation. | 2 |

---

## C4.2 External Reporting & Intake

Many incidents are first noticed by someone outside the organization, so external reports must have somewhere to go and someone watching.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **4.2.1** | **Verify that** the organization publishes a contact point for external parties to report security issues, for example through a security.txt file. | 2 |
| **4.2.2** | **Verify that** reports received through external reporting channels are reviewed within a defined time. | 2 |
| **4.2.3** | **Verify that** customers have a documented channel to report suspected security incidents affecting their accounts or data. | 2 |
| **4.2.4** | **Verify that** a procedure exists for receiving incident notifications from law enforcement, CSIRTs, and regulators, including verifying the notifier's authenticity. | 2 |
| **4.2.5** | **Verify that** external sources indicating compromise, such as leaked credentials and data leak sites, are monitored and feed incident intake. | 3 |

---

## C4.3 Alert Handling & Escalation

Alerts must reach someone responsible, be reviewed in time, and be escalated to incident response on consistent criteria.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **4.3.1** | **Verify that** alerts from deployed security tools are routed to a monitored destination with assigned responsibility for review. | 1 |
| **4.3.2** | **Verify that** maximum times for initial review of alerts are defined for each alert severity. | 2 |
| **4.3.3** | **Verify that** documented criteria define when an alert or event is escalated to the incident response process. | 2 |
| **4.3.4** | **Verify that** alerts are enriched with asset owner, asset criticality, and identity context at or before triage. | 2 |
| **4.3.5** | **Verify that** changes that suppress, disable, or tune alerts are recorded and reviewed. | 2 |
| **4.3.6** | **Verify that** detection coverage is mapped to an adversary behavior framework such as MITRE ATT&CK, with gaps prioritized for remediation. | 3 |
| **4.3.7** | **Verify that** proactive threat hunting is conducted at a defined frequency, with findings fed into detection and incident response. | 3 |

---

## References

* [NIST SP 800-61 Rev. 3: Incident Response Recommendations and Considerations for Cybersecurity Risk Management](https://csrc.nist.gov/pubs/sp/800/61/r3/final)
* [NIST Cybersecurity Framework (CSF) 2.0: DE.AE Adverse Event Analysis, RS.MA-02](https://www.nist.gov/cyberframework)
* [NIST SP 800-53 Rev. 5: IR-6 Incident Reporting, SI-4 System Monitoring](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final)
* [CIS Critical Security Controls: Safeguards 17.3 and 14.6](https://www.cisecurity.org/controls/incident-response-management)
* [RFC 9116: A File Format to Aid in Security Vulnerability Disclosure (security.txt)](https://www.rfc-editor.org/rfc/rfc9116)
* [ISO/IEC 29147:2018 Vulnerability disclosure](https://www.iso.org/standard/72311.html)
* [FIRST CSIRT Services Framework v2.1: Information Security Event Management](https://www.first.org/standards/frameworks/csirts/csirt_services_framework_v2.1)
* [MITRE ATT&CK](https://attack.mitre.org/)
* [UK NCSC: Incident Management](https://www.ncsc.gov.uk/collection/incident-management)
