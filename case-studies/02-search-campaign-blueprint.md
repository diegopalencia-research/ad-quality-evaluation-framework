# Case Study 02: Search Campaign Blueprint — LexGuatemala

> **Objective:** Design a complete Google Ads account architecture for a legal services client, organized around a single conversion KPI: cost per consultation lead.

---

## Client Profile

**LexGuatemala** is a composite client representing immigration and corporate law services in Guatemala with a secondary market among the Guatemalan diaspora in the United States.

**Primary Service Lines:**
- **Immigration:** Visa applications, residency processing, citizenship guidance
- **Corporate Law:** Business formation, contract review, regulatory compliance

**Target Audiences:**
1. Guatemalan nationals seeking U.S. immigration assistance
2. Guatemalan entrepreneurs requiring corporate legal services
3. English-speaking Guatemalan diaspora in the U.S. seeking bilingual legal services

---

## Campaign Architecture

Four ad groups, each aligned to a distinct search intent following Broder's (2002) taxonomy:

| Ad Group | Search Intent | Representative Keyword | Match Type |
|:---|:---|:---|:---:|
| **AG-01: Visa & Immigration** | Transactional | `[abogado de visas Guatemala]` | Exact |
| **AG-02: Corporate & Business Law** | Commercial Investigation | `[abogado corporativo Guatemala]` | Exact |
| **AG-03: US Diaspora (English)** | Transactional | `[Guatemala immigration lawyer]` | Exact |
| **AG-04: Brand & Competitor Defense** | Navigational | `[LexGuatemala]` | Exact |

**Total:** 24 keywords · 8 Responsive Search Ads · Independent negative-keyword lists per ad group

---

## Ad Group Details

### AG-01: Visa & Immigration (Transactional)
- **Goal:** Capture users actively seeking to initiate immigration services
- **Keywords:** `visa lawyer Guatemala`, `US visa application help`, `immigration attorney near me`, `residency permit Guatemala`
- **RSA Headlines:**
  - *"Abogado de Visas Guatemala · Consulta Gratis"*
  - *"Trámite de Residencia USA · Asesoría Legal"*
  - *"Visa de Trabajo Guatemala · Experiencia Comprobada"*
- **Quality Score Projection:** 8/10

### AG-02: Corporate & Business Law (Commercial Investigation)
- **Goal:** Capture users evaluating legal providers for business needs
- **Keywords:** `business lawyer Guatemala`, `company formation attorney`, `contract review service`, `corporate law firm Guatemala`
- **RSA Headlines:**
  - *"Abogado Corporativo Guatemala · PYMES"*
  - *"Constitución de Empresas · Desde Q2,500"*
  - *"Revisión de Contratos · Proteja su Negocio"*
- **Quality Score Projection:** 7/10

### AG-03: US Diaspora (English) (Transactional)
- **Goal:** Serve English-speaking diaspora with independently written copy (not direct translation)
- **Keywords:** `Guatemala immigration lawyer`, `Guatemala visa US citizen`, `dual citizenship Guatemala`, `Guatemala attorney English speaking`
- **RSA Headlines:**
  - *"Guatemala Immigration Lawyer · Online Consultations"*
  - *"Trusted Legal Experts · Get Help Now"*
  - *"US-Guatemala Visa Process · Bilingual Support"*
- **Negative Keywords:** U.S.-domestic immigration queries (`USCIS`, `green card application USA`) to prevent structural ambiguity
- **Quality Score Projection:** 8/10

### AG-04: Brand Defense (Navigational)
- **Goal:** Protect branded search traffic from competitor conquest
- **Keywords:** `LexGuatemala`, `LexGuatemala immigration`, `LexGuatemala reviews`
- **RSA Headlines:**
  - *"LexGuatemala · Abogados de Confianza"*
  - *"Consulta Gratis · Reserva Hoy"*
- **Quality Score Projection:** 9/10

---

## Extensions Strategy

| Extension Type | Application |
|----------------|-------------|
| **Sitelinks** | Visas, Corporate, Consultation Booking, About Us |
| **Callouts** | Bilingual Services, Virtual Consultations, 20+ Years Experience, Free Initial Consultation |
| **Structured Snippets** | Service categories: Immigration, Corporate, Family Law, Tax Advisory |
| **Call Extensions** | Direct phone contact — critical for urgent legal queries |
| **Location Extensions** | Guatemala City office + virtual consultation availability |

---

## Bidding Strategy (3-Phase)

| Phase | Duration | Strategy | Objective |
|-------|----------|----------|-----------|
| **Phase 1: Launch** | Weeks 1–4 | Maximize Clicks (daily budget cap) | Generate traffic, accumulate conversion data, identify high-performers |
| **Phase 2: Optimization** | Weeks 5–12 | Target CPA (tCPA @ GTQ 200 / ~USD 26) | Optimize for lead form completions and consultation bookings |
| **Phase 3: Scale** | Week 13+ | Maximize Conversions (enhanced tracking) | ML-driven optimization for highest-value conversion actions |

---

## Quality Score Diagnostic

A per-ad-group diagnostic was applied following Google's published methodology:

### AG-01 Diagnostic

| Component | Rating | Notes |
|-----------|--------|-------|
| Expected CTR | Above Average | Strong intent match, competitive CTR |
| Ad Relevance | Above Average | Keywords present in headlines, clear value proposition |
| Landing Page Experience | Average | **Identified constraint** — primary optimization target |

**Documented Recommendation:**
> "Incorporate the primary keyword into the page's main heading, reduce page load time, and surface a trust signal above the fold, rather than adjusting advertisement copy that is already performing above average."

This diagnostic approach — identifying the *specific* underperforming component and attaching a concrete action — mirrors the feedback standard required for AI-powered advertising system calibration.

---

## Bilingual Design Evidence

AG-03 demonstrates working proficiency in **both English and Spanish** within a single applied project:
- Independent copywriting (not translation) for the English-speaking diaspora audience
- Culturally specific value propositions ("Trusted Legal Experts" vs. "Abogados de Confianza")
- Separate negative-keyword lists addressing structural ambiguity in each language

---

*[← Back to main README](../README.md)*
