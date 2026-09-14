# Documentation Guide

## Purpose

Define how ADEF documentation should be selected, owned, updated, and connected to delivery.

## Principle

Documentation exists to preserve decisions, constraints, contracts, evidence, and operational knowledge. It should reduce ambiguity, not create ceremony.

## Profiles

### Essential
Use for prototypes, internal tools, and small MVPs. Keep only the artifacts required to align the team and prevent costly ambiguity.

### Standard
Use for production systems with multiple contributors, integrations, operational responsibilities, or meaningful architectural decisions.

### Enterprise / Regulated
Use when traceability, formal governance, security controls, resilience, auditability, or regulatory evidence are required.

### AI Extension
Add only when the product itself contains AI/ML/LLM behavior that must be designed, evaluated, governed, or monitored.

## Every artifact should answer

- Why does this document exist?
- When should it be used?
- When should it not be used?
- Who owns it?
- What are its inputs?
- What decision or output should it produce?
- Which later artifacts depend on it?
- What changes require it to be updated?

## Lifecycle rule

Documentation should evolve with decisions. A stale document that contradicts the system is worse than no document.

## AI rule

AI may draft artifacts, but accountable humans remain responsible for validating assumptions, trade-offs, security implications, and final decisions.