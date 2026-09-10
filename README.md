# Dispersion Trading - HEC Montréal Trading Club

Research on a dispersion trading strategy,
based on the methodology of Marshall (2009) and Nelken (2006).

## Team

| Name    |
|---------|
| Jeremy  |
| Rami    |
| Kevin   |
| Rafael  |
| Mia     |

## Repo structure

- `data/` — raw and processed data (WRDS/OptionMetrics) — not version-controlled, see `.gitignore`
- `strategy/` — strategy logic (IOIV/MIV calculation, modified Markowitz equation, ATM definition)
- `backtest/` — trade simulation, delta hedging, transaction costs, results
