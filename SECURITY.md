# Security Policy

## Scope

APC is an early-stage project focused on cryptographic provenance for AI-agent delegation and execution workflows.

The public repository does not contain the private APC core implementation.

## Reporting a Vulnerability

If you discover a security issue in material published in this repository, please do not publicly disclose exploitable details before we have had an opportunity to investigate.

For now, open a GitHub issue with the title:

`[SECURITY] Private disclosure requested`

Do not include:

- credentials or secrets;
- private customer information;
- unpublished exploit code;
- proprietary system information; or
- sensitive production data.

A dedicated private security-reporting channel will be published before the public reference implementation is released.

## Security Philosophy

APC is designed as a provenance layer.

Its purpose is to provide cryptographically verifiable evidence of delegation and execution lineage.

APC should not be interpreted as a complete authorization, policy-enforcement, or runtime-security system.

Applications integrating provenance information remain responsible for deciding whether an action should be permitted.

## Current Status

The APC core is currently undergoing private development and security evaluation.

Public protocol and implementation details will be released progressively.
