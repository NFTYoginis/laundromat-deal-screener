# Due-diligence framework

What the buyer pulls, in what order, by what professional, on what timeline. The output of Job 4 (due-diligence checklist) is generated from this file, customized to the sub-vertical (per `sub-vertical-routing.md`) and buyer sub-segment (per the routing table in `rules.md`).

Modeled on HVAC repo's `reference/qoe-framework.md` (per `reference/source-repos.md` #10), adapted for laundromat economics. The HVAC analog labels this "QoE framework" — this file uses "due-diligence framework" because for laundromats the work is broader than financial QoE (lease, environmental, equipment, water-bill, regulatory are each comparable in deal-killer weight to QoE).

---

## Phase structure

### Phase 0 — Pre-LOI (before earnest money)

Cheap, parallel, mostly buyer-driven. The buyer's goal is to surface structural deal-killers before committing earnest money.

| Item | Who | Time | Cost (typical, US, varies by metro) |
| --- | --- | --- | --- |
| Read the lease in full | Transactional / commercial-lease attorney | 3–7 days | $400–$1,200 lease-review-only |
| Pre-LOI conversation with SBA lender (structural screen) | SBA lender (buyer should have lender selected before screening listings) | 30 min – 1 hour conversation | $0 (lender's BD time) |
| 24-month bank deposit reconciliation against reported revenue | CPA | 7–14 days | $1,000–$3,000 |
| City permitting records search for catchment | Buyer self-serve | 1–2 hours | $0 (public records) |
| Census-tract demographics review for catchment | Buyer self-serve | 1–2 hours | $0 (Census public data) |
| Drive-the-route observation of competing stores | Buyer self-serve | 2–4 hours | $0 |
| In-store observation across ≥3 day-parts × 2 week-parts | Buyer self-serve | 12+ hours over 1–2 weeks | $0 |
| Card-system transaction data export request | Through broker / seller | 3–7 days to receive | $0 |
| Utility statements request (24 months, directly from utility) | Through broker / seller / utility | 7–21 days to receive | $0 (or small records fee) |
| Independent reason-for-sale verification | Buyer self-serve + 1–2 conversations | 1–2 weeks | $0 |

**Phase 0 deal-killer signals:**

- Broker resistance to producing card data, utility statements, or full lease
- SBA lender flagging structural issues in pre-LOI conversation
- CPA reconciliation showing material gap (>15%) between deposits and reported revenue
- Permitting records showing competing new-build in the catchment
- Stated reason for sale not verifiable

If any of these surface in Phase 0, the buyer should not proceed to LOI without a written plan addressing the issue.

### Phase 1 — Post-LOI, pre-close diligence

Earnest money in escrow; financing contingencies running; lease assignment process initiated. Most diligence work happens here.

| Item | Who | Time | Cost (typical, varies) |
| --- | --- | --- | --- |
| Independent equipment inspection (serial-plate read across full fleet) | Coin-laundry equipment inspector (NOT seller's distributor) | 1–2 days on-site + written report 1 week | $500–$2,000 |
| Independent water-bill audit | Water-bill auditor OR buyer-CPA collaboration | 1–3 weeks | $1,000–$3,000 |
| Phase 1 environmental survey | Environmental consultant | 2–4 weeks | $2,500–$5,000 |
| Lease assignment negotiation with landlord (and anchor if applicable) | Transactional attorney + buyer + landlord | 2–8 weeks | Attorney time billed; landlord may charge admin fee $500–$2,500 |
| Franchise agreement review (if franchise) | Franchise-specialist attorney (different from lease attorney) | 1–2 weeks | $1,500–$4,000 |
| Asset Purchase Agreement (APA) drafting + negotiation | Transactional attorney | 2–6 weeks | $3,000–$10,000 |
| SBA loan application submission + underwriting | SBA lender | 30–90 days from complete file to commitment | Bank fees + SBA guarantee fee per the loan amount |
| Final CPA review of working-capital adjustment + tax-structure | CPA | 1–2 weeks | $1,500–$3,500 |
| Insurance binding (general liability, property, business interruption) | Commercial insurance broker | 1–2 weeks | First-year premiums typically $2,500–$6,000 for a single store |
| Card-system support-status verification with manufacturer | Card-system distributor / manufacturer | 3–7 days written confirmation | $0 |
| General-trades inspection (water heater, HVAC, plumbing, electrical, roof) | General-trades inspector | 1 day on-site + written report 1 week | $400–$1,000 |
| ADA / accessibility compliance review | ADA consultant OR buyer's attorney | 1 week | $500–$1,500 |
| Verify reason-for-sale via additional channels | Buyer + corroborating conversations | Ongoing | $0 |
| Confirm continuation intent from any concentrated customer (if applicable) | Buyer + named customer | 1–2 weeks | $0 |

**Phase 1 deal-killer signals:**

- Equipment inspector reports CapEx burden > Phase 0 estimate by >50%
- Phase 1 environmental flags prior dry-cleaner contamination concerns
- Landlord refuses assignment or imposes conditions beyond standard (rent increase, personal-guarantee carve-outs not in original)
- Anchor (if applicable) refuses or demands consideration
- SBA lender's underwriting flags an issue not surfaced in pre-LOI conversation
- CPA's final working-capital adjustment moves SDE materially

### Phase 2 — Close and transition

Title transfer, key transfer, training period, post-close stabilization.

| Item | Who | Time | Cost |
| --- | --- | --- | --- |
| Close — funding, title, key transfer | Transactional attorney + lender + escrow | 1 day | Closing costs typical ~2–3% of purchase price |
| Seller-to-buyer training period | Seller (per APA — typical 2–4 weeks) | 2–4 weeks | Included in deal |
| Card-system account transfer to buyer | Card-system vendor | 1–3 days | Vendor admin fee |
| Utility account transfer | Utilities | 1–2 weeks | $0 (or small deposit) |
| Insurance binders go effective on close date | Insurance broker | 1 day | First premium due |
| Employee retention conversations (attended stores) | Buyer | First week post-close | $0 (or retention-bonus structure if any) |
| Vendor / supplier introductions | Seller-to-buyer per APA | First 1–2 weeks | $0 |
| Bank account opening / merchant services | Bank + card processor | 2–4 weeks (start in Phase 1) | Bank fees |

---

## Sub-vertical-specific diligence layers

The base framework above applies to all six sub-vertical combinations. Each combination adds specific items. Per `sub-vertical-routing.md`:

### Card-only

- Card-system support status verification is **load-bearing** (no fallback if card system fails). Manufacturer written confirmation required pre-close.
- Card-system processing fees verified (typically 2–3% of card revenue; older agreements may be higher).

### Coin-only

- Bank deposit reconciliation is **load-bearing** for revenue verification (no card data trail). 24-month reconciliation may extend to 36 months.
- Coin theft history reviewed (insurance claims, police reports).
- Coin-vault security inspection.
- Card-system retrofit cost-estimate produced as part of year-1 CapEx (most buyers will plan to add card within year 1).

### Hybrid

- Both card-only and coin-only items apply but at reduced weight.
- Card-to-coin revenue ratio over 12 months reviewed (the trend matters — is card share growing?).

### Attended

- Employee retention conversations are **load-bearing**. Identify key employees, their tenure, their wages, their schedule, their reliability. Plan for any retention-bonus structure.
- Labor cost line scrubbed for off-books employees or 1099-reclassification issues (an SBA-underwriting flag).
- Workers' compensation history reviewed.

### Unattended

- Camera-system / remote-monitoring infrastructure reviewed.
- Cash-collection routine documented (frequency, route, who has keys).
- After-hours incident history (police calls, vandalism, etc.).

### Standalone

- Roof condition is **load-bearing** (no shared structure).
- Parking lot condition.
- Signage / storefront condition.
- HVAC / rooftop unit ages.

### Anchor-store-attached (in-line strip)

- Anchor lease reviewed alongside the laundromat lease (anchor's exit creates the laundromat's co-tenancy / kickout exposure).
- Anchor's tenure + lease term remaining.
- CAM reconciliation history with the anchor's pro-rata share.
- Anchor-consent rights on assignment (if applicable, Phase 0 lease review surfaces this).

---

## Buyer-sub-segment specific layers

### First-time SBA-financed individual

- Pre-LOI lender conversation is **load-bearing** (per `red-flags-checklist.md` §SBA-underwriting-friction).
- Personal financial statement preparation — lenders require comprehensive PFS; buyer should have this ready before LOI.
- Down-payment liquidity source documented (gift, savings, retirement-rollover-via-ROBS, etc.) — each has different lender treatment.
- Reserves verified (lenders typically require 3–6 months of operating expenses in reserve at close).

### E-2 visa buyer

- Visa-renewal timeline relative to lease term (lease should ideally cover at least the next E-2 renewal cycle).
- US-citizen/LPR partner structure (if needed for SBA path — see `sba-financing.md` §E-2-section).
- Investment-amount documentation for E-2 maintenance (USCIS-side; the buyer's immigration attorney handles).

### Regional clusterer

- Existing-portfolio impact analysis (does this listing complement or cannibalize existing stores?).
- Cross-portfolio CapEx schedule (if 2 stores in portfolio also have equipment-age clusters, year-2 CapEx becomes concentrated).
- Management-bandwidth review (can existing management absorb a new store, or does this trigger a hire?).

---

## What this framework does NOT do

- Does not produce a Quality-of-Earnings report. QoE is the buyer's CPA's deliverable; this framework names where QoE would land but produces the screen, not the QoE.
- Does not produce a legal opinion. Legal opinions are the buyer's attorney's deliverables.
- Does not produce an SBA underwriting decision. The lender's underwriting is theirs.
- Does not estimate specific professional fees beyond "typical band, varies by metro." Actual fees should come from named professionals.

---

Last updated: 2026-05-13 (initial build).
