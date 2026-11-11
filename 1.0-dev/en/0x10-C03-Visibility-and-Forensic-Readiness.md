# C3 Visibility & Forensic Readiness

## Control Objective

This chapter addresses ensuring that the data needed to detect, scope, and investigate an incident exists, is trustworthy, is retained long enough, and is accessible to responders before the incident begins.

---

## C3.1 Asset & Context Information

Responders must be able to find out quickly what a system is, who owns it, how important it is, and what it connects to.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **3.1.1** | **Verify that** responders have access to a current inventory of systems, cloud accounts, and SaaS applications that identifies an owner for each. | 1 |
| **3.1.2** | **Verify that** critical systems and data stores are identified with a business criticality rating that responders can use to prioritize incidents. | 2 |
| **3.1.3** | **Verify that** responders have access to current network architecture and data flow documentation for critical systems. | 2 |
| **3.1.4** | **Verify that** responders have access to an inventory of privileged accounts, service accounts, and trust relationships such as federation and application grants. | 2 |
| **3.1.5** | **Verify that** baselines of expected configuration and behavior are maintained for critical systems so that deviations can be identified during an investigation. | 3 |

---

## C3.2 Log Generation & Coverage

The events an investigator will need must be recorded, and gaps in coverage must be known instead of discovered mid-incident.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **3.2.1** | **Verify that** authentication and administrative activity logging is enabled for identity providers, email, remote access services, and cloud management interfaces. | 1 |
| **3.2.2** | **Verify that** a logging standard defines the log sources, event types, and fields required for incident investigation for each class of system. | 2 |
| **3.2.3** | **Verify that** log coverage is measured against the logging standard, with gaps tracked to remediation or risk acceptance. | 2 |
| **3.2.4** | **Verify that** endpoint telemetry recording process execution, network connections, and persistence-related changes is collected from servers and workstations. | 2 |
| **3.2.5** | **Verify that** network telemetry, including DNS queries and connection records at network boundaries, is collected. | 2 |
| **3.2.6** | **Verify that** access to critical data stores is logged at a granularity sufficient to determine which records or objects were accessed. | 2 |
| **3.2.7** | **Verify that** an alert is generated when an expected log source stops sending data. | 2 |
| **3.2.8** | **Verify that** full network packet capture can be enabled on demand for critical network segments. | 3 |

---

## C3.3 Log Integrity, Time & Retention

Logs must outlive the adversary's dwell time, resist tampering, and share a common clock so that events can be correlated.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **3.3.1** | **Verify that** security-relevant logs are retained for a documented period of at least 90 days. | 1 |
| **3.3.2** | **Verify that** system clocks are synchronized to a consistent, authoritative time source. | 1 |
| **3.3.3** | **Verify that** security-relevant logs are forwarded to a central store separate from the systems that generate them. | 2 |
| **3.3.4** | **Verify that** security-relevant logs are retained for at least 12 months, with at least the most recent 3 months immediately searchable. | 2 |
| **3.3.5** | **Verify that** the central log store prevents modification and deletion of logs by administrators of the source systems. | 2 |
| **3.3.6** | **Verify that** log timestamps are recorded in a consistent format that includes the time zone or UTC offset. | 2 |
| **3.3.7** | **Verify that** responders have pre-provisioned access to search the central log store. | 2 |
| **3.3.8** | **Verify that** log integrity is protected by write-once storage or cryptographic verification. | 3 |
| **3.3.9** | **Verify that** administrative access to the central log store uses credentials that are separate from the production identity system. | 3 |

---

## C3.4 Forensic Acquisition Readiness

The ability to collect evidence from every platform in scope must be prepared in advance.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **3.4.1** | **Verify that** documented procedures exist for acquiring memory, storage, and log evidence from each platform in scope, including workstations, servers, virtual machines, containers, and mobile devices. | 2 |
| **3.4.2** | **Verify that** responders can remotely collect triage artifacts from endpoints without physical access. | 2 |
| **3.4.3** | **Verify that** secure storage capacity sufficient to hold evidence from a significant incident is available or pre-arranged. | 2 |
| **3.4.4** | **Verify that** a mechanism exists to preserve evidence from ephemeral workloads, such as containers and auto-scaled instances, before they are terminated. | 3 |

---

## References

* [NIST SP 800-92: Guide to Computer Security Log Management](https://csrc.nist.gov/pubs/sp/800/92/final)
* [NIST SP 800-86: Guide to Integrating Forensic Techniques into Incident Response](https://csrc.nist.gov/pubs/sp/800/86/final)
* [NIST SP 800-53 Rev. 5: AU family (Audit and Accountability), CM-8 System Component Inventory](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final)
* [NIST Cybersecurity Framework (CSF) 2.0: ID.AM, PR.PS-04, DE.CM](https://www.nist.gov/cyberframework)
* [ASD ACSC, CISA, and partners: Best Practices for Event Logging and Threat Detection](https://www.cisa.gov/resources-tools/resources/best-practices-event-logging-and-threat-detection)
* [OMB M-26-14: Ensuring Effective and Efficient Agency Logging and Network Visibility to Defend Against Evolving Cyber Threats](https://www.whitehouse.gov/wp-content/uploads/2026/05/M-26-14-Ensuring-Effective-and-Efficient-Agency-Logging-and-Network-Visibility-to-Defend-Against-Evolving-Cyber-Threats.pdf) (rescinds and replaces M-21-31)
* [CISA: Logging Reference Architecture](https://www.cisa.gov/resources-tools/resources/logging-reference-architecture)
* [PCI DSS: Requirement 10, Log and Monitor All Access to System Components and Cardholder Data](https://www.pcisecuritystandards.org/document_library/)
* [CIS Critical Security Controls: Control 8, Audit Log Management](https://www.cisecurity.org/controls/audit-log-management)
* [ISO/IEC 27043:2015 Incident investigation principles and processes (investigative readiness)](https://www.iso.org/standard/44407.html)
* [NIST SP 800-201: NIST Cloud Computing Forensic Reference Architecture](https://csrc.nist.gov/pubs/sp/800/201/final)
