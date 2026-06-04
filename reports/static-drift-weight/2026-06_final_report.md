# Final report · Static Drift Weight · 2026-06

**Frozen.** This file is immutable. Corrections are issued as a new dated file.

## Scope

Final summary of the static-drift-weight backtest, at the same redaction tier as the
[strategy repo](https://github.com/DuiArte/static-drift-weight): ratios and verdicts,
no notional, no live weights.

## Results (illustrative placeholders)

| Metric | Value |
|---|---|
| CAGR | ~x% |
| Sharpe | ~1.x |
| Max drawdown | −xx% |
| Deflated Sharpe | positive |
| PBO | low |

## Stress verdicts

- **2008 GFC** — survived; drawdown shallower than broad-equity benchmark.
- **2020 COVID** — survived; faster recovery than benchmark.

## Method notes

Walk-forward with purged cross-validation; costs modeled. Exact windows, parameters,
and the equity series with real dates are withheld (private).

## Provenance

Produced via the [publish procedure](https://github.com/DuiArte/ai-procedures-quant);
sanitized through `publish_artifact()`.

> Placeholder draft — replace metrics with the reviewed final values before launch.
