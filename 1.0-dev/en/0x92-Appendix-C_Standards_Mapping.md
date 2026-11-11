# Appendix C: Standards Mapping

This appendix maps each IRSVS section to related elements of five widely used frameworks, so that organizations already measured against them can see where IRSVS applies and where it adds depth.

The mapping is informative. An entry means that the framework element addresses the same subject as the IRSVS section. It does not mean that meeting one satisfies the other. IRSVS requirements are generally more specific than the elements they map to, and a dash indicates that the framework has no element that addresses the section directly.

Framework versions used:

* **NIST CSF 2.0.** NIST Cybersecurity Framework 2.0, Subcategory identifiers.
* **SP 800-53.** NIST SP 800-53 Rev. 5 control identifiers. A number in parentheses is a control enhancement.
* **ISO/IEC 27001.** ISO/IEC 27001:2022 Annex A control numbers.
* **CIS.** CIS Critical Security Controls v8.1 Safeguard numbers.
* **PCI DSS.** PCI DSS v4.0.1 requirement numbers.

## C1 Governance, Policy & Authority

| IRSVS section | NIST CSF 2.0 | SP 800-53 | ISO/IEC 27001 | CIS | PCI DSS |
| --- | --- | --- | --- | --- | --- |
| C1.1 Policy & Plan | GV.PO-01, GV.PO-02, ID.IM-04 | IR-1, IR-8 | 5.24 | 17.4 | 12.10.1 |
| C1.2 Authority & Decision Rights | GV.RR-01, GV.RR-02, GV.OV-03 | IR-1, IR-4, IR-8 | 5.2, 5.24 | 17.1, 17.5 | 12.10.1 |
| C1.3 Legal, Regulatory & Contractual Obligations | GV.OC-03 | IR-6, IR-8 | 5.31 | — | 12.10.1 |
| C1.4 Scope & Risk Alignment | ID.RA-03, ID.IM-01 | CA-2, IR-8, RA-3 | 5.35 | — | — |

## C2 Team, Roles & Responder Readiness

| IRSVS section | NIST CSF 2.0 | SP 800-53 | ISO/IEC 27001 | CIS | PCI DSS |
| --- | --- | --- | --- | --- | --- |
| C2.1 Roles & Structure | GV.RR-02 | IR-4(11), IR-8 | 5.2, 5.24 | 17.1, 17.5 | 12.10.1 |
| C2.2 Contact & Availability | GV.RR-02 | IR-7, IR-8 | 5.24 | 17.2, 17.6 | 12.10.3 |
| C2.3 Training & Competence | PR.AT-01, PR.AT-02 | AT-2, AT-3, IR-2 | 6.3 | 14.6, 14.9 | 12.10.4 |
| C2.4 External Support | GV.SC-08, ID.RA-02 | IR-7, IR-7(2), PM-15 | 5.5, 5.6 | 17.2 | — |
| C2.5 Responder Tooling & Access | — | IR-4, IR-4(1) | 5.24 | 17.6 | — |

## C3 Visibility & Forensic Readiness

| IRSVS section | NIST CSF 2.0 | SP 800-53 | ISO/IEC 27001 | CIS | PCI DSS |
| --- | --- | --- | --- | --- | --- |
| C3.1 Asset & Context Information | ID.AM-01, ID.AM-02, ID.AM-03, ID.AM-05, ID.AM-07 | CM-8, PM-5, RA-9 | 5.9, 5.12 | 1.1, 2.1, 3.2, 12.4 | 1.2.3, 1.2.4, 12.5.1 |
| C3.2 Log Generation & Coverage | PR.PS-04, DE.CM-01, DE.CM-03, DE.CM-09 | AU-2, AU-3, AU-12, SI-4 | 8.15, 8.16 | 8.2, 8.5, 8.6, 8.7, 8.8, 13.6 | 10.2 |
| C3.3 Log Integrity, Time & Retention | PR.PS-04 | AU-8, AU-9, AU-11 | 8.15, 8.17 | 8.3, 8.4, 8.9, 8.10 | 10.3, 10.5, 10.6 |
| C3.4 Forensic Acquisition Readiness | RS.AN-07 | IR-4, IR-8 | 5.28 | — | — |

## C4 Detection, Reporting & Intake

| IRSVS section | NIST CSF 2.0 | SP 800-53 | ISO/IEC 27001 | CIS | PCI DSS |
| --- | --- | --- | --- | --- | --- |
| C4.1 Internal Reporting | PR.AT-01, RS.MA-02 | AT-2, IR-6 | 6.8 | 14.6, 17.3 | — |
| C4.2 External Reporting & Intake | ID.RA-08, RS.MA-02 | IR-6, RA-5(11), SI-5 | 5.5, 6.8 | 17.3 | — |
| C4.3 Alert Handling & Escalation | DE.AE-02, DE.AE-03, DE.AE-06, DE.AE-08, RS.MA-02 | AU-6, IR-4, IR-5, SI-4 | 5.25, 8.16 | 8.11, 13.1, 13.11 | 10.4, 12.10.5 |

## C5 Triage, Classification & Incident Management

| IRSVS section | NIST CSF 2.0 | SP 800-53 | ISO/IEC 27001 | CIS | PCI DSS |
| --- | --- | --- | --- | --- | --- |
| C5.1 Classification & Prioritization | DE.AE-04, RS.MA-03, RS.AN-08 | IR-4, IR-5 | 5.25 | 17.9 | — |
| C5.2 Declaration & Escalation | DE.AE-08, RS.MA-04, RC.RP-06 | IR-4, IR-6 | 5.25, 5.26 | 17.4, 17.9 | 12.10.1 |
| C5.3 Incident Record & Coordination | RS.MA-01, RS.AN-06 | IR-4, IR-5 | 5.26, 5.28 | 17.4 | — |

## C6 Investigation & Analysis

| IRSVS section | NIST CSF 2.0 | SP 800-53 | ISO/IEC 27001 | CIS | PCI DSS |
| --- | --- | --- | --- | --- | --- |
| C6.1 Scoping & Analysis | DE.AE-02, DE.AE-03, DE.AE-04, RS.AN-03, RS.AN-08 | AU-6, IR-4, IR-4(12), IR-4(13) | 5.25, 5.26 | — | — |
| C6.2 Threat Intelligence | DE.AE-07, ID.RA-02, ID.RA-03 | IR-4(8), PM-16 | 5.7 | — | — |
| C6.3 Operational Security | — | IR-4 | — | — | — |

## C7 Evidence Handling & Digital Forensics

| IRSVS section | NIST CSF 2.0 | SP 800-53 | ISO/IEC 27001 | CIS | PCI DSS |
| --- | --- | --- | --- | --- | --- |
| C7.1 Collection & Preservation | RS.AN-07 | AU-11, IR-4 | 5.28 | — | — |
| C7.2 Chain of Custody & Storage | RS.AN-06, RS.AN-07 | AU-9, AU-11, IR-4 | 5.28, 5.33, 5.34 | — | — |
| C7.3 Forensic Analysis Quality | RS.AN-03 | IR-4(12) | 5.28 | — | — |

## C8 Containment

| IRSVS section | NIST CSF 2.0 | SP 800-53 | ISO/IEC 27001 | CIS | PCI DSS |
| --- | --- | --- | --- | --- | --- |
| C8.1 Containment Decisions | RS.MI-01 | IR-4 | 5.26 | 17.4 | 12.10.1 |
| C8.2 Containment Capabilities | RS.MI-01 | AC-2(13), IR-4, SC-7 | 5.26, 8.22 | 6.2 | — |
| C8.3 Safe Containment | RS.MI-01 | CM-3, IR-4 | 8.32 | — | — |

## C9 Eradication & Recovery

| IRSVS section | NIST CSF 2.0 | SP 800-53 | ISO/IEC 27001 | CIS | PCI DSS |
| --- | --- | --- | --- | --- | --- |
| C9.1 Eradication | RS.MI-02 | IR-4, SI-2, SI-3 | 5.26, 8.8 | — | — |
| C9.2 Recovery Readiness | PR.DS-11, ID.IM-04 | CP-2, CP-9, CP-10 | 5.29, 5.30, 8.13 | 11.1, 11.2, 11.3, 11.4 | 12.10.1 |
| C9.3 Restoration & Validation | RS.MA-05, RC.RP-01, RC.RP-02, RC.RP-03, RC.RP-04, RC.RP-05, RC.RP-06 | CP-10, IR-4 | 5.26, 5.29, 5.30 | 11.1 | — |

## C10 Communication, Notification & Information Sharing

| IRSVS section | NIST CSF 2.0 | SP 800-53 | ISO/IEC 27001 | CIS | PCI DSS |
| --- | --- | --- | --- | --- | --- |
| C10.1 Internal Communication | RS.CO-02, RS.CO-03, RC.CO-03 | IR-4, IR-6 | 5.26 | 17.4, 17.6 | 12.10.1 |
| C10.2 Regulatory & Legal Notification | GV.OC-03, RS.CO-02 | IR-6 | 5.5, 5.26, 5.31 | 17.2, 17.3 | 12.10.1 |
| C10.3 Affected Parties & Public Communication | RS.CO-02, RC.CO-03, RC.CO-04 | IR-4(15), IR-6 | 5.26 | — | — |
| C10.4 Law Enforcement & Information Sharing | RS.CO-03, ID.RA-02 | IR-4(8), IR-6, PM-15, PM-16 | 5.5, 5.6 | 17.2 | — |

## C11 Third Parties, Cloud & Supply Chain

| IRSVS section | NIST CSF 2.0 | SP 800-53 | ISO/IEC 27001 | CIS | PCI DSS |
| --- | --- | --- | --- | --- | --- |
| C11.1 Supplier Obligations | GV.SC-05, GV.SC-07, GV.SC-08 | IR-6(3), SA-9, SR-8 | 5.19, 5.20, 5.21, 5.22 | 15.1, 15.4 | 12.8 |
| C11.2 Third-Party Incident Handling | GV.SC-08, ID.AM-04, RS.MA-01 | CM-8, IR-4(10), SR-8 | 5.19, 5.21, 5.22 | 2.1, 15.1 | 6.3.2 |
| C11.3 Cloud & SaaS Readiness | GV.SC-08, PR.PS-04, DE.CM-06 | AU-2, AU-12, IR-4, SA-9 | 5.23, 8.15 | 8.12 | — |

## C12 Scenario Playbooks

| IRSVS section | NIST CSF 2.0 | SP 800-53 | ISO/IEC 27001 | CIS | PCI DSS |
| --- | --- | --- | --- | --- | --- |
| C12.1 Playbook Management | ID.IM-04, RS.MA-01 | IR-4, IR-8 | 5.24, 5.37 | 17.4 | 12.10.1 |
| C12.2 Ransomware & Extortion | RS.MI-01, RC.RP-01 | CP-10, IR-4, IR-8 | 5.24, 5.26 | 11.4 | — |
| C12.3 Identity & Email Compromise | RS.MI-01, RS.MI-02 | AC-2, IR-4 | 5.26 | 6.2 | — |
| C12.4 Data Breach | RS.AN-08, RS.CO-02 | IR-2(3), IR-8(1), IR-9 | 5.26, 5.34 | — | 12.10.7 |
| C12.5 Other Common Scenarios | RS.MI-01 | IR-4, SC-5 | 5.26 | — | — |
| C12.6 Specialized Environments | RS.MA-01 | IR-4 | 5.26 | — | — |

## C13 Automation & AI-Assisted Response

| IRSVS section | NIST CSF 2.0 | SP 800-53 | ISO/IEC 27001 | CIS | PCI DSS |
| --- | --- | --- | --- | --- | --- |
| C13.1 Automated Response Actions | RS.MI-01 | IR-4(1), IR-4(5), SI-4(7) | — | — | — |
| C13.2 AI-Assisted Analysis & Agents | — | IR-4(1) | — | — | — |

## C14 Exercises, Testing & Validation

| IRSVS section | NIST CSF 2.0 | SP 800-53 | ISO/IEC 27001 | CIS | PCI DSS |
| --- | --- | --- | --- | --- | --- |
| C14.1 Exercise Program | ID.IM-02, PR.AT-02 | CP-4, IR-3, IR-3(2) | 5.24, 5.30 | 17.7 | 12.10.2 |
| C14.2 Technical Validation | ID.IM-02, PR.DS-11 | CA-8, CA-8(2), CP-4, CP-9(1), IR-3 | 5.30, 8.13 | 11.5, 17.7, 18.1 | 12.10.2 |

## C15 Post-Incident Activity & Continuous Improvement

| IRSVS section | NIST CSF 2.0 | SP 800-53 | ISO/IEC 27001 | CIS | PCI DSS |
| --- | --- | --- | --- | --- | --- |
| C15.1 Post-Incident Review | ID.IM-03, ID.IM-04, RC.RP-06 | IR-4, IR-8 | 5.27 | 17.8 | 12.10.6 |
| C15.2 Metrics & Reporting | GV.OV-03, ID.IM-01 | IR-5, PM-6 | 5.27 | — | — |
| C15.3 Records Retention | RS.AN-06, RC.RP-06 | AU-11, IR-5 | 5.33 | — | — |

## Where IRSVS Adds Depth

The dashes in the tables above, and the sections that map only to a broad control such as IR-4 or to a general requirement to test, show the areas that general-purpose frameworks address least. These are the areas where IRSVS contributes requirements that organizations would otherwise have to write for themselves:

* **Operational security of the investigation (C6.3).** Protecting responder credentials and avoiding disclosure of the investigation to the adversary.
* **Evidence handling detail (C7).** General frameworks require that evidence be collected and its integrity preserved. IRSVS specifies order of volatility, hashing, working copies, chain of custody, tool validation, and reproducibility.
* **Responder tooling resilience (C2.5).** Out-of-band communication, emergency access, and response infrastructure that survives compromise of the production identity system.
* **Scenario-specific decisions (C12).** Extortion payment decision processes, identity infrastructure compromise, and incidents involving AI systems.
* **Safety of automation and AI in the response (C13).** Approval, blast radius limits, and resistance to adversary-controlled input for automated and AI-driven response actions.
* **Technical validation (C14.2).** General frameworks require that the plan and backups be tested. IRSVS specifies which capabilities must be demonstrated, including containment, recovery against objectives, evidence acquisition, and emergency access, with performance measured.
