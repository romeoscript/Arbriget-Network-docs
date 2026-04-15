# Arbridge Core Labs

Arbridge Core Labs is the research arm of the Arbridge Network Lab. It is where opportunity surfaces are studied, new strategies are prototyped, and the assumptions underlying the Pulse engine are continuously re-examined.

## Remit

Core Labs is chartered to answer a single standing question: **where is the next structural inefficiency, and is it durable enough to execute against?**

## Activities

- **Market microstructure research** — venue-level studies of liquidity fragmentation, fee dynamics, and block-inclusion behavior
- **Strategy prototyping** — building, back-testing, and shadow-running candidate strategies in isolated environments before any production exposure
- **Model refinement** — continuous tuning of Pulse's probabilistic validation layer using real execution telemetry
- **Post-incident review** — when an execution outcome deviates materially from the engine's prediction, Core Labs is responsible for explaining why

## Interaction with production

Core Labs does not push code or strategy into the production Pulse engine directly. Promotion follows a defined path: isolated simulation → shadow execution → Risk Desk approval → staged rollout → full activation. This separation is deliberate — research operates without production pressure, and production operates without unvetted research changes.

## Publishing

Core Labs findings that materially shift member-visible behavior are summarized in the [Education Hub](../learning-and-resources/arbridge-education-hub.md). Methodology is explained; specific strategy parameters remain proprietary.
