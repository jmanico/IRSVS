# C2 Team, Roles & Responder Readiness

## Control Objective

This chapter addresses ensuring that the people who will respond to an incident are identified, reachable, trained, and equipped before the incident occurs.

---

## C2.1 Roles & Structure

Incident response roles must be defined and filled, with a clear command structure, so that nobody is working out who is in charge during an incident.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **2.1.1** | **Verify that** the roles needed during an incident, at minimum incident lead, technical investigation, and communications, are defined and assigned to named individuals or external providers. | 1 |
| **2.1.2** | **Verify that** each incident response role has at least one designated alternate. | 2 |
| **2.1.3** | **Verify that** the legal, privacy, human resources, communications, IT operations, and executive functions each have a named representative for incident response. | 2 |
| **2.1.4** | **Verify that** each incident has a single incident lead at any time, with a documented procedure for handing over leadership. | 2 |
| **2.1.5** | **Verify that** a documented staffing model for incidents lasting longer than one working shift defines responder rotation and maximum continuous duty periods. | 3 |

---

## C2.2 Contact & Availability

Responders must be reachable when needed, including when the organization's own systems are the thing that has failed.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **2.2.1** | **Verify that** an incident contact list holds current contact details for incident response roles, alternates, key vendors, and relevant external parties. | 1 |
| **2.2.2** | **Verify that** the incident contact list includes, for each responder, at least one contact method that does not depend on the organization's own systems. | 1 |
| **2.2.3** | **Verify that** the incident contact list is validated at least annually. | 1 |
| **2.2.4** | **Verify that** a defined method exists for reaching an incident responder outside business hours. | 1 |
| **2.2.5** | **Verify that** an on-call arrangement defines who is on call and the maximum time to acknowledge an incident notification. | 2 |
| **2.2.6** | **Verify that** incident response is available at all times with a defined maximum time to engage a qualified responder. | 3 |

---

## C2.3 Training & Competence

Everyone must know how to report an incident, and those with response roles must be competent to perform them.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **2.3.1** | **Verify that** all workforce members are trained, at onboarding and at least annually, to recognize and report suspected security incidents. | 1 |
| **2.3.2** | **Verify that** individuals assigned incident response roles receive training specific to their role within a defined period after assignment and at least annually thereafter. | 2 |
| **2.3.3** | **Verify that** technical responders have documented competence in investigating the platforms the organization operates, including its operating systems, cloud platforms, and identity systems. | 2 |
| **2.3.4** | **Verify that** the incident response team's skills are assessed against the organization's technology and threat profile at least annually, with identified gaps tracked to closure. | 3 |

---

## C2.4 External Support

Outside help must be arranged before it is needed, because procurement and legal agreements cannot be completed at incident speed.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **2.4.1** | **Verify that** the external parties the organization would call for incident response assistance have been identified in advance and recorded in the incident contact list. | 1 |
| **2.4.2** | **Verify that** an agreement with an external incident response provider is in place with defined response time commitments, where internal capability does not cover all required response functions. | 2 |
| **2.4.3** | **Verify that** the procedure for granting external responders access to environments and data, including the required legal agreements, is documented. | 2 |
| **2.4.4** | **Verify that** points of contact at relevant law enforcement agencies and the national or sector CSIRT have been identified before an incident. | 2 |
| **2.4.5** | **Verify that** the organization participates in at least one information sharing community relevant to its sector or region. | 3 |

---

## C2.5 Responder Tooling & Access

Responders must have the tools, access, and communication channels they need, and these must survive compromise of the environment being investigated.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **2.5.1** | **Verify that** an out-of-band communication channel independent of the organization's primary identity and messaging systems is established, with all incident response roles enrolled. | 2 |
| **2.5.2** | **Verify that** an incident tracking system is available to record and manage incidents. | 2 |
| **2.5.3** | **Verify that** tools for evidence acquisition and analysis are approved, licensed, and available for every platform in scope before an incident. | 2 |
| **2.5.4** | **Verify that** emergency access credentials for critical systems, including identity, cloud management, security tooling, and backup systems, are stored securely and that their use generates an alert. | 2 |
| **2.5.5** | **Verify that** an isolated analysis environment is available for examining malicious code and untrusted artifacts. | 3 |
| **2.5.6** | **Verify that** incident response tooling, communications, and case data remain available and confidential if the production identity system is compromised. | 3 |

---

## References

* [NIST SP 800-61 Rev. 3: Incident Response Recommendations and Considerations for Cybersecurity Risk Management](https://csrc.nist.gov/pubs/sp/800/61/r3/final)
* [NIST SP 800-53 Rev. 5: IR-2 Incident Response Training, IR-7 Incident Response Assistance](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final)
* [FIRST CSIRT Services Framework v2.1](https://www.first.org/standards/frameworks/csirts/csirt_services_framework_v2.1)
* [Open CSIRT Foundation: SIM3 Security Incident Management Maturity Model](https://opencsirt.org/csirt-maturity/sim3-and-references/)
* [ISO/IEC 27035-2:2023 Information security incident management, Part 2: Guidelines to plan and prepare for incident response](https://www.iso.org/standard/78974.html)
* [CIS Critical Security Controls: Safeguards 17.1, 17.2, 17.5, and 17.6](https://www.cisecurity.org/controls/incident-response-management)
* [FEMA National Incident Management System (NIMS)](https://www.fema.gov/emergency-managers/nims)
* [Google SRE Book: Managing Incidents](https://sre.google/sre-book/managing-incidents/)
