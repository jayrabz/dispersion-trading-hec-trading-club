# Dispersion Trading — Club de Trading HEC Montréal

Recherche sur une stratégie de dispersion trading (vol de l'indice vs vol des composantes),
basée sur la méthodologie de Marshall (2009) et Nelken (2006).

## Équipe

| Nom     | 
|---------|
| Jeremy  | 
| Rami    | 
| Kevin   |
| Rafael  |
| Mia     | 

## Structure du repo

- `data/` — données brutes et traitées (WRDS/OptionMetrics/CRSP) — non versionnées, voir `.gitignore`
- `strategy/` — logique de la stratégie (calcul IOIV/MIV, équation de Markowitz modifiée, définition ATM)
- `backtest/` — simulation du trade, delta hedge, coûts de transaction, résultats


