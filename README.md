# Dispersion Trading — Club de Trading HEC Montréal

Recherche sur une stratégie de dispersion trading (vol de l'indice vs vol des composantes),
basée sur la méthodologie de Marshall (2009) et Nelken (2006).

## Équipe

| Nom     | Rôle                          | Mandat |
|---------|-------------------------------|--------|
| Jeremy  | Lead / encadrement            | Coordination, revue, décisions de scope |
| Rami    | Senior analyste               | Mécanique des instruments (straddle ATM, Greeks), horizon/tenor |
| Kevin   | Senior analyste (quant)       | Pipeline de données, code (Markowitz modifié, IOIV/MIV, delta hedge) |
| Rafael  | Analyste                      | Revue de littérature, estimation de la corrélation implicite |
| Mia     | Analyste                      | Choix de l'indice/univers, poids, définition ATM/interpolation |

## Structure du repo

- `data/` — données brutes et traitées (WRDS/OptionMetrics/CRSP) — non versionnées, voir `.gitignore`
- `strategy/` — logique de la stratégie (calcul IOIV/MIV, équation de Markowitz modifiée, définition ATM)
- `backtest/` — simulation du trade, delta hedge, coûts de transaction, résultats

## Références

- Marshall, C.M. (2009). "Dispersion trading: Empirical evidence from U.S. options markets." *Global Finance Journal*, 20, 289-301.
- Nelken, I. (2006). "Variance swap volatility dispersion." *Derivatives Use, Trading & Regulation*, 11(4), 334-344.

## Statut du projet

En démarrage.
