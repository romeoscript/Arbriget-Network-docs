# Arbridge Engineering Division

The Engineering Division is responsible for the software and systems on which every Arbridge product runs. Its mandate spans the Pulse execution engine, the Arbridge dashboard, cross-chain routing infrastructure, and the internal tooling that keeps the network observable and secure.

## Responsibilities

- **Pulse engine development** — the execution core, its probabilistic validator, and its routing graph
- **Dashboard and member experience** — the surfaces through which members observe and interact with the network
- **Cross-chain infrastructure** — bridge integrations, settlement paths, and liquidity-venue connectors
- **Internal operations tooling** — dashboards, alerting, and runbooks used by the Risk Desk and A-Ops
- **Release discipline** — versioning, staged rollout, rollback rehearsal, and post-deploy verification

## How engineering operates

The division works in lockstep with Core Labs, the Risk Desk, and A-Ops. Changes to Pulse's behavior require Risk Desk sign-off. Changes to infrastructure topology require A-Ops sign-off. No unilateral deploy path exists for any component that can move member capital.

## Quality posture

- Automated test coverage is treated as a non-negotiable property of production code, not an optional add-on
- Every deployment is reversible; every change has a documented rollback
- Code touching key material, signing logic, or settlement flow is reviewed by at least two engineers and verified by the Compliance and Governance Unit

The Engineering Division is held to the same standard it holds the Pulse engine to: correctness measured against evidence, not assertion.
