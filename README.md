# strats

Hypothesis storage for indicators and strategies.

Fresh project. Not under QMX. No backtest pipeline. No strategy factory.

Purpose: a local / private corpus of indicators and strategies (public, private, invite-only you have access to) as **hypothesis material** — like keeping research papers offline while access lasts. QMX may consume this later; it does not own this repo now.

Repo: https://github.com/MubarakHimself/strats


## How we work right now

**Store-first, sort later.** Drop material into the matching folder with a `meta.yaml`; curation can wait.

Operating plan: [`notes/OPERATING.md`](notes/OPERATING.md)  
`meta.yaml` template: [`templates/meta.yaml`](templates/meta.yaml)

**Privacy:** this GitHub repo is **public**. Folders `private/` and `invite-only/` are labeled for sorting — do not push invite-granted or personal scripts here until you are fine with that visibility (or the repo is made private).

## Layout

- `public/` — openly published scripts / notes (with license + source URL)
- `private/` — your own work (label for sort; careful on a public remote)
- `invite-only/` — entitled / invite-granted material (label for sort; never republish; careful on a public remote)
- `sources/` — pointers to upstream repos/tools (attribution only)
- `notes/` — hypotheses, readings, why something mattered

Each item should eventually have a small `meta.yaml` — see [`templates/meta.yaml`](templates/meta.yaml) for fields (`id`, `title`, `kind`, `access`, `provenance`, `captured_at`, `license`, `tags`).

## Non-goals (for now)

- QMX integration
- Backtesting / optimization / live trading
- Unofficial TradingView premium bypass / mass scrape of content you are not licensed for

## Related

- TradingView-API fork (tool reference only): https://github.com/MubarakHimself/TradingView-API
