# C9 Eradication & Recovery

## Control Objective

This chapter addresses removing the adversary's access and the conditions that enabled it, and restoring systems to trustworthy operation from assets whose integrity has been verified.

IRSVS does not replace business continuity or disaster recovery planning. It covers the recovery requirements that are specific to a security incident, where the adversary may have tampered with systems, credentials, and backups.

---

## C9.1 Eradication

Everything the adversary used or left behind must be removed, and the weakness that let them in must be closed, before systems are trusted again.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **9.1.1** | **Verify that** the identified cause of compromise, including malicious code, unauthorized accounts, and the exploited weakness, is removed or remediated before affected systems return to service. | 1 |
| **9.1.2** | **Verify that** systems whose integrity cannot be assured are rebuilt from a trusted source instead of being cleaned in place. | 2 |
| **9.1.3** | **Verify that** all credentials known or suspected to have been exposed are reset or rotated during eradication. | 2 |
| **9.1.4** | **Verify that** the removal of each identified persistence mechanism is confirmed. | 2 |
| **9.1.5** | **Verify that** the exploited vulnerability or misconfiguration is remediated or mitigated on all systems of the same class, not only on those found to be compromised. | 2 |
| **9.1.6** | **Verify that** the environment is swept for known indicators of compromise after eradication to confirm that the adversary's access has been removed. | 2 |

---

## C9.2 Recovery Readiness

The assets needed to rebuild must exist, must be out of the adversary's reach, and must be prioritized before they are needed.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **9.2.1** | **Verify that** backups of critical systems and data are created on a defined schedule. | 1 |
| **9.2.2** | **Verify that** at least one backup copy of critical data is offline, immutable, or otherwise inaccessible using production credentials. | 1 |
| **9.2.3** | **Verify that** recovery time and recovery point objectives are defined for critical services. | 2 |
| **9.2.4** | **Verify that** a documented recovery sequence prioritizes services and accounts for dependencies such as identity, DNS, and network services. | 2 |
| **9.2.5** | **Verify that** trusted system images, infrastructure definitions, and configuration backups are stored so that they remain available and integrity-protected during an incident. | 2 |
| **9.2.6** | **Verify that** a documented procedure covers rebuilding core identity infrastructure when it cannot be trusted. | 3 |
| **9.2.7** | **Verify that** an isolated recovery environment is available in which systems can be restored and validated before reconnection to production. | 3 |

---

## C9.3 Restoration & Validation

Systems must be restored from verified assets, validated before reconnection, and watched afterwards for signs that the adversary has returned.

| # | Description | Level |
| :--------: | ------------------------------------------------------------------------------------------------------------------- | :---: |
| **9.3.1** | **Verify that** documented criteria define when recovery may begin and who approves it. | 2 |
| **9.3.2** | **Verify that** backups and other restoration assets are checked for integrity and indicators of compromise before they are used. | 2 |
| **9.3.3** | **Verify that** the restore point selected for each system is assessed against the incident timeline to confirm that it predates the compromise. | 2 |
| **9.3.4** | **Verify that** restored systems are confirmed to be patched, securely configured, and free of known indicators of compromise before they are reconnected to production. | 2 |
| **9.3.5** | **Verify that** recovered systems are subject to heightened monitoring for a defined period after restoration. | 2 |
| **9.3.6** | **Verify that** service owners confirm normal operation before recovery is declared complete. | 2 |
| **9.3.7** | **Verify that** temporary containment measures and emergency changes are tracked and are either removed or made permanent through change management after recovery. | 2 |

---

## References

* [NIST SP 800-184: Guide for Cybersecurity Event Recovery](https://csrc.nist.gov/pubs/sp/800/184/final)
* [NIST Cybersecurity Framework (CSF) 2.0: RS.MI-02, RC.RP Incident Recovery Plan Execution, PR.DS-11](https://www.nist.gov/cyberframework)
* [NIST SP 800-53 Rev. 5: CP-9 System Backup, CP-10 System Recovery and Reconstitution](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final)
* [NIST SP 800-34 Rev. 1: Contingency Planning Guide for Federal Information Systems](https://csrc.nist.gov/pubs/sp/800/34/r1/upd1/final)
* [CISA and partners (Joint Ransomware Task Force): #StopRansomware Guide](https://www.cisa.gov/resources-tools/resources/stopransomware-guide)
* [CIS Critical Security Controls: Control 11, Data Recovery](https://www.cisecurity.org/controls/data-recovery)
* [ISO/IEC 27035-3:2020 Information security incident management, Part 3: Guidelines for ICT incident response operations](https://www.iso.org/standard/74033.html)
* [ISO/IEC 27031:2025 Information and communication technology readiness for business continuity](https://www.iso.org/standard/27031)
* [ISO 22301:2019 Business continuity management systems](https://www.iso.org/standard/75106.html)
