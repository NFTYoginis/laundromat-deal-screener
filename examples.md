# Examples

Two worked listings. **Both fictional-but-realistic.** Financials drawn from publicly-documented BizBuySell category aggregates and Coin Laundry / Laundry Association industry surveys. No real broker URL. No real company name. No city-block specificity.

Each example shows input (the listing as the buyer would receive it) → output (the screen the specialist produces).

---

## Example 1 — PURSUE-with-flags

### Input

> **Listing summary (fictional, broker tearsheet style)**
>
> Suburban Midwest metro, growing residential corridor. **Unattended, hybrid-payment (card + coin), standalone building (owned by landlord, separate from any anchor tenant).**
>
> Ask: **$385,000**. Reported gross revenue: **$268,000** (TTM). Reported SDE: **$92,000** (TTM, owner-adjusted). 22 washers (capacities 20/30/50 lb mix), 30 dryers, mix of front-load and top-load. Equipment ages: range 4 to 14 years per seller-supplied list. Card system: installed 18 months ago. Lease: 4 years remaining + 1 × 5-year option, landlord's standard form, base rent + CAM, no exclusive-use clause stated. Water/sewer reported at ~24% of gross. Seller selling for "personal reasons, moving to be closer to family." Owner-operator on-site ~5 hours/week.
>
> **Buyer:** First-time SBA-financed individual buyer, ~$80K liquid for down payment + reserves.

### Output

> **Verdict: PURSUE WITH CAUTION** — financials sit inside the comp band (industry-benchmarks.md §SDE-multiple-by-revenue-band, $250K–$300K revenue tier, 3.5–4.0x SDE); the headline ask of $385K = **4.18x SDE**, just above the band midpoint. The deal pencils. Three flags need resolution before LOI.
>
> *Buyer sub-segment assumed: first-time SBA-financed individual. Correct me if not.*
>
> **Ranked risk flags (severity-ordered, citations to `reference/laundromat/`):**
>
> 1. **Lease term 4 years remaining + 1×5-year option is structurally tight for an SBA 7(a) deal** *(red-flags-checklist.md §lease-assignability, sba-financing.md §lease-term-rule).* SBA generally wants the lease (including options the buyer can exercise) to match the loan amortization — typically 10 years for laundromat-secured. 4+5 = 9 years available; if the loan amortizes 10 years, you are 1 year short and the lender may discount, restructure, or decline.
> 2. **Equipment-age range 4 to 14 years means the oldest cohort is approaching front-load-washer replacement window** *(red-flags-checklist.md §equipment-lifecycle, due-diligence-framework.md §equipment-inspection).* Industry-typical front-load life is 10–15 years; the 14-year machines are within 1–4 years of mandatory replacement. CapEx exposure on the buyer's first 3 years is non-trivial. Inspector-verified remaining-useful-life is the gating diligence item.
> 3. **Water/sewer at 24% of gross is at the top of the typical band** *(industry-benchmarks.md §cost-structure, red-flags-checklist.md §water-bill-ratio).* 20–25% is normal; 24% is normal-but-high. Two sub-questions: is the meter sub-metered for any sewer credit (irrigation, evaporation), and is there a rate hike scheduled in this metro? Both go to the water-bill auditor / 24 months of statements pulled directly.
>
> **Strengths:**
>
> - **Unattended-hybrid-standalone is the modern default** *(sub-vertical-routing.md §unattended-hybrid-standalone).* Lowest staffing risk, highest payment-trend tailwind.
> - **Card system installed 18 months ago** *(sub-vertical-routing.md §hybrid-payment).* Capital cost already absorbed; data trail exists for verification.
> - **Owner-operator at 5 hours/week is a credible buyer-attention assumption** — the deal does not collapse if the buyer matches that hour count.
> - **Stated reason for sale ("moving to be closer to family") is neutral.** It is not "I'm tired of dealing with equipment failures," not "the city is raising water rates 40%," not "the landlord is selling the building." Worth verifying via independent channels but no automatic red.
>
> **Data gaps (pull before next step):**
>
> - **24 months of utility statements pulled directly from the utility** (not seller-supplied). Reconciles the 24% water/sewer claim.
> - **Card-system transaction data** (full 18-month history, by week). Reconciles the $268K revenue claim and reveals seasonality, daypart, machine-utilization mix.
> - **Equipment-by-equipment age list with serial-plate manufacture dates** (independent inspector verification, not seller list). Reconciles the 4–14 year range claim and yields a CapEx forecast for years 1–3.
> - **Lease in full, including assignment clause, percentage-rent (if any), exclusive-use clause, demolition / relocation clause, and CAM reconciliation history.** Reconciles the 4+5 lease-term assumption against SBA lender requirements.
> - **Seller's reason for sale verified** via 1–2 independent channels (broker is not an independent channel).
>
> **DON'T-DECIDE-YET column:**
>
> | Item buyer should NOT commit to | Named professional | Before-action trigger |
> | --- | --- | --- |
> | Submitting the SBA loan commitment | SBA lender + transactional attorney coordinating | Lease assignment consent received in writing from landlord, with assignment-survives-renewal language and no escalation clauses |
> | Accepting the 24% water/sewer cost as the run-rate | Independent water-bill auditor OR 24 months of utility statements pulled directly | Statements reconciled with meter-read history; sewer-credit / irrigation-meter setup verified or ruled out |
> | Accepting the equipment age list as accurate | Coin-laundry equipment inspector (independent of seller's distributor) | Inspector has read serial-plate dates on every machine and produced a written remaining-useful-life schedule |
> | Releasing earnest money | Transactional attorney | All financing contingencies cleared; lease assignment closed; environmental review (Phase 1 minimum if lender requires) complete |
>
> **Next 3 steps:**
>
> 1. Email broker requesting (a) 24 months of utility statements, (b) full card-system transaction export, (c) equipment-by-equipment serial-plate photos. Frame as standard diligence; if broker resists any one, that itself is a flag.
> 2. Schedule independent equipment inspection conditional on accepted LOI (most inspectors won't book against a pre-LOI deal).
> 3. Have transactional attorney read the lease before LOI submission. Lease term against SBA amortization is the most-likely deal-killer here — settle it before you spend earnest money.
>
> **`reference/` files consulted:** `industry-benchmarks.md`, `red-flags-checklist.md`, `sub-vertical-routing.md`, `sba-financing.md`, `due-diligence-framework.md`.

---

## Example 2 — PASS

### Input

> **Listing summary (fictional, broker tearsheet style)**
>
> Older urban neighborhood, declining residential density per public census trend. **Attended (one part-time employee covers weekday afternoons + Saturdays), coin-only, in-line with strip retail (anchor: discount grocery, lease assignment requires both landlord AND anchor approval per broker).**
>
> Ask: **$240,000**. Reported gross revenue: **$148,000** (TTM, all coin, "estimated from coin-pull frequency"). Reported SDE: **$71,000** (TTM, owner-adjusted including substantial cash-not-deposited add-backs). 18 washers (mostly top-load, ages 9 to 17 years per seller-supplied list), 22 dryers (similar age range). No card system. Lease: 2 years remaining + 1 × 3-year option. Water/sewer ~31% of gross. Seller has owned 14 years, "ready to retire." Owner-attended ~15 hours/week + 1 part-time employee 25 hours/week.
>
> **Buyer:** First-time SBA-financed individual buyer.

### Output

> **Verdict: PASS** — five severe flags compound. Headline multiple looks favorable (~3.38x SDE on stated numbers) but the stated numbers are not trustworthy and the structural risks (lease term, equipment age, water-bill ratio, payment system, anchor-landlord consent) are each independently disqualifying for a first-time SBA buyer.
>
> *Buyer sub-segment assumed: first-time SBA-financed individual. Correct me if not.*
>
> **Ranked risk flags (severity-ordered, citations to `reference/laundromat/`):**
>
> 1. **SDE includes "cash-not-deposited" add-backs and revenue is "estimated from coin-pull frequency"** *(red-flags-checklist.md §revenue-verification, due-diligence-framework.md §SDE-quality).* This is the deal-killer. Unverifiable cash revenue cannot pass SBA underwriting QoE. Cash-not-deposited add-backs are SBA's auto-flag category. The lender will discount the SDE substantially or decline.
> 2. **Equipment ages 9–17 years on top-load-dominant fleet** *(red-flags-checklist.md §equipment-lifecycle, valuation-methodology.md §CapEx-adjustment).* Industry-typical top-load life is 8–12 years. The 17-year cohort is past end-of-life. CapEx exposure year 1 is likely $40K–$80K minimum on a $240K ask — that's 17–33% of purchase price spent before stabilization.
> 3. **Lease 2+3 years against SBA 10-year amortization** *(sba-financing.md §lease-term-rule).* SBA wants lease ≥ loan term. 5 years available against 10-year amortization is a structural decline-risk.
> 4. **Water/sewer at 31% of gross is above the typical band** *(industry-benchmarks.md §cost-structure, red-flags-checklist.md §water-bill-ratio).* 25–30% is high; >30% suggests either a meter issue (leak, missing sewer credit), a rate-hike risk, or that the revenue figure is inflated (driving the ratio down on the denominator side rather than the numerator).
> 5. **Anchor-tenant lease-assignment consent requirement** *(red-flags-checklist.md §lease-assignability, sub-vertical-routing.md §anchor-store-attached).* Anchor approval rights on a sub-tenant's assignment are unusual and tilted heavily against the buyer. Anchor has no obligation to consent and can extract concessions.
> 6. **Coin-only payment system in a declining residential corridor with no card upgrade installed** *(sub-vertical-routing.md §coin-only, red-flags-checklist.md §payment-system).* Multiple compounding risks: coin theft, cash-handling labor, customer migration to card-only competitors, no transaction-level data trail for QoE.
>
> **Strengths:** None material enough to offset. The 14-year ownership history is a neutral data point (could indicate stability OR could indicate a tired operator deferring CapEx).
>
> **Data gaps:** Not the operative question on this deal. The five flags above mean PASS regardless of what additional data shows. If the buyer is determined to pursue anyway, the gaps to pull would be (a) full bank deposit history to reconcile coin-pull revenue, (b) independent equipment inspection, (c) full lease text including anchor-consent rights. But the recommended action is to PASS, not to fill gaps.
>
> **DON'T-DECIDE-YET column:**
>
> | Item buyer should NOT commit to | Named professional | Before-action trigger |
> | --- | --- | --- |
> | Submitting any LOI at the current ask | Buyer's own re-screen against `reference/laundromat/red-flags-checklist.md` | All five flags acknowledged and the buyer has a written plan for each before any LOI |
> | Accepting the "estimated from coin-pull frequency" revenue figure | CPA conducting a 24-month bank-deposit reconciliation | Reconciliation produces a verified gross revenue figure, with cash-not-deposited add-backs separately quantified and disclosed |
> | Believing the anchor-consent clause is "probably fine" | Transactional attorney reviewing anchor lease + sub-lease assignment-rights | Attorney has read both leases in full and produced a written assessment of anchor's incentive structure |
> | Pricing the deal on stated SDE | Independent valuation reflecting CapEx burden, revenue-verification haircut, and lease-term discount | Adjusted SDE produced; comp band reset to reflect the adjusted figure |
>
> **Next 3 steps:**
>
> 1. **Pass.** Email broker thanking them, citing "structural fit doesn't match my financing path." Do not name the specific flags — protect future relationship.
> 2. If the buyer is determined to negotiate rather than pass, the conversation is at a substantially lower price (sub-2.5x adjusted SDE, accounting for verified-revenue haircut + CapEx burden + lease-term discount) AND with the lease term re-negotiated to ≥10 years before any LOI. The seller likely won't accept either condition; that's evidence the PASS is correct.
> 3. Reset the search criteria. The next listing should have: ≥6 years lease + options, hybrid or card-only payment, equipment-age range concentrated in 4–10 years, water/sewer < 28% of gross, deposit-verifiable revenue.
>
> **`reference/` files consulted:** `industry-benchmarks.md`, `red-flags-checklist.md`, `sub-vertical-routing.md`, `sba-financing.md`, `valuation-methodology.md`, `due-diligence-framework.md`.

---

## Notes on these examples

- Both listings are **composites drawn from public BizBuySell category data and industry-survey aggregates**. The financials sit inside published bands. The structural details (lease, equipment age, payment system) are typical of the category. **No real broker page was used.** No real company, city, or person is referenced.
- The CAUTION middle slot is load-bearing. Example 1 could read as PURSUE if the buyer is willing to absorb a 1-year SBA-amortization gap; CAUTION is the honest framing because the gap is real and resolution requires specific work.
- Example 2 reads as PASS because **revenue verification is the gating flag**. Without trusted top-line numbers, every downstream calculation (multiple, CapEx ratio, financing cap) is suspect.
- A third example for the regional-clusterer or E-2 buyer would change which flags rank highest (lease assignability weighs heavier for E-2; CapEx weighs lower for clusterer). The screening discipline does not change.
