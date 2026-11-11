# C8 Containment

## Control Objective

This chapter addresses limiting the spread and impact of an incident quickly, through deliberate decisions and proven technical capabilities, without destroying evidence or causing avoidable harm.

---

## C8.1 Containment Decisions

Containment trades off speed, evidence, service availability, and what the adversary learns, so the choice must be made deliberately and recorded.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **8.1.1** | **Verify that** the incident response plan documents the available containment actions and who may execute each. | 1 |
| **8.1.2** | **Verify that** documented criteria guide the choice of containment strategy, including potential damage, the need for evidence preservation, service availability, and the effort and duration of the action. | 2 |
| **8.1.3** | **Verify that** containment decisions and their rationale, including any decision to delay containment in order to observe adversary activity, are recorded in the incident record. | 2 |
| **8.1.4** | **Verify that** the owners of affected business services are identified and are consulted or informed about containment actions according to pre-defined rules. | 2 |
| **8.1.5** | **Verify that** containment actions in environments with safety or physical process implications require approval from the operational owner of the affected process. | 2 |
| **8.1.6** | **Verify that** containment of an established intrusion is planned and executed as a coordinated action across all known adversary footholds, so that the adversary cannot react to partial containment. | 3 |

---

## C8.2 Containment Capabilities

The technical means to cut off an adversary must exist, be within responders' reach, and be confirmed to have worked.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **8.2.1** | **Verify that** responders can disable a user account and revoke its active sessions and tokens. | 1 |
| **8.2.2** | **Verify that** responders can disconnect an affected device from the network. | 1 |
| **8.2.3** | **Verify that** responders can remotely isolate an endpoint from the network while retaining the access needed for investigation. | 2 |
| **8.2.4** | **Verify that** responders can block malicious domains, IP addresses, URLs, file hashes, and email senders across relevant security controls within a defined time. | 2 |
| **8.2.5** | **Verify that** a documented procedure covers revoking and rotating credentials, API keys, tokens, and certificates, including those used by service accounts and automation. | 2 |
| **8.2.6** | **Verify that** responders can remove a malicious email from all mailboxes after delivery. | 2 |
| **8.2.7** | **Verify that** pre-identified network isolation points allow segments, sites, or environments to be separated from one another. | 2 |
| **8.2.8** | **Verify that** responders confirm that each containment action took effect. | 2 |
| **8.2.9** | **Verify that** a documented procedure covers organization-wide credential reset, including the trust anchors of directory and federation services. | 3 |

---

## C8.3 Safe Containment

Containment actions are themselves changes to production and must be controlled so that the response does not cause its own outage.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **8.3.1** | **Verify that** changes made during containment are recorded in sufficient detail to be reversed. | 2 |
| **8.3.2** | **Verify that** emergency changes made during an incident follow a documented emergency change procedure that includes retrospective review. | 2 |
| **8.3.3** | **Verify that** the dependencies of critical services are documented so that the business impact of a containment action can be assessed before it is taken. | 3 |

---

## References

* [NIST SP 800-61 Rev. 3: Incident Response Recommendations and Considerations for Cybersecurity Risk Management](https://csrc.nist.gov/pubs/sp/800/61/r3/final)
* [NIST Cybersecurity Framework (CSF) 2.0: RS.MI-01 Incidents are contained](https://www.nist.gov/cyberframework)
* [NIST SP 800-53 Rev. 5: IR-4 Incident Handling](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final)
* [CISA: Federal Government Cybersecurity Incident and Vulnerability Response Playbooks](https://www.cisa.gov/resources-tools/resources/federal-government-cybersecurity-incident-and-vulnerability-response-playbooks)
* [ISO/IEC 27035-3:2020 Information security incident management, Part 3: Guidelines for ICT incident response operations](https://www.iso.org/standard/74033.html)
* [MITRE D3FEND](https://d3fend.mitre.org/)
* [NIST SP 800-82 Rev. 3: Guide to Operational Technology (OT) Security](https://csrc.nist.gov/pubs/sp/800/82/r3/final)
* [Microsoft: Incident response playbooks](https://learn.microsoft.com/en-us/security/zero-trust/security-operations-incident-response-playbooks)
