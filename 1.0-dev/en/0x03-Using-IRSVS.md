# Using the IRSVS

The Incident Response Security Verification Standard (IRSVS) defines verification requirements for an organization's cybersecurity incident response capability.

The IRSVS is intended for anyone building or evaluating that capability, including incident response and security operations teams, security leaders, IT and cloud operations, legal and privacy counsel, internal and external auditors, insurers, and customers performing supplier due diligence. This chapter introduces the structure and use of the IRSVS, including its verification levels, how requirements are assessed, and how it is positioned alongside other standards.

## How to Read This Standard

### Chapter Structure

Each of the 15 requirement chapters follows the same format:

* **Control Objective.** A brief statement of the goal for the chapter.
* **Sections.** Requirements are grouped into related sections, each with a short description of its purpose.
* **Requirement Tables.** Individual requirements are presented in tables with the following columns:

| Column | Meaning |
| --- | --- |
| **#** | Unique requirement identifier (e.g., 1.1.1, 9.3.2). |
| **Description** | The requirement text, always beginning with "Verify that" to emphasize testability. |
| **Level** | The verification level (1, 2, or 3) indicating the depth of assurance required; see the verification levels below. |

* **References.** The authoritative sources from which the chapter's requirements were derived.

### Chapters

The chapters follow the order in which a capability is built and then used:

| Phase | Chapters |
| --- | --- |
| Govern and prepare | C1 Governance, Policy & Authority; C2 Team, Roles & Responder Readiness; C3 Visibility & Forensic Readiness |
| Detect and manage | C4 Detection, Reporting & Intake; C5 Triage, Classification & Incident Management |
| Respond | C6 Investigation & Analysis; C7 Evidence Handling & Digital Forensics; C8 Containment; C9 Eradication & Recovery; C10 Communication, Notification & Information Sharing |
| Extend | C11 Third Parties, Cloud & Supply Chain; C12 Scenario Playbooks; C13 Automation & AI-Assisted Response |
| Prove and improve | C14 Exercises, Testing & Validation; C15 Post-Incident Activity & Continuous Improvement |

### Appendices

Four appendices support the core requirements:

* **Appendix A (Glossary)** defines key terms and acronyms used throughout the standard.
* **Appendix B (References)** catalogues the authoritative sources IRSVS draws on and describes how each is used.
* **Appendix C (Standards Mapping)** maps each IRSVS section to related elements of NIST CSF 2.0, NIST SP 800-53 Rev. 5, ISO/IEC 27001:2022, the CIS Controls, and PCI DSS.
* **Appendix D (Notification Timelines)** is an informative summary of commonly encountered legal and regulatory incident notification deadlines.

## Incident Response Security Verification Levels

The IRSVS defines three ascending levels of verification. Each level includes all requirements of the levels below it.

Organizations may begin at Level 1 and adopt higher levels as their maturity and threat exposure increase. An organization should select a target level based on its risk profile, the sensitivity of the data and services it is responsible for, and the adversaries it expects to face.

| Level | Description | When to use |
| :---: | --- | --- |
| **1** | A foundational capability. Someone is accountable, incidents can be reported and recognized, basic containment and recovery work, and legal obligations are known. | All organizations that operate information systems, including small organizations and those that outsource most of their IT and security. |
| **2** | A documented, repeatable, and exercised capability, with the visibility and evidence handling needed to investigate incidents properly and to meet notification obligations with confidence. | Organizations that handle sensitive or regulated data, deliver customer-facing or business-critical services, or maintain a security function. Most organizations should target at least Level 2. |
| **3** | A high-assurance capability validated against sophisticated adversaries, resilient to compromise of core infrastructure, and independently tested. | Critical infrastructure, high-value targets, heavily regulated sectors, and organizations that expect targeted attacks. |

### Definition of the Levels

#### Level 1 requirements

Level 1 contains the requirements whose absence most often turns a manageable incident into a serious one. They address the most common failure modes: nobody is in charge, nobody can be reached, the plan cannot be found, the basic logs do not exist, the backups are destroyed along with production, and nobody knows who must be notified. Level 1 requirements are achievable by a small organization without a dedicated security team, including through an external provider.

#### Level 2 requirements

Level 2 turns incident response into a managed discipline. It adds defined severity, declaration, and escalation criteria, centralized and protected logging, sound evidence handling, scenario playbooks, controlled communications, supplier and cloud readiness, and regular exercises with tracked outcomes. Level 2 assumes the organization has people, internal or contracted, whose role includes incident response.

#### Level 3 requirements

Level 3 addresses determined, capable adversaries and the hardest situations: compromise of identity infrastructure, coordinated eviction of an established intruder, evidence that must stand up in legal proceedings, and response at all hours. It requires that the capability be validated by adversary emulation and independent assessment, and that the response infrastructure itself survive compromise of the environment it protects.

## Assessing Against the IRSVS

### Evidence

Every requirement is written so that an assessor can determine whether it is met. Three kinds of evidence are used:

| Evidence | Description | Examples |
| --- | --- | --- |
| **Inspection** | Review of documents and configuration. | The incident response plan, the contact list, the notification register, supplier contracts, log retention settings. |
| **Demonstration** | The capability is performed for or by the assessor. | Isolating a test endpoint, revoking a test account's sessions, querying the central log store, restoring a system from backup. |
| **Records** | Evidence that the capability has been used. | Incident records, exercise after-action reports, chain of custody forms, post-incident reviews, corrective action tracking. |

A document shows intent. A demonstration or a record shows capability. Where a requirement describes something responders must be able to do, assessors should prefer demonstration or records over inspection. Where a requirement describes something that happens during incidents, assessors should sample real incident records, and may use exercise records where the organization has had no qualifying incident in the assessment period.

### Applicability

Some requirements apply only where a stated condition holds, for example "where the organization operates operational technology" or "where security monitoring or response is outsourced". Where the condition does not hold, the requirement is not applicable. Any other requirement that an organization considers not applicable should be recorded with a justification.

### Outsourced Capabilities

Many organizations rely on managed detection and response providers, incident response retainers, cloud providers, and outside counsel. A requirement may be met by an external party. The organization remains accountable for it and must be able to produce the evidence, whether from its own records or from the provider. Requirements about decision authority, notification obligations, and governance cannot be delegated.

### Reporting Results

An assessment against the IRSVS should state the version assessed against, the target level, the scope of environments and legal entities covered, the result for each requirement (met, not met, or not applicable), and the evidence relied on. An organization meets a level when it meets every applicable requirement at that level and all levels below it.

## How to Reference IRSVS Requirements

Each requirement has an identifier in the format `C<chapter>.<section>.<requirement>`, where each element is a number, for example `C8.2.3`.

* The `C<chapter>` value corresponds to the chapter from which the requirement comes; for example, all `C8.#.#` requirements are from the Containment chapter.
* The `<section>` value corresponds to the section within that chapter; for example, all `C8.2.#` requirements are in the Containment Capabilities section.
* The `<requirement>` value identifies the specific requirement within the chapter and section.

Since identifiers may change between versions of the standard, other documents, reports, and tools should use the format `v<version>-C<chapter>.<section>.<requirement>`, for example `v1.0-C8.2.3`. The `v` preceding the version number is always lowercase.

## Scope of the IRSVS

IRSVS covers the capability to respond to cybersecurity incidents: the governance, people, data, tooling, procedures, and proof that determine how an incident will go. It assumes that the organization's preventive security controls, general IT operations, and business continuity arrangements are addressed by other standards, and it adds the incident response layer.

The following are intentionally out of scope and are not duplicated in IRSVS chapters:

* **Incident response process models.** How to structure the incident response life cycle is defined by [NIST SP 800-61 Rev. 3](https://csrc.nist.gov/pubs/sp/800/61/r3/final) and the [ISO/IEC 27035](https://www.iso.org/standard/78973.html) series. IRSVS is compatible with any of them and prescribes none.
* **Preventive security controls.** Access control, hardening, patching, secure development, and network security are defined by the [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework), [NIST SP 800-53](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final), [ISO/IEC 27001](https://www.iso.org/standard/27001), the [CIS Controls](https://www.cisecurity.org/controls), and the [OWASP ASVS](https://owasp.org/www-project-application-security-verification-standard/). IRSVS includes logging and backup requirements only to the extent that investigation and recovery depend on them.
* **Detection engineering and security operations.** How to build detections, operate a SOC, or run a threat intelligence program is out of scope. IRSVS covers the handover from detection to response and the detection assurance that response depends on.
* **Business continuity and disaster recovery.** Continuity planning for non-security disruptions is defined by [ISO 22301](https://www.iso.org/standard/75106.html) and [NIST SP 800-34](https://csrc.nist.gov/pubs/sp/800/34/r1/upd1/final). IRSVS covers the interface with those plans and the recovery concerns specific to an adversary being present.
* **Product vulnerability management.** Coordinated vulnerability disclosure and product security incident response are defined by [ISO/IEC 29147](https://www.iso.org/standard/72311.html), [ISO/IEC 30111](https://www.iso.org/standard/69725.html), and the [FIRST PSIRT Services Framework](https://www.first.org/standards/frameworks/psirts/psirt_services_framework_v1.1). IRSVS covers intake of external reports and coordination between the two functions.
* **CSIRT organizational maturity.** The maturity of a CSIRT as an organization is assessed by [SIM3](https://opencsirt.org/csirt-maturity/sim3-and-references/). IRSVS verifies capability outcomes and can be used alongside it.
* **AI system security.** Security controls for AI systems are defined by the [OWASP AISVS](https://github.com/OWASP/AISVS). IRSVS covers response to incidents involving AI systems and the safe use of AI in the response itself.
* **Legal advice.** IRSVS requires that an organization identify and meet its notification obligations. It does not state what those obligations are for any particular organization. Appendix D is informative only.
* **Vendor-specific guidance.** IRSVS is vendor-neutral. It specifies what to verify, not which product to use.

## Cross-References Inside IRSVS

IRSVS chapters are organized by control family, so responding well to a given kind of incident draws on several chapters together. For example, readiness for ransomware combines requirements from C1 (decision rights for extortion demands), C3 (logs that survive the attack), C8 (isolation capabilities), C9 (backups out of the adversary's reach and restoration validation), C10 (notification), C12 (the ransomware playbook), and C14 (restore testing).

Capability chapters state that something must exist. C14 states that it must be tested. When assessing a capability, read the requirement that establishes it together with the C14 requirement that validates it.

## Relationship to Other Standards

| Standard | Focus | IRSVS relationship |
| --- | --- | --- |
| NIST SP 800-61 Rev. 3 | Incident response recommendations and considerations, organized by CSF 2.0 function | IRSVS expresses these as verifiable requirements with assurance levels |
| NIST Cybersecurity Framework 2.0 | Cybersecurity outcomes across Govern, Identify, Protect, Detect, Respond, Recover | IRSVS provides testable depth beneath the incident-related outcomes; see Appendix C |
| ISO/IEC 27035 series | Incident management principles, process, planning, and operations | IRSVS verifies that the outputs of such a process exist and work |
| ISO/IEC 27001:2022 | Information security management system, including incident controls in Annex A | IRSVS provides detailed verification beneath Annex A 5.24 to 5.28 and 6.8 |
| NIST SP 800-53 Rev. 5 | Security and privacy control catalogue, including the IR family | IRSVS is narrower and more specific on incident response evidence |
| CIS Controls | Prioritized safeguards, including Control 17 | IRSVS extends Control 17 into a full verification standard |
| FIRST CSIRT Services Framework | The services a CSIRT may provide | IRSVS verifies the organizational capability those services deliver |
| SIM3 | CSIRT maturity | Complementary; SIM3 scores maturity, IRSVS verifies specific requirements |
| OWASP ASVS and AISVS | Verification of applications and AI systems | IRSVS follows the same model and applies it to incident response |
