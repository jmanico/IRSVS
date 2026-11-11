# Contributing

## What is the IRSVS?

The Incident Response Security Verification Standard (IRSVS) is a catalogue of testable requirements for an organization's cybersecurity incident response capability. It is modeled on the OWASP [ASVS](https://owasp.org/www-project-application-security-verification-standard/) and [AISVS](https://github.com/OWASP/AISVS). It is an independent project and is not an OWASP project.

## Current status

IRSVS 1.0 is a draft. All work targets [`1.0-dev/`](1.0-dev/en). Until 1.0 is released, requirements may be added, removed, reworded, moved, and renumbered.

## How can I help?

The most valuable thing you can do right now is read the draft requirements as someone who has run or assessed real incidents and ask:

* **Is this requirement independently testable?** Could one assessor verify it with one specific piece of evidence?
* **Is it a single concern?** Requirements that bundle two distinct testable concerns should be split.
* **Is the level right?** Level 1 should be achievable by a small organization without a dedicated security team. Level 3 should be reserved for what high-assurance environments need.
* **Is anything missing?** Is there something that routinely goes wrong in real incidents that no requirement would catch?
* **Is anything duplicated?** Do two requirements, in the same or different chapters, say the same thing?
* **Is it grounded?** Can the requirement be traced to an authoritative source or to well-established practice?

Please log ideas, issues, and questions at <https://github.com/jmanico/IRSVS/issues> before opening a pull request, especially for changes that would alter the meaning, level, or scope of a requirement. A clear description of a problem is as valuable as a fix.

## Writing requirements

Requirements follow the conventions set out in the [Preface](1.0-dev/en/0x02-Preface.md) and [Using the IRSVS](1.0-dev/en/0x03-Using-IRSVS.md):

* Begin with "Verify that".
* Address a single concern that can be verified with one piece of evidence.
* Describe an outcome, not a product. Name specific technologies only as examples.
* Stay within scope. IRSVS covers the capability to respond to incidents. It does not restate preventive controls, detection engineering, or general business continuity.
* Do not duplicate an existing requirement. Check the whole standard first, since related concerns are often spread across chapters. In particular, requirements that a capability be tested belong in C14.
* Avoid stating what a law requires. Requirements should hold regardless of jurisdiction.

## Sources

Every proposal for a new or changed requirement should cite the source it derives from. IRSVS prefers, in order:

1. International and national standards (ISO/IEC, NIST, IETF)
2. Guidance from government cybersecurity agencies (CISA, UK NCSC, ASD, ENISA, and equivalents)
3. Established community frameworks (FIRST, CIS, MITRE, OASIS)
4. Widely adopted industry practice, supported by public documentation

Link to the publisher's own page. Check that the cited edition is current. Vendor marketing material is not a source.

## AI-assisted contributions

AI tools are welcome as an aid for drafting, spotting gaps, and checking consistency. The line is ownership and substance. Every contribution must reflect the contributor's own judgment, and you should be able to explain and defend every sentence you submit. Requirement text that reads as generic boilerplate, or citations that have not been checked against the source, will be declined regardless of how they were produced.

## License

By contributing, you agree that your contributions are licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](LICENSE.md).
