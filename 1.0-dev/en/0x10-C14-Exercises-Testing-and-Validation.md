# C14 Exercises, Testing & Validation

## Control Objective

This chapter addresses proving that the incident response capability works, through exercises that rehearse people and decisions and through technical tests that demonstrate each capability under realistic conditions.

Other chapters require that a capability exists. This chapter requires evidence that it has been exercised. An untested plan, backup, or containment action should be treated as unverified, whatever the documentation says.

---

## C14.1 Exercise Program

Exercises must be regular, must include the people who will actually make the decisions, and must produce tracked improvements.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **14.1.1** | **Verify that** the incident response plan is exercised at least annually with the participation of the assigned incident response roles. | 1 |
| **14.1.2** | **Verify that** an exercise program defines objectives, scenarios, participants, and a schedule that covers the organization's prioritized incident scenarios over a defined cycle. | 2 |
| **14.1.3** | **Verify that** designated decision owners, including executive leadership, participate at least annually in an exercise that requires them to make the decisions assigned to them. | 2 |
| **14.1.4** | **Verify that** exercises include the legal, communications, privacy, and business functions that have incident response roles. | 2 |
| **14.1.5** | **Verify that** each exercise produces an after-action report with findings assigned to owners and tracked to completion. | 2 |
| **14.1.6** | **Verify that** exercises involving critical service providers and the external incident response provider are conducted at a defined interval. | 3 |
| **14.1.7** | **Verify that** at least one exercise per year is unannounced or conducted outside business hours. | 3 |

---

## C14.2 Technical Validation

Each technical capability the response depends on must be demonstrated to work, with its performance measured.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **14.2.1** | **Verify that** restoration from backup is tested at least annually. | 1 |
| **14.2.2** | **Verify that** responder contact details and the out-of-band communication channel are tested at least annually. | 2 |
| **14.2.3** | **Verify that** technical responders perform hands-on investigation and containment in a realistic exercise at least annually. | 2 |
| **14.2.4** | **Verify that** account disablement with session revocation, endpoint isolation, and indicator blocking are tested at least annually, with the time to execute measured. | 2 |
| **14.2.5** | **Verify that** recovery of critical services is tested against their recovery time and recovery point objectives at least annually. | 2 |
| **14.2.6** | **Verify that** emergency access credentials are tested at least annually. | 2 |
| **14.2.7** | **Verify that** evidence acquisition procedures are tested on each platform in scope at least annually. | 3 |
| **14.2.8** | **Verify that** end-to-end detection and response is tested at least annually through adversary emulation, with time to detect and time to contain measured. | 3 |
| **14.2.9** | **Verify that** detections for the organization's prioritized incident scenarios are validated at least annually by executing or simulating the relevant adversary techniques. | 3 |
| **14.2.10** | **Verify that** rebuilding core identity infrastructure is tested at a defined interval. | 3 |
| **14.2.11** | **Verify that** activation of the external incident response provider, including provisioning of access, is tested at a defined interval. | 3 |
| **14.2.12** | **Verify that** retrieval of archived logs is tested, with the time to make them searchable measured. | 3 |

---

## References

* [NIST SP 800-84: Guide to Test, Training, and Exercise Programs for IT Plans and Capabilities](https://csrc.nist.gov/pubs/sp/800/84/final)
* [NIST Cybersecurity Framework (CSF) 2.0: ID.IM-02](https://www.nist.gov/cyberframework)
* [NIST SP 800-53 Rev. 5: IR-3 Incident Response Testing, CP-4 Contingency Plan Testing](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final)
* [CISA Tabletop Exercise Packages (CTEP)](https://www.cisa.gov/resources-tools/services/cisa-tabletop-exercise-packages)
* [CIS Critical Security Controls: Safeguards 17.7 and 11.5](https://www.cisecurity.org/controls/incident-response-management)
* [PCI DSS: Requirement 12.10.2](https://www.pcisecuritystandards.org/document_library/)
* [European Central Bank: TIBER-EU framework for threat intelligence-based ethical red teaming](https://www.ecb.europa.eu/paym/cyber-resilience/tiber-eu/html/index.en.html)
* [MITRE ATT&CK](https://attack.mitre.org/)
