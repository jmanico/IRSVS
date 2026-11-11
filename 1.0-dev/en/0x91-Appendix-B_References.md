# Appendix B: References

This appendix catalogues the authoritative sources that IRSVS draws on and describes how each is used. Individual chapters list the sources most relevant to their requirements.

IRSVS cites sources to show where its requirements come from. It does not reproduce their content, and citation does not imply that the publisher endorses IRSVS. Standards are revised over time, so readers should check the publisher's page for the current edition.

## Incident Response Process and Management

| Source | How IRSVS uses it |
| --- | --- |
| [NIST SP 800-61 Rev. 3, Incident Response Recommendations and Considerations for Cybersecurity Risk Management: A CSF 2.0 Community Profile](https://csrc.nist.gov/pubs/sp/800/61/r3/final) (2025) | The primary source. Its recommendations across the Govern, Identify, Protect, Detect, Respond, and Recover functions underpin every chapter. |
| [NIST Cybersecurity Framework (CSF) 2.0](https://www.nist.gov/cyberframework) (2024) | Provides the outcome structure that IRSVS sections are mapped to in Appendix C. |
| [ISO/IEC 27035-1:2023, Information security incident management, Part 1: Principles and process](https://www.iso.org/standard/78973.html) | Incident management principles and phases; basis for C1, C5, and C15. |
| [ISO/IEC 27035-2:2023, Part 2: Guidelines to plan and prepare for incident response](https://www.iso.org/standard/78974.html) | Planning and preparation; basis for C1 and C2. |
| [ISO/IEC 27035-3:2020, Part 3: Guidelines for ICT incident response operations](https://www.iso.org/standard/74033.html) | Response operations; basis for C6, C8, and C9. |
| [ISO/IEC 27035-4:2024, Part 4: Coordination](https://www.iso.org/standard/80973.html) | Coordination between organizations; informs C10 and C11. |
| [FIRST CSIRT Services Framework v2.1](https://www.first.org/standards/frameworks/csirts/csirt_services_framework_v2.1) | The service areas of a CSIRT; used to check the coverage of C2, C4, C5, and C6. |
| [RFC 2350, Expectations for Computer Security Incident Response](https://www.rfc-editor.org/rfc/rfc2350) | What a response team should publish about its scope, authority, and contact methods; informs C1 and C2. |
| [CISA, Federal Government Cybersecurity Incident and Vulnerability Response Playbooks](https://www.cisa.gov/resources-tools/resources/federal-government-cybersecurity-incident-and-vulnerability-response-playbooks) (2021) | Operational procedures for the phases of response; informs C5, C6, C8, and C12. |
| [UK NCSC, Incident Management](https://www.ncsc.gov.uk/collection/incident-management) | Practical guidance on building and exercising a response capability; informs C2, C4, and C14. |
| [Open CSIRT Foundation, SIM3 Security Incident Management Maturity Model](https://opencsirt.org/csirt-maturity/sim3-and-references/) (v2 interim) | CSIRT maturity parameters; used to check coverage of organizational, human, tooling, and process aspects. |
| [ENISA, Good Practice Guide for Incident Management](https://www.enisa.europa.eu/publications/good-practice-guide-for-incident-management) (2010) | Incident handling workflow and team operation; informs C2 and C5. |
| [SANS, Incident Handler's Handbook](https://www.sans.org/white-papers/33901/) (2012) | The widely used preparation, identification, containment, eradication, recovery, and lessons learned model; informs the ordering of C4 to C9 and C15. |
| [FEMA, National Incident Management System](https://www.fema.gov/emergency-managers/nims) | The incident command model of a single commander and defined handover; informs C2.1. |
| [Google SRE Book, Managing Incidents](https://sre.google/sre-book/managing-incidents/) | Incident command applied to technology operations; informs C2.1 and C5.3. |

## Digital Forensics and Evidence

| Source | How IRSVS uses it |
| --- | --- |
| [NIST SP 800-86, Guide to Integrating Forensic Techniques into Incident Response](https://csrc.nist.gov/pubs/sp/800/86/final) | Forensic process within incident response; basis for C3.4, C6, and C7. |
| [RFC 3227, Guidelines for Evidence Collection and Archiving](https://www.rfc-editor.org/rfc/rfc3227) | Order of volatility and chain of custody; basis for C7.1 and C7.2. |
| [ISO/IEC 27037:2012, Guidelines for identification, collection, acquisition and preservation of digital evidence](https://www.iso.org/standard/44381.html) | Evidence handling; basis for C7.1 and C7.2. |
| [ISO/IEC 27041:2015, Guidance on assuring suitability and adequacy of incident investigative method](https://www.iso.org/standard/44405.html) | Validation of methods and tools; basis for 7.1.7 and C7.3. |
| [ISO/IEC 27042:2015, Guidelines for the analysis and interpretation of digital evidence](https://www.iso.org/standard/44406.html) | Analysis and reporting quality; basis for C6.1 and C7.3. |
| [ISO/IEC 27043:2015, Incident investigation principles and processes](https://www.iso.org/standard/44407.html) | Investigative readiness; basis for C3. |
| [NIST Computer Forensics Tool Testing Program (CFTT)](https://www.nist.gov/itl/ssd/software-quality-group/computer-forensics-tool-testing-program-cftt) | Forensic tool validation; informs 7.1.7. |
| [NIST SP 800-201, NIST Cloud Computing Forensic Reference Architecture](https://csrc.nist.gov/pubs/sp/800/201/final) | Forensic challenges specific to cloud; informs C3.4 and C11.3. |

## Logging and Visibility

| Source | How IRSVS uses it |
| --- | --- |
| [NIST SP 800-92, Guide to Computer Security Log Management](https://csrc.nist.gov/pubs/sp/800/92/final) (2006) | Log management practice; basis for C3.2 and C3.3. A revision, [SP 800-92 Rev. 1](https://csrc.nist.gov/pubs/sp/800/92/r1/ipd), has been in public draft since 2023. |
| [ASD ACSC, CISA, and partners, Best Practices for Event Logging and Threat Detection](https://www.cisa.gov/resources-tools/resources/best-practices-event-logging-and-threat-detection) (2024) | Log source priorities, centralization, integrity, and timestamp consistency; basis for C3.2 and C3.3. |
| [OMB M-26-14, Ensuring Effective and Efficient Agency Logging and Network Visibility to Defend Against Evolving Cyber Threats](https://www.whitehouse.gov/wp-content/uploads/2026/05/M-26-14-Ensuring-Effective-and-Efficient-Agency-Logging-and-Network-Visibility-to-Defend-Against-Evolving-Cyber-Threats.pdf) (2026) | United States federal logging baseline and maturity model, which rescinded and replaced M-21-31. Its maturity model includes logs searchable for at least 3 months and retrievable for at least 12 months; one source for the retention value in 3.3.4. |
| [CISA, Logging Reference Architecture](https://www.cisa.gov/resources-tools/resources/logging-reference-architecture) (2026) | Implementation guidance accompanying M-26-14; informs C3.2 and C3.3. |

## Recovery and Continuity

| Source | How IRSVS uses it |
| --- | --- |
| [NIST SP 800-184, Guide for Cybersecurity Event Recovery](https://csrc.nist.gov/pubs/sp/800/184/final) | Recovery planning and execution after a cyber event; basis for C9. |
| [NIST SP 800-34 Rev. 1, Contingency Planning Guide for Federal Information Systems](https://csrc.nist.gov/pubs/sp/800/34/r1/upd1/final) | Contingency planning, recovery objectives, and plan testing; informs C9.2 and C14. |
| [ISO/IEC 27031:2025, Information and communication technology readiness for business continuity](https://www.iso.org/standard/27031) | ICT readiness for disruption; informs C9.2. |
| [ISO 22301:2019, Business continuity management systems](https://www.iso.org/standard/75106.html) | Business continuity; referenced as the adjacent discipline in C1.1 and C9. |
| [ISO 22361:2022, Crisis management guidelines](https://www.iso.org/standard/50267.html) | Crisis management; referenced as the adjacent discipline in C1.1 and C10. |

## Exercises and Testing

| Source | How IRSVS uses it |
| --- | --- |
| [NIST SP 800-84, Guide to Test, Training, and Exercise Programs for IT Plans and Capabilities](https://csrc.nist.gov/pubs/sp/800/84/final) | Exercise types and program design; basis for C14.1. |
| [CISA Tabletop Exercise Packages](https://www.cisa.gov/resources-tools/services/cisa-tabletop-exercise-packages) | Exercise scenarios and after-action templates; informs C14.1. |
| [European Central Bank, TIBER-EU framework](https://www.ecb.europa.eu/paym/cyber-resilience/tiber-eu/html/index.en.html) | Threat intelligence-based red teaming; informs 14.2.8. |

## Communication, Information Sharing, and Taxonomies

| Source | How IRSVS uses it |
| --- | --- |
| [FIRST Traffic Light Protocol (TLP) 2.0](https://www.first.org/tlp/) | Marking of shared information; basis for 10.1.3 and 10.4.2. |
| [NIST SP 800-150, Guide to Cyber Threat Information Sharing](https://csrc.nist.gov/pubs/sp/800/150/final) | Sharing relationships and sanitization; basis for C6.2 and C10.4. |
| [OASIS STIX and TAXII](https://oasis-open.github.io/cti-documentation/) | Structured representation and exchange of threat information; informs 6.2.2. |
| [Reference Security Incident Taxonomy](https://github.com/enisaeu/Reference-Security-Incident-Taxonomy-Task-Force) (TF-CSIRT working group, hosted by ENISA) | Incident classification; informs 5.1.4. |
| [VERIS, Vocabulary for Event Recording and Incident Sharing](https://verisframework.org/) | Incident description and metrics; informs 5.1.4 and C15.2. |
| [RFC 9116, A File Format to Aid in Security Vulnerability Disclosure](https://www.rfc-editor.org/rfc/rfc9116) | Publication of a security contact; basis for 4.2.1. |
| [The Sedona Conference Incident Response Guide](https://thesedonaconference.org/publication/Incident_Response_Guide) | Legal considerations in incident response, including privilege and notification; informs C1.3 and C10.2. |

## Control Frameworks

| Source | How IRSVS uses it |
| --- | --- |
| [NIST SP 800-53 Rev. 5, Security and Privacy Controls for Information Systems and Organizations](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final) | The IR, AU, and CP control families; mapped in Appendix C. |
| [ISO/IEC 27001:2022, Information security management systems](https://www.iso.org/standard/27001) (with Amd 1:2024) | Annex A controls 5.24 to 5.28, 6.8, and related controls; mapped in Appendix C. |
| [CIS Critical Security Controls v8.1](https://www.cisecurity.org/controls/v8-1) | Control 17 and related Safeguards in Controls 8, 11, and 15; mapped in Appendix C. Safeguard 8.10 is the source for the retention value in 3.3.1. |
| [PCI DSS v4.0.1](https://www.pcisecuritystandards.org/document_library/) | Requirements 10 and 12.10; mapped in Appendix C. Requirement 10.5.1 is one source for the retention value in 3.3.4. |
| [NIST SP 800-55 Vol. 1, Measurement Guide for Information Security](https://csrc.nist.gov/pubs/sp/800/55/v1/final) | Selecting measures; informs C15.2. |

## Adversary Knowledge Bases

| Source | How IRSVS uses it |
| --- | --- |
| [MITRE ATT&CK](https://attack.mitre.org/) | Adversary tactics and techniques; referenced in 4.3.6, 6.1.8, and C14.2. |
| [MITRE D3FEND](https://d3fend.mitre.org/) | Defensive techniques, including isolation and eviction; informs C8.2. |
| [MITRE ATLAS](https://atlas.mitre.org/) | Adversary techniques against AI systems; informs 12.6.2 and C13.2. |

## Scenario, Cloud, Supply Chain, and Specialized Guidance

| Source | How IRSVS uses it |
| --- | --- |
| [CISA and partners (Joint Ransomware Task Force), #StopRansomware Guide](https://www.cisa.gov/resources-tools/resources/stopransomware-guide) (2023) | Ransomware preparation and response checklist; basis for C9.2 and C12.2. |
| [NIST IR 8374 Rev. 1, Ransomware Risk Management: A Cybersecurity Framework 2.0 Community Profile](https://csrc.nist.gov/pubs/ir/8374/r1/final) (2026) | Ransomware-specific outcomes; informs C12.2. Supersedes the 2022 edition, which has been withdrawn. |
| [US Treasury OFAC, Updated Advisory on Potential Sanctions Risks for Facilitating Ransomware Payments](https://ofac.treasury.gov/media/912981/download?inline) (2021) | Sanctions exposure from extortion payments; basis for 12.2.2. |
| [Microsoft, Incident response playbooks](https://learn.microsoft.com/en-us/security/zero-trust/security-operations-incident-response-playbooks) | Worked identity and email compromise playbooks; informs C12.3. |
| [AWS Security Incident Response User Guide](https://docs.aws.amazon.com/security-ir/latest/userguide/) | Cloud preparation, containment, and evidence acquisition; informs C11.3. |
| [Cloud Security Alliance, Cloud Incident Response Framework](https://cloudsecurityalliance.org/artifacts/cloud-incident-response-framework) | Shared responsibility in cloud incident response; informs C11.3. |
| [NIST SP 800-82 Rev. 3, Guide to Operational Technology (OT) Security](https://csrc.nist.gov/pubs/sp/800/82/r3/final) | Response considerations where safety and physical processes are involved; informs 8.1.5 and 12.6.1. |
| [FIRST PSIRT Services Framework 1.1](https://www.first.org/standards/frameworks/psirts/psirt_services_framework_v1.1) | Product security incident response; informs 12.6.4. |
| [ISO/IEC 29147:2018, Vulnerability disclosure](https://www.iso.org/standard/72311.html) and [ISO/IEC 30111:2019, Vulnerability handling processes](https://www.iso.org/standard/69725.html) | Receipt and handling of vulnerability reports; inform C4.2 and 12.6.4. |
| [OASIS CACAO Security Playbooks v2.0](https://docs.oasis-open.org/cacao/security-playbooks/v2.0/security-playbooks-v2.0.html) | Machine-readable playbook structure; informs C12.1 and C13.1. |
| [ASD ACSC, CISA, and partners, Guidance for SIEM and SOAR Implementation](https://www.cisa.gov/resources-tools/resources/guidance-siem-and-soar-implementation) (2025) | Risks and safeguards of automated response; informs C13.1. |
| [NIST AI 600-1, Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile](https://doi.org/10.6028/NIST.AI.600-1) (2024) | Incident-related risks of generative AI; informs C13.2. |
| [OWASP GenAI Security Project, GenAI Incident Response Guide 1.0](https://genai.owasp.org/resource/genai-incident-response-guide-1-0/) (2025) | Response to incidents involving generative AI systems; informs 12.6.2, 12.6.3, and C13.2. |
| [Coalition for Secure AI (CoSAI), AI Incident Response Framework V1.0](https://github.com/cosai-oasis/ws2-defenders/tree/main/incident-response) (2025) | Adapting incident response to AI systems; informs 12.6.2, 12.6.3, and C13.2. |

## Laws and Regulations

IRSVS does not interpret law. The instruments below are cited as examples of the obligations that requirements in C1.3 and C10.2 are designed to help organizations meet. Appendix D summarizes the notification deadlines of these and other instruments, with links to each primary text.

| Source | Relevance |
| --- | --- |
| [Regulation (EU) 2016/679 (GDPR)](https://eur-lex.europa.eu/eli/reg/2016/679/oj), Articles 33 and 34 | Personal data breach notification to authorities and data subjects. |
| [Directive (EU) 2022/2555 (NIS2)](https://eur-lex.europa.eu/eli/dir/2022/2555/oj), Article 23 | Staged reporting of significant incidents. |
| [Regulation (EU) 2022/2554 (DORA)](https://eur-lex.europa.eu/eli/reg/2022/2554/oj), Articles 17 to 19 | ICT-related incident management and reporting for financial entities. |

## Related Verification Standards

| Source | Relationship |
| --- | --- |
| [OWASP Application Security Verification Standard (ASVS)](https://owasp.org/www-project-application-security-verification-standard/) | The model for the structure, levels, and requirement style of IRSVS. |
| [OWASP Artificial Intelligence Security Verification Standard (AISVS)](https://github.com/OWASP/AISVS) | The direct template for IRSVS, and the source of security requirements for AI systems that C12.6 and C13 refer to. |
