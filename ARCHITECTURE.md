# APC Architecture

APC is designed as a provenance layer that can sit alongside an existing AI-agent or distributed execution system.

## High-Level Model

```text
Human / Root Authority
        |
        v
   Provenance Claim
        |
        v
   Orchestrator
        |
        +------> Agent A
        |          |
        |          +------> Tool
        |
        +------> Agent B
                   |
                   +------> Sub-agent
                              |
                              +------> External system

Each delegation or execution step can contribute to a verifiable provenance lineage.

Core Principle

The system separates three concerns:

1. Provenance

What was claimed?

Who originated the authorization?

How did the work move through the system?

Can the resulting lineage be verified?

2. Enforcement

Should an action actually be allowed?

APC does not attempt to replace application-level authorization or policy enforcement.

3. Execution

What did the agent or tool actually do?

Runtime systems, observability platforms, and security controls can provide this layer.

Verification Model

A verifier should be able to independently evaluate a provenance claim using the information required by the protocol.

The intended design avoids making provenance verification dependent on the availability of the originating application.

Distributed Workflows

APC is intended for workflows where execution can cross boundaries such as:

agent → agent;

orchestrator → sub-agent;

agent → tool;

process → process;

service → service; and

framework → framework.


The provenance layer should remain independent of the specific orchestration framework.

Security Boundary

APC does not claim that a valid provenance claim means an action was safe.

A valid claim establishes cryptographic provenance according to the protocol.

Applications must separately determine:

whether the authority was appropriate;

whether the requested action was permitted;

whether the execution behaved correctly; and

whether additional approval is required.


Current Implementation

The production/private APC core is intentionally not included in this repository.

This document describes the public architectural direction rather than exposing private implementation details.

More detailed protocol documentation will be published as the public release progresses.
