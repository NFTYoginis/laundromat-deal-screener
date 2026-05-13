# Screening criteria

The structured criteria used to convert a listing into a verdict. Six dimensions, each scored against a band. The verdict is **not** a sum of scores — it is a structural read where any single high-severity flag can drive PASS regardless of how the other dimensions score.

Modeled on HVAC Fire Safety Acquisition Analyst `reference/screening-criteria.md` (per source-repos.md #10), adapted for laundromat economics.

---

## Dimension 1 — Financial integrity

**What you're testing:** can the reported numbers be reconciled to verifiable sources?

| Band | Reported revenue source | Reported SDE add-backs | Verdict bias |
| --- | --- | --- | --- |
| Green | Card-system transactional data + bank deposit history reconciled, ≥24 months | Add-backs are limited to documented owner perks (insurance, vehicle, owner-compensation true-up); each item has supporting documentation | PURSUE-eligible |
| Yellow | Mixed card + coin; coin revenue extrapolated from documented coin-pull frequency with reconciled deposit history | Add-backs include reasonable one-time items (one-off CapEx, owner-personal-expense reclassification); 1–2 items are seller-asserted | CAUTION |
| Red | All-coin revenue with no card data; revenue "estimated from coin-pull frequency"; cash-not-deposited add-backs | Add-backs include unverifiable cash-not-deposited; "owner manages this personally" line items; >20% of SDE is asserted-without-documentation | PASS bias |

Cash-not-deposited add-backs are the auto-flag category for SBA underwriting. See `sba-financing.md` §revenue-verification.

## Dimension 2 — Lease structure

**What you're testing:** does the lease support an SBA-financed 10-year amortization, and can the buyer assign without unreasonable consent costs?

| Band | Term remaining + options | Assignment clause | Other clauses | Verdict bias |
| --- | --- | --- | --- | --- |
| Green | ≥10 years total (base + options the buyer controls) | Landlord consent required but not to be unreasonably withheld; standard language | No percentage-rent, no demolition / relocation clauses, CAM is base-year with reasonable annual caps | PURSUE-eligible |
| Yellow | 6–9 years total; landlord historically reasonable; option exercise is buyer-side | Consent required, "reasonable" standard, but anchor or co-tenant interactions exist | Percentage-rent kicks in above a floor materially above current revenue; CAM has reconciliation history available | CAUTION |
| Red | <6 years total; or options require landlord re-approval; or assignment requires anchor tenant consent | Anchor consent required; "in landlord's sole discretion" language; or assignment triggers personal-guarantee carve-outs | Percentage-rent kicks in below current revenue; demolition / relocation / kickout clauses present; CAM history shows large reconciliations | PASS bias |

See `sba-financing.md` §lease-term-rule for SBA-specific lease requirements.

## Dimension 3 — Equipment fleet

**What you're testing:** what is the year-1 to year-3 CapEx exposure?

| Band | Equipment age range | Mix | Maintenance records | Verdict bias |
| --- | --- | --- | --- | --- |
| Green | All machines 0–8 years old; concentration in 3–6 year range | Front-load washer dominant; high-efficiency rated; matched fleet | Distributor-stamped maintenance log + parts-replacement history available | PURSUE-eligible |
| Yellow | Range 4–12 years; oldest cohort approaching but not at end-of-life | Mixed front-load / top-load; mixed efficiency tiers | Spotty maintenance records; some self-maintenance gaps | CAUTION |
| Red | Range includes machines >12–14 years (front-load) or >10 years (top-load) | Top-load dominant; older inefficient models; mismatched fleet | No maintenance records; "owner does it himself" | PASS bias |

Industry-typical equipment lifecycle bands: front-load washers 10–15 years; top-load washers 8–12 years; dryers 12–18 years. See `red-flags-checklist.md` §equipment-lifecycle.

## Dimension 4 — Utility cost structure

**What you're testing:** are the water/sewer and gas/electric costs sustainable at current rates, and what is the rate-hike exposure?

| Band | Water/sewer % of gross | Sewer credit / sub-metering | Rate-hike exposure | Verdict bias |
| --- | --- | --- | --- | --- |
| Green | 18–24% of gross | Sewer credit in place (irrigation meter or evaporation deduction); high-efficiency machines reducing gallons-per-cycle | Metro on a documented multi-year rate plan with caps; no pending rate case | PURSUE-eligible |
| Yellow | 24–28% of gross | No sewer credit but documented water rate is stable | Rate case pending but historical hikes have been moderate | CAUTION |
| Red | >28% of gross | No sewer credit; coin-laundry inefficient fixture mix; meter problems documented | Metro on track for material rate hikes; or sewer-rate trajectory unfavorable | PASS bias |

See `red-flags-checklist.md` §water-bill-ratio for diagnostic questions.

## Dimension 5 — Payment system

**What you're testing:** is the payment system aligned with customer expectations in this corridor, and does it produce verifiable revenue data?

| Band | System | Customer alignment | Data trail | Verdict bias |
| --- | --- | --- | --- | --- |
| Green | Card-only or hybrid with card-dominant mix; modern card system (≤3 years old) | Corridor demographics align with card adoption | Full transaction-level export available, by week / by machine | PURSUE-eligible |
| Yellow | Hybrid coin + card; older card system but functional; cards adopted by partial customer base | Mixed corridor; some customer-base lag on card adoption | Card portion has data trail; coin portion has reconciled coin-pull frequency | CAUTION |
| Red | Coin-only with no card system; or card system older than 7 years with unsupported hardware | Corridor would benefit from card upgrade but seller has deferred | No transaction-level data; revenue is coin-pull extrapolation only | PASS bias |

See `sub-vertical-routing.md` §payment-system for routing differences across card-only / coin-only / hybrid.

## Dimension 6 — Operator-attention model

**What you're testing:** is the buyer's planned operator-attention model compatible with the listing's current staffing structure, and does the transition introduce gaps?

| Band | Current staffing | Hours of owner attention | Transition risk | Verdict bias |
| --- | --- | --- | --- | --- |
| Green | Unattended; owner ~3–8 hours/week (cash collection, refresh, light maintenance) | Buyer plan matches | Low — model is structurally stable across owner transition | PURSUE-eligible |
| Yellow | Attended part-time (1–2 employees, predictable hours); owner ~10–20 hours/week | Buyer plan matches OR buyer plans to reduce attendance | Medium — employee retention and shift coverage matter | CAUTION |
| Red | Owner is the operation (owner present >30 hours/week, no documented systems, "we just know what to do") | Buyer plan diverges materially from current owner-attention model | High — buyer is buying a job, or buyer is overestimating remote-operability | PASS bias |

The owner-is-the-business pattern is HVAC repo's stated auto-PASS trigger. The laundromat version: if the owner cannot articulate the operation as a set of repeatable tasks executable by someone else (or by no one, for unattended), the deal collapses on transition.

---

## How dimensions combine into a verdict

**PURSUE:** at minimum 4 of 6 dimensions in Green, with no dimension in Red. Remaining dimensions in Green or Yellow with clear paths to diligence-resolution.

**PROCEED WITH CAUTION:** at least 1 dimension in Yellow OR 1 dimension in Red where the Red can be moved to Yellow by a specific diligence item (e.g., revenue verification, lease renegotiation). The CAUTION verdict is a directive: *the deal could pencil if [specific items] resolve*.

**PASS:** any one of:

- Dimension 1 (financial integrity) is Red AND cannot be resolved via 24-month deposit reconciliation
- Dimension 2 (lease) is Red AND the landlord/anchor is unwilling to restructure
- Dimension 3 (equipment) is Red AND the year-1 CapEx burden exceeds 25% of purchase price
- Two or more dimensions are Red with no clear diligence path
- HVAC-pattern auto-PASS triggers: owner-is-the-business; customer-concentration (in laundromat: ≥40% of revenue from a single commercial-pickup contract); revenue declining >10% YoY without external cause; price >4.5x SDE without comp justification; active litigation or environmental violations

---

## Edge cases (handle explicitly)

- **Recently-renovated store (≤2 years since major CapEx)** — equipment dimension reads Green, but revenue history may be insufficient (only post-renovation months are representative). Adjust dimension 1 toward Yellow until ≥18 months post-renovation data exists.
- **Distressed seller / forced-sale** — verdict-bias is the same; the discount on price is captured in `valuation-methodology.md`, not in the screening criteria.
- **Pre-existing card-system + coin-vault hybrid** — payment system reads Green/Yellow; do not penalize hybrid vs. pure card-only. Hybrid is the modern default in many corridors.
- **Multi-store seller listing one of several stores** — selling-the-worst-one risk is high; ask seller why this specific store is being sold, not the others. If answer is unconvincing, dimension 1 bias toward Yellow regardless of stated numbers.

---

Last updated: 2026-05-13 (initial build, structurally modeled on HVAC repo's screening-criteria.md per `reference/source-repos.md` #10).
