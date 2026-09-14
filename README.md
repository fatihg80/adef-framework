# Architecture-Driven Engineering Framework (ADEF)

> A practical, AI-ready engineering framework for designing, building, validating, deploying, operating, and evolving software systems.

[English](README.md) | [العربية](README.ar.md)

## Why ADEF exists

AI coding tools can generate code faster than teams can preserve the reasoning behind it. ADEF treats software engineering knowledge as a first-class project asset so humans and AI agents can work from the same product intent, requirements, architecture, decisions, contracts, security constraints, and operational context.

> **Code should be the result of engineering decisions, not the starting point of them.**

ADEF is not a requirement to write every possible document. Use the smallest set of artifacts that provides enough clarity, traceability, and engineering confidence for your project.

## Engineering lifecycle

```text
Business → Product Vision → Requirements → Scope → Architecture
→ Architecture Decisions → Technical Design → Contracts
→ Implementation → Testing & Validation → Deployment → Operations → Evolution
```

## What ADEF provides

- A structured engineering documentation hierarchy.
- Reusable templates for PRDs, ADRs, TDDs, RFCs, runbooks, and more.
- Guidance for when each artifact is useful and when it is unnecessary.
- An `AGENTS.md` entry point for AI coding agents.
- Documentation profiles that scale from MVPs to enterprise systems.
- An optional AI engineering layer for systems that actually contain AI capabilities.

## Repository structure

```text
.
├── README.md
├── README.ar.md
├── AGENTS.md
├── CONTRIBUTING.md
├── CHANGELOG.md
├── docs/
│   ├── 00-governance/
│   ├── 01-product/
│   ├── 02-requirements/
│   ├── 03-architecture/
│   ├── 04-decisions/
│   ├── 05-design/
│   ├── 06-contracts/
│   ├── 07-security/
│   ├── 08-testing/
│   ├── 09-deployment/
│   ├── 10-operations/
│   ├── 11-ai/
│   └── 12-evolution/
├── templates/
└── examples/
```

## Documentation profiles

| Profile | Best for | Typical scope |
|---|---|---|
| **Essential** | prototypes, internal tools, MVPs | vision, MVP/scope, architecture, key ADRs, acceptance criteria |
| **Standard** | production applications | requirements, C4, design, contracts, security, testing, deployment, operations |
| **Enterprise / Regulated** | government, finance, healthcare, critical systems | full traceability, formal security, resilience, governance, audit evidence |
| **AI Extension** | systems using models or LLM capabilities | AI architecture, model strategy, prompt contracts, safety, evaluation, model documentation |

The AI Extension is optional. Using an AI coding assistant does not by itself make the product an AI system.

## AI-assisted engineering

Move from:

```text
Prompt → Code
```

to:

```text
Intent → Specification → Architecture → Decisions → Design & Contracts
→ Human + AI Implementation → Verification → Production → Feedback → Evolution
```

AI agents should not be expected to remember everything. They should be able to discover a reliable project knowledge base.

## How to use ADEF

1. Choose the smallest profile appropriate for the project.
2. Start with product intent and scope before architecture or implementation.
3. Record consequential decisions as ADRs.
4. Create TDDs only when a change benefits from explicit design.
5. Treat API, event, data, and integration contracts as implementation boundaries.
6. Define validation before considering generated code complete.
7. Keep operational knowledge and evolution decisions in the same system of record.
8. Update documentation when the underlying decision changes.

See [`docs/00-governance/DOCUMENTATION_GUIDE.md`](docs/00-governance/DOCUMENTATION_GUIDE.md).

## For AI coding agents

Start with [`AGENTS.md`](AGENTS.md). It defines reading order and change discipline for agents working in a project that adopts ADEF.

## Status

ADEF is currently in **v0.1.0** development. The first release establishes the framework structure, core guidance, and reusable templates.

## Contributing

See [`CONTRIBUTING.md`](CONTRIBUTING.md).

## License

No open-source license has been selected yet. A license should be chosen before promoting ADEF as an unrestricted open-source project.