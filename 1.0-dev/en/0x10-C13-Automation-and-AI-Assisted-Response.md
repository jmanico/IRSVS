# C13 Automation & AI-Assisted Response

## Control Objective

This chapter addresses ensuring that automated playbooks and AI systems used in detection and response act within defined authority, are tested, remain attributable, and fail safely, so that the response does not itself become a source of harm.

Response automation holds some of the most powerful privileges in an organization: it can disable accounts, isolate hosts, and block traffic at scale. AI systems used in triage read content that the adversary wrote. This chapter applies to both. The security of AI systems in general is covered by the [OWASP AISVS](https://github.com/OWASP/AISVS).

---

## C13.1 Automated Response Actions

Every automated action must have an owner, a defined scope, a record, and a limit on how much damage it can do if it fires wrongly.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **13.1.1** | **Verify that** an inventory of automated response actions records the trigger, the action, the scope, and the owner of each. | 2 |
| **13.1.2** | **Verify that** each automated action capable of disrupting business operations is either explicitly pre-approved for unattended execution under defined conditions or requires human approval at run time. | 2 |
| **13.1.3** | **Verify that** every automated response action is logged with its trigger, inputs, target, outcome, and the automation identity that performed it. | 2 |
| **13.1.4** | **Verify that** automated response actions are constrained by safeguards, such as critical asset exclusions and limits on the number of targets affected in a period, that prevent a faulty or manipulated trigger from causing a large-scale outage. | 2 |
| **13.1.5** | **Verify that** automated response playbooks are tested before deployment and after each change. | 2 |
| **13.1.6** | **Verify that** changes to automated response playbooks are version controlled and peer reviewed. | 2 |
| **13.1.7** | **Verify that** automated response actions can be rapidly disabled and that their effects can be reversed. | 2 |
| **13.1.8** | **Verify that** credentials held by response automation platforms are limited to the permissions that the documented actions require. | 2 |
| **13.1.9** | **Verify that** response automation platforms are protected and monitored as high-value assets commensurate with the privileges they hold. | 3 |

---

## C13.2 AI-Assisted Analysis & Agents

AI may speed up triage and analysis, but accountability for response decisions stays with people, and adversary-written content must not be able to steer the tooling.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **13.2.1** | **Verify that** incident data, evidence, and personal data are submitted only to AI services approved for that purpose under a documented policy. | 2 |
| **13.2.2** | **Verify that** AI-generated conclusions that inform containment, notification, or closure decisions are reviewed by an accountable human responder, with the review recorded. | 2 |
| **13.2.3** | **Verify that** AI agents able to execute response actions act under distinct identities and are subject to the same approval, logging, and safeguard requirements as other automated response actions. | 2 |
| **13.2.4** | **Verify that** alerts closed by automation or AI without human review are sampled and reviewed at a defined rate to measure the rate of missed incidents. | 2 |
| **13.2.5** | **Verify that** AI systems that process adversary-controllable content, such as email bodies, log fields, file contents, and web pages, cannot be induced by that content to execute response actions or disclose incident data without independent authorization. | 3 |
| **13.2.6** | **Verify that** the prompts, model versions, and outputs of AI systems used in incident analysis are retained with the incident record so that the analysis can be reviewed. | 3 |

---

## References

* [NIST SP 800-61 Rev. 3: Incident Response Recommendations and Considerations for Cybersecurity Risk Management](https://csrc.nist.gov/pubs/sp/800/61/r3/final)
* [NIST SP 800-53 Rev. 5: IR-4(1) Automated Incident Handling Processes](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final)
* [ASD ACSC, CISA, and partners: Guidance for SIEM and SOAR Implementation](https://www.cisa.gov/resources-tools/resources/guidance-siem-and-soar-implementation)
* [OWASP Artificial Intelligence Security Verification Standard (AISVS): C9 Orchestration and Agentic Security](https://github.com/OWASP/AISVS)
* [OWASP GenAI Security Project: GenAI Incident Response Guide 1.0](https://genai.owasp.org/resource/genai-incident-response-guide-1-0/)
* [Coalition for Secure AI (CoSAI): AI Incident Response Framework V1.0](https://github.com/cosai-oasis/ws2-defenders/tree/main/incident-response)
* [OASIS CACAO Security Playbooks v2.0](https://docs.oasis-open.org/cacao/security-playbooks/v2.0/security-playbooks-v2.0.html)
* [MITRE ATLAS: Adversarial Threat Landscape for AI Systems](https://atlas.mitre.org/)
* [NIST AI 600-1: Artificial Intelligence Risk Management Framework, Generative Artificial Intelligence Profile](https://doi.org/10.6028/NIST.AI.600-1)
* [MITRE D3FEND](https://d3fend.mitre.org/)
