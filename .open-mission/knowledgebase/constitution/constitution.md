---
resource: open-mission/provision/knowledgebase/constitution/constitution
title: Open Mission Constitution
type: constitution
summary: Repository-wide law for ownership, boundaries, validation, documentation authority, and convergence.
owner: package
layout: default
status: accepted
---

## Open Mission Constitution

This constitution is the governing starting point for a provisioned repository. Keep it short and update it only when repository-wide law changes.

## Authority

1. The Open Mission installation and daemon-owned canonical state are authoritative for runtime coordination.
2. Tenant-scoped behavior resolves through the active Organization and namespace.
3. Work is Workspace-centered. Workspaces own operator-facing identity and lifecycle.
4. StorageRoots own file and path behavior.
5. ExternalResources own provider resource identity. CredentialAuthority owns provider-neutral authority metadata.
6. WorkflowDefinition owns workflow law. WorkflowExecution owns workflow runtime truth. AgentExecution owns agent runtime truth and audit material.

## Documentation

1. `.open-mission/knowledgebase/` is the authority tree for agents and maintainers.
2. `.open-mission/docs/` is the user-facing documentation tree.
3. Entity pages live only under `.open-mission/knowledgebase/entities/`.
4. ADRs live under `.open-mission/knowledgebase/decisions/`.

## Ownership

1. Every non-trivial behavior must have one clear owner.
2. Entities own invariants and stateful behavior.
3. Policies own legality.
4. Adapters own translation to external systems.
5. Contracts own cross-boundary payloads.
6. UI owns presentation and interaction, not domain truth.

## Discipline

1. Prefer the simplest direct design.
2. Keep owned behavior on the owner.
3. Reject malformed inputs instead of silently normalizing them.
4. Make surgical changes.
5. Validate meaningful changes with deterministic evidence.
6. Remove stale paths, obsolete terms, duplicate docs, and parallel truths when a change makes them unnecessary.
