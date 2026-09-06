# PMBJP Generic Dermatology Protocol
### Profile: 20 y/o male · 5-year active acne · post-acne hyperpigmentation · dehydrated-yet-oily barrier · daily bus commute (UV + heat + pollution)

**Source of truth:** `Product List_6_9_2026 @ 0_31_23.csv` (2,439 items) in this repo.
Note: the two CSVs in this repo are **byte-identical duplicates** (same MD5 `6c3627a6…`), so this analysis is built from a single 2,439-row catalog.

**How to read the price column:** items showing **MRP ₹0.00** in the source file have an allotted Janaushadhi drug code but **no published price** — in practice this means the SKU is approved but not currently manufactured/stocked. Treat every ₹0 item as *ask, don't count on it*, and use the priced alternative listed beside it.

**Scope note:** this is an educational mapping of a government catalog to your stated profile. It is not a diagnosis or a prescription. Items marked **[Rx]** are prescription-only in India and the steroid-containing ones are genuinely dangerous on facial skin without supervision — see [Section 6](#6-do-not-use-on-your-face).

---

## 1. The single most important finding: PMBJP has no sunscreen

I searched all 2,439 rows for `sunscreen`, `SPF`, `broad spectrum`, `titanium dioxide`, `zinc oxide`, `avobenzone`, `octinoxate`, `oxybenzone`, `octocrylene`, `homosalate`, `ensulizole`, `sunblock`, and `photoprotect`.

**Result: zero sunscreen products exist in the PMBJP catalog.** The only `zinc oxide` hits are an oral supplement tablet and a haemorrhoid cream.

This matters more than anything else on this list, because of the way your two main complaints interact:

- Post-acne hyperpigmentation (**PIH**) is pigment that UV actively re-darkens. Without daily UV protection, PIH fades slowly or not at all.
- Every effective ingredient below — adapalene, glycolic acid, azelaic acid, benzoyl peroxide, salicylic acid — is a photosensitiser. They thin the stratum corneum and raise your UV vulnerability.
- You sit in a bus in Indian daylight every single day, often next to a window, with reflected and diffuse UVA coming through glass. Window glass blocks UVB but passes UVA, which is the dominant driver of pigmentation.

Using this protocol **without** sunscreen is the one scenario where you can end up with *worse* pigmentation than you started with, despite the acne improving. Sunscreen is the only item in this routine you must buy outside Janaushadhi. Budget ₹250–400 for a gel or fluid SPF 30+ PA+++ from a regular pharmacy and treat it as non-negotiable infrastructure, not a luxury step.

---

## 2. Complete relevant PMBJP inventory

Every skin-relevant item in the catalog, with the drug code you quote at the Kendra counter.

### 2A. Cleansers

| Code | Exact generic formulation | Unit | MRP |
|---|---|---|---|
| 2261 | Salicylic Acid 2% w/v Foaming Facewash | 60 ml | ₹65.63 |
| 2259 | Salicylic Acid 1% w/v Foaming Facewash | 60 ml | ₹46.88 |
| 1993 | Glycolic Acid 1% w/w + Aloe Vera 5% w/w Face Wash | 100 g | ₹56.25 |
| 2422 | Glycolic Acid 2% + Salicylic Acid 1% + Niacinamide 0.5% + Licorice Extract 1% + Vitamin E 0.2% + Aloe Vera 1% Face Wash | 100 ml | ₹0 |
| 1994 | Glycolic Acid 1% + Aloe Vera 5% + Salicylic Acid 2% Facewash | 60 ml | ₹0 |
| 2797 | Benzoyl Peroxide 5% Soap | 75 g | ₹0 |
| 1672 | Ketoconazole Soap 2% | 75 g | ₹48.46 |

**Reading this for your profile:** code **2422** is the theoretical best single product in the entire catalog for you — salicylic acid for pores, glycolic for texture and marks, niacinamide for oil and pigment, licorice for pigment, aloe and vitamin E to offset stripping. It is unpriced, so ask for it by code but expect **2261** or **2259** instead.

Between the two salicylic washes, **2259 (1%) is the correct pick for you, not 2261 (2%)**. This is counterintuitive with 5 years of acne, but your "tight after washing, oil slick by noon" pattern is the classic signature of a compromised barrier: over-cleansing strips lipids, the skin reads the dryness as damage, and sebaceous glands overproduce to compensate. A 2% salicylic foaming wash used twice daily will deepen exactly that cycle. Start at 1%.

Code **2797** (BPO 5% soap) is useful if you also get chest, shoulder or back acne — it is too harsh for facial skin but genuinely good body-acne value. It also bleaches towels and pillowcases; use white cotton.

Code **1672** is only relevant if your oiliness comes with flaking on the scalp, hairline or eyebrows — that is *Malassezia* seborrhoeic dermatitis or fungal acne, which looks like acne but does not respond to any anti-acne item on this list.

### 2B. Topical acne treatments

| Code | Exact generic formulation | Unit | MRP |
|---|---|---|---|
| 110 | Adapalene Gel 0.1% w/w | 15 g | ₹27.19 |
| 2286 | Adapalene 0.1% w/w + Benzoyl Peroxide 2.5% w/w Gel | 15 g | ₹23.44 |
| 633 | Adapalene 0.1% w/w + Clindamycin Phosphate 1% w/w Gel | 15 g | ₹30.00 |
| 2077 | Benzoyl Peroxide Gel IP 2.5% w/w | 20 g | ₹20.63 |
| 2798 | Benzoyl Peroxide Gel 5% | 15 g | ₹0 |
| 1572 | Clindamycin 1% w/w + Nicotinamide 4% w/w Gel | 15 g | ₹18.75 |
| 2674 | Clindamycin Phosphate Gel 1% w/w | 20 g | ₹30.00 |
| 2331 | Nadifloxacin 1% w/w Cream | 10 g | ₹28.13 |
| 2506 | Benzoic Acid 6% + Salicylic Acid 3% Ointment (Whitfield's) | 15 g | ₹12.19 |
| 2260 | Salicylic Acid 3% Powder | 150 g | ₹0 |

**Reading this for your profile:** **code 110, Adapalene 0.1% gel at ₹27.19, is the backbone of your entire routine.** A third-generation retinoid, it is the only item here that treats all three of your problems at once: it normalises follicular keratinisation so new comedones stop forming, it is anti-inflammatory on active lesions, and it accelerates epidermal turnover so existing dark marks clear faster. It is also the only agent that prevents the *next* mark rather than just fading the last one — which, after 5 years of breakouts, is where your real leverage is.

**Code 2286** (adapalene + BPO 2.5%) is the more powerful choice on paper and excellent value at ₹23.44, because BPO kills *C. acnes* and blocks the antibiotic resistance that plain clindamycin breeds. But it is significantly more drying, and on your already-dehydrated barrier it is likely to trigger a retinoid dermatitis that makes you quit. Earn your way to it after 8–12 weeks on plain adapalene.

**Codes 1572, 2674, 633, 2331 — a deliberate caution.** These are topical antibiotics (clindamycin, nadifloxacin). Used alone on a 5-year acne history they will help for a few weeks and then stop working, while cultivating resistant flora. Standard dermatological practice is never to use a topical antibiotic as monotherapy and never beyond ~12 weeks. If you use one, **1572** (clindamycin + nicotinamide 4%) is the best of the four for you, since the nicotinamide component also reduces sebum and pigment. Pair it with BPO, never solo.

### 2C. Hyperpigmentation and post-acne marks

| Code | Exact generic formulation | Unit | MRP |
|---|---|---|---|
| 2795 | Azelaic Acid 20% Cream | 15 g | ₹0 |
| 2391 | Azelaic Acid 10% + Benzoic Acid 0.2% (preservative) Cream | 15 g | ₹37.50 |
| 2815 | Glycolic Acid Cream 6% | 30 g | ₹0 |
| 2814 | Glycolic Acid Cream 12% | 30 g | ₹0 |
| 459 | **[Rx]** Hydroquinone 2% + Mometasone 0.1% + Tretinoin 0.025% Cream | 20 g | ₹27.23 |
| 2563 | **[Rx]** Hydroquinone 2% + Tretinoin 0.05% + Fluocinolone Acetonide 0.01% Cream | 20 g | ₹0 |
| 2564 | **[Rx]** Hydroquinone 4% + Tretinoin 0.05% + Fluocinolone Acetonide 0.01% Cream | 15 g | ₹0 |

**Reading this for your profile:** **azelaic acid is the ideal molecule for your exact combination**, and code **2391** at ₹37.50 is the one to buy. It is simultaneously anticomedonal, antibacterial against *C. acnes*, anti-inflammatory, and a competitive tyrosinase inhibitor that suppresses new melanin — so it treats the active acne and the marks in a single step. Critically, it is the gentlest of all the pigment agents here and is safe on darker Indian skin, where harsher options can rebound into *more* pigmentation. If code 2795 (20%) is ever stocked, it is the stronger version of the same thing.

The glycolic creams (**2815** at 6%, **2814** at 12%) are genuine PIH faders via exfoliation, but both are unpriced, and 12% on a dehydrated barrier alongside adapalene is a recipe for irritation. Skip 2814 entirely for now.

**Codes 459, 2563, 2564 are the trap in this catalog.** These triple-combination creams are cheap, sold widely, dramatically effective for the first month, and responsible for a large share of steroid-damaged faces in India. The problem is the steroid: mometasone or fluocinolone on facial skin for more than a few weeks causes irreversible skin atrophy, visible telangiectasia (permanent broken capillaries), a steroid-dependent rebound where your face flares worse every time you stop, and **steroid-induced acne** — which would make your primary complaint worse, not better. They are formally indicated for melasma under dermatologist supervision, **not** for post-acne marks, and they are the wrong tool for your problem. Do not buy them. Azelaic acid gets you there safely.

### 2D. Moisturisers and barrier repair

| Code | Exact generic formulation | Unit | MRP |
|---|---|---|---|
| 1960 | Aloe Vera 10% w/w + Vitamin E 1% w/w Moisturising Cream | 60 g | ₹50.00 |
| 715 | Glycerin IP 98% w/w | 50 g | ₹22.69 |
| 2511 | Calamine 8% + Aloe Vera Gel 10% + Light Liquid Paraffin 10% Lotion | 100 ml | ₹56.25 |
| 115 | Calamine Lotion IP | 100 ml | ₹26.25 |

**Reading this for your profile:** this is the catalog's weakest category and the second real gap after sunscreen. There is no ceramide cream, no hyaluronic acid serum, no oil-free gel moisturiser — nothing purpose-built for a dehydrated-but-oily face.

**Code 1960 at ₹50 is your only sensible facial moisturiser here**, and moisturising is the step that actually fixes your core problem. The tight-then-greasy cycle is barrier dysfunction: water is escaping through a damaged barrier, and oil production is the compensation. Consistent moisturising reduces midday oiliness within 2–3 weeks, which is the opposite of what most oily-skinned people expect. It also doubles as your retinoid-tolerance buffer.

**Code 715 (Glycerin IP 98%) is excellent value but must never be applied neat** — at that concentration glycerin is hygroscopic enough to pull water *out* of your skin in dry air. Dilute roughly 1 part glycerin to 8–9 parts water in a clean bottle to make a serviceable humectant toner. This is the cheapest hydration in the entire catalog at ₹22.69.

**Code 2511** is worth keeping for a different reason: calamine plus aloe plus light liquid paraffin is genuinely soothing on heat rash, prickly heat and post-commute flushing across the neck and jaw. Use it as an after-commute calming layer, not as a daily facial moisturiser — calamine is mildly occlusive and drying over time.

### 2E. Oral agents — prescription only, listed for completeness

| Code | Exact generic formulation | Unit | MRP |
|---|---|---|---|
| 2111 | **[Rx]** Isotretinoin Capsules IP 10 mg | 10's | ₹28.13 |
| 1670 | **[Rx]** Isotretinoin Capsules IP 20 mg | 10's | ₹46.88 |
| 92 | **[Rx]** Doxycycline Capsules IP 100 mg | 10's | ₹15.88 |
| 2880–2884 | **[Rx]** Minocycline 50/65/100 mg (incl. ER/MR forms) | 10's | ₹0 |
| 2143 | Zinc Sulphate Dispersible Tablets IP 20 mg | 10's | ₹9.38 |
| 2206 / 588 | Vitamin E Capsules 600 mg / 400 mg | 10's | ₹26.25 / ₹22.69 |
| 2278 | Vitamin C 1000 mg + Vitamin D3 400 IU + Zinc 10 mg Effervescent | 10's | ₹0 |

**Reading this for your profile:** you should know these exist, because **5 years of continuous active acne with scarring and pigmentation is, by standard dermatological criteria, exactly the presentation that warrants oral therapy** rather than another year of topicals. Oral isotretinoin is the only treatment that produces lasting remission in persistent acne, and at ₹28–47 per strip the PMBJP pricing makes a full course affordable in a way branded isotretinoin is not.

It requires a dermatologist. It needs baseline and periodic liver enzymes and lipids, it causes significant dryness that changes this entire routine, it is absolutely incompatible with tetracyclines, and it is severely teratogenic — the last point is not a personal risk for you but it governs how the drug is dispensed. **Do not self-start it.** Take this list to a doctor; a single government-hospital dermatology consult plus PMBJP-priced isotretinoin is plausibly the highest-value move available to you.

Zinc sulphate (**2143**, ₹9.38) has modest evidence as an adjunct in inflammatory acne and is low-risk. Do not take it in the same hour as doxycycline or minocycline — zinc chelates tetracyclines and blocks their absorption.

---

## 3. What to actually buy

The minimum effective kit, all currently priced and stockable:

| Code | Product | MRP |
|---|---|---|
| 2259 | Salicylic Acid 1% Foaming Facewash, 60 ml | ₹46.88 |
| 110 | Adapalene Gel 0.1%, 15 g | ₹27.19 |
| 2391 | Azelaic Acid 10% Cream, 15 g | ₹37.50 |
| 1960 | Aloe Vera 10% + Vitamin E 1% Moisturising Cream, 60 g | ₹50.00 |
| 715 | Glycerin IP 98%, 50 g — to dilute | ₹22.69 |
| | **PMBJP subtotal** | **₹184.26** |
| | Broad-spectrum SPF 30+ PA+++ gel/fluid — **non-PMBJP, mandatory** | ~₹250–400 |

Ask by drug code, and also ask for **2422** (the 6-active face wash) — if your Kendra has it, buy it instead of 2259.

---

## 4. Morning routine — commute defence

Your morning has one job: leave a functional barrier and a UV shield between your skin and the bus.

**Step 1 — Cleanse, lukewarm water only.** Code **2259**, a pea-sized amount, 20–30 seconds, then rinse. Hot water strips lipids and drives the tight-then-oily rebound. Pat dry with a clean towel; do not rub. If your face feels tight and squeaky at this point, you have used too much or washed too long.

**Step 2 — Hydrate on damp skin.** Diluted **715** glycerin toner (1:9 with water), patted on while your face is still slightly damp. Humectants need water present to work; on bone-dry skin they pull moisture from your dermis instead. This step is what breaks your dehydration cycle.

**Step 3 — Moisturise.** Code **1960**, a thin layer. Wait ~2 minutes before the next step. Do not skip this because you feel oily — the oil is *caused* by skipping it.

**Step 4 — Sunscreen, every single day.** Broad-spectrum SPF 30+ PA+++, two finger-lengths for face and neck, applied 15 minutes before leaving. Include your ears and the back of your neck — bus windows, and you are likely getting asymmetric exposure on whichever side you sit. This step protects your marks from re-darkening and protects the adapalene-thinned skin from burning. On a heavy-sun commute, reapply once around midday if you can; otherwise carry a cap and prefer the aisle or shaded side.

**Do not** use azelaic acid or adapalene in the morning. Layering more photosensitising acid under direct UV works against you.

### Midday, on the road
Blot oil with plain tissue or blotting paper. **Do not wash your face at a public tap** — a third wash strips the barrier further and drives more oil, and unfiltered tap water on freshly exfoliated skin is an avoidable irritant and infection route. Blotting removes surface oil without touching the barrier.

---

## 5. Evening routine — repair and correct

**Step 1 — Cleanse.** Code **2259** again. This wash matters most: it removes a day of pollution particulates, sweat, sebum and sunscreen. Particulate pollution generates oxidative stress that both aggravates acne and worsens pigmentation, so the evening cleanse is doing real work for your commute exposure.

**Step 2 — Dry completely, then treat.** Applying a retinoid to damp skin increases penetration and irritation. Give it 5–10 minutes.

**Step 3 — Active, on alternating nights.** Do **not** use adapalene and azelaic acid on the same night when starting out.

- **Nights A (adapalene, code 110):** one pea-sized amount for the *entire* face. This is the most common mistake — more adapalene does not work faster, it only irritates. Spread it thin over all acne-prone areas rather than dotting it on individual pimples; it is preventive, not a spot treatment. Avoid the eyelids, nostril creases and lip corners.
- **Nights B (azelaic acid, code 2391):** a thin layer over marked areas, or the whole face. Expect mild transient tingling for the first week.

**Ramp-up schedule** — this is the difference between success and quitting in week three:

| Weeks | Adapalene (110) | Azelaic (2391) |
|---|---|---|
| 1–2 | 2 nights/week | 2 nights/week, on off-days |
| 3–4 | 3 nights/week | 3 nights/week, on off-days |
| 5–8 | alternate nights | alternate nights |
| 9+ | nightly if comfortable | nightly, or AM once tolerated |

**The buffering technique** for the first 2–4 weeks: apply moisturiser (**1960**) *first*, wait 10 minutes, then apply adapalene on top. This reduces irritation substantially with only a small loss of potency, and it is far better to run a buffered routine you actually stick to than an aggressive one you abandon.

**Step 4 — Moisturise.** Code **1960**, applied ~20 minutes after the active. Reapply generously if you feel tight.

**Optional:** on a hot, sweaty commute day with flushing or prickly heat on the neck and jaw, code **2511** as a calming layer before bed.

### What to expect, honestly
- **Weeks 2–5: purging.** Adapalene accelerates turnover and pushes existing microcomedones to the surface, so your acne will likely look *worse* before it looks better. This is expected and is not an allergic reaction. Distinguish it from true irritation: purging is small pimples in your usual breakout zones; irritation is diffuse redness, burning, peeling and stinging. Purging — continue. Irritation — reduce frequency and buffer more.
- **Weeks 8–12:** meaningful reduction in new lesions.
- **Marks:** PIH fades over **3–6 months** with consistent sun protection, sometimes longer on deeper skin tones. Nothing in this catalog fades marks in weeks.
- **Midday oiliness:** should measurably improve by weeks 3–4 once the barrier rehydrates.

One caveat worth naming: **if your marks are indented or raised rather than flat and brown, they are scars, not pigmentation.** Post-acne scarring does not respond to any topical in this catalog — it needs procedural treatment. That, plus 5 years of activity, is another reason a dermatologist visit is worth more than any product on this list.

---

## 6. Do not use on your face

| Code | Product | Why |
|---|---|---|
| 459, 2563, 2564 | Hydroquinone + Tretinoin + **steroid** triple creams | Facial skin atrophy, permanent telangiectasia, steroid rebound, steroid-induced acne. Indicated for melasma under supervision, not for post-acne marks. |
| 118, 1575–1580, 2299, 2055, 2081 | Clobetasol / Halobetasol combinations | Super-potent steroids. Cause steroid acne and atrophy. Never on the face. |
| 112, 113, 461, 462, 672, 1162, 1522, 1527, 634, 1638, 2421, 2423 | Betamethasone / Beclomethasone / Mometasone / Fluocinolone / Hydrocortisone / Fusidic acid combos | Steroid + antibiotic + antifungal "all-in-one" creams. Widely misused for acne in India; reliably worsen it. |
| 2558 | Janaushadhi Footcare Cream (Urea 10% + Lactic Acid 10%) | Formulated for plantar skin. Far too aggressive for facial skin despite being a tempting "moisturiser". |
| 2506, 2260 | Benzoic 6% + Salicylic 3% ointment; Salicylic 3% powder | Whitfield's ointment and dusting powder — keratolytic strengths meant for feet and body, not the face. |
| 2814 | Glycolic Acid Cream 12% | Too strong to combine with adapalene on a dehydrated barrier. Revisit only after months of stability. |
| 1497, 1512–1514, 1810, 2642 | Acitretin, Apremilast, Tacrolimus, Tofacitinib | Psoriasis/eczema/immunomodulator agents. Not acne drugs, significant systemic risk. |

---

## 7. Summary

The PMBJP catalog covers your **active acne** well (adapalene at ₹27 is world-standard therapy at a rounding-error price) and covers your **pigmentation** adequately through azelaic acid at ₹37.50, provided you avoid the steroid combination creams that dominate that category.

It covers your **barrier dehydration** poorly — one aloe/vitamin-E cream and a glycerin tub — but that is workable.

It does **not** cover **photoprotection at all**, and photoprotection is the load-bearing step for a daily bus commuter with post-inflammatory hyperpigmentation. Buy the sunscreen outside the scheme. Roughly ₹184 of generics plus one non-PMBJP sunscreen gives you a genuinely complete, evidence-aligned routine.

And given 5 continuous years of activity plus marks, the highest-leverage step is not on this list: get a dermatologist to assess whether you are a candidate for oral isotretinoin, which PMBJP then makes affordable at ₹28–47 per strip.

---

*Prepared from the PMBJP product list in this repository. Educational information, not a prescription. Prescription-only items require a registered medical practitioner.*
