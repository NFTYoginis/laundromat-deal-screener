# Valuation methodology

How the specialist arrives at a defensible $low / $mid / $high valuation band when Job 3 (valuation) fires.

**The specialist refuses Job 3 if the comp band needed isn't in `industry-benchmarks.md`** (Gate 3 — Valuation-without-comps refusal in `rules.md`). Method below applies when comps exist.

---

## Method (5 steps)

### Step 1 — Bound the comp band

Identify the revenue band in `industry-benchmarks.md` §SDE-multiple-by-revenue-band that the listing falls into. State the band explicitly in output.

If the listing is on a band boundary (e.g., $345K revenue, between the $200K–$350K and $350K–$500K bands), use the lower band as the anchor and the upper band as the ceiling unless the listing's other dimensions justify upper-band placement.

### Step 2 — Adjust for the six dimensions in screening-criteria.md

Apply the per-factor adjustments from `industry-benchmarks.md` §adjustments-to-the-multiple. Compound them. State each adjustment with its source flag.

Worked example: a $280K-revenue listing with **10+ year lease + buyer-controlled options** (+0.3x), **equipment-age range 4–8 years** (+0.2x), **hybrid payment with data trail** (+0.2x), **water/sewer at 26% of gross** (–0.1x):

- Base band: $200K–$350K → 2.7x / 3.4x / 4.0x (low / mid / high)
- Net adjustment: +0.6x
- Adjusted band: 3.3x / 4.0x / 4.6x

Multiply by SDE to get the $-band.

### Step 3 — Sanity-check against the ask

Compare the adjusted multiple at the ask price against the band. Three outcomes:

| Ask multiple vs. adjusted band | What it tells you |
| --- | --- |
| At or below low | Ask is favorable; if other dimensions are clean, this is a PURSUE-pricing signal |
| Mid-band | Ask is fair-market; the deal pencils at this price if structural fit is good |
| Above high | Ask is aggressive; either the seller's comp narrative is upper-band and there's a strategic-buyer market, or the ask is over-priced and an LOI below ask is appropriate |
| Above 4.5x un-adjusted | Auto-PASS trigger without comp justification (HVAC-pattern ceiling). Specialist refuses valuation; surfaces as PASS or as a structural CAUTION pending price reduction |

### Step 4 — Cross-check with CapEx-adjusted SDE

If the equipment-age list shows year-1-to-3 CapEx >10% of purchase price, compute CapEx-adjusted SDE = stated SDE – (annualized CapEx replacement reserve).

Re-run Step 2 against CapEx-adjusted SDE. If the result moves the deal from mid-band to high-band-aggressive, the headline ask is masking a CapEx burden the buyer would pay twice for (once in price, once in year-1 CapEx outlay).

### Step 5 — Output the band with citation

State:

- The revenue band used (cite `industry-benchmarks.md` row)
- The base multiple low/mid/high
- Each adjustment with its source flag (cite `red-flags-checklist.md` or `screening-criteria.md` row)
- The adjusted multiple low/mid/high
- The CapEx adjustment if applicable
- The final $-band low/mid/high
- The recommended LOI strategy (full ask / ask minus X% / range)

---

## Buyer-sub-segment-specific valuation differences

Per the routing table in `rules.md` (Job 3 — Valuation row), valuations differ by buyer sub-segment:

### First-time SBA-financed individual (default)

Use the base band + standard adjustments. SBA underwriting will discount any cash-not-deposited revenue; reflect this in the SDE used for valuation, not in the multiple.

### E-2 visa buyer (cash-financed, often via partnership with US-citizen/LPR guarantor)

Cash buyers often accept a modestly higher multiple than SBA buyers because the deal closes faster, contingencies are fewer, and the seller does not bear the SBA-underwriting timeline risk. Cap this premium at **+0.25x SDE** above the band-adjusted figure.

The flip side: E-2 buyers typically have less reserve capital margin against equipment-CapEx surprises, so the equipment-age adjustment should be applied more conservatively (use the upper end of the negative range for equipment-age flags).

### Regional clusterer (2–5 stores already in portfolio)

Clusterers have synergies (shared maintenance crew, distributed CapEx amortization, shared management software, supplier-volume pricing). These synergies justify a **modest premium up to +0.25x SDE** above the band-adjusted figure for an in-market add.

Out-of-market adds (>30 minutes from existing stores) do not justify a clusterer premium.

Clusterer-buyer valuations should also weight operator-attention-bandwidth: the clusterer is buying with the assumption that they will NOT be on-site daily. The owner-is-the-business red-flag is therefore even more disqualifying for a clusterer than for a first-time individual buyer.

---

## Strategic-buyer market detection

Some markets have an active strategic-buyer cohort (regional clusterers, family-office-backed mini-portfolios, recently-funded laundromat-platform investors). When the strategic-buyer market is active:

- Multiples sit at the upper end of bands
- Strong-corridor / hybrid-unattended-standalone deals can transact above 4.5x SDE
- First-time individual buyers may be priced out of the best deals

The specialist does **not** speculate on strategic-buyer presence based on national narrative. The signal that a strategic-buyer market is active in a specific corridor is the broker mentioning multiple offers from named operators, or visible recent transactions at upper-band-aggressive multiples on comparable stores.

If the buyer asks *"is there a strategic-buyer market in my corridor?"* → the specialist redirects to: ask the broker how many offers they typically get, and from whom (cohort, not name). The specialist does not have local-market signal beyond what the buyer can produce themselves.

---

## What the specialist will NOT produce

- A point-estimate valuation. Always a band.
- A multiple without a comp-band citation.
- A "trust me" adjustment without a flag-source citation.
- A valuation that ignores the equipment-CapEx-adjusted SDE if the equipment-age list shows >10% of purchase price in year-1-to-3 CapEx.
- An LOI-price recommendation that contradicts the band-anchored math.
- A valuation that assumes a specific revenue growth rate. Growth assumptions belong in the buyer's pro-forma, not in the valuation; the valuation reflects what the store is worth as currently operating.

---

## Refusal of valuation work

Gate 3 fires when:

- The listing's revenue, SDE, or sub-vertical combination doesn't fit any band in `industry-benchmarks.md`
- The listing's reported numbers fail Step 4 sanity (CapEx-adjusted SDE goes negative, for example)
- The buyer hasn't named which sub-segment they are, and the answer materially affects the valuation

Refusal language is in `rules.md` Gate 3.

---

Last updated: 2026-05-13 (initial build).
