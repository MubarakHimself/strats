# How strats works (operating plan)

## Goal
Offline **hypothesis library** for indicator/strategy source material.
Not QMX. Not a backtest factory. Not the X “Astra → live trades” workflow.

## What lives here
| Folder | What |
|--------|------|
| `public/` | Openly published scripts (license + URL required) |
| `private/` | Captain’s own scripts |
| `invite-only/` | Scripts the captain’s TradingView account is entitled to; personal archive only — never republish |
| `sources/` | Pointers to tools/repos (e.g. TradingView-API fork) |
| `notes/` | Hypotheses and capture notes |

Each capture gets `meta.yaml`: id, title, kind, access, provenance, captured_at, license, tags.

## Capture modes (in order of preference)
1. **Manual / paste** — captain drops Pine or notes; we file + metadata. No TV session.
2. **Public web sources** — documented public GitHub / docs URLs. No unofficial client.
3. **Account-bound export** — only after captain signs into TradingView on Firstmate’s computer. Then we export **only** indicators that account already has access to (saved / invite-granted), into `invite-only/` or `private/`. One-time login; no repeated asks.
4. **Out of scope** — bulk marketplace scrape, premium-without-subscription, or anything the account is not entitled to.

## Machines
- **Firstmate computer**: capture/normalize/file into this repo; hold TV session if used.
- **GitHub `MubarakHimself/strats`**: source of truth for the library.
- **Captain laptop**: optional; not required once GitHub auth works on Firstmate’s computer.
- **QMX**: future consumer only.

## TradingView-API (fork)
Reference tool only (`sources/` pointer). Useful later for account-bound export of entitled studies — not for standing up a scrape farm on day one.

## Status
Scaffold ready locally. Push to GitHub pending credentials on Firstmate’s computer.
