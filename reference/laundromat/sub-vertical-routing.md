# Sub-vertical routing

The six sub-vertical combinations the specialist screens, and how the screening logic differs per combination. Per the brief's Precondition 3 default (a): cover all six.

**The three axes are orthogonal:**

1. **Payment system:** card-only / coin-only / hybrid
2. **Staffing:** attended / unattended
3. **Real-estate posture:** standalone / anchor-store-attached (in-line strip retail)

3 × 2 × 2 = 12 theoretical combinations, but the operationally distinct combinations cluster into **six** (the brief's Precondition 3 framing). Below: each of the six combinations, with the specific screening differences that matter.

Listings outside these combinations — route-only laundry pickup, commercial-B2B laundry, drop-off-service-only storefront with no self-serve — fire Gate 5 (off-domain refusal in `rules.md`).

---

## §payment-system (cross-cutting)

### card-only

- Modern installs default here; trend favors
- Customer-base must be card-aligned; some corridors lag adoption
- Revenue is fully data-trail; reconciliation is straightforward
- Card-system support-status verification is **load-bearing** (no fallback if it fails)
- Card-system replacement is a $25K–$60K CapEx event every 7–10 years
- Card processing fees (typically 2–3% of card revenue) hit margin

### coin-only

- Revenue verification is **load-bearing** (no card data trail; deposits-only reconciliation)
- Theft risk highest in category (coin vault is the dominant insurance-claim category for laundromats)
- Cash-handling labor cost
- Customer migration risk to card-adopting competitors
- Card-system retrofit cost should be in year-1 CapEx plan ($25K–$60K)
- SBA underwriting weights revenue-verification risk higher

### hybrid

- Modern default in many corridors
- Card-to-coin revenue ratio trend matters (is card share growing?)
- Both card-only and coin-only risks apply at reduced weight
- Most flexible to customer-base composition

---

## §staffing (cross-cutting)

### attended

- Employee retention is screening factor (key employees, tenure, wages, schedule, reliability)
- Labor cost line 8–18% of gross (vs. 0–4% unattended)
- Workers' compensation history reviewed
- 1099-vs-W-2 misclassification risk (SBA-underwriting flag if surfaced)
- Owner can be more remote; employee-led operation can be more resilient to owner-transition

### unattended

- Camera-system / remote-monitoring infrastructure load-bearing
- Cash-collection routine documented
- After-hours incident history reviewed
- Lower labor cost; higher capital cost (monitoring + automation)
- Customer-experience risk if machine breaks during unattended hours
- Modern default; trend favors

---

## §real-estate (cross-cutting)

### standalone

- Roof condition is load-bearing (no shared structure)
- Parking lot, signage, storefront condition all buyer's eventual responsibility
- HVAC / rooftop unit ages reviewed
- No co-tenancy / kickout exposure from a neighboring tenant
- Typically simpler lease structure

### anchor-store-attached (in-line strip)

- Anchor lease should be reviewed alongside the laundromat lease (anchor's exit creates co-tenancy / kickout exposure for the laundromat)
- Anchor tenure + remaining lease term matter (laundromat is more vulnerable if anchor's lease is shorter than laundromat's)
- CAM reconciliation history with anchor's pro-rata share
- **Anchor-consent rights on assignment** — when present, weighted as severe red flag (per `red-flags-checklist.md` §lease-assignability)
- Storefront and signage may be limited by landlord standards
- Foot-traffic interaction with anchor (positive or negative depending on anchor type)

---

## The six combinations

### 1. unattended-hybrid-standalone (modern default)

**Most common in the BizBuySell category.** Combines the lowest staffing risk + the most flexible payment system + the simplest real-estate structure.

**Screening differences vs. baseline:** baseline IS this combination. All other combinations are deltas off this.

**Typical multiple positioning** (per `valuation-methodology.md`): mid-to-high band of the revenue tier, all else equal.

**Most-common flags:** equipment-lifecycle (since "modern" installs are often 5–10 years post-renovation, equipment-aged into the yellow band), water-bill-ratio, lease-term.

### 2. unattended-card-only-standalone

**Modern, capital-light, no-labor.** Strong tailwind in card-adoption markets.

**Screening differences:**
- Card-system support-status verification weighted as load-bearing pre-close diligence
- Customer-base alignment with card adoption verified (drive-the-route observation of who's actually using the store)
- Lower customer-flexibility (no fallback for coin-preference customers)
- Higher resilience to theft (no coin vault)

**Typical multiple positioning:** high band of the revenue tier in card-adopting corridors; mid band in lagging corridors.

### 3. unattended-coin-only-standalone

**Increasingly rare in modern markets.** Often older stores deferred-maintenance into selling.

**Screening differences:**
- Revenue-verification is load-bearing pre-LOI diligence
- Year-1 CapEx plan should include card-system retrofit
- Customer-migration risk to nearby card-adopting competitors weighted higher
- SBA-underwriting friction higher (revenue verification)
- Multiple positioning typically low band of revenue tier

**Auto-CAUTION** at minimum unless year-1 card-system retrofit is in the buyer's plan and budget.

### 4. attended-hybrid-standalone

**Common in higher-volume / longer-hours stores.** Attendant manages drop-off service, change machine, machine availability, customer service.

**Screening differences:**
- Employee retention conversations load-bearing
- Labor cost line scrubbed for off-books / 1099 issues
- Drop-off service revenue line (if present) is its own sub-screen — concentration risk and operational complexity
- Higher SDE on stated basis (drop-off adds revenue) but higher operator-attention assumption
- Workers' compensation history reviewed

**Typical multiple positioning:** mid band; the SDE-increase from drop-off service is often offset by the labor-cost line.

### 5. unattended-hybrid-anchor-attached

**Common in newer strip retail.** Laundromat is co-tenant with grocery / discount / coin-op-services / pharmacy.

**Screening differences:**
- Anchor lease reviewed alongside laundromat lease
- Anchor-consent rights on assignment surfaced in Phase 0 lease review
- Anchor tenure + remaining term matter (co-tenancy risk)
- Foot-traffic interaction with anchor (grocery anchor = positive; discount-store anchor = neutral; restaurant anchor = potentially neutral-to-negative for laundromat-customer experience)
- CAM history with anchor reconciled
- Lower flexibility on storefront / signage typically

**Typical multiple positioning:** mid band if anchor is stable and lease is buyer-friendly; lower if anchor-consent rights are present.

### 6. attended-hybrid-anchor-attached

**Common in older strip retail with full-service laundromat operation.** Combines attended-store operational complexity with anchor-attached real-estate complexity.

**Screening differences:**
- All attended-hybrid-standalone screening differences apply
- All unattended-hybrid-anchor-attached screening differences apply
- Compounding operational complexity — operator-attention model must absorb both attended-staffing and anchor-attached real-estate interactions
- Multiple positioning typically mid-to-low band given compounding factors

---

## §portfolio-fit (regional clusterer routing)

When the buyer sub-segment is regional clusterer, the screening adds a **portfolio-fit** layer before the financial screen.

### Portfolio-fit screening questions

1. **Geographic adjacency** — is the listing within the clusterer's existing operational radius (typically ≤30 min drive from existing stores)? If not, the clusterer-premium adjustment in `valuation-methodology.md` should not apply
2. **Sub-vertical compatibility** — does the listing's sub-vertical combination match the clusterer's existing portfolio operating model? (A clusterer running 3 unattended-hybrid-standalones adding an attended-anchor-attached creates operational-model complexity)
3. **CapEx-schedule overlap** — does the listing's equipment-age cluster overlap with the existing portfolio's CapEx schedule, concentrating year-2 or year-3 CapEx?
4. **Management-bandwidth** — does the clusterer have capacity to absorb the listing without a management hire, or is a hire embedded in the year-1 cost structure?
5. **Existing-portfolio CapEx schedule visibility** — does the clusterer have a documented portfolio-level CapEx schedule that this listing slots into?

### Output for a clusterer screen

The screen output includes a portfolio-fit section before the standard verdict. If portfolio-fit fails (geographic non-adjacency, sub-vertical incompatibility, CapEx concentration, management-bandwidth shortage), the verdict bias is CAUTION at minimum even if the listing's standalone financials are PURSUE-eligible.

---

## §combination-screening-quick-reference

| Combination | Distinct load-bearing diligence | Multiple positioning |
| --- | --- | --- |
| 1. unattended-hybrid-standalone | Standard (baseline) | Mid-to-high |
| 2. unattended-card-only-standalone | Card support-status verification | High (card markets) / mid (lagging markets) |
| 3. unattended-coin-only-standalone | Revenue verification; card retrofit CapEx | Low; auto-CAUTION minimum |
| 4. attended-hybrid-standalone | Employee retention; labor scrub | Mid |
| 5. unattended-hybrid-anchor-attached | Anchor lease review; co-tenancy risk | Mid (anchor-consent absent) / lower (anchor-consent present) |
| 6. attended-hybrid-anchor-attached | All of (4) + (5) | Mid-to-low |

---

## What's out of scope for this file

- Route-only laundry pickup businesses → Gate 5
- Commercial-B2B laundry (hospital linen, hotel linen, restaurant linen) → Gate 5
- Drop-off-service-only storefront with no self-serve → Gate 5
- Wash-fold-only mobile-app businesses → Gate 5
- Coin-op equipment installed in other businesses (laundromat-corner-of-apartment-building / dorm-laundry / military-base) → not addressed; ask before screening

---

Last updated: 2026-05-13 (initial build).
