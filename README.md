# DealSponsor — Adversarial Real-Estate Deal Underwriter

An AI skill that fights your deal before your money does. Paste a listing and what you want to do with the property — DealSponsor checks the marketing against public records, tells you how long until you could legally operate, what it really costs, and hands you one cheap "kill test."

**Speculation tool for real-estate speculators. Never legal, tax, or financial advice. Always consult licensed professionals and verify everything.** Full terms: [TERMS_OF_SERVICE.md](TERMS_OF_SERVICE.md).

## Install — paste ONE prompt into Claude, then just talk

Copy this whole block, paste it into any Claude Code session (desktop, web, or CLI), press enter. Done forever.

```
Install DealSponsor for me so it works everywhere, then start it:
1) Clone https://github.com/RND-Technology/dealsponsor-plugin (or fetch the raw files).
2) Copy skills/deal to BOTH ~/.claude/skills/deal AND ./.claude/skills/deal;
   copy agents/deal-verifier.md to BOTH ~/.claude/agents/ AND ./.claude/agents/;
   copy commands/deal.md to BOTH ~/.claude/commands/ AND ./.claude/commands/;
   put TERMS_OF_SERVICE.md inside both skills/deal folders. Verify by listing every file.
3) Then run it RIGHT NOW in this session: read ~/.claude/skills/deal/SKILL.md and follow it
   exactly — Gate 0 (temporal pin + deal ledger), terms acceptance, then intake.
4) Finally tell me in one line: "DealSponsor is installed. From now on, in any chat, just say
   'underwrite <address>' or 'deal' — no commands needed. /deal also appears in new sessions."
```

**How users use it after install — no commands, no menus, no tech:**
Just type, in plain English, in any session:
- *"Underwrite 4571 Ridge Rd, Nevada County — I want to run weddings there."*
- *"Deal: paste-of-a-Zillow-listing — is this a lemon?"*
- *"Resume my deal."*

Claude recognizes it and runs the full underwriter every time. The `/deal` slash command also appears in new sessions for people who like menus — but nobody ever needs it.

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
