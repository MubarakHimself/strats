# strats

Hypothesis storage for indicators and strategies.

Fresh project. Not under QMX. No backtest pipeline. No strategy factory.

Purpose: a local / private corpus of indicators and strategies (public, private, invite-only you have access to) as **hypothesis material** — like keeping research papers offline while access lasts. QMX may consume this later; it does not own this repo now.

Repo: https://github.com/MubarakHimself/strats

## Layout

- `public/` — openly published scripts / notes (with license + source URL)
- `private/` — your own work, not for distribution
- `invite-only/` — material you were granted access to; do not republish
- `sources/` — pointers to upstream repos/tools (attribution only)
- `notes/` — hypotheses, readings, why something mattered

Each item should eventually have a small `meta.yaml` (id, title, kind: indicator|strategy|note, access: public|private|invite-only, provenance, captured_at, license, tags).

## Non-goals (for now)

- QMX integration
- Backtesting / optimization / live trading
- Unofficial TradingView premium bypass / mass scrape of content you are not licensed for

## Related

- TradingView-API fork (tool reference only): https://github.com/MubarakHimself/TradingView-API
