# DeVMurshid Safety and Agents

This note expands the public-safe interpretation of the real `agents list` and `doctor` outputs.

## Agent model

The built-in agent list suggests a workflow where different roles handle different responsibilities:

- analysis
- repo mapping
- architecture
- symbol verification
- TDD gating
- implementation
- hygiene review
- documentation
- PR preparation

## Safety posture

The public `doctor` output shows that the system can expose and reason about:

- whether file writes are allowed
- whether shell execution is allowed
- whether git cleanliness is required
- whether secret patterns are guarded
- whether task scope is capped

## Why this is important publicly

These details show that the product direction is built around controlled engineering workflows, not just high-speed code generation claims.
