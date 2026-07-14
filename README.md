# DealSponsor — Adversarial Real-Estate Deal Underwriter

An AI skill that fights your deal before your money does. Paste a listing and what you want to do with the property — DealSponsor checks the marketing against public records, tells you how long until you could legally operate, what it really costs, and hands you one cheap "kill test."

**Speculation tool for real-estate speculators. Never legal, tax, or financial advice. Always consult licensed professionals and verify everything.** Full terms: [TERMS_OF_SERVICE.md](TERMS_OF_SERVICE.md).

## Install — paste ONE prompt into Claude Code (desktop, web, or CLI)

Copy this whole block, paste it into any Claude Code session, press enter. Done.

```
Install the DealSponsor skill for me at USER scope so /deal works in every project:
clone https://github.com/RND-Technology/dealsponsor-plugin (or fetch the raw files), then copy
skills/deal to ~/.claude/skills/deal, agents/deal-verifier.md to ~/.claude/agents/deal-verifier.md,
and TERMS_OF_SERVICE.md into ~/.claude/skills/deal/. Verify every file landed by listing them.
Newly installed skills only load when a session starts, so do NOT tell me to type /deal yet —
instead, read ~/.claude/skills/deal/SKILL.md now and follow it directly as my DealSponsor
underwriter: run Gate 0 (temporal pin + deal ledger), show the terms summary, then intake.
Finally tell me, in one line: "/deal is now installed — it appears as a slash command in every
NEW session from now on."
```

**Why this works every time:** the skill runs immediately in this session (Claude follows the file directly), and because it installs to `~/.claude` (user scope, not one project folder), **`/deal` appears in every new session in every project** — restart Claude Code once and it's there for good.

CLI users with plugin support can instead run:

```
/plugin marketplace add RND-Technology/dealsponsor-plugin
/plugin install dealsponsor@dealsponsor-marketplace
```

## Full workspace

The plugin is the free underwriter. The full DealSponsor workspace — saved deals, 10-gate county analysis, Gantt charts, investor-ready packages — lives at **[wealthtechsi.com](https://wealthtechsi.com/?src=plugin)** (free tier; founding rate $49/mo).

## What you get

- **Time-to-Operate first** — months until the use is legal, permit named (the number that kills deals silently)
- **Cash-to-Operate & Total Capital at Risk**
- **Listing–Reality Gap** — marketed claims vs. what public records prove
- **Sponsor Fit** — pass/fail against YOUR time and cash budget (captured once)
- **Independent verification** — nothing tagged VERIFIED without the deal-verifier agent
- **One kill test** — the cheapest action that settles the biggest unknown
- A standalone HTML review page you keep

## License

Thin-client skill files © 2026 Jesse Niesen. Free to install and use with your own Claude subscription; see [TERMS_OF_SERVICE.md](TERMS_OF_SERVICE.md). Premium engine (jurisdiction rules database, comparable-deal matching, deal notifications) runs server-side and is not in this repo.
