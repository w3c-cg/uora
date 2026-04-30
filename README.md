# Physical Asset Attestation (UORA) Community Group

## Overview

The Physical Asset Attestation (UORA) Community Group operates under the World Wide Web Consortium (W3C) to define a vendor-neutral, decentralized framework for representing, identifying, and verifying physical assets in digital systems.

UORA establishes a model for binding physical objects to cryptographically verifiable digital representations, enabling lifecycle tracking, state verification, and interoperable data exchange across organizational boundaries.

This work builds on existing W3C standards, including:
- Decentralized Identifiers (DIDs)
- Verifiable Credentials Data Model (VCs)

---

## Mission

To develop a universal, interoperable protocol for **physical asset identity and attestation**, enabling verifiable interactions between physical and digital systems across industries.

---

## Scope

The group focuses on the technical specifications required to bind physical assets to digital identifiers and represent their lifecycle through verifiable attestations.

### Universal Addressing
Define mechanisms for assigning and resolving decentralized identifiers (DIDs) to physical assets at multiple levels of granularity:
- Batch  
- SKU  
- Serialized unit  

---

### Attestation Schemas
Define standardized data models and vocabularies for representing lifecycle events as verifiable attestations.

Core event categories include:
- **Origin** — creation, extraction, or manufacture  
- **Transfer** — change of custody or ownership  
- **Transformation** — processing, assembly, or modification  
- **Disposition** — recycling, decommissioning, or end-of-life  

---

### Secure Physical Binding
Establish specifications and best practices for securely linking physical assets to their digital identifiers, including:
- Tamper-evident mechanisms  
- Physical-digital binding techniques (e.g., NFC, QR, secure elements, IoT devices)  
- Verification of possession and state  

---

### Implementation and Interoperability
Define guidance for integrating UORA with existing enterprise systems and networks, including:
- ERP systems  
- Supply chain management systems  
- Interoperability with verifiable data ecosystems  

---

## Deliverables

The group is expected to produce the following outputs:

### UORA Core Specification
A formal definition of:
- DID-native addressing of physical assets  
- Resolution and representation models  
- Core architectural components  

---

### Universal Resource Attestation Schemas
A reusable library of:
- Event-based attestation models  
- Cross-industry vocabularies  

---

### Secure Physical Binding Specification
A technical specification describing:
- Binding methods  
- Security considerations  
- Verification approaches  

---

### Implementation Guidance and Use Cases
Non-normative documentation covering:
- Reference architectures  
- Integration patterns  
- Real-world use cases  

---

## Success Criteria

The Community Group will be considered successful when:
- At least two independent implementations demonstrate interoperability using UORA specifications  
- UORA is adopted in multi-party environments involving physical asset tracking  
- External groups or ecosystems build on UORA as a foundational layer  

---

## Out of Scope

The group does not define:
- New blockchain or distributed ledger protocols  
- New cryptographic primitives  
- Vendor-specific hardware, sensor, or IoT platforms  
- Domain-specific business workflows  

---

## Relationship to Other Work

UORA provides a foundational layer for domain-specific applications, including:
- Supply chain systems (e.g., Verifiable Supply Chain Community Group)  
- Asset tracking and provenance systems  
- Compliance and regulatory reporting frameworks  

These systems build on UORA by defining domain-specific constraints, profiles, and governance models.

---

## Participation

Participation is open to all interested individuals and organizations.

To contribute:
1. Join the Community Group via W3C  
2. Participate in discussions via the public mailing list  
3. Contribute through GitHub issues and pull requests  

---

## Communication

- Mailing List: *(add UORA CG mailing list)*  
- GitHub: https://github.com/w3c-cg/uora  
- Meeting details and minutes are shared via the mailing list  

---

## License

This work is published under the W3C Community Contributor License Agreement (CLA).

---

## Acknowledgements

This work is developed collaboratively by participants of the UORA Community Group.

---

## Current Work

- [ ] Abstract and Scope Definition  
- [ ] Core Architecture (Actors, Objects, Flows)  
- [ ] Event-Based Attestation Model  
- [ ] Secure Physical Binding Approaches  

---