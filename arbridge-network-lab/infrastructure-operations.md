# Arbridge Infrastructure Operations (A-Ops)

A-Ops is the team that keeps the network running. It is responsible for the availability, performance, and recoverability of every production surface Arbridge members depend on.

## Scope

- **Production environments** — the infrastructure on which Pulse, the dashboard, and supporting services run
- **Network connectivity** — peering, node infrastructure, and direct connections to supported blockchain networks
- **Observability** — metrics, logs, traces, and alerting across the operational estate
- **Incident response** — on-call rotation, escalation, and post-incident review
- **Disaster recovery** — backup integrity, failover rehearsal, and recovery-time objectives

## Operating commitments

- **Availability.** Critical execution paths are designed with redundancy at every layer. Member-facing surfaces have defined uptime targets, measured against independent probes.
- **Recoverability.** Every component has a documented recovery plan. Recovery procedures are rehearsed on a fixed cadence — not discovered during an incident.
- **Observability.** If a failure mode cannot be observed, it is treated as undetected risk. A-Ops invests in the instrumentation needed to see failure early.

## Interaction with the Risk Desk

When operational conditions deteriorate — network congestion, upstream venue instability, unusual gas volatility — A-Ops coordinates with the Risk Desk on whether to reduce exposure, narrow the execution surface, or halt operations entirely. Availability is never pursued at the cost of executing into unsafe conditions.
