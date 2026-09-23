# Financial Resonance

Evidence-first event impact graph and research workbench for open-source financial analysis.

Financial Resonance turns an event, expectation, asset and market snapshot into a traceable impact calculation. The project is designed for research workflows where evidence, provenance and uncertainty must remain visible.

## Why this project matters

Financial and economic events propagate across industries, suppliers and assets. Existing tools often collapse observed price movement, causal impact and investment recommendation into one opaque number. This project keeps them separate and fails closed when evidence is missing.

## Current scope

- Replaceable Impact Model contract and deterministic V0.1 calculation baseline
- Point-in-time and evidence semantics: FACT, ESTIMATE, ASSUMPTION and UNKNOWN
- Explicit uncertainty and historical-calibration boundaries
- JSON schemas, fixtures and tests for reproducible review
- No trading execution, no investment advice and no claim of calibrated profitability

## Run

Requires Node.js 22.18+.

```bash
npm install
npm test
node examples/run-fixture.ts
```

The fixture is synthetic and validates the input/output contract only. It is not a financial forecast.

## Open-source maintenance use case

The repository is intended for active maintenance with Codex-assisted pull-request review, test triage, documentation updates and release workflows. External providers are replaceable adapters; they cannot write financial truth directly into the formal graph.

## Safety boundary

Observed price move is not causal impact. Abnormal return is not causal impact. UNKNOWN is not zero. Outputs are research aids, not investment advice or trading instructions.

## License

MIT. See [LICENSE](LICENSE).
