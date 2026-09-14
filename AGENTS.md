# ADEF Agent Instructions

This repository is designed to be usable by humans and AI coding agents.

## Mandatory reading order before implementation

1. `docs/01-product/PRODUCT_VISION.md`
2. `docs/01-product/SCOPE_GUARDRAILS.md`
3. Relevant files under `docs/02-requirements/`
4. `docs/03-architecture/ARCHITECTURE.md`
5. Relevant ADRs under `docs/04-decisions/`
6. Relevant TDDs under `docs/05-design/`
7. Relevant contracts under `docs/06-contracts/`
8. Security and testing constraints as applicable

## Change discipline

- Do not invent requirements that are not documented.
- Do not silently override an accepted ADR.
- For a material architectural change, propose or update an ADR before implementation.
- For a substantial technical change, create a TDD when design trade-offs matter.
- Preserve API, event, schema, and integration contracts unless the change explicitly updates them.
- Treat tests and acceptance criteria as executable evidence, not optional cleanup.
- Update documentation when a change invalidates it.
- Prefer the smallest change that satisfies the documented requirement.

## Definition of done

A change is not complete only because the code compiles or runs. It should satisfy applicable requirements, contracts, tests, security constraints, operational considerations, and documentation updates.