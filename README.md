# Incident Response Security Verification Standard (IRSVS)

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: https://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-blue.svg

## What is IRSVS?

The **Incident Response Security Verification Standard (IRSVS)** is a catalogue of testable requirements for an organization's cybersecurity incident response capability. It gives incident responders, security leaders, auditors, insurers, and customers a structured way to specify and verify how well an organization can prepare for, detect, contain, investigate, recover from, and learn from security incidents.

IRSVS is modeled after the [OWASP Application Security Verification Standard (ASVS)](https://owasp.org/www-project-application-security-verification-standard/) and the [OWASP Artificial Intelligence Security Verification Standard (AISVS)](https://github.com/OWASP/AISVS) and follows the same philosophy: every requirement should be **verifiable, testable, and implementable**.

Most organizations have an incident response plan. IRSVS asks whether it will work: whether the plan can be reached when the network is down, whether the logs exist and go back far enough, whether the backups are out of the intruder's reach, whether anyone has authority to pull the plug, and whether any of it has been tested.

> **Status: draft.** Version 1.0 is in active development. Requirement text, levels, and identifiers may change before release. IRSVS is an independent project and is not an OWASP project.

---

### Grounded in authoritative sources

IRSVS does not invent a new incident response process. It converts what established guidance already recommends into requirements an assessor can check. Each chapter cites its sources, and [Appendix B](1.0-dev/en/0x91-Appendix-B_References.md) catalogues them. The primary sources are:

* [NIST SP 800-61 Rev. 3](https://csrc.nist.gov/pubs/sp/800/61/r3/final), Incident Response Recommendations and Considerations for Cybersecurity Risk Management
* [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework)
* [ISO/IEC 27035](https://www.iso.org/standard/78973.html), Information security incident management (Parts 1 to 4)
* [FIRST CSIRT Services Framework](https://www.first.org/standards/frameworks/csirts/csirt_services_framework_v2.1) and [Traffic Light Protocol](https://www.first.org/tlp/)
* [CISA Cybersecurity Incident and Vulnerability Response Playbooks](https://www.cisa.gov/resources-tools/resources/federal-government-cybersecurity-incident-and-vulnerability-response-playbooks)
* [NIST SP 800-86](https://csrc.nist.gov/pubs/sp/800/86/final), [RFC 3227](https://www.rfc-editor.org/rfc/rfc3227), and ISO/IEC 27037 for forensics and evidence handling
* [NIST SP 800-184](https://csrc.nist.gov/pubs/sp/800/184/final) for recovery and [NIST SP 800-84](https://csrc.nist.gov/pubs/sp/800/84/final) for exercises
* [CIS Controls](https://www.cisecurity.org/controls), [NIST SP 800-53 Rev. 5](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final), ISO/IEC 27001:2022, and PCI DSS for control mappings

### What IRSVS is NOT

* **Not an incident response process.** How to structure the response life cycle is covered by NIST SP 800-61 and ISO/IEC 27035. IRSVS works with any of them.
* **Not a maturity model.** IRSVS requirements are met or not met. CSIRT maturity is assessed by [SIM3](https://opencsirt.org/csirt-maturity/sim3-and-references/).
* **Not a playbook library.** IRSVS verifies that playbooks exist and contain the decisions that matter. It does not supply their content.
* **Not legal advice.** IRSVS requires an organization to know and meet its notification obligations. It does not say what they are.
* **Not a tool recommendation list.** IRSVS is vendor-neutral.

### How IRSVS complements other standards

| Standard | Focus | IRSVS relationship |
| --- | --- | --- |
| NIST SP 800-61 Rev. 3 | Incident response recommendations and considerations | IRSVS expresses these as verifiable requirements with assurance levels |
| NIST CSF 2.0 | Cybersecurity outcomes | IRSVS provides testable depth beneath the incident-related outcomes |
| ISO/IEC 27035 | Incident management process | IRSVS verifies that the outputs of the process exist and work |
| ISO/IEC 27001:2022 | Information security management system | IRSVS provides detailed verification beneath Annex A 5.24 to 5.28 |
| CIS Controls | Prioritized safeguards | IRSVS extends Control 17 into a full verification standard |
| OWASP ASVS and AISVS | Verification of applications and AI systems | IRSVS applies the same model to incident response |

---

## Current Development

**IRSVS 1.0 is the active development version.** There is no stable release yet. Contributions target [1.0-dev](1.0-dev/en).

---

## Verification Levels

Each IRSVS requirement is assigned a verification level (1, 2, or 3):

| Level | Description | When to use |
| :---: | --- | --- |
| **1** | A foundational capability. Someone is accountable, incidents can be reported and recognized, basic containment and recovery work, and legal obligations are known. | All organizations, including small organizations and those that outsource most of their IT and security. |
| **2** | A documented, repeatable, and exercised capability with the visibility and evidence handling needed to investigate incidents properly. | Organizations that handle sensitive or regulated data, deliver customer-facing or business-critical services, or maintain a security function. |
| **3** | A high-assurance capability validated against sophisticated adversaries, resilient to compromise of core infrastructure, and independently tested. | Critical infrastructure, high-value targets, heavily regulated sectors, and organizations that expect targeted attacks. |

Organizations should select a target level based on their risk profile. Most should aim for at least Level 2.

## How to use IRSVS

* **To build a program.** Use Level 1 as a starting checklist and the higher levels as a roadmap.
* **To assess a program.** Use the requirements as audit criteria, preferring demonstration and incident records over documents.
* **To prepare for an exercise.** Pick the requirements a scenario should prove, and write the after-action report against them.
* **For procurement and due diligence.** Reference specific requirements when evaluating managed security providers, critical suppliers, or acquisition targets.
* **For insurance and assurance.** Use the levels as a common basis for describing incident readiness.

## Requirement Chapters

1. [Governance, Policy & Authority](1.0-dev/en/0x10-C01-Governance-Policy-and-Authority.md)
2. [Team, Roles & Responder Readiness](1.0-dev/en/0x10-C02-Team-Roles-and-Responder-Readiness.md)
3. [Visibility & Forensic Readiness](1.0-dev/en/0x10-C03-Visibility-and-Forensic-Readiness.md)
4. [Detection, Reporting & Intake](1.0-dev/en/0x10-C04-Detection-Reporting-and-Intake.md)
5. [Triage, Classification & Incident Management](1.0-dev/en/0x10-C05-Triage-Classification-and-Incident-Management.md)
6. [Investigation & Analysis](1.0-dev/en/0x10-C06-Investigation-and-Analysis.md)
7. [Evidence Handling & Digital Forensics](1.0-dev/en/0x10-C07-Evidence-Handling-and-Digital-Forensics.md)
8. [Containment](1.0-dev/en/0x10-C08-Containment.md)
9. [Eradication & Recovery](1.0-dev/en/0x10-C09-Eradication-and-Recovery.md)
10. [Communication, Notification & Information Sharing](1.0-dev/en/0x10-C10-Communication-Notification-and-Information-Sharing.md)
11. [Third Parties, Cloud & Supply Chain](1.0-dev/en/0x10-C11-Third-Parties-Cloud-and-Supply-Chain.md)
12. [Scenario Playbooks](1.0-dev/en/0x10-C12-Scenario-Playbooks.md)
13. [Automation & AI-Assisted Response](1.0-dev/en/0x10-C13-Automation-and-AI-Assisted-Response.md)
14. [Exercises, Testing & Validation](1.0-dev/en/0x10-C14-Exercises-Testing-and-Validation.md)
15. [Post-Incident Activity & Continuous Improvement](1.0-dev/en/0x10-C15-Post-Incident-Activity-and-Continuous-Improvement.md)

Front matter: [Frontispiece](1.0-dev/en/0x01-Frontispiece.md), [Preface](1.0-dev/en/0x02-Preface.md), [Using the IRSVS](1.0-dev/en/0x03-Using-IRSVS.md)

## Appendices

* [Appendix A: Glossary](1.0-dev/en/0x90-Appendix-A_Glossary.md)
* [Appendix B: References](1.0-dev/en/0x91-Appendix-B_References.md)
* [Appendix C: Standards Mapping](1.0-dev/en/0x92-Appendix-C_Standards_Mapping.md)
* [Appendix D: Notification Timelines](1.0-dev/en/0x93-Appendix-D_Notification_Timelines.md)

---

## How to Reference IRSVS Requirements

Each requirement has an identifier in the format `C<chapter>.<section>.<requirement>`, where each element is a number, for example `C8.2.3`.

* The `C<chapter>` value corresponds to the chapter from which the requirement comes; for example, all `C8.#.#` requirements are from the Containment chapter.
* The `<section>` value corresponds to the section within that chapter; for example, all `C8.2.#` requirements are in the Containment Capabilities section.
* The `<requirement>` value identifies the specific requirement within the chapter and section; for example, `C8.2.3`, which in the current draft is:

> Verify that responders can remotely isolate an endpoint from the network while retaining the access needed for investigation.

Since identifiers may change between versions of the standard, other documents, reports, and tools should use the format `v<version>-C<chapter>.<section>.<requirement>`, for example `v1.0-C8.2.3`. The `v` preceding the version number is always lowercase.

---

## Versioning

IRSVS uses a two-part version number, `v<MAJOR>.<MINOR>`, following the approach used by [OWASP AISVS](https://github.com/OWASP/AISVS). Each release is published as a numbered folder in this repository. Once a version is released, its folder is locked and all further work happens in a new folder.

```text
/
├── 1.0-dev/   <- first version (in progress)
```

---

## Contributing

Contributions are welcome, particularly from practicing incident responders, forensic analysts, breach counsel, and assessors. Please [open an issue](https://github.com/jmanico/IRSVS/issues) to report problems or suggest improvements. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

The entire project content is under the **[Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/)** license.
