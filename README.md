# The Hesstimations

*Evidence over intuition.*

Football market intelligence and research for the NFL and NCAA FBS: model estimates ("Hesstimations"),
sportsbook and consensus prices, the evidence for and against each disagreement, and honest tracking
of how the model actually performs.

This is an analytical and educational project. It does not accept wagers, hold money, place bets,
or promise results. Models are uncertain, and historical results do not guarantee future results.

## Repository layout

| Path | Purpose |
|---|---|
| `pipeline/` | Python: ingestion, data quality, features, models, evaluation |
| `web/` | Next.js application (not started) |
| `supabase/` | Database migrations and config (created in a later milestone) |
| `docs/` | Architecture decisions and documentation |

## Notices

- Code license: MIT (see `LICENSE`). It covers our source code only.
- Third-party data: see `DATA_NOTICE.md`. No third-party data is stored in this repository.
- Security: see `SECURITY.md`.
