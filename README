# APC — Autonomous Provenance Claims

**Cryptographic provenance infrastructure for AI-agent delegation and execution.**

> 🚧 Coming soon — public reference material and early-access reservation.

## The Problem

AI-agent systems increasingly delegate work across agents, tools, workflows, and execution boundaries.

Once an instruction moves through those boundaries, ordinary logs can make it difficult to establish:

- Who authorized the work?
- Which delegation chain produced an action?
- Was the provenance altered or broken?
- Which execution context does a claim belong to?
- Can an observed action be cryptographically tied back to its originating authorization?

APC is being developed to address this problem at the **provenance layer**.

## What APC Is

APC is designed around **verifiable provenance claims** — cryptographically protected evidence that can travel with an AI-agent workflow and be independently verified.

The intended architecture includes:

- Cryptographically signed provenance claims
- Execution and delegation lineage
- Integrity protection across a provenance graph
- Independent verification
- Session/context binding
- Clear separation between provenance and runtime enforcement

APC is not intended to replace an agent framework, authorization system, policy engine, or observability platform.

Its purpose is to provide a **verifiable provenance layer** that those systems can consume.

## Why This Matters

Modern agentic systems can involve:

**Human → Orchestrator → Agent → Sub-agent → Tool → External System**

At each boundary, trust assumptions can accumulate.

APC explores a way to preserve cryptographic evidence of that lineage so that systems can answer questions such as:

> "Where did this action originate, and can the claimed delegation chain be verified?"

## Provenance, Not Enforcement

A core design principle is:

**Provenance is evidence, not enforcement.**

APC is intended to establish what was cryptographically claimed and how claims relate to one another.

Whether an application should:

- permit an action,
- reject it,
- quarantine it,
- require additional authorization, or
- trigger an incident response

remains an application and policy-layer decision.

## Potential Use Cases

APC is being explored for systems involving:

- Multi-agent delegation
- Agent-to-agent workflows
- MCP and tool execution
- Distributed AI orchestration
- AI security and incident investigation
- Provenance and auditability
- Secure AI/software supply chains
- Long-running autonomous workflows
- Cross-framework agent interoperability

## Status

APC is currently in **private development and security evaluation**.

The private implementation is intentionally **not included in this repository**.

This public repository will contain only material that is appropriate for public review.

Private implementation details, credentials, private test vectors, deployment configuration, and unreleased protocol material will remain outside this repository.

## Coming Soon

Public material will be released progressively, including:

- Technical documentation
- Architecture overview
- Threat model
- Public reference examples
- Interoperability documentation
- Security considerations
- Public reference implementation information
- Early-access / evaluation information

## Early Interest

If you are building distributed or multi-agent systems and care about verifiable delegation provenance, you can open a GitHub Discussion or Issue describing the workflow you would want APC to support.

There is currently no public SDK release.

Please do not post:

- Secrets or credentials
- Private customer information
- Proprietary architecture
- Confidential security findings

## For Researchers and Security Engineers

APC is particularly interested in feedback from people working on:

- Distributed systems
- AI-agent security
- Cryptographic protocols
- Software supply-chain security
- Observability
- Agent interoperability
- Authorization and delegation
- Secure execution environments

Technical criticism and adversarial review are welcome as the public specification develops.

## Project Status

**Stage:** Private core / public project preparation

**Public release:** Coming soon

**Early-access reservation:** Planned

---

**APC — making agent provenance independently verifiable.**
