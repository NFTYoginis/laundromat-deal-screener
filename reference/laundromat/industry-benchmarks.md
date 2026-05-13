# Industry benchmarks

Reference numbers used to cite comp bands in screen / valuation outputs. **Every number on this page has a source attribution.** When the specialist refuses a valuation under Gate 3 (no-comps refusal), it is because the listing falls outside these bands.

Last benchmark-refresh: **2026-05-13**. The HVAC analog repo uses a 90-day market-intelligence refresh gate (`rules.md` §market-intelligence-refresh). This specialist follows the same pattern — when this file is older than 90 days, the specialist flags it at conversation start before screening.

---

## Source-set provenance

The numbers below are aggregated from public sources catalogued at end-of-file. Aggregation is **band-based** rather than point-estimate — every number is a range with named source(s).

The specialist does not cite the broker name, listing URL, or any source not in this file. If the buyer asks for a comp the file does not contain, Gate 3 (valuation-without-comps refusal) fires.

---

## Median deal economics

Drawing from publicly-aggregated BizBuySell category data + Coin Laundry / Laundry Association published surveys:

| Metric | Typical band (US, 2024–2026) | Source-type |
| --- | --- | --- |
| Ask price (single store, independent owner) | $250,000 – $750,000 | BizBuySell laundromat category aggregate |
| Median ask | ~$350,000 | BizBuySell laundromat category aggregate |
| Gross revenue (TTM) | $150,000 – $400,000 | BizBuySell category aggregate + industry survey |
| Median revenue | ~$250,000 | Same |
| SDE (TTM) | $50,000 – $150,000 | BizBuySell category aggregate |
| Median SDE | ~$81,000 | BizBuySell category aggregate |
| SDE margin (SDE / gross) | 28% – 38% | Industry survey aggregate |
| Square footage | 1,800 – 4,000 sq ft typical | Operator-blog aggregation |

**These bands are typical; tails exist in both directions.** Stores below the band may be distressed (justifying a price discount or signaling underlying problems); stores above the band may be high-end / multi-store flagship / strong-corridor (justifying a price premium or signaling a strategic-buyer market).

---

## SDE multiple by revenue band

The most-frequently-cited number on the screen page. Cite the specific row when stating a multiple.

| Revenue band (TTM) | SDE multiple — low | SDE multiple — mid | SDE multiple — high | Notes |
| --- | --- | --- | --- | --- |
| $100K – $200K | 2.0x | 2.7x | 3.4x | Lower band; small-store discount; equipment-CapEx risk dominates |
| $200K – $350K | 2.7x | 3.4x | 4.0x | Most-common pilot-buyer band |
| $350K – $500K | 3.2x | 3.8x | 4.4x | Strong-corridor / hybrid / unattended-with-systems |
| $500K – $750K | 3.5x | 4.0x | 4.5x | Premium band; strategic-buyer interest enters; SBA-financing-borderline-amount territory |
| >$750K | 3.8x | 4.2x | 4.5x+ | Multi-store / portfolio-fit / clusterer-bidder market; ceiling depends on synergy story |

**Aggregate band across all revenue tiers: 2.72x – 4.5x SDE.** Bands published by BizBuySell category data and industry-survey aggregation. The HVAC analog uses a 4.5x SDE auto-PASS ceiling without comp justification; same discipline applies here.

### Adjustments to the multiple

The multiple bands above are *un-adjusted*. Real comp work adjusts up or down based on:

| Factor | Adjustment direction | Magnitude |
| --- | --- | --- |
| Lease term ≥10 years base + options | + | +0.2–0.4x |
| Lease term <6 years | – | –0.4–0.8x |
| Equipment-age range 0–8 years | + | +0.1–0.3x |
| Equipment-age range with machines >12 yr | – | –0.3–0.6x (CapEx adjusted into purchase price) |
| Hybrid / card-only payment with data trail | + | +0.1–0.3x |
| Coin-only with no card upgrade | – | –0.1–0.3x |
| Water/sewer <22% of gross | + | +0.0–0.2x |
| Water/sewer >28% of gross | – | –0.2–0.4x |
| Owner-is-the-business / no systems | — | Auto-PASS (see screening-criteria.md) |
| Cash-not-deposited add-backs | — | Auto-PASS at SBA-financing path; substantial discount at cash path |
| Strategic-buyer presence (clusterer in market) | + | +0.1–0.3x (one-sided; only applies if buyer is the strategic) |

Adjustments compound. A deal with 3 + factors and 1 – factor lands in the upper-mid of the band.

---

## Cost structure (typical, % of gross)

| Cost line | Typical band | Notes |
| --- | --- | --- |
| Water + sewer | 18% – 28% (yellow above 24%, red above 28%) | Most-cited line; metro variation is material |
| Gas (for dryers) | 6% – 12% | Front-load wash + matched dryer drives lower; older mismatched fleets drive higher |
| Electric | 4% – 8% | Lighting + machine motors + card-system base load |
| Rent + CAM | 12% – 20% | Below 12% suggests below-market lease (price the upside); above 20% is a structural red flag |
| Labor (attended stores) | 8% – 18% | Unattended stores: 0–4% (light cleaning + cash-collection only) |
| Maintenance + parts | 4% – 10% | Older fleets cluster at the top of this band |
| Insurance | 2% – 4% | |
| Other (supplies, marketing, software, card-system fees) | 2% – 5% | Card-system processing fees alone are typically 2–3% of card revenue |

**Total typical operating cost: 60% – 75% of gross.** SDE margin (remaining ~25–38%) tracks inversely.

---

## Equipment lifecycle bands

| Equipment | Typical useful life | Replacement cost (per machine, US 2024–2026 typical) |
| --- | --- | --- |
| Front-load washer, 20–30 lb | 10 – 15 years | $4,000 – $8,000 |
| Front-load washer, 40–60 lb | 10 – 15 years | $7,000 – $14,000 |
| Top-load washer | 8 – 12 years | $1,500 – $3,000 |
| Stack dryer | 12 – 18 years | $5,000 – $10,000 |
| Single dryer, 30–50 lb | 12 – 18 years | $3,000 – $6,000 |
| Card system (hardware + readers, full installation) | 7 – 10 years | $25,000 – $60,000 per store typical |
| Water heater (gas, commercial) | 10 – 15 years | $4,000 – $8,000 |
| HVAC (rooftop unit) | 12 – 18 years | $7,000 – $15,000 |

**CapEx-as-percent-of-purchase-price flag:** if year-1 to year-3 CapEx (based on remaining-useful-life on each machine, prorated) exceeds 25% of purchase price, the deal is structurally CapEx-burdened. Adjust the multiple downward OR PASS.

---

## Industry-shape benchmarks

| Metric | Typical value | Notes |
| --- | --- | --- |
| US laundromat count | ~29,000 (range 25,000–35,000 across published surveys) | Industry surveys + association data |
| Aggregate industry revenue (US) | ~$5 billion annually (range) | Industry surveys |
| Unattended share of category | Majority (>50% in modern markets) | Trend toward unattended over the past decade |
| Card-system penetration | Rising; modern installs default to hybrid or card-only | Operator-blog aggregation; manufacturer trend reports |
| Customer-base composition | Renter-heavy corridors dominate; multi-family residential within 1-mile radius is the primary catchment | Industry survey + operator-blog aggregation |
| Customer-frequency | 1–4 visits/month per household typical | Industry survey |

These shape benchmarks contextualize a specific listing. They are not predictive of a specific store's performance.

---

## Source-set (catalogued; specialist does not re-cite mid-output)

The specialist cites this file when stating a benchmark; it does NOT mid-output cite the underlying sources. The buyer can trace any band back here. Sources used in aggregation:

1. **BizBuySell laundromat category page** — public listing aggregate; multi-year median trends (revenue, ask, SDE) for sold/listed laundromats
2. **Coin Laundry Association / Laundry Association of America** — public industry surveys; count, revenue aggregate, payment-trend reports (the org renamed; verify current URL when refreshing)
3. **Cents** (laundromat-operator software vendor) **+ Turns** (operator software) — operator-blog aggregations on water-bill economics, equipment lifecycle, payment-system trends
4. **Manufacturer trend reports** (Speed Queen / Continental Girbau / Dexter / Huebsch / Wascomat distributor-channel publications) — equipment lifecycle, replacement cost, technology trends
5. **Operator-acquisition podcast aggregate notes** — public episode notes from small-business-acquisition podcast aggregators (used for narrative grounding; never as a benchmark citation; named hosts deliberately not surfaced — see `rules.md` Never list)
6. **SBA 7(a) public eligibility page + SOP 50 10 V8 (effective 2025-06-01)** — financing-rule grounding; see `sba-financing.md` for SOP-specific citations

**When a benchmark in this file is older than 90 days, the specialist flags the file's age at conversation start before screening** (HVAC pattern; rules.md §market-intelligence-refresh in source repo).

---

Last updated: 2026-05-13 (initial build).
