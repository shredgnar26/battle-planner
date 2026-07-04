# Partnership Proposal: A Physician-Led, Cash-Pay Weight Loss & Lifestyle Medicine Platform

**Prepared for:** Dr. Morsy (Triple Board-Certified — Anesthesiology, Pain Medicine, Obesity Medicine)
**Prepared by:** [Your Name], Co-Founder / CTO & Operations
**Date:** July 4, 2026
**Status:** Draft for discussion — v1.0

---

## 0. Why this document exists

The June 24 strategic brief was preparation for *listening* at the discovery meeting. This document is the other side of that conversation: an actual proposal for what we build, how we split responsibility, and what we ask of each other to make it real. It assumes the discovery conversation confirmed the direction — a cash-pay, physician-led obesity and lifestyle medicine platform, modeled directionally on Dr. Darshan Shah's Next Health trajectory, but built at our scale and starting with one clinical thesis instead of fifteen service lines.

Anything below that depends on facts we don't have yet (his actual financial commitment, his time budget, his equity expectations) is flagged explicitly rather than assumed. This is a proposal to align on, not a finished document to sign.

---

## 1. Executive Summary

We propose building **a productized, cash-pay obesity and lifestyle medicine platform** that combines:

1. **Medical oversight** — Dr. Morsy and his NPs manage GLP-1 pharmacotherapy (semaglutide/tirzepatide), metabolic testing, and clinical safety under physician-directed protocols.
2. **Productized coaching** — a structured, curriculum-driven behavior-change program built on Motivational Interviewing and the six ACLM lifestyle medicine pillars, delivered by trained coaches, not ad hoc advice.
3. **A branded mindset product** — a companion app (working name: **The Battle Plan**) that gives each member a daily accountability system: a plan, a check-in, and a weekly reflection — turning "I'm on Ozempic" into "I'm becoming someone who doesn't need it."

The clinical thesis is narrow on purpose: **GLP-1 is the bridge, not the destination.** Medication drives the biological window of appetite suppression and glycemic improvement; the coaching and mindset layer is what makes the weight loss durable after the medication is tapered or stopped. That integration — not the prescription itself — is the product, and it's what protects the business from being "one regulatory change away from an existential crisis," per the earlier strategic brief.

Revenue is cash-pay membership plus medication cost pass-through, not insurance billing. Target launch price: **$250–500/month core membership**, with GLP-1 costs billed separately at pharmacy cost or a modest markup, and an optional concierge tier above that.

Long-term, the ambition mirrors the Shah/Next Health arc — a branded, systemized, multi-location or licensable platform — but the path there runs through Year 1 discipline: one clinical thesis, one location, provable retention, before any expansion conversation.

---

## 2. The Opportunity

- **The GLP-1 moment is real but time-limited as a standalone offer.** Semaglutide and tirzepatide are the most effective pharmacological weight-loss tools available, and patient demand is at an all-time high. But roughly two-thirds of weight lost on GLP-1s returns within 12 months of stopping the medication without an accompanying lifestyle change, and a meaningful share of what's lost without resistance training is lean muscle, not fat — a worse metabolic outcome than doing nothing. That's the gap this business exists to close.
- **Cash-pay demand already exists and is growing.** Patients paying $900–1,300/month out of pocket for brand-name GLP-1s have already opted out of the insurance system. They are not price-sensitive in the way a typical primary care patient is; they are outcome-sensitive and skeptical, having likely failed Weight Watchers, keto, a trainer, or an app before arriving here.
- **The market has a coaching-quality gap.** Every major competitor in this space (Calibrate, Found, Noom Med) has been criticized publicly for thin or inconsistent coaching quality once medication is delivered. A physician-led platform with a genuinely structured, credentialed coaching layer is a real point of differentiation, not a marketing claim.
- **Lifestyle Medicine gives us a defensible clinical framework, not just a marketing narrative.** The ACLM's six pillars (nutrition, physical activity, sleep, stress management, connectedness, avoidance of risky substances) and its emphasis on Motivational Interviewing as a clinical tool are evidence-based and well-documented — this is a credentialing and protocol foundation, not wellness-adjacent hand-waving.

---

## 3. What We Are Actually Selling

Borrowing the framing that tested well in earlier discovery prep: **the patient is not buying a prescription, a membership, or a diet. They are buying a credible path to becoming a different version of themselves, at a point where they've stopped believing that path exists.**

That means the product has to be built in four layers, and every one of them needs an owner:

| Layer | What it is | Primary owner |
|---|---|---|
| **1. Clinical infrastructure** | Physician-led intake, metabolic workup, GLP-1 prescribing, biomarker tracking, NP-driven monitoring | Dr. Morsy + NPs |
| **2. Behavior change system** | MI-based coaching, structured curriculum across the six pillars, weekly touchpoints | Coaching team, protocol designed jointly |
| **3. Community & accountability** | Cohort programming, peer groups, milestone recognition | Coaching team + product |
| **4. Identity & mindset product** | Daily planning, vision-setting, weekly reflection — "The Battle Plan" | You (product/CTO) |

Layers 1 and 2 are what make this defensible as medicine. Layers 3 and 4 are what make it a *productized* offer instead of a clinic with a subscription bolted on — and they're also where the "mindset products" you mentioned live concretely, not abstractly.

### The Battle Plan: turning the mindset product into something real, not aspirational

This repository already contains a working prototype of exactly this layer — a daily accountability app built around a military "battle plan" metaphor:

- **Quadrants** — daily prioritization across the areas that actually move outcomes (nutrition, movement, sleep, stress/mindset), instead of a single "did you log your food" checkbox.
- **Daily** — a lightweight daily check-in.
- **Vision** — where the member articulates who they're becoming, not just a number on a scale — directly answering the "identity change, not weight loss" insight above.
- **AAR (After Action Review)** — a weekly reflection modeled on the military debrief format: what worked, what didn't, what changes next week. This is a natural home for MI-style reflective prompts and ties directly into the coach's weekly touchpoint.

Rather than building a generic wellness app from scratch, the proposal is to extend this existing prototype into the member-facing mindset product — rebranded and re-themed around the transformation journey, feeding data (engagement, check-in completion) into the coaching and churn-risk workflows described in Section 7. It's a real asset already in hand, not a line item on a future roadmap.

---

## 4. Roles & Partnership Structure

This is the section the earlier discovery prep flagged as the single most important thing to nail down before building anything, and it deserves the same directness here.

### Proposed division of responsibility

| Function | Owner | Notes |
|---|---|---|
| Medical direction, GLP-1 prescribing, clinical protocol authority | **Dr. Morsy** | Final say on all clinical matters; brand-anchoring credibility (triple board certification) |
| Day-to-day patient monitoring, med management under protocol | **NPs** | Supervised by Dr. Morsy per Texas requirements |
| Coaching curriculum design & delivery, behavior-change protocol | **You**, in collaboration with Dr. Morsy on clinical boundaries | Coaches operate under a written scope: they support behavior change, they do not interpret labs or adjust medications |
| Technology stack, mindset product, data architecture, automation/AI | **You (CTO)** | EHR selection, patient portal, Battle Plan app, HIPAA-compliant infrastructure |
| Business operations, marketing systems, growth | **You**, with Dr. Morsy's public-facing brand participation | See Section 8 on content/media |
| Final clinical authority vs. final business/operational authority | **To be defined in the operating agreement** | This is the one item that should not be left implicit |

### Your clinical scope needs an explicit answer, not an assumption

If your own clinical license (e.g., CRNA or equivalent) is part of the value you bring, that needs to be scoped precisely against this specific service line before it's built into the plan — obesity medicine and lifestyle medicine coaching is a different scope question than anesthesia. Two honest paths, and either is fine, but they lead to different agreements:

- **Path A: You are CTO/Operator, full stop.** Your clinical background informs product and protocol design, but you are not delivering hands-on clinical care in this venture. This is the cleaner path and the one that avoids scope-of-practice ambiguity.
- **Path B: You hold a defined clinical role** (e.g., specific monitoring or intake functions your license supports). This requires explicit confirmation with a healthcare attorney before it's written into the business model — not assumed because it would be convenient.

**Recommendation: default to Path A for the proposal, and treat Path B as a possible expansion once counsel confirms it's viable.** It's easier to add clinical scope later than to unwind a structure built on an incorrect assumption.

### Legal/equity structure (Texas)

Texas's corporate practice of medicine doctrine means a non-physician cannot own the medical practice outright. The standard, well-established workaround:

- Dr. Morsy owns the **Professional Association or PLLC** that employs clinical staff and carries clinical liability.
- A separate **Management Services Organization (MSO)** — where you can hold real equity — owns the brand, technology, real estate, marketing, and operations, and contracts with the physician entity for a management fee.

This structure is not optional if equity is the goal. Without it, the relationship defaults to employee-or-contractor, not partner. **This should be the first thing locked in with counsel, before a single patient is seen** — not a detail to resolve after the business is running.

### The open question that has to be asked directly, not assumed

A handshake and "I'll offer you a partnership if the proposal is good" is real interest — it is not an equity commitment, a governance structure, or a term sheet. Before this proposal becomes a business, two numbers need to be on the table explicitly: **what equity stake and what decision rights** you're each expecting. This proposal is written to earn that conversation, not to replace it.

---

## 5. Getting Your Lifestyle Medicine Credential

Dr. Morsy's suggestion to pursue a lifestyle medicine credential is worth acting on for two reasons: it strengthens your standing to design and oversee the coaching/behavior-change layer (Section 3, Layers 2–4), and it signals to patients and to Dr. Morsy that the coaching side of the business is built on the same evidence-based footing as the clinical side — not a soft add-on.

Practical path:

1. **Join ACLM as a member now** (lifestylemedicine.org/membership) — low cost, immediate access to the clinician/coach community and CME-accredited coursework in nutrition, physical activity, behavior change, and clinical application.
2. **Complete ACLM's education pathway** relevant to your role — the coursework spans food-as-medicine, behavior change, and clinical implementation modules, independent of whether you hold prescribing authority.
3. **Confirm the correct certification track for a non-prescribing operator/coach role directly with ACLM** before committing to a specific credential name or timeline — certification pathways (including any board-certification-adjacent tracks for allied health roles) are evolving, and eligibility depends on your specific license. Don't let this proposal assert a credential name that turns out to be the wrong one; verify it as the very next action.
4. **Target having a credential in hand, or clearly in progress, before launch marketing goes out** — the ACLM identity should show up in Dr. Morsy's bio *and* yours, reinforcing that the whole team, not just the physician, operates on an evidence-based framework.

This is a low-cost, near-term action item you can start on this week, independent of how the equity conversation resolves.

---

## 6. Pricing & Revenue Model

Four revenue engines, consistent with how membership-based longevity and obesity platforms actually make money (Next Health, Virta, Calibrate all rely on some combination of these):

1. **Core membership fee** — $250–500/month. Includes coaching cadence, curriculum access, community/cohort programming, and the Battle Plan mindset product.
2. **Physician-guided clinical program** — initial 60–90 minute physician consultation, ongoing NP-driven monitoring, biomarker tracking.
3. **GLP-1 medication** — billed at or near actual cost (brand-name Wegovy/Zepbound run $900–1,300/month retail; compounded alternatives carry real regulatory risk post-2025 FDA enforcement and should not be the basis of the financial model — verify current compounding legality before pricing anything around it).
4. **Ancillary/concierge upsells** — advanced testing, higher-touch physician access tiers, later-stage additions (only after Year 1 retention is proven — resist the temptation to add a broad service menu on day one).

**Target metric, not a guess:** 70%+ member retention at 12 months. Below 60% signals a structural product problem, not a marketing problem — this is the number to track from week one.

---

## 7. Technology & AI Approach (lean version)

Keep this deliberately minimal for launch — the instinct to overbuild the tech stack before the clinical model is proven is a real failure mode in this category.

- **EHR (clinical system of record):** a standard HIPAA-compliant EHR for prescriptions, labs, and clinical documentation. Not consumer-facing — that's what the Battle Plan app is for.
- **Member-facing app:** extend the existing Battle Plan prototype rather than building new — Supabase-backed, HIPAA-appropriate configuration once it touches any identifiable health data.
- **Communications:** SMS/automated check-ins and reminders via a BAA-covered provider (e.g., Twilio) — never send anything referencing a specific patient's health status without a signed BAA in place first.
- **AI, used narrowly at first:** de-identified engagement data to flag churn risk 30–60 days before a member actually cancels; AI-assisted clinical documentation to protect physician/NP time; personalized curriculum sequencing inside the Battle Plan app. Anything touching PHI directly needs a signed enterprise BAA before deployment — treat this as a hard gate, not a compliance afterthought.
- **The single most important early-warning metric:** curriculum/module completion in the first 30 days is the strongest predictor of 90-day retention. Build the Battle Plan's engagement tracking around catching this early, not after the member has already disengaged.

---

## 8. Compliance Guardrails (flag, don't solve, in this document)

None of the following is legal advice — it is a list of what needs a licensed healthcare attorney's sign-off before the business takes its first patient:

- **MSO/PLLC structure** (Section 4) — confirm mechanics and management-fee terms.
- **Cash-pay model** — confirm that not billing Medicare/Medicaid for any covered service keeps the anti-kickback exposure clean given the specific service mix.
- **Coaching scope** — coaches are not licensed clinical providers in Texas; they cannot diagnose, prescribe, or interpret labs. This boundary needs to be written into the coaching protocol, not left implicit.
- **GLP-1 compounding risk** — the 2025–2026 FDA enforcement environment against compounded semaglutide/tirzepatide is active. Do not build the financial model around compounded pricing without current legal verification.
- **Advertising claims** — FTC scrutiny of weight-loss marketing is real. Lean on Dr. Morsy's board certifications and your own outcomes data once you have it; avoid "lose X pounds in Y days" language entirely.
- **Telemedicine/multi-state** — if any patients are outside Texas, confirm state-by-state prescribing rules, especially for DEA-controlled substances, before designing a telemedicine-first protocol.

---

## 9. Competitive Snapshot

| Platform | Core thesis | What to learn from them |
|---|---|---|
| Virta Health | Clinical outcomes data as defensibility | Publish your own outcomes data early — it becomes the moat |
| Calibrate | Medication + coaching | Coaching quality complaints sank trust — do not let coaching feel like an afterthought |
| Found | Accessible price, multi-medication | Struggled with clinical quality at scale — don't chase volume before quality is proven |
| Noom Med | Behavioral psychology brand, app-first | App-first without real clinical depth reads as thin — our clinical layer must be unambiguously real medicine |
| Next Health (Shah) | Broad service menu, experience design, franchise systemization | The long-term aspiration, not the launch template — do not lead with a broad menu in Year 1 |
| Open Loop Health | Cash-pay, high-touch GLP-1 + coaching model (referenced by name in the brief) | *Direct site research was blocked by network policy in this session (openloophealth.com returned a 403 at the network gateway level, not from the site itself) — worth pulling a fresh look at their positioning and pricing manually before finalizing our own, since this is the closest named comparable.* |

---

## 10. Phased Roadmap

- **Year 1 — Validate.** One clinical thesis (Obesity + Lifestyle Medicine), one location, physician + one NP + two-to-three coaches. Target 50–150 members, $500K–$1M ARR. Lock the MSO/PLLC legal structure and operating agreement *before* seeing a single patient — this is the single highest-priority task of the year.
- **Year 2 — Optimize.** Formalize the community/cohort layer, begin publishing your own outcomes data, start Dr. Morsy's public content presence (podcast, LinkedIn, or speaking) to bring down acquisition cost over time.
- **Year 3 — Systemize.** Document protocols and training so the business can run at high quality without either of you present full-time. Test a virtual-only expansion into one adjacent market.
- **Years 4–5 — Expand.** Second location, broader virtual footprint, or licensing the operating system to other physicians — decide the vehicle based on what Year 1–3 actually proved, not on the Next Health aspiration.
- **Years 6–7 — Optionality.** A business with value independent of either founder's daily presence — sellable, licensable, or a platform for continued founder-led growth.

---

## 11. What This Proposal Is Asking For

1. **Agreement on the clinical thesis:** Obesity Medicine + Lifestyle Medicine, GLP-1 as bridge not destination, one location to start.
2. **A real conversation about equity and decision rights** — not deferred, not assumed.
3. **Confirmation of the MSO/PLLC structure with counsel**, so equity is actually possible.
4. **Sign-off to start the ACLM membership and certification path now**, independent of the rest of the negotiation.
5. **Agreement to extend the existing Battle Plan prototype into the member-facing mindset product**, rather than commissioning something new.

---

*This is a proposal to align on, not a final agreement. Compliance items in Section 8 require licensed healthcare attorney review before any business formation step is taken. Certification specifics in Section 5 should be confirmed directly with ACLM before being finalized in any marketing material.*
