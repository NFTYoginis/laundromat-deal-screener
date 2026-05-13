# Red flags checklist

The flags the specialist watches for. Ordered roughly by frequency-at-which-they-kill-deals, not by severity (severity is determined per-deal by `screening-criteria.md`).

For each flag: what to look for, why it matters, what diligence retires it, what the **DON'T-DECIDE-YET** entry should say.

---

## §water-bill-ratio

**Look for:** water + sewer cost expressed as a percentage of gross revenue.

**Bands** (per `industry-benchmarks.md` §cost-structure):
- Green: 18–24% of gross
- Yellow: 24–28% of gross
- Red: >28% of gross

**Why it matters:** water/sewer is the largest single variable cost in most laundromats. A high ratio reflects one or more of: high local utility rates, no sewer credit / sub-metering setup, older inefficient machines using high gallons per cycle, meter problems (slow leak / under-charged credit), revenue understated (denominator small).

**Diligence to retire:** 24 months of utility statements **pulled directly from the utility, not seller-supplied**. Reconcile meter reads with billed gallons. Verify whether the store has a sewer credit (irrigation meter, evaporation credit, or sub-meter setup). Check whether the metro is on a documented rate plan and whether a rate case is pending.

**DON'T-DECIDE-YET:** *"Accepting the seller's water/sewer figure as the run-rate"* → independent water-bill auditor OR buyer pulls 24 months of utility statements directly → reconciled before LOI release.

---

## §equipment-lifecycle

**Look for:** range of equipment ages across washers and dryers.

**Bands** (per `industry-benchmarks.md` §equipment-lifecycle):
- Front-load washer: 10–15 years
- Top-load washer: 8–12 years
- Stack dryer: 12–18 years
- Single dryer: 12–18 years

**Why it matters:** end-of-life equipment becomes year-1 CapEx. If the year-1-to-3 CapEx burden exceeds 25% of purchase price, the deal is structurally CapEx-burdened and either needs price-adjustment or PASS.

**Diligence to retire:** independent coin-laundry equipment inspector (not seller's distributor) reads serial-plate manufacture dates on **every** machine. Produces a written remaining-useful-life schedule with per-machine replacement cost. Buyer adds the schedule to the year-1-to-3 P&L forecast.

**DON'T-DECIDE-YET:** *"Accepting the seller's equipment-age list as accurate"* → independent equipment inspector → serial-plate-read across full fleet before LOI release.

---

## §lease-assignability

**Look for:** lease term remaining + options, assignment clause language, anchor / co-tenant consent rights, percentage-rent clauses, demolition / relocation / kickout clauses, CAM reconciliation history.

**Bands** (per `screening-criteria.md` §dimension-2):
- Green: ≥10 years total (base + buyer-controlled options); standard assignment clause; no anchor consent; no problem clauses
- Yellow: 6–9 years; consent reasonable; some anchor / co-tenant interactions
- Red: <6 years; anchor consent required; "sole discretion" language; percentage-rent below current revenue; demolition / relocation present

**Why it matters:** SBA 7(a) lenders typically require lease term (including options the buyer can exercise) to match the loan amortization (typically 10 years for laundromat-secured). A short lease is an SBA-decline risk. Anchor-consent rights tilt the deal heavily toward the anchor. Percentage-rent below current revenue compounds against the buyer's growth case.

**Diligence to retire:** transactional / commercial-lease attorney reads the lease **in full** (not summary; not broker-paraphrase). Reads anchor lease too if anchor-consent applies. Produces written assessment.

**DON'T-DECIDE-YET:** *"Assigning the existing lease vs. negotiating a new one"* → transactional / commercial-lease attorney → lease read in full before LOI release; assignment-consent received in writing before SBA loan commitment signed.

---

## §revenue-verification

**Look for:** how revenue is reported. Is it card-system transactional data + bank deposit history? Is it coin-pull frequency? Is it "estimated"? Does the seller's SDE include cash-not-deposited add-backs?

**Bands** (per `screening-criteria.md` §dimension-1):
- Green: card data + bank deposit reconciled, ≥24 months
- Yellow: hybrid with reconciled coin extrapolation
- Red: all-coin estimated; cash-not-deposited add-backs

**Why it matters:** unverifiable revenue cannot pass SBA underwriting QoE (per `sba-financing.md` §revenue-verification). Cash-not-deposited add-backs are SBA's auto-flag category. Even if the buyer is paying cash, unverifiable revenue means the buyer is paying for revenue the seller may have over-stated.

**Diligence to retire:** 24-month bank deposit reconciliation by CPA. Card-system transactional export. If coin-only and no card system, the only path is the CPA reconciling deposits to a reasonable cash-handling-loss assumption — and SBA is likely to discount the SDE substantially regardless.

**DON'T-DECIDE-YET:** *"Pricing the deal on stated SDE"* → CPA running 24-month deposit reconciliation → adjusted SDE produced before LOI price strategy is finalized.

---

## §customer-density

**Look for:** corridor demographics. Multi-family rental within 1-mile radius. Median household income (laundromat catchment is renter-heavy; <$60K median is typical, <$40K very dense catchment; >$100K is luxury / amenity-laundry market and unusual). Competing laundromats within 1-mile. Population trend (growing / stable / declining).

**Why it matters:** laundromat is a catchment business. Demographic decline within the catchment is structural revenue-decline risk. Competing-store density compresses pricing power.

**Diligence to retire:** publicly-available census-tract data for 1-mile catchment. Drive-the-route observation of competing stores. Verify any seller "the neighborhood is growing" claim against public data.

**DON'T-DECIDE-YET:** *"Trusting the seller's corridor-growth narrative"* → buyer's own public-census-tract review + drive-the-route observation → independent verification before LOI submission.

---

## §payment-system

**Look for:** card-only, coin-only, or hybrid. Age of card system if present. Hardware support status. Customer-base alignment with card adoption.

**Bands** (per `sub-vertical-routing.md` §payment-system):
- Green: card-only or card-dominant hybrid; modern system (≤3 years old)
- Yellow: hybrid with older but functional card system
- Red: coin-only with no card upgrade; or card system >7 years old with unsupported hardware

**Why it matters:** coin-only stores have multiple compounding risks: theft (coin vault breach is the dominant insurance claim category), cash-handling labor, customer migration to card-adopting competitors, no transaction-level revenue data trail. Aging card systems become unsupported and require full replacement (typically $25K–$60K per store).

**Diligence to retire:** card system age and hardware support status verified with manufacturer / distributor. Card-system transaction export pulled across full available history.

**DON'T-DECIDE-YET:** *"Believing the card system is fine without manufacturer confirmation"* → card-system manufacturer / distributor → written confirmation of support status before LOI release.

---

## §hidden-CapEx

**Look for:** items not on the equipment-age list. Water heater age. HVAC age (rooftop unit). Plumbing-stack inspection. Electrical panel capacity (especially if buyer plans to add machines or upgrade card system). Roof condition. Parking-lot condition. Storefront condition (signage, glass, door, accessibility compliance).

**Why it matters:** the equipment list typically covers washers + dryers + card system. Everything else can be deferred-maintenance gold-mining by the seller. Water heater failure mid-Saturday-rush is a revenue event. HVAC failure in summer is a customer-walk-out event. Electrical-panel inadequacy blocks any growth plan.

**Diligence to retire:** physical site walk by buyer + (ideally) a general-trades inspector covering water heater, HVAC, plumbing, electrical, roof, parking lot. Storefront accessibility (ADA) inspected if buyer is risk-averse.

**DON'T-DECIDE-YET:** *"Ignoring the items not on the equipment list"* → general-trades inspector OR buyer-with-checklist physical walk → written assessment of non-equipment CapEx before LOI release.

---

## §customer-concentration

**Look for:** any single commercial-pickup contract, wash-and-fold standing client, or single-source revenue contributor ≥20% of gross.

**Why it matters:** laundromats are typically self-serve high-fragmentation businesses. Customer concentration ≥20% is unusual and signals dependency. ≥40% is the HVAC-pattern auto-PASS trigger (`screening-criteria.md` §how-dimensions-combine).

**Diligence to retire:** revenue breakdown by source. Verify any contract is assignable and that the customer's intent to continue post-close has been documented.

**DON'T-DECIDE-YET:** *"Assuming concentrated customers will stay after close"* → direct conversation with the concentrated customer (typically requires seller intro) → written continuation intent before LOI submission.

---

## §environmental-exposure

**Look for:** prior tenant history of the site (was this a dry cleaner before it was a laundromat? a gas station?). Floor-drain history. Phase 1 environmental survey if any. Discharge permit (some metros regulate laundromat discharge).

**Why it matters:** dry-cleaner-prior-tenant is the dominant laundromat environmental risk. PCE / TCE contamination from prior dry-cleaner operations can sit in soil and groundwater under the site. SBA lenders typically require Phase 1 environmental survey at minimum. Landlord may have its own requirement.

**Diligence to retire:** Phase 1 environmental survey conducted by independent environmental consultant. If Phase 1 flags concerns, Phase 2 (soil/groundwater sampling) follows.

**DON'T-DECIDE-YET:** *"Skipping environmental review because the listing is a laundromat, not a dry cleaner"* → environmental consultant + Phase 1 survey → completed before SBA loan commitment signed AND before earnest money release.

---

## §seller-reason-for-sale

**Look for:** the stated reason for sale. Is it consistent across broker, seller, listing copy? Is it verifiable via independent channels?

**Common patterns:**
- Genuine retirement (verifiable: age, time in ownership, no other businesses)
- Genuine relocation (verifiable: moving to a known destination, family event)
- "Other opportunities" (often a yellow signal; ask specifically what)
- "Health reasons" (yellow; verify nothing is being hidden about the store)
- "Just ready for a change" (yellow; press for specifics)
- "Owner is selling to focus on other stores" (yellow; selling-the-worst-one risk)

**Why it matters:** the stated reason for sale interacts with the diligence findings. A retiring 70-year-old who built the store from scratch and is moving to be with grandchildren is a different deal than a 45-year-old who "just wants a change" and is also reportedly selling the building next door.

**Diligence to retire:** verify reason via 1–2 independent channels (the broker is not independent). Talk to neighboring businesses. Public records on owner.

**DON'T-DECIDE-YET:** *"Trusting the stated reason for sale at face value"* → independent verification → at least 1 corroborating data point before LOI release.

---

## §SBA-underwriting-friction

**Look for:** anything that will make SBA 7(a) underwriting either slow or risk a decline. Cash-not-deposited add-backs (auto-flag). Lease term < amortization (likely-decline). Owner-is-the-business (likely-decline). Customer concentration. Prior environmental concerns. Buyer's personal financial profile gaps.

**Why it matters:** SBA-financed deals can collapse late if the lender flags a structural issue post-LOI. Surfacing these before LOI saves earnest money and time.

**Diligence to retire:** pre-LOI conversation with the SBA lender, walking the listing's structural facts and asking *"would your underwriting flag any of these?"* before earnest money. See `sba-financing.md` §pre-LOI-lender-conversation.

**DON'T-DECIDE-YET:** *"Submitting an SBA-financed LOI without a pre-LOI lender conversation"* → SBA lender → 30-minute structural-screen conversation before LOI submitted.

---

## §competition-emergence

**Look for:** new laundromat construction within the 1-mile catchment. Permitting records. Visible buildout in nearby retail. Major employer or housing-development changes that could shift catchment.

**Why it matters:** a competing new-build laundromat with modern equipment and card-only payment can compress an older store's revenue within 12 months of opening.

**Diligence to retire:** city permitting records search for the catchment. Drive-the-route. Talk to commercial real-estate brokers in the corridor.

**DON'T-DECIDE-YET:** *"Trusting that 'no new competition' in the seller's narrative is current"* → city permitting records search → completed before LOI submission.

---

## §franchise-vs-independent

**Look for:** is this an independent laundromat or part of a franchise? (Laundromat franchising is unusual but exists; e.g., Wash House Inc., LaundroLab, etc.)

**Why it matters:** franchise listings carry transfer fees, royalty obligations, and franchisor-consent requirements on assignment. Most listings in the BizBuySell category are independent; franchise listings should be flagged because the diligence shape changes materially.

**Diligence to retire:** franchise agreement reviewed by transactional attorney specializing in franchise law (different attorney than the lease attorney; this is a sub-specialty).

**DON'T-DECIDE-YET:** *"Treating a franchise listing as if it were an independent listing"* → franchise-specialist attorney → franchise agreement read before LOI submission.

---

Last updated: 2026-05-13 (initial build).
