# Five-Dimension Scoring Rubric

> **A reproducible, theory-grounded instrument for evaluating search advertisement quality.**
> 
> Each dimension scored 1–10, consistent with Google's published Quality Score methodology.

---

## Rubric Overview

| Dimension | Weight | What It Measures |
|-----------|:------:|-----------------|
| **1. Keyword Alignment** | Equal | Correspondence between query's literal terms and ad copy |
| **2. Intent Match** | Equal | Whether the ad addresses the underlying reason for the search |
| **3. Ad Relevance** | Equal | Clarity, specificity, and quality of the ad copy itself |
| **4. Landing Page Fit** | Equal | Correspondence between ad promise and post-click experience |
| **5. Trust Signals** | Equal | Credibility markers supporting the advertisement's claims |

**Composite Score:** Arithmetic mean of the five dimensions (max 10.0)

---

## Dimension 1: Keyword Alignment

> *Correspondence between the query's literal terms and the advertisement's visible copy.*

| Score | Anchor Description |
|:---:|:---|
| **10** | All query terms (core + modifiers) appear prominently in headline and description |
| **8–9** | Core terms appear in headline; most modifiers appear in description or extensions |
| **6–7** | Core terms appear in description but not headline; modifiers absent |
| **4–5** | Some query terms appear, but not the most distinctive or high-intent terms |
| **2–3** | Minimal term overlap; generic copy that could apply to any related query |
| **1** | No apparent connection between query terms and ad copy |

**Key Signal:** Does the headline contain the query's most specific modifier? (e.g., "small business" for "affordable CRM software for small business")

---

## Dimension 2: Intent Match

> *Whether the advertisement addresses the underlying reason for the search, not just its literal wording.*

| Score | Anchor Description |
|:---:|:---|
| **10** | Perfect alignment — ad offer directly matches query intent category and stage |
| **8–9** | Strong alignment — ad addresses intent with minor stage mismatch |
| **6–7** | Moderate alignment — ad partially addresses intent; some mismatch in offer type |
| **4–5** | Weak alignment — ad addresses a related but different intent |
| **2–3** | Poor alignment — ad is well-written but for a fundamentally different intent |
| **1** | Fundamental mismatch — ad contradicts or ignores query intent |

**Intent Categories:**
- **Informational:** User wants to learn (ad should educate, offer resources)
- **Commercial Investigation:** User compares options (ad should differentiate, offer comparisons)
- **Transactional:** User ready to act (ad should enable purchase/booking with clear CTA)
- **Navigational:** User seeks a specific brand (ad should confirm brand identity, direct efficiently)

**Critical Principle:** A well-written ad for the *wrong* intent scores lower than a mediocre ad for the *right* intent.

---

## Dimension 3: Ad Relevance

> *Clarity, specificity, and quality of the advertisement copy itself.*

| Score | Anchor Description |
|:---:|:---|
| **10** | Exceptional copy — compelling, specific, clear value proposition, strong CTA |
| **8–9** | Strong copy — clear benefits, specific offer, appropriate urgency |
| **6–7** | Competent copy — readable, on-topic, but generic or undifferentiated |
| **4–5** | Weak copy — vague claims, no specific offer, weak or missing CTA |
| **2–3** | Poor copy — confusing, misleading, or grammatically flawed |
| **1** | Unusable copy — broken, off-topic, or spam-like |

**Evaluation Criteria:**
- Is the value proposition stated in the first headline?
- Is there a clear, appropriate call-to-action?
- Are claims specific and verifiable (not "best" or "#1" without evidence)?
- Is the copy free of ambiguity or contradiction?

---

## Dimension 4: Landing Page Fit

> *Correspondence between the advertisement's promise and the page it links to.*

| Score | Anchor Description |
|:---:|:---|
| **10** | Seamless fulfillment — page immediately delivers on every ad promise |
| **8–9** | Strong fit — page delivers on primary promise with minor secondary gaps |
| **6–7** | Moderate fit — page related but requires navigation to find promised content |
| **4–5** | Weak fit — page only loosely related to ad; user must search for relevance |
| **2–3** | Poor fit — page contradicts ad or leads to unrelated content |
| **1** | Broken/misleading — page is error, spam, or fundamentally different offering |

**Evaluation Criteria:**
- Does the page headline match the ad headline's core promise?
- Is the promised offer (price, feature, action) immediately visible above the fold?
- Is the page technically functional (loads, no errors, mobile-responsive)?
- Are trust signals present (security, contact info, social proof)?

---

## Dimension 5: Trust Signals

> *Credibility markers supporting the advertisement's claims.*

| Score | Anchor Description |
|:---:|:---|
| **10** | Abundant, high-quality trust signals — reviews, certifications, guarantees, transparent pricing |
| **8–9** | Strong trust signals — recognizable brand, clear contact, professional design |
| **6–7** | Adequate trust signals — basic contact info, functional design, no red flags |
| **4–5** | Weak trust signals — minimal contact info, dated design, sparse content |
| **2–3** | Poor trust signals — missing contact info, no security, suspicious claims |
| **1** | No trust signals or active red flags (scam indicators, false claims) |

**Trust Signal Checklist:**
- [ ] Business name and physical address visible
- [ ] Contact method (phone, email, form) accessible
- [ ] Security certificate (HTTPS)
- [ ] Customer reviews or testimonials
- [ ] Professional, modern design
- [ ] Transparent pricing or clear service description
- [ ] Industry certifications or affiliations

---

## Composite Score Interpretation

| Composite | Interpretation | Action |
|:---:|:---|:---|
| **9.0–10.0** | Exemplary | Benchmark; study for replication |
| **7.0–8.9** | Strong | Minor optimization opportunities |
| **5.0–6.9** | Moderate | Specific dimension(s) require intervention |
| **3.0–4.9** | Weak | Fundamental mismatch or structural problem |
| **1.0–2.9** | Unacceptable | Remove or completely rebuild |

---

## Inter-Rater Reliability Design

This rubric is designed to support formal inter-rater reliability testing:

1. **Named dimensions** allow independent scoring (no holistic "gut feeling")
2. **Numeric scale** enables statistical agreement calculation (Cohen's kappa, ICC)
3. **Written justifications** make scores challengeable and revisable
4. **Evidence citations** allow a second reviewer to verify the basis for each score

**Target Standard:** Two independent evaluators should produce composite scores within ±0.5 points for the same advertisement, with no dimension differing by more than 1 point.

---

*[← Back to main README](../README.md)*
