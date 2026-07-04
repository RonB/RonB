---
resource: open-mission/knowledgebase/index
title: Open Mission Knowledgebase
type: navigation
summary: Canonical repository-owned knowledge for agents, maintainers, architecture, decisions, entities, contracts, operations, and quality.
owner: repository
nav_title: Knowledgebase
nav_order: 1
has_children: true
---

## Open Mission Knowledgebase

The knowledgebase is the agent-discovery and governance root for this repository. It defines what Open Mission is, what each Entity owns, which decisions are active, and which source files implement those decisions.

Use this tree for engineering work:

| Area | Purpose |
| --- | --- |
| [Product](product/) | Canonical product purpose, vocabulary, capabilities, roles, and scope. |
| [Entities](entities/) | The single canonical Entity documentation folder. |
| [Decisions](decisions/) | Durable ADR register, active decisions, superseded history, and decision templates. |
| [Architecture](architecture/) | Systems, components, boundaries, flows, and diagrams. |
| [Contracts](contracts/) | Stable exchange, package, module, file, and repository contracts. |
| [Doctrine](doctrine/) | Reusable implementation principles, patterns, anti-patterns, conventions, and examples. |
| [Operations](operations/) | Runbooks and operational procedures. |
| [Quality](quality/) | Requirements, verification rules, audits, exemptions, and lessons. |

User-facing documentation lives in [`../docs/`](../docs/). Do not duplicate governance pages into user docs. User docs may link here when a reader needs source-level detail.
