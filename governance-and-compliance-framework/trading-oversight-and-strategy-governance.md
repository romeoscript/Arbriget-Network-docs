# Trading Oversight and Strategy Governance

Every strategy Pulse executes against is a governed artifact. Governance begins before a strategy is live and continues for as long as it remains in production.

## Strategy lifecycle

1. **Proposal** — a candidate strategy is documented by Core Labs with its thesis, expected performance surface, risk indicators, and failure modes.
2. **Simulation** — the strategy is run in an isolated environment using historical and live-shadow data. Pulse evaluates it under the same probabilistic validator that will govern it in production.
3. **Risk Desk review** — the Risk Desk evaluates exposure characteristics, worst-case behavior, and the venues the strategy touches. Approval is formal and written.
4. **Staged rollout** — the strategy goes live under tight exposure limits, closely observed, with the ability to halt immediately.
5. **Full activation** — limits are expanded as evidence accumulates that real-world behavior matches expectation.
6. **Continuous oversight** — the strategy's live telemetry is monitored against its approved envelope. Drift triggers review.
7. **Retirement** — when a strategy no longer clears the validator's threshold — whether because markets have changed or venues have shifted — it is taken out of production and archived.

## Oversight principles

- **No silent changes.** Any modification to an approved strategy re-enters governance at the appropriate stage.
- **No override for performance.** Strong performance does not relax oversight. If anything, it invites additional scrutiny to verify the outcome is structural rather than incidental.
- **Failure is information.** When a strategy produces an outcome outside its approved envelope, Core Labs is responsible for explaining why, and the Risk Desk is responsible for deciding what changes as a result.

## Member-visible effect

Members experience strategy governance as consistency: the Pulse engine behaves predictably, execution matches telemetry, and the surface of what Arbridge does is documented and stable — even as the specific strategies behind the surface evolve.
