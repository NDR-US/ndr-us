# Brian Covarrubias

Independent research exploring AI governance, cryptographic verification systems, and evidentiary infrastructure for autonomous systems.

Currently building **CEYO**, a conceptual architecture examining how AI decision events can produce deterministic, cryptographically sealed artifacts that enable independent verification without exposing model internals.

---

## Technical Areas

AI governance  
cryptographic verification  
auditability of automated systems  
risk and safety infrastructure  
deterministic data canonicalization  

---

## Current Project

### CEYO — Evidentiary Infrastructure for Autonomous Systems

CEYO explores a neutral evidentiary layer capable of producing deterministic artifacts describing AI inference events.

These artifacts are designed to support later independent verification using cryptographic hashing and digital signatures while preserving the confidentiality of proprietary model weights and internal system architecture.

Core ideas explored:

- policy-scoped decision capture  
- deterministic canonicalization  
- SHA-256 hashing  
- digital signatures for artifact integrity  
- independent verification workflows  

Protocol repository:  
https://github.com/ndr-us/ceyo-protocol  

Project site:  
https://ndr-us.github.io/ceyo-site/

---

## Technical Demonstration

The CEYO prototype includes a minimal Python implementation demonstrating deterministic artifact generation and verification.

The demonstration explores the following workflow:

1. Capture a structured AI decision event  
2. Canonicalize the record deterministically  
3. Produce a SHA-256 hash of the canonical artifact  
4. Generate a digital signature  
5. Verify artifact integrity independently  

Example components included in the repository:

**seal_artifact.py**  
Creates a deterministic artifact from structured event data and produces a cryptographic signature.

**demo.py**  
Demonstrates the full artifact lifecycle:

record → canonicalize → hash → sign → verify

This prototype illustrates how AI decision records could be sealed and later verified without exposing internal model weights or proprietary system architecture.

Repository:  
https://github.com/ndr-us/ceyo-protocol

---

## Background

Former **CAL FIRE Type 1 handcrew firefighter** experienced in safety-critical operational environments.

Traveled across **70+ countries** and worked internationally across six countries.

Based in **San Diego, California.**
