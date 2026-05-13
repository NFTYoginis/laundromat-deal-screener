# Memo mode

A job-mode variant. Trigger: type `memo` after any screen output, or paste a listing and prefix the request with `memo:`. The specialist reformats the screen as an **investment-screening memo** — the format the buyer would walk into an SBA lender meeting with, or send to a partner reviewing the deal.

Same underlying reasoning. Different format. Risk flags become full arguments rather than compressed bullets.

---

## Memo structure (sections in order)

### 1. Cover block

- **Deal:** [city/metro + sub-vertical descriptor, no broker / company name unless the buyer pasted one]
- **Date screened:** [conversation date]
- **Buyer sub-segment:** [first-time SBA individual / E-2 / regional clusterer]
- **Verdict:** PURSUE / PROCEED WITH CAUTION / PASS
- **One-line thesis:** ten words or fewer

### 2. Executive summary

Three paragraphs:

- **What the deal is** — sub-vertical, ask, revenue, SDE, lease, equipment, payment system. Plain factual. No verdict-leaning language.
- **Why the verdict** — top two flags or top two strengths driving the call. Specific, not generic.
- **What would change the verdict** — name the one or two diligence items whose resolution could move PURSUE→CAUTION, CAUTION→PURSUE, CAUTION→PASS, etc. The buyer should know what to look for, not just what was found.

### 3. Financial snapshot

| Metric | Reported | Adjusted (if applicable) | Comp-band reference |
| --- | --- | --- | --- |
| Gross revenue (TTM) | $X | $X (note adjustment) | `industry-benchmarks.md` §revenue-band-by-store-size |
| SDE (TTM) | $X | $X (note adjustment) | `industry-benchmarks.md` §SDE-margin-band |
| SDE multiple at ask | X.Xx | X.Xx adjusted | `industry-benchmarks.md` §SDE-multiple-by-revenue-band |
| Water/sewer % of gross | X% | — | `industry-benchmarks.md` §cost-structure |
| Equipment age range | X–Y years | — | `red-flags-checklist.md` §equipment-lifecycle |
| Lease term + options remaining | X+Y years | — | `sba-financing.md` §lease-term-rule |

Every cell has a comp-band citation OR an explicit "no comp band — gap flagged" note. Never a fabricated comp.

### 4. Risk register

Each top flag becomes its own paragraph (not a bullet). Structure per flag:

- **Flag name** — bolded one-line statement
- **Severity:** high / medium / low (and why this severity, not the next one up or down)
- **Mechanism:** what specifically would go wrong if this flag is real
- **Magnitude:** dollar / percentage / time impact if it materializes
- **Reference:** which `reference/` file(s) and which row(s)
- **Diligence path to resolution:** what specifically the buyer pulls or has reviewed to retire this flag

Three to six flags typical. More than six suggests the deal should be PASS rather than CAUTION.

### 5. Market context

One paragraph. The sub-vertical's structural tailwinds and headwinds relevant to *this listing* — not generic. References `reference/laundromat/sub-vertical-routing.md` and `industry-benchmarks.md`. Avoids macro-narrative; sticks to the listing's specific corridor, payment system, staffing model.

### 6. Deal structure (PURSUE and CAUTION verdicts only)

If the verdict is PURSUE or CAUTION, this section names:

- **Financing path** — SBA 7(a) / SBA 7(a) + seller note / cash + seller note. Per buyer sub-segment. Per `sba-financing.md`.
- **LOI price strategy** — full ask / ask minus X% with stated reason / range. Pricing is justified by the comp-band citation in §3, not invented.
- **Earnest money** — typical range (1–2% of purchase price); released-on-what-trigger phrasing
- **Contingencies** — financing, lease assignment, equipment inspection, environmental review, revenue verification. Each contingency names what the buyer is checking.

If the verdict is PASS, this section is replaced with **"Why the deal cannot be restructured into PURSUE or CAUTION."** Names the specific reasons the buyer should not negotiate counter-terms.

### 7. Diligence roadmap

The DON'T-DECIDE-YET column from the screen, expanded into a sequenced checklist with rough time estimates. Each item:

- **What** — the diligence action
- **Who** — named professional (lease attorney / equipment inspector / water-bill auditor / CPA / environmental consultant / SBA lender)
- **When** — pre-LOI / post-LOI / pre-close
- **Time estimate** — typical days/weeks from engagement to deliverable
- **Cost estimate** — typical fee range, with explicit "varies by metro" note

### 8. Decision-rights closer

Three short paragraphs:

- **What the buyer decides** — whether to LOI, at what price, with what contingencies, on what timeline.
- **What the specialist does not decide** — anything binding. Restates Gate 1 (binding-advice refusal) in summary.
- **What professionals decide** — names the three roles whose binding voices the buyer needs (SBA lender / transactional attorney / CPA) and what each decides.

---

## Memo length

- **Verdict PURSUE / CAUTION memo:** 2 pages typed, ~800–1,200 words
- **Verdict PASS memo:** 1 page typed, ~400–600 words (the deal does not need a long argument; the case for passing is concise)

Memos are formatted for plain-text rendering (no images, no charts) so the buyer can paste them directly into a Notion / Google Doc / email to their lender or partner.

---

## Memo output never invents

- No comp band not cited in `industry-benchmarks.md`
- No professional's name (only the role)
- No specific dollar fee estimate without a "varies by metro" qualifier
- No claim of specific lender appetite ("this lender will fund this deal") — those calls belong to the buyer's actual lender, not the memo
- No social proof appeals to popular acquisition voices or framework-quoting; the memo stands on the comp-band citation, not on a named author

---

Last updated: 2026-05-13 (initial build, modeled on HVAC Fire Safety Acquisition Analyst memo-mode trigger pattern).
