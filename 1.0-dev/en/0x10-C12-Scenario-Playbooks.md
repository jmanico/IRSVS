# C12 Scenario Playbooks

## Control Objective

This chapter addresses translating the general incident response plan into concrete, rehearsable steps for the incident types the organization is most likely to face.

IRSVS does not supply playbook content. It verifies that playbooks exist for the scenarios that matter and that each contains the decisions and steps that are routinely missed. Requirements that begin with "where" apply only to organizations that operate the kind of environment described.

---

## C12.1 Playbook Management

Playbooks must exist for the prioritized scenarios, follow a consistent structure, and be kept current by an owner.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **12.1.1** | **Verify that** documented playbooks exist for each of the organization's prioritized incident scenarios. | 2 |
| **12.1.2** | **Verify that** each playbook defines its triggers, roles, investigation steps, containment and recovery actions, communication requirements, and decision points. | 2 |
| **12.1.3** | **Verify that** each playbook has an assigned owner and is reviewed at least annually and after each use. | 2 |

---

## C12.2 Ransomware & Extortion

Ransomware and extortion compress technical, legal, financial, and ethical decisions into hours, so those decisions must be worked through in advance.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **12.2.1** | **Verify that** the incident response plan addresses ransomware, including immediate isolation steps, who to contact, and how recovery from backups is initiated. | 1 |
| **12.2.2** | **Verify that** a documented decision process for extortion demands identifies the decision makers and requires legal review, sanctions screening, and consideration of law enforcement engagement before any payment. | 2 |
| **12.2.3** | **Verify that** the ransomware playbook addresses data theft extortion, including assessing what data was taken and the resulting notification obligations. | 2 |
| **12.2.4** | **Verify that** the ransomware playbook requires preservation of ransom notes, malware samples, and examples of encrypted files. | 2 |
| **12.2.5** | **Verify that** any provider that would be engaged to communicate with extortionists has been identified and vetted in advance. | 3 |

---

## C12.3 Identity & Email Compromise

Compromised identities are the most common route into an organization, and cleaning one up properly involves more than a password reset.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **12.3.1** | **Verify that** a playbook for compromised user accounts covers session and token revocation, credential reset, review of authentication methods, review of mailbox rules and forwarding, and review of application grants. | 2 |
| **12.3.2** | **Verify that** a playbook for payment fraud through business email compromise covers rapid contact with the financial institution to attempt recall of funds and reporting to law enforcement. | 2 |
| **12.3.3** | **Verify that** a playbook covers compromise of privileged accounts, including review of all actions taken with the account's privileges. | 2 |
| **12.3.4** | **Verify that** a playbook covers compromise of identity infrastructure such as directory services, identity providers, and federation trusts. | 3 |

---

## C12.4 Data Breach

When personal or regulated data is exposed, the organization must be able to work out whose data it was and what it owes them.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **12.4.1** | **Verify that** a playbook for unauthorized disclosure of personal or regulated data covers identifying the data and individuals affected, assessing the risk to those individuals, and deciding on notification. | 2 |
| **12.4.2** | **Verify that** the organization can identify which individuals' records are held in an affected data store within a time that supports its notification deadlines. | 2 |

---

## C12.5 Other Common Scenarios

Other frequently encountered scenarios each have steps that are easy to miss without a playbook.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **12.5.1** | **Verify that** a procedure for lost or stolen devices covers remote lock or wipe and revocation of the device's credentials and sessions. | 1 |
| **12.5.2** | **Verify that** a playbook for denial-of-service attacks includes the contacts and activation procedure for upstream providers or mitigation services. | 2 |
| **12.5.3** | **Verify that** a playbook for exploitation of internet-facing systems covers emergency mitigation and assessing exposed systems for compromise that occurred before mitigation. | 2 |
| **12.5.4** | **Verify that** a playbook for suspected insider incidents requires involvement of the human resources and legal functions and coordinates the timing of access removal. | 2 |

---

## C12.6 Specialized Environments

Operational technology, AI systems, and products shipped to customers each change what "contain" and "recover" mean.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **12.6.1** | **Verify that**, where the organization operates operational technology, playbooks for those environments are developed with operations and safety personnel and prioritize human safety and process integrity. | 2 |
| **12.6.2** | **Verify that**, where the organization operates AI systems, playbooks cover AI-specific incidents such as prompt injection leading to unauthorized actions or data disclosure, tampering with models or training data, and misuse of agent credentials. | 2 |
| **12.6.3** | **Verify that**, where the organization operates AI systems, responders know how to disable, roll back, or restrict an affected model, agent, or tool integration. | 2 |
| **12.6.4** | **Verify that**, where the organization develops or distributes software or hardware products, a playbook covers incidents affecting product integrity, such as compromise of build or update systems, and coordinates with the product vulnerability response function. | 3 |

---

## References

* [CISA: Federal Government Cybersecurity Incident and Vulnerability Response Playbooks](https://www.cisa.gov/resources-tools/resources/federal-government-cybersecurity-incident-and-vulnerability-response-playbooks)
* [CISA and partners (Joint Ransomware Task Force): #StopRansomware Guide](https://www.cisa.gov/resources-tools/resources/stopransomware-guide)
* [NIST IR 8374 Rev. 1: Ransomware Risk Management, A Cybersecurity Framework 2.0 Community Profile](https://csrc.nist.gov/pubs/ir/8374/r1/final)
* [US Treasury OFAC: Updated Advisory on Potential Sanctions Risks for Facilitating Ransomware Payments](https://ofac.treasury.gov/media/912981/download?inline)
* [Microsoft: Incident response playbooks](https://learn.microsoft.com/en-us/security/zero-trust/security-operations-incident-response-playbooks)
* [NIST SP 800-82 Rev. 3: Guide to Operational Technology (OT) Security](https://csrc.nist.gov/pubs/sp/800/82/r3/final)
* [OWASP Artificial Intelligence Security Verification Standard (AISVS)](https://github.com/OWASP/AISVS)
* [OWASP GenAI Security Project: GenAI Incident Response Guide 1.0](https://genai.owasp.org/resource/genai-incident-response-guide-1-0/)
* [Coalition for Secure AI (CoSAI): AI Incident Response Framework V1.0](https://github.com/cosai-oasis/ws2-defenders/tree/main/incident-response)
* [MITRE ATLAS: Adversarial Threat Landscape for AI Systems](https://atlas.mitre.org/)
* [FIRST PSIRT Services Framework](https://www.first.org/standards/frameworks/psirts/psirt_services_framework_v1.1)
* [ISO/IEC 30111:2019 Vulnerability handling processes](https://www.iso.org/standard/69725.html)
* [OASIS CACAO Security Playbooks v2.0](https://docs.oasis-open.org/cacao/security-playbooks/v2.0/security-playbooks-v2.0.html)
