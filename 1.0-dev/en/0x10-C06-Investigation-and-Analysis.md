# C6 Investigation & Analysis

## Control Objective

This chapter addresses establishing what happened, how, and how far it reached, with conclusions grounded in evidence, and without alerting the adversary or widening the compromise.

---

## C6.1 Scoping & Analysis

The full extent of an incident must be determined, because containment and notification decisions are only as good as the scoping behind them.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **6.1.1** | **Verify that** the systems, accounts, and data known or suspected to be affected are identified and recorded for each incident. | 1 |
| **6.1.2** | **Verify that** a timeline of adversary and responder activity is reconstructed from evidence, with the source of each entry identified. | 2 |
| **6.1.3** | **Verify that** the investigation seeks to identify the initial access vector and root cause and, where either cannot be determined, records the evidence gaps that prevented it. | 2 |
| **6.1.4** | **Verify that** indicators of compromise identified during an investigation are searched for across the whole environment and not only on initially affected systems. | 2 |
| **6.1.5** | **Verify that** the investigation assesses whether data was accessed or exfiltrated and records the evidential basis for the conclusion. | 2 |
| **6.1.6** | **Verify that** the investigation searches for persistence mechanisms and additional adversary access paths before eradication begins. | 2 |
| **6.1.7** | **Verify that** investigative findings are recorded with their supporting evidence and are distinguished from unconfirmed hypotheses. | 2 |
| **6.1.8** | **Verify that** observed adversary behaviors are mapped to a common framework such as MITRE ATT&CK to guide scoping toward related activity that has not yet been detected. | 3 |
| **6.1.9** | **Verify that** the organization has access to a malware analysis capability able to extract indicators and determine the functionality of malicious code. | 3 |

---

## C6.2 Threat Intelligence

Knowledge of adversary behavior must inform the investigation, and what the investigation learns must be captured for reuse.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **6.2.1** | **Verify that** responders have access to current threat intelligence relevant to the organization's sector and technology. | 2 |
| **6.2.2** | **Verify that** indicators and adversary techniques identified in incidents are recorded in a structured format that supports reuse and sharing. | 3 |

---

## C6.3 Operational Security

The investigation itself must not hand the adversary credentials, warning, or insight into what the responders know.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **6.3.1** | **Verify that** documented criteria define when responders must move incident communications to the out-of-band channel. | 2 |
| **6.3.2** | **Verify that** responders do not expose privileged credentials on systems suspected to be compromised, by using dedicated investigation accounts or access methods that do not leave reusable credentials. | 2 |
| **6.3.3** | **Verify that** samples and indicators from an active investigation are not submitted to public analysis services where submission would reveal the investigation to the adversary, unless approved by the incident lead. | 2 |
| **6.3.4** | **Verify that** knowledge of sensitive incidents, such as suspected insider activity, is limited to a documented list of informed individuals. | 3 |

---

## References

* [NIST SP 800-61 Rev. 3: Incident Response Recommendations and Considerations for Cybersecurity Risk Management](https://csrc.nist.gov/pubs/sp/800/61/r3/final)
* [NIST Cybersecurity Framework (CSF) 2.0: RS.AN Incident Analysis, DE.AE-07](https://www.nist.gov/cyberframework)
* [NIST SP 800-86: Guide to Integrating Forensic Techniques into Incident Response](https://csrc.nist.gov/pubs/sp/800/86/final)
* [NIST SP 800-150: Guide to Cyber Threat Information Sharing](https://csrc.nist.gov/pubs/sp/800/150/final)
* [CISA: Federal Government Cybersecurity Incident and Vulnerability Response Playbooks](https://www.cisa.gov/resources-tools/resources/federal-government-cybersecurity-incident-and-vulnerability-response-playbooks)
* [ISO/IEC 27035-3:2020 Information security incident management, Part 3: Guidelines for ICT incident response operations](https://www.iso.org/standard/74033.html)
* [ISO/IEC 27042:2015 Guidelines for the analysis and interpretation of digital evidence](https://www.iso.org/standard/44406.html)
* [MITRE ATT&CK](https://attack.mitre.org/)
* [OASIS STIX and TAXII](https://oasis-open.github.io/cti-documentation/)
