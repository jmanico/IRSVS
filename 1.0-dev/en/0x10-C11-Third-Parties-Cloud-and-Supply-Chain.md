# C11 Third Parties, Cloud & Supply Chain

## Control Objective

This chapter addresses handling incidents that originate in, pass through, or depend on suppliers and cloud services with the same speed and evidential quality as incidents in environments the organization controls directly.

---

## C11.1 Supplier Obligations

What a supplier will tell the organization, how fast, and what evidence it will hand over must be settled in the contract, not negotiated during an incident.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **11.1.1** | **Verify that** the organization maintains a list of its critical service providers with a security incident contact for each. | 1 |
| **11.1.2** | **Verify that** contracts with service providers that process the organization's data or deliver critical services require notification of security incidents affecting the organization within a defined time. | 2 |
| **11.1.3** | **Verify that** supplier incident notification times are short enough for the organization to meet its own notification deadlines. | 2 |
| **11.1.4** | **Verify that** contracts with critical service providers require cooperation with investigations, including access to relevant logs and evidence. | 2 |
| **11.1.5** | **Verify that** the incident response capability of critical service providers is assessed during selection and at a defined interval thereafter. | 3 |

---

## C11.2 Third-Party Incident Handling

When a supplier or software component is compromised, the organization must be able to work out its own exposure and cut the connection quickly.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **11.2.1** | **Verify that** a documented procedure covers responding to an incident at a supplier, including assessing exposure, restricting the supplier's access, and rotating shared secrets. | 2 |
| **11.2.2** | **Verify that** an inventory of third-party access to the organization's environment, including accounts, network connections, and application integrations, allows a supplier's access to be suspended promptly. | 2 |
| **11.2.3** | **Verify that** the organization can determine which of its systems use a given software component within a defined time, for example by querying software bills of materials. | 2 |
| **11.2.4** | **Verify that**, where security monitoring or response is outsourced, the division of responsibilities during incidents is documented, including who holds authority to execute containment actions. | 2 |

---

## C11.3 Cloud & SaaS Readiness

Cloud and SaaS environments need their own logging, access, containment, and evidence procedures, because the techniques used on premises do not carry over.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **11.3.1** | **Verify that** the division of incident response responsibilities between the organization and each cloud and SaaS provider in scope is documented. | 2 |
| **11.3.2** | **Verify that** control plane audit logging is enabled in every cloud account, subscription, or tenant and in every region, and is aggregated to a location that workload administrators cannot modify. | 2 |
| **11.3.3** | **Verify that** the roles and permissions responders need for investigation and containment are pre-provisioned in every cloud account, subscription, or tenant, including newly created ones. | 2 |
| **11.3.4** | **Verify that** documented procedures cover cloud containment actions, including revoking access keys and active sessions, isolating compute resources, and restricting access to storage. | 2 |
| **11.3.5** | **Verify that** documented procedures cover cloud evidence acquisition, including snapshots of storage volumes and export of provider logs. | 2 |
| **11.3.6** | **Verify that**, for each critical SaaS application, the available audit logs, their retention, and the method of obtaining them are documented, and that optional audit logging is enabled. | 2 |
| **11.3.7** | **Verify that** the procedure for engaging each cloud provider's security or incident support is documented. | 2 |
| **11.3.8** | **Verify that** a dedicated cloud environment, isolated from workload environments, is available for storing and analyzing evidence. | 3 |

---

## References

* [NIST Cybersecurity Framework (CSF) 2.0: GV.SC-08, DE.CM-06, RS.MA-01](https://www.nist.gov/cyberframework)
* [NIST SP 800-61 Rev. 3: Incident Response Recommendations and Considerations for Cybersecurity Risk Management](https://csrc.nist.gov/pubs/sp/800/61/r3/final)
* [NIST SP 800-53 Rev. 5: IR-4(10) Supply Chain Coordination, IR-6(3) Supply Chain Coordination, SR-8 Notification Agreements](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final)
* [NIST SP 800-201: NIST Cloud Computing Forensic Reference Architecture](https://csrc.nist.gov/pubs/sp/800/201/final)
* [ISO/IEC 27001:2022 Annex A 5.19 to 5.23: Supplier relationships and use of cloud services](https://www.iso.org/standard/27001)
* [Cloud Security Alliance: Cloud Incident Response Framework](https://cloudsecurityalliance.org/artifacts/cloud-incident-response-framework)
* [AWS Security Incident Response User Guide](https://docs.aws.amazon.com/security-ir/latest/userguide/)
* [CIS Critical Security Controls: Control 15, Service Provider Management](https://www.cisecurity.org/controls/service-provider-management)
* [Regulation (EU) 2022/2554 (DORA): ICT third-party risk and incident reporting](https://eur-lex.europa.eu/eli/reg/2022/2554/oj)
