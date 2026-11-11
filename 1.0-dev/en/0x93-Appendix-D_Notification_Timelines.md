# Appendix D: Notification Timelines

This appendix is informative. It summarizes commonly encountered legal and regulatory incident notification deadlines to illustrate why the requirements in C1.3, C5.2, C10.2, and C11.1 exist.

**This appendix is not legal advice and is not a complete list.** It omits sector rules, state and provincial breach laws, contractual obligations, and many jurisdictions. Each entry is a brief summary of an instrument that contains definitions, thresholds, and exceptions not reproduced here. Laws change. The entries were checked against the primary texts on 11 November 2026, and each links to its source so that readers can confirm the current position. An organization's own register of obligations (requirement 1.3.2) must be built with qualified counsel.

## Reading the Tables

The **clock starts** column matters as much as the deadline. Instruments start the clock at different moments: when the organization becomes aware, when it discovers a breach, when it determines that an incident has occurred or is material, when it classifies an incident, or when it makes a payment. This is why IRSVS requires the times of detection, awareness, and declaration to be recorded (5.2.2), deadlines to be tracked from the event that started each clock (10.2.3), and materiality or significance determinations to be documented with their time (10.2.7).

## European Union

| Instrument | Who notifies whom | Clock starts | Deadline |
| --- | --- | --- | --- |
| [GDPR](https://eur-lex.europa.eu/eli/reg/2016/679/oj), Regulation (EU) 2016/679, Art. 33 and 34 | Controller to supervisory authority; processor to controller; controller to data subjects where there is high risk | Controller "having become aware" of the personal data breach | Authority: without undue delay and, where feasible, not later than 72 hours. Processor to controller and controller to data subjects: without undue delay. |
| [NIS2](https://eur-lex.europa.eu/eli/dir/2022/2555/oj), Directive (EU) 2022/2555, Art. 23 (applies through national law) | Essential and important entities to the CSIRT or competent authority | Becoming aware of the significant incident | Early warning within 24 hours. Incident notification within 72 hours (24 hours for trust service providers). Final report not later than one month after the incident notification. |
| [DORA](https://eur-lex.europa.eu/eli/reg/2022/2554/oj), Regulation (EU) 2022/2554, Art. 19, with [Delegated Regulation (EU) 2025/301](https://eur-lex.europa.eu/eli/reg_del/2025/301/oj) | Financial entities to the competent authority | Classification of the incident as major, and becoming aware of the incident | Initial notification within 4 hours of classification as major and no later than 24 hours from becoming aware. Intermediate report within 72 hours of the initial notification. Final report no later than one month after the latest intermediate report. |
| [Cyber Resilience Act](https://eur-lex.europa.eu/eli/reg/2024/2847/oj), Regulation (EU) 2024/2847, Art. 14 (reporting applies from 11 September 2026) | Manufacturers of products with digital elements to the coordinating CSIRT and ENISA | Manufacturer becoming aware of an actively exploited vulnerability or a severe incident | Early warning within 24 hours. Notification within 72 hours. Final report no later than 14 days after a corrective or mitigating measure is available (vulnerabilities) or within one month of the incident notification (severe incidents). |
| [AI Act](https://eur-lex.europa.eu/eli/reg/2024/1689/oj), Regulation (EU) 2024/1689, Art. 73 | Providers of high-risk AI systems to market surveillance authorities | Provider or, where applicable, deployer becoming aware of the serious incident | Not later than 15 days. Not later than 2 days for a widespread infringement or serious disruption of critical infrastructure. Not later than 10 days in the event of a death. The high-risk obligations this duty depends on were deferred by [Regulation (EU) 2026/1744](https://eur-lex.europa.eu/eli/reg/2026/1744/oj) to 2 December 2027 (Annex III systems) and 2 August 2028 (Annex I systems). |

## United Kingdom

| Instrument | Who notifies whom | Clock starts | Deadline |
| --- | --- | --- | --- |
| [UK GDPR](https://www.legislation.gov.uk/eur/2016/679/article/33), Art. 33 and 34 | Controller to the Information Commission; controller to data subjects where there is high risk | Controller having become aware of the personal data breach | Without undue delay and, where feasible, not later than 72 hours. The Data (Use and Access) Act 2025 aligned breach reporting by communications providers under PECR to the same 72 hours. |
| [NIS Regulations 2018](https://www.legislation.gov.uk/uksi/2018/506/regulation/11), reg. 11 | Operators of essential services to the competent authority | Operator being aware that a NIS incident has occurred | No later than 72 hours. |

## United States

| Instrument | Who notifies whom | Clock starts | Deadline |
| --- | --- | --- | --- |
| [SEC Form 8-K](https://www.sec.gov/files/form8-k.pdf), Item 1.05 | Public companies to the SEC and the market | Registrant determining that the incident is material, a determination to be made without unreasonable delay after discovery | Four business days. Foreign private issuers furnish Form 6-K promptly. |
| [HIPAA Breach Notification Rule](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164/subpart-D), 45 CFR 164.400 to 164.414 | Covered entities to individuals, HHS, and in some cases the media; business associates to covered entities | Discovery of the breach | Without unreasonable delay and no later than 60 calendar days. HHS is notified at the same time for breaches affecting 500 or more individuals, and annually for smaller breaches. |
| [Computer-Security Incident Notification Rule](https://www.ecfr.gov/current/title-12/part-53), 12 CFR Parts 53, 225, and 304 | Banking organizations to their primary federal regulator; bank service providers to affected bank customers | Banking organization determining that a notification incident has occurred | Banking organization: as soon as possible and no later than 36 hours. Service provider: as soon as possible. |
| [NYDFS Cybersecurity Regulation](https://www.dfs.ny.gov/cybersecurity/23-NYCRR-Part-500), 23 NYCRR 500.17 | Covered entities to the Superintendent of Financial Services | Determining that a cybersecurity incident has occurred, including at an affiliate or third-party service provider | No later than 72 hours. Extortion payments: notice within 24 hours and a written explanation within 30 days. |
| [FTC Safeguards Rule](https://www.ecfr.gov/current/title-16/section-314.4), 16 CFR 314.4(j) | Non-bank financial institutions to the FTC | Discovery of a notification event involving at least 500 consumers | As soon as possible and no later than 30 days. |
| [FTC Health Breach Notification Rule](https://www.ecfr.gov/current/title-16/section-318.4), 16 CFR 318.4 | Vendors of personal health records and related entities to individuals, the FTC, and in some cases the media | Discovery of a breach of security | Without unreasonable delay and no later than 60 calendar days. |
| [DFARS 252.204-7012](https://www.ecfr.gov/current/title-48/section-252.204-7012) | Defense contractors to the Department of Defense | Discovery of a cyber incident | Within 72 hours. |
| [CISA Federal Incident Notification Guidelines](https://www.cisa.gov/federal-incident-notification-guidelines) | Federal civilian executive branch agencies to CISA | Incident being identified by the agency's top-level CSIRT, SOC, or IT department | Within one hour. CISA has indicated that these guidelines are being revised. |

## Asia-Pacific and Canada

| Instrument | Who notifies whom | Clock starts | Deadline |
| --- | --- | --- | --- |
| [India CERT-In Directions](https://www.cert-in.org.in/PDF/CERT-In_Directions_70B_28.04.2022.pdf) of 28 April 2022 | Service providers, intermediaries, data centres, bodies corporate, and government organisations to CERT-In | Noticing the incident or having it brought to notice | Within 6 hours. |
| [Australia Security of Critical Infrastructure Act 2018](https://www.legislation.gov.au/C2018A00029/latest/text), ss. 30BC and 30BD | Responsible entities for critical infrastructure assets to the designated Commonwealth body | Entity becoming aware of the incident | Within 12 hours where the incident has a significant impact on the availability of the asset. Within 72 hours where it has a relevant impact. |
| [Australia Cyber Security Act 2024](https://www.legislation.gov.au/C2024A00098/latest/text), s. 27 | Reporting business entities to the designated Commonwealth body | Making a ransomware payment or becoming aware that one has been made | Within 72 hours. |
| [Australia Privacy Act 1988](https://www.legislation.gov.au/C2004A03712/latest/text), Part IIIC (Notifiable Data Breaches) | Entities to the Commissioner and affected individuals | Reasonable grounds to suspect (assessment) or to believe (notification) that an eligible data breach has occurred | All reasonable steps to complete the assessment within 30 days. Notification as soon as practicable. |
| [Singapore Personal Data Protection Act 2012](https://sso.agc.gov.sg/Act/PDPA2012), ss. 26C and 26D | Organisations to the PDPC and affected individuals | Organisation assessing that the breach is notifiable | PDPC: as soon as practicable and no later than 3 calendar days. Individuals: on or after notifying the PDPC. |
| [Canada PIPEDA](https://laws-lois.justice.gc.ca/eng/acts/P-8.6/section-10.1.html), s. 10.1 | Organizations to the Privacy Commissioner and affected individuals | Organization determining that the breach has occurred | As soon as feasible. |

## Industry Standards

| Instrument | Position |
| --- | --- |
| [PCI DSS v4.0.1](https://www.pcisecuritystandards.org/document_library/), Requirement 12.10.1 | The standard sets no notification deadline. It requires the incident response plan to cover notification of payment brands and acquirers. Timing is set by payment brand rules, acquirer contracts, and applicable law. |

## Pending and Recently Changed

The following were not in effect, or were in the process of changing, when this appendix was checked:

* **United States, CIRCIA.** The [Cyber Incident Reporting for Critical Infrastructure Act of 2022](https://www.cisa.gov/topics/cyber-threats-and-advisories/information-sharing/cyber-incident-reporting-critical-infrastructure-act-2022-circia) provides for reporting covered cyber incidents to CISA within 72 hours and ransom payments within 24 hours. These duties take effect on dates set by a final rule, which had not been published.
* **United Kingdom, Cyber Security and Resilience Bill.** The [Bill](https://bills.parliament.uk/bills/4035) would introduce an initial notification within 24 hours followed by a fuller report within 72 hours. It had not completed its passage through Parliament.
* **European Union, AI Act.** The deferral described in the table above was made in July 2026.
* **European Union, GDPR and NIS2.** Proposals that would amend incident and breach reporting provisions were under consideration in the EU legislative process.
* **United States, federal agencies.** CISA had indicated that its incident notification guidelines for federal agencies were being replaced.

## What the Timelines Mean for Incident Response

The deadlines above have practical consequences that IRSVS requirements are written to address:

* **The shortest clocks leave no time to work out the process.** One hour, four hours from classification, six hours, and twelve hours all appear above. An organization subject to them must have the responsible role, template, and submission method settled in advance (10.2.2).
* **Staged reporting is common.** NIS2, DORA, and the Cyber Resilience Act each require an early notice followed by fuller reports, so the first notice goes out before the facts are known (10.2.6).
* **Clocks start at decisions as well as discoveries.** Several regimes run from a determination or classification made by the organization, which makes the timing and documentation of that decision a matter of record (5.2.2, 10.2.7).
* **Payments can be reportable events.** Extortion payments carry their own deadlines in some jurisdictions (12.2.2).
* **Supplier delay consumes the organization's time.** A processor or service provider that takes days to report leaves its customer little of a 72-hour window (11.1.2, 11.1.3).
* **Several regimes usually apply at once.** A single incident at a regulated multinational may trigger privacy, sectoral, securities, and contractual obligations with different recipients, triggers, and deadlines, which is why a register is required (1.3.2).
