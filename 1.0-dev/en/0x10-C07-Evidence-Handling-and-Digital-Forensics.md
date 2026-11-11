# C7 Evidence Handling & Digital Forensics

## Control Objective

This chapter addresses collecting, preserving, and handling evidence so that it remains complete, intact, and attributable, supporting sound conclusions and, where needed, legal or regulatory proceedings.

---

## C7.1 Collection & Preservation

Evidence must be captured before it is lost and in a way that allows its integrity to be demonstrated later.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **7.1.1** | **Verify that** the incident response plan instructs personnel not to wipe, reimage, or power off affected systems until the incident lead has confirmed that required evidence has been preserved. | 1 |
| **7.1.2** | **Verify that** relevant logs are preserved against normal retention expiry as soon as an investigation begins. | 2 |
| **7.1.3** | **Verify that** evidence collection procedures follow the order of volatility, capturing memory and other volatile data before non-volatile data. | 2 |
| **7.1.4** | **Verify that** a cryptographic hash of each evidence item is recorded at the time of acquisition. | 2 |
| **7.1.5** | **Verify that** analysis is performed on verified copies of evidence and that originals are preserved unaltered. | 2 |
| **7.1.6** | **Verify that** the record for each evidence item identifies who collected it, when, from which source, and with which tool and version. | 2 |
| **7.1.7** | **Verify that** forensic tools are validated before use, with the validation results retained. | 3 |

---

## C7.2 Chain of Custody & Storage

Custody of evidence must be continuously accounted for, and stored evidence must be protected, retained, and disposed of deliberately.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **7.2.1** | **Verify that** a chain of custody record documents every transfer of each evidence item, including the persons involved, the date and time, and the purpose. | 2 |
| **7.2.2** | **Verify that** access to stored evidence is restricted to authorized individuals and is logged. | 2 |
| **7.2.3** | **Verify that** evidence retention periods are defined and that evidence is securely disposed of when the period expires and no legal hold applies. | 2 |
| **7.2.4** | **Verify that** a legal hold procedure can suspend routine deletion of data relevant to an incident when litigation or regulatory action is anticipated. | 2 |
| **7.2.5** | **Verify that** evidence containing personal data is handled according to documented privacy requirements that limit access to what the investigation requires. | 2 |
| **7.2.6** | **Verify that** evidence transferred to external parties, such as law enforcement or forensic providers, is sent by a secure method and recorded in the chain of custody. | 2 |
| **7.2.7** | **Verify that** evidence is stored encrypted in a location isolated from the production environment. | 3 |

---

## C7.3 Forensic Analysis Quality

Forensic conclusions that may be relied on by courts, regulators, or executives must be reproducible and reviewed.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **7.3.1** | **Verify that** forensic analysis methods are documented in sufficient detail for another qualified analyst to reproduce the results. | 3 |
| **7.3.2** | **Verify that** forensic findings are reviewed by a second qualified analyst before being included in a final report. | 3 |
| **7.3.3** | **Verify that** documented criteria define when an external or accredited forensic provider must be engaged, such as when evidence is likely to be used in legal proceedings. | 3 |

---

## References

* [RFC 3227: Guidelines for Evidence Collection and Archiving](https://www.rfc-editor.org/rfc/rfc3227)
* [NIST SP 800-86: Guide to Integrating Forensic Techniques into Incident Response](https://csrc.nist.gov/pubs/sp/800/86/final)
* [NIST Cybersecurity Framework (CSF) 2.0: RS.AN-06, RS.AN-07](https://www.nist.gov/cyberframework)
* [ISO/IEC 27037:2012 Guidelines for identification, collection, acquisition and preservation of digital evidence](https://www.iso.org/standard/44381.html)
* [ISO/IEC 27041:2015 Guidance on assuring suitability and adequacy of incident investigative method](https://www.iso.org/standard/44405.html)
* [ISO/IEC 27042:2015 Guidelines for the analysis and interpretation of digital evidence](https://www.iso.org/standard/44406.html)
* [ISO/IEC 27001:2022 Annex A 5.28: Collection of evidence](https://www.iso.org/standard/27001)
* [NIST Computer Forensics Tool Testing Program (CFTT)](https://www.nist.gov/itl/ssd/software-quality-group/computer-forensics-tool-testing-program-cftt)
* [NIST SP 800-201: NIST Cloud Computing Forensic Reference Architecture](https://csrc.nist.gov/pubs/sp/800/201/final)
