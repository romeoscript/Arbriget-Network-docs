# Compliance and Operational Architecture

The Arbridge compliance program is not a department that reviews work after the fact — it is an architectural layer woven through every operational surface.

## Architectural layers

**Layer 1 — Member perimeter.** Identity verification, sanctions screening, and source-of-funds review form the entry boundary. Nothing reaches the Pulse engine without clearing this layer.

**Layer 2 — Execution perimeter.** The Risk Desk's approved venue and token registry defines the operational surface Pulse is allowed to touch. The engine refuses to route outside this perimeter — not as policy, but as code.

**Layer 3 — Telemetric perimeter.** Every execution, settlement, and disbursement is written to an immutable log that both members and internal control functions reconcile against independently.

**Layer 4 — Governance perimeter.** Material changes to any of the above — new venues, new tokens, new strategies, new jurisdictions — require review through the Compliance and Governance Unit and, where relevant, the Risk Desk before they go live.

## Why layered architecture matters

A single point of compliance is a single point of failure. By distributing compliance enforcement across entry, execution, observation, and change-management, Arbridge ensures that a failure at any one layer is contained by the others.

## Review cadence

The architecture itself is subject to periodic review. Independent assessors evaluate both the controls as designed and the controls as operating. Findings drive architectural change — compliance posture at Arbridge is a living property of the system, not a frozen artifact.
