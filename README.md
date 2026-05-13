# Laundromat Deal Screener

A screening discipline for **first-time SBA-financed laundromat acquisition buyers** (plus light coverage of E-2 visa cash buyers and small regional clusterers). MIT-licensed. Runs in your own Claude Project. Zero install, no API key, no monthly cost beyond the Claude subscription.

**Live landing page:** [nftyoginis.github.io/laundromat-deal-screener](https://nftyoginis.github.io/laundromat-deal-screener/) *(once GitHub Pages is enabled — see Deployment below)*

---

## What this is

You paste a listing (BizBuySell tearsheet, broker email, P&L, lease summary, equipment list). The specialist returns:

- **Verdict:** PURSUE / PROCEED WITH CAUTION / PASS — one-line rationale
- **Ranked risk flags** — severity-ordered, each cited to a specific `reference/` file and row
- **Strengths** — only material ones
- **Data gaps** — what you need to pull before the next step
- **DON'T-DECIDE-YET column** — items you should NOT commit to until specific professional review, each paired with the named professional and the before-action trigger
- **Next 3 concrete steps** — specific actions, not "do diligence"

Five jobs total (screen / compare / valuation / due-diligence / SBA feasibility) plus a `memo` mode that reformats a screen as an 8-section investment-screening memo you could walk into a lender meeting with.

---

## What this isn't

- Not a marketplace, not an auto-screener, not a SaaS, not a hosted product
- Not a replacement for an SBA lender, a transactional attorney, or a CPA
- Not laundromat industry insider expertise — the author hasn't bought a laundromat
- Not domain-extensible beyond laundromat (vending / MHP / car wash etc. would be separate builds — see `reference/_template-vertical/`)

---

## File layout

```
laundromat-deal-screener/
├── README.md                ← you are here
├── LICENSE                  ← MIT
├── .gitignore
├── identity.md              ← persona, buyer sub-segments, scope-limit
├── rules.md                 ← Always / Never / 6 refusal gates / DON'T-DECIDE-YET / routing table
├── examples.md              ← 2 worked listings (fictional-but-realistic): one CAUTION, one PASS
├── memo-mode.md             ← memo trigger + 8-section memo structure
├── reference/
│   ├── laundromat/
│   │   ├── screening-criteria.md       6 dimensions, banded
│   │   ├── industry-benchmarks.md      SDE multiples, cost structure, equipment lifecycle, industry shape
│   │   ├── red-flags-checklist.md      12 flag categories with diligence paths
│   │   ├── valuation-methodology.md    5-step valuation; refusal-without-comps discipline
│   │   ├── due-diligence-framework.md  Phase 0 / 1 / 2 with professionals + costs
│   │   ├── sba-financing.md            7(a) baseline + 3 sub-segment routings
│   │   └── sub-vertical-routing.md     6 sub-vertical combinations
│   └── _template-vertical/             scaffold for spinning up sibling specialists (vending, MHP, etc.)
└── docs/
    └── index.html           ← Pages-ready public landing page (single self-contained file)
```

---

## Setup (in your Claude Project)

About twenty minutes once.

1. **Download the repo.** Clone or ZIP-download from GitHub.
2. **Create a new Claude Project** named "Laundromat Deal Screener" (or whatever you prefer).
3. **Add the files to the Project's knowledge.** Upload:
   - `identity.md`, `rules.md`, `examples.md`, `memo-mode.md`
   - All seven files under `reference/laundromat/`
   - Skip `docs/index.html` and `reference/_template-vertical/` — they're for the public site and future verticals, not the runtime.
4. **Set custom instructions.** Paste:

   > *You are the laundromat deal screener defined in the project knowledge files. Follow identity.md, rules.md, and the reference layer. Always start by stating the buyer sub-segment you're assuming, and invite correction. Verdict first, reasoning second, evidence cited from `reference/`.*

5. **First-run prompt.** Paste a real BizBuySell listing and write:

   > *Screen this listing. I'm a first-time SBA-financed individual buyer.*

   Output should arrive in the verdict-first, ranked-flags, DON'T-DECIDE-YET shape demonstrated in `examples.md`.

---

## First-run prompts (full set)

| Job | Trigger phrase |
| --- | --- |
| 1 — Screen | *"Screen this listing. I'm a [first-time SBA / E-2 / regional clusterer]."* (paste listing) |
| 2 — Compare | *"Compare these listings — which (if any) should I LOI?"* (paste 2–4 listings) |
| 3 — Valuation | *"What's this worth? Give me a $low / $mid / $high band with the comp set."* |
| 4 — Due diligence | *"What do I check at the [pre-LOI / post-LOI pre-close / close] stage?"* |
| 5 — SBA feasibility | *"Will SBA underwriting fund this? Walk the structural facts with me."* |
| memo mode | Type `memo` after any screen output — or prefix a listing-paste with `memo:` |

---

## Buyer sub-segments

The specialist routes differently per buyer. State which you are at conversation start; the specialist asks if you don't.

| Sub-segment | Description | Routing |
| --- | --- | --- |
| **First-time SBA-financed individual** *(primary)* | First laundromat acquisition, planning 7(a) financing, planning to own and operate | Default routing; full reference layer applies |
| **E-2 visa buyer** *(secondary)* | Non-immigrant treaty-investor visa holder; SBA 7(a) generally requires citizenship or LPR status for personal guarantors | `sba-financing.md` §E-2 routing — cash, seller note, partnership-with-LPR-guarantor paths |
| **Small regional clusterer** *(secondary)* | Already operates 2–5 stores; adding one more | `sub-vertical-routing.md` §portfolio-fit + `sba-financing.md` §second-loan-dynamics |

---

## Deployment (GitHub Pages)

Standard GitHub Pages from `/docs`. Operator runs these once:

```bash
# from the laundromat-deal-screener directory:
git init
git add .
git commit -m "Initial commit — laundromat deal screener"

# create the public repo + push (gh CLI authenticated):
gh repo create NFTYoginis/laundromat-deal-screener --public --source=. --remote=origin --push

# enable GitHub Pages serving from /docs:
gh api repos/NFTYoginis/laundromat-deal-screener/pages \
  -X POST \
  -f "source[branch]=main" \
  -f "source[path]=/docs"

# wait ~30–60s, then verify:
open https://nftyoginis.github.io/laundromat-deal-screener/
```

If `gh` isn't authenticated, use the web UI: Settings → Pages → Source = `main` branch, `/docs` folder → Save.

---

## License

MIT. See [`LICENSE`](LICENSE). Fork it, modify it, redistribute it. The reference layer is meant to improve with real-user signal — PRs on benchmark refreshes, new red-flag patterns, and domain corrections are welcome.

---

## Acknowledgments

Structural patterns ported from public ICM specialist repos. Verdict trichotomy and `memo-mode` trigger pattern adapted from the **HVAC Fire Safety Acquisition Analyst** (`github.com/orteug/hvac-fire-safety-acquisition-analyst`, MIT). DON'T-DECIDE-YET column primitive ported from **Grief Admin Compass** (`github.com/astetic-dev/grief-admin-compass`, MIT) via this author's earlier Online Funeral Family Compass build. Routing-table-per-job pattern from this author's Realtor Copilot v2 (`github.com/NFTYoginis/realtor-copilot-v2`, MIT).

Built with [Claude Code](https://claude.com/claude-code).

---

Last updated: 2026-05-13 (initial release).
