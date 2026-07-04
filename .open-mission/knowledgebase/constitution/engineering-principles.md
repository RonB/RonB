---
resource: open-mission/provision/knowledgebase/constitution/engineering-principles
title: Engineering principles
type: constitution
summary: Repository-wide engineering principles for simple design, clear ownership, canonical vocabulary, validation, and convergence.
owner: architecture
id: constitution:engineering-principles
kind: constitution
status: accepted
---

## Engineering Principles

1. Prefer the simplest direct implementation that satisfies the requirement.
2. Every abstraction must earn its existence.
3. Preserve clear ownership of behavior and state.
4. Do not introduce speculative extension points.
5. Respect documented architecture boundaries and contracts.
6. Use canonical vocabulary from `.open-mission/knowledgebase/product/context.md`.
7. Keep Workspace, StorageRoot, ExternalResource, WorkflowExecution, and AgentExecution responsibilities separate.
8. Comments explain non-obvious reasons, invariants, and constraints.
9. Verify changed behavior before delivery.
10. Remove stale paths, obsolete terms, duplicate docs, and parallel truths when the change makes them unnecessary.
