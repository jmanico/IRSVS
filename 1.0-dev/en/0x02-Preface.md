# Preface

Welcome to the **Incident Response Security Verification Standard (IRSVS) version 1.0**.

This is the first draft and the active development version. There is no stable release yet.

## Why IRSVS Exists

Most organizations have an incident response plan. Far fewer know whether it works. The plan sits in a document management system that is unreachable during a ransomware attack. The contact list names people who left two years ago. The logs that would show what the intruder took were never enabled, or were kept for thirty days when the intruder was present for ninety. The backups share credentials with the systems they protect. Nobody has decided who may shut down production, who talks to the regulator, or who decides whether to pay. These gaps are found during the incident, when they are most expensive.

The guidance on how to do incident response well is mature and widely available. NIST SP 800-61, now in its third revision and aligned with the Cybersecurity Framework 2.0, describes what organizations should consider across governance, preparation, detection, response, and recovery. The ISO/IEC 27035 series defines a management process. FIRST describes the services a CSIRT provides. CISA, the UK NCSC, ENISA, and others publish playbooks and practical guides. Regulations such as GDPR, NIS2, DORA, and the SEC cybersecurity disclosure rules set deadlines.

What has been missing is a way to verify the result. Process guidance tells an organization what to think about. Maturity models tell it how developed its practices are. Neither gives an assessor a list of specific, binary questions whose answers show whether the capability will hold when it is needed. Security teams building a program, auditors assessing one, insurers underwriting one, and customers relying on one all end up writing their own checklists.

IRSVS fills that gap. It does for incident response what ASVS does for application security and AISVS does for AI systems: it converts established guidance into requirements that are each verifiable, testable, and implementable, organized into levels that let an organization pick a target proportionate to its risk.

## Design Principles

IRSVS is organized into 15 control families. Each control family is divided into focused sections that support its control objective, and each section contains verification requirements. IRSVS defines three verification levels, described under Using the IRSVS. Sections need not include requirements at every level.

Each requirement must address a single concern that can ordinarily be verified with one piece of evidence. Requirements must not duplicate one another. Higher levels may introduce stricter criteria, but those criteria are stated as separate requirements. Requirements use clear, technology-neutral language and name specific technologies only as examples where they improve clarity.

Every IRSVS requirement follows four design principles derived from the standard's name:

* **Incident Response.** Requirements must address the capability to prepare for, detect and report, analyze, contain, eradicate, recover from, communicate about, or learn from security incidents. IRSVS does not restate preventive controls. A control belongs in IRSVS only if its absence would be felt during or after an incident.
* **Security.** Requirements must reduce the impact of cybersecurity incidents or the risk introduced by the response itself. Controls that serve only general IT operations, compliance reporting, or business continuity for non-security events are out of scope.
* **Verification.** Requirements must be objectively verifiable through inspection of documents and records, technical test or demonstration, or evidence from exercises and real incidents. Aspirational statements, subjective judgments of quality, and requirements that can only be satisfied by assertion are excluded.
* **Standard.** Requirements use consistent structure, terminology, and level semantics so that IRSVS remains coherent, navigable, and suitable for repeatable assessment by different assessors.

## Grounded in Authoritative Sources

Every chapter cites the sources its requirements were derived from. IRSVS favors, in order: international and national standards (ISO/IEC, NIST, IETF), guidance from government cybersecurity agencies (CISA, UK NCSC, ASD, ENISA), established community frameworks (FIRST, CIS, MITRE, OASIS), and widely adopted industry practice. Where sources disagree or leave a threshold open, such as a log retention period, IRSVS selects a value that at least one authoritative source specifies and assigns it to the appropriate level.

Appendix B catalogues the sources. Appendix C maps IRSVS sections to NIST CSF 2.0, NIST SP 800-53, ISO/IEC 27001, the CIS Controls, and PCI DSS so that organizations already measured against those frameworks can see where IRSVS adds depth.
