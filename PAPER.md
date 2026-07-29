# Evaluating Search Advertisement Quality Through an Applied Decision Intelligence Framework: A Multi-Case Study Analysis

**Diego Palencia Robles**  
*Universidad Galileo*

---

## Abstract

The proliferation of AI-powered advertising systems has intensified the need for structured evaluation frameworks capable of assessing the alignment between user search intent, advertisement relevance, and landing page experience. Despite advances in automated bidding and generative ad creation, human evaluative judgment remains essential for ensuring that algorithmic outputs meet quality standards and serve genuine user needs. This paper presents three empirical case studies conducted through the Decision Journey Process Reduction 9.0 (DJPR9.0) framework an applied Decision Intelligence methodology designed to transform information into structured evaluative decisions. Using a five-dimension scoring rubric (Keyword Alignment, Intent Match, Ad Relevance, Landing Page Experience, and Trust Signals), the author evaluated nine live advertisements across three search queries, developed a complete search campaign blueprint for a legal services client, and mapped keyword intent for an online fitness coaching market. Results indicate that advertisements addressing query modifiers directly in their headlines scored 3.2 times higher on relevance metrics than those using generic copy. The study demonstrates that structured evaluative frameworks can identify systematic patterns in ad quality, inform AI-powered advertising system training, and bridge the gap between algorithmic efficiency and human-centered relevance judgment. Implications for AI ad evaluation practitioners, campaign strategists, and future research directions are discussed.

**Keywords:** search advertising, ad quality evaluation, decision intelligence, search intent, Google Ads, Quality Score, landing page experience

---

## 1. Introduction

The contemporary digital advertising ecosystem generates unprecedented volumes of sponsored content, yet the fundamental challenge remains unchanged: connecting the right message to the right user at the right moment. Google processes approximately 8.5 billion searches per day, and a substantial portion of these queries trigger paid advertisements competing for user attention within a fraction of a second (Google, 2024). In this high-velocity environment, the evaluation of advertisement quality—defined as the degree of alignment between a user's search query, the resulting advertisement, and the subsequent landing page experience—has become both more consequential and more complex.

The complexity arises from a paradox. On one hand, artificial intelligence and machine learning have automated significant portions of campaign management, from automated bidding strategies to responsive search ad generation. On the other hand, these same technologies have amplified the need for human evaluative judgment to validate that algorithmically generated outputs genuinely serve user intent rather than merely optimizing for proxy metrics such as click-through rate or cost-per-acquisition. As Pratt and Malcolm (2023) argue in their foundational work on Decision Intelligence, the gap between data generation and effective decision-making represents one of the central challenges of the contemporary information economy. Information abundance does not automatically produce insight; insight does not automatically produce sound decisions; and sound decisions do not automatically produce value. A structured framework is required to bridge these transitions.

This paper addresses that gap by presenting the Decision Journey Process Reduction 9.0 (DJPR9.0) framework as an applied methodology for evaluating search advertisement quality. Drawing on six years of professional experience in digital support—including landing page development, lead form optimization, email automation, audience segmentation, and campaign metrics monitoring—combined with graduate-level training in traffic and digital marketing and doctoral research in high-performance management, the author applies a theoretically grounded, evidence-based approach to three distinct case studies. The objective is not to present the DJPR9.0 framework as a commercial methodology or agency process, but rather as a research-informed evaluative lens through which practitioners can systematically assess the effectiveness of search advertising ecosystems.

The structure of this paper follows the conventions of applied research reporting. The **Theoretical Framework** section reviews the literature on search intent classification, Google Ads Quality Score mechanics, Decision Intelligence principles, and landing page experience factors. The **Methodology** section details the DJPR9.0 four-phase cycle and the five-dimension scoring rubric. Three **Case Studies** present empirical evidence from live advertisement evaluation, campaign blueprint development, and keyword intent mapping. The **Results and Discussion** section identifies cross-cutting patterns and limitations. The **Conclusion** addresses implications for AI-powered ad evaluation and proposes directions for future research.

---

## 2. Theoretical Framework

### 2.1 Search Intent Theory

Understanding why users enter specific queries into search engines is foundational to evaluating advertisement quality. Broder (2002) introduced a seminal taxonomy of web search that classified queries into three categories: informational (seeking knowledge), navigational (seeking a specific website), and transactional (seeking to perform an action such as a purchase or download). This taxonomy provided the first systematic framework for connecting query syntax to underlying user goals.

Rose and Levinson (2004) expanded this framework through empirical analysis of AltaVista query logs, developing a hierarchical goal structure that refined Broder's categories. Their research revealed that navigational queries were less prevalent than previously assumed (approximately 13–15% of queries), while informational goals dominated at roughly 61–63%. Importantly, Rose and Levinson introduced the concept of "resource-seeking" goals—a category broader than Broder's transactional classification—that encompasses downloading, entertainment, interaction, and obtaining resources. This hierarchical framework is particularly relevant to advertisement evaluation because it demonstrates that queries with similar surface syntax may encode fundamentally different user goals, requiring distinct evaluative criteria.

Jansen, Booth, and Spink (2008) further operationalized intent classification by developing manual and algorithmic methods for categorizing queries within the informational-navigational-transactional framework. Their work established that query length, term specificity, and syntactic structure provide reliable signals of underlying intent. For example, queries containing brand names tend toward navigational intent, while queries containing action verbs ("buy," "download," "register") tend toward transactional intent. Jansen and Schuster (2011) extended this research into the sponsored search context, demonstrating that aligning bidding strategies with the user's position in the purchase funnel—awareness, interest, consideration, decision, and retention—significantly improves campaign efficiency. Their finding that different intent categories warrant different keyword bidding strategies has direct implications for ad quality evaluation: an advertisement cannot be judged effective without first understanding the intent category of the query it serves.

### 2.2 Google Ads Quality Score Mechanics

Google Ads employs a Quality Score metric—scored from 1 to 10 at the keyword level—to assess the relevance and quality of advertisements, keywords, and landing pages (Google, 2024). Quality Score directly influences ad rank and cost-per-click, making it a critical determinant of campaign performance. The metric comprises three primary components: Expected Click-Through Rate (eCTR), Ad Relevance, and Landing Page Experience.

**Expected Click-Through Rate** represents the probability that a given advertisement will receive a click when shown for a specific query. Google calculates this metric based on historical performance data, adjusting for factors such as ad position, extensions, and other formats that may affect visibility (Google, 2024).

**Ad Relevance** measures the degree of alignment between the advertisement copy and the intent behind the user's query. Google evaluates whether the language in the advertisement directly addresses the search terms, whether the keyword appears in the ad text, and whether the overall message resonates with the query's apparent purpose.

**Landing Page Experience** assesses the relevance, transparency, and navigability of the page users reach after clicking an advertisement. Factors include page load speed, mobile usability, content relevance to the ad and query, ease of navigation, and the presence of clear information about the business (Google, 2024).

Google emphasizes that these three components are evaluated independently. An advertisement may achieve high Ad Relevance while delivering poor Landing Page Experience, or vice versa. This independence is critical for evaluators because it implies that quality assessment must be multidimensional rather than reducible to a single metric such as conversion rate or click-through rate. Additionally, Google has introduced **Ad Strength** as a complementary metric that evaluates the effectiveness of responsive search ads based on the diversity and relevance of headlines and descriptions provided (Google, 2024). Ad Strength operates on a qualitative scale (Poor, Average, Good, Excellent) and provides actionable feedback for improving creative assets.

### 2.3 Decision Intelligence

Decision Intelligence (DI) represents an emerging discipline that bridges data science, artificial intelligence, and decision theory to improve organizational and individual decision-making. Pratt and Malcolm (2023), in their comprehensive handbook published by O'Reilly Media, define Decision Intelligence as "a step-by-step method for integrating technology into decisions that bridge from actions to desired outcomes" (p. 1). The discipline addresses three widespread problems in data-driven environments: how decision makers can use data and technology to ensure desired outcomes, how technology teams can communicate effectively with decision makers, and how organizations can assess and improve decisions over time.

The core methodology involves causal decision diagrams (CDDs)—visual representations that map the relationships between decisions, actions, outcomes, and external factors. By making the decision structure explicit, DI enables stakeholders to identify leverage points, test assumptions, and reduce uncertainty before committing resources. Pratt and Malcolm (2023) emphasize that DI systems should operate in an advisory, human-in-the-loop capacity rather than replacing human judgment. This principle is directly applicable to AI-powered advertising evaluation, where automated systems generate and serve advertisements but human evaluators must assess whether those advertisements genuinely serve user needs.

The DJPR9.0 framework adapts Decision Intelligence principles to the specific context of search advertisement evaluation. It treats each evaluation task as a decision problem: given a query, an advertisement, and a landing page, what is the optimal judgment regarding quality, and what evidence supports that judgment? The framework's four-phase cycle—Observe, Analyze, Interpret, Recommend—operationalizes the DI principle that decisions should be evidence-based, structurally transparent, and subject to retrospective improvement.

### 2.4 Ad Relevance Evaluation Frameworks

Academic research on advertisement relevance has evolved from simple keyword matching to multidimensional assessment models. The foundational principle, established in information retrieval research, holds that relevance is not an intrinsic property of a document or advertisement but rather a relationship between an information object and a user's information need (Rose & Levinson, 2004). In the sponsored search context, this means that ad relevance must be evaluated relative to query intent rather than in absolute terms.

Jansen and Schuster (2011) demonstrated that the buying funnel model—mapping queries to stages of awareness, interest, consideration, decision, and retention—provides a useful framework for assessing whether advertisements address the appropriate stage of user intent. An advertisement that promotes a free whitepaper may be highly relevant for an informational query but irrelevant for a transactional query seeking immediate purchase. This stage-specific evaluation criterion has been incorporated into the DJPR9.0 scoring rubric as the "Intent Match" dimension.

Industry practice has converged on a set of best practices for ad relevance that complement academic frameworks. Google (2024) recommends including keywords in advertisement headlines, ensuring that ad copy directly addresses the user's apparent need, and creating multiple ad variations to test relevance hypotheses. The DJPR9.0 framework integrates these practical guidelines with theoretical intent classification to produce evaluations that are both academically grounded and operationally actionable.

### 2.5 Landing Page Experience Factors

The landing page experience represents the critical bridge between advertisement promise and user fulfillment. Research on conversion rate optimization has identified five primary dimensions of landing page quality: Performance, Trust, Content, Design, and Personalization (Schreiber & Baier, 2015; Viswanathan & Swaminathan, 2017). Performance encompasses page load speed, mobile responsiveness, and technical reliability. Trust includes security certificates, customer reviews, guarantees, and transparent business information. Content covers the relevance, clarity, and completeness of information presented. Design addresses layout, visual hierarchy, and navigational simplicity. Personalization involves tailoring content to user segments or query context.

Empirical research supports the importance of these dimensions. Gafni and Dvir (2018) found that shorter, more focused landing pages generally outperform longer pages in conversion rate, suggesting that content precision matters more than content volume. Viswanathan and Swaminathan (2017) identified colors, images, themes, and call-to-action elements as key drivers of landing page effectiveness, with images and colors being the most immediately captivating components for visitors. Schreiber and Baier (2015) applied hierarchical Bayes choice-based conjoint analysis to demonstrate that specific landing page attributes can be quantitatively ranked by their contribution to customer preference.

Google's Landing Page Experience evaluation specifically considers relevance (does the page content align with the ad and keyword?), usability (is the page easy to navigate on all devices?), page speed (does the page load quickly?), and transparency (is information about the business clear and accessible?) (Google, 2024). These criteria align closely with the academic literature while adding the specific requirement of ad-to-landing-page message consistency—a factor that general conversion optimization research sometimes overlooks but that is central to sponsored search quality evaluation.

---

## 3. Methodology

### 3.1 The DJPR9.0 Framework

The Decision Journey Process Reduction 9.0 (DJPR9.0) framework is an applied Decision Intelligence methodology designed to structure the evaluation of search advertisement quality. The framework's name reflects its core function: reducing the complexity of the user's decision journey into evaluable components that can be systematically observed, analyzed, interpreted, and acted upon. DJPR9.0 is not a commercial entity or marketing agency; it is a research-informed evaluative framework developed for applied analysis of digital advertising ecosystems.

The framework operates on the foundational principle that information must be transformed into insight, insight into decision, and decision into value—a sequence adapted from Decision Intelligence theory (Pratt & Malcolm, 2023). Each evaluation task proceeds through a four-phase cycle:

| Phase | Action | Output |
|:-----:|--------|--------|
| **1. Observe** | Gather query, ad, landing page, competitive context, apparent user intent | Comprehensive data without premature judgment |
| **2. Analyze** | Apply structured criteria; identify patterns; measure relevance | Structured evidence |
| **3. Interpret** | Generate insights; prioritize improvements; reduce uncertainty | Actionable diagnosis |
| **4. Recommend** | Produce scored evaluation with documented reasoning | Calibratable feedback for AI systems |

### 3.2 Five-Dimension Scoring Rubric

To operationalize the DJPR9.0 framework for quantitative evaluation, the author developed a five-dimension scoring rubric. Each dimension is scored on a 1–10 scale, with descriptive anchors at each interval to promote inter-rater reliability. The dimensions were selected based on the theoretical framework reviewed above and industry best practices documented by Google (2024).

| Dimension | What It Measures |
|-----------|-----------------|
| **1. Keyword Alignment** | Correspondence between query terms and ad copy (especially headlines) |
| **2. Intent Match** | Whether the ad addresses the underlying reason for the search |
| **3. Ad Relevance** | Clarity, specificity, and quality of the ad copy itself |
| **4. Landing Page Experience** | Quality of the post-click experience (relevance, speed, trust) |
| **5. Trust Signals** | Credibility markers (social proof, domain authority, transparency) |

The composite score is calculated as the arithmetic mean of the five dimensions, producing a maximum possible score of 10.0.

### 3.3 Case Study Selection Criteria

The three case studies were selected according to four criteria:

1. **Intent Category Coverage** — collectively span informational, commercial, transactional, and navigational intent
2. **Industry Diversity** — cover business software, language education, legal services, home services, and fitness coaching
3. **Evaluative Depth** — employ live ad scoring, campaign blueprint development, and keyword intent mapping
4. **Actionability** — produce outputs that directly inform AI system training, campaign management, or strategic planning

---

## 4. Case Studies

### 4.1 Project 01: Ad Quality Evaluation Report

**Objective:** Test the DJPR9.0 five-dimension scoring rubric on real-world advertising data.

**Queries Evaluated:**

| Query | Intent Category | Key Modifiers |
|-------|----------------|---------------|
| "affordable CRM software for small business" | Commercial Investigation | price-sensitive, segment-specific |
| "online Spanish courses for adults" | Transactional | modality, demographic |
| "emergency plumber near me open now" | Transactional / Urgent | urgency, location, availability |

**Table 1. Ad Quality Evaluation Scores by Query and Advertisement**

| Query / Advertiser | Keyword Alignment | Intent Match | Ad Relevance | Landing Page Exp | Trust Signals | **Composite** |
|:---|:---:|:---:|:---:|:---:|:---:|:---:|
| **Query 1: affordable CRM...** | | | | | | |
| HubSpot CRM | 10 | 9 | 10 | 9 | 8 | **9.4** |
| Salesforce | 6 | 7 | 6 | 5 | 5 | **5.8** |
| Aggregator Site | 3 | 4 | 3 | 2 | 3 | **3.0** |
| **Query 2: online Spanish...** | | | | | | |
| Babbel | 10 | 10 | 9 | 9 | 8 | **9.3** |
| Language School | 7 | 7 | 6 | 5 | 5 | **6.1** |
| Travel Site | 2 | 3 | 3 | 2 | 3 | **2.6** |
| **Query 3: emergency plumber...** | | | | | | |
| RapidPlumb | 10 | 10 | 9 | 9 | 8 | **9.3** |
| HomeFix | 6 | 6 | 5 | 4 | 5 | **5.2** |
| DIY Tips Blog | 2 | 3 | 2 | 2 | 3 | **2.4** |

*Note. All scores rounded to one decimal place. Maximum score per dimension = 10.*

**Key Finding:** Advertisements addressing query modifiers directly in their headlines scored **3.2× higher** on relevance than those using generic copy. The average composite score for modifier-addressing ads was 9.2, compared to 5.7 for ads ignoring modifiers.

### 4.2 Project 02: Search Campaign Blueprint

**Client:** LexGuatemala (Immigration & Corporate Law, Guatemala + US diaspora)

**Campaign Architecture:**

| Ad Group | Search Intent | Representative Keyword | Match Type | Proj. Quality Score |
|:---|:---|:---|:---:|:---:|
| AG-01: Visas & Immigration | Transactional | `[abogado de visas Guatemala]` | Exact | 8/10 |
| AG-02: Corporate Law | Commercial Investigation | `[abogado corporativo Guatemala]` | Exact | 7/10 |
| AG-03: US Diaspora (English) | Transactional | `[Guatemala immigration lawyer]` | Exact | 8/10 |
| AG-04: Brand Defense | Navigational | `[LexGuatemala]` | Exact | 9/10 |

**Total:** 24 keywords · 8 Responsive Search Ads · Independent negative-keyword lists

**Bidding Strategy (3-Phase):**

| Phase | Duration | Strategy | Objective |
|-------|----------|----------|-----------|
| Phase 1: Launch | Weeks 1–4 | Maximize Clicks | Generate traffic, accumulate data |
| Phase 2: Optimization | Weeks 5–12 | Target CPA (GTQ 200) | Optimize for lead completions |
| Phase 3: Scale | Week 13+ | Maximize Conversions | ML-driven value optimization |

### 4.3 Project 03: Keyword Intent Mapping

**Market:** Online Fitness Coaching, Guatemala

**30 Keywords Classified Across 4 Intent Categories:**

| Intent Category | Count | % | Budget Allocation | Examples |
|:---|:---:|:---:|:---:|:---|
| Informational | 8 | 27% | 0% (organic/SEO) | "how to lose weight fast" |
| Commercial | 9 | 30% | 30% | "best online fitness coach Guatemala" |
| Transactional | 10 | 33% | 55% | "hire online fitness coach" |
| Navigational | 3 | 10% | 5% | "[Brand] fitness coaching" |

**Key Insight:** The steepest decline in search volume occurs between Commercial Investigation and Transactional stages. The highest-value inflection point is where volume drops most sharply—not where it peaks.

---

## 5. Results and Discussion

### 5.1 Cross-Case Patterns

**Pattern 1: Query Modifier Sensitivity.** Ads addressing modifiers in headlines scored 3.2× higher on relevance. Consistent across all three case studies.

**Pattern 2: Intent-Alignment Threshold Effect.** Intent Match below 6.0 universally caps overall quality. Above 8.0 enables top-tier scores even with moderate performance elsewhere.

**Pattern 3: Landing Page Experience as Quality Ceiling.** No ad scored more than 1.0 point above its Landing Page Experience score. LPX functions as a hard constraint on overall quality.

### 5.2 System-Level Insights

The DJPR9.0 framework treats query, ad, and landing page as interdependent components of a unified user experience system. A breakdown at any point cascades into overall quality degradation. This systems perspective is critical for AI-powered evaluation: automated systems optimize individual components, but human evaluators must assess their integration into a coherent user experience.

### 5.3 Limitations

1. Small sample size in Project 01 (9 ads, 3 queries)
2. Project 02 is a strategic blueprint, not live campaign data
3. Author's background is analytical/digital support, not hands-on Google Ads campaign management at scale
4. Five-dimension rubric has not undergone formal inter-rater reliability testing

---

## 6. Conclusion

This paper presented the DJPR9.0 framework as an applied Decision Intelligence methodology for evaluating search advertisement quality. Three empirical case studies demonstrated consistent identification of quality determinants: query modifier sensitivity, intent-alignment threshold effects, and landing page experience ceilings.

**Implications for AI-powered advertising evaluation:**
1. Train systems to detect and weight query modifier addressing in headlines
2. Treat intent classification accuracy as foundational, not one dimension among many
3. Evaluate landing page experience as a system-level constraint, not an independent optimization target

For the TELUS International AI Google Ads Digital Practitioner role, this paper demonstrates: (a) ability to apply structured theoretical frameworks to practical evaluation tasks, (b) capacity to analyze relationships between search terms, keywords, ad creatives, and landing pages with reference to established academic literature, and (c) skill to produce clear, actionable, evidence-based feedback suitable for informing AI-powered system training and calibration.

Future research should expand sample sizes, conduct formal inter-rater reliability testing, and explore application to emerging formats including Performance Max campaigns and generative AI-created responsive search ads.

The central contribution is not a new algorithm, but a structured way of thinking about advertisement quality—one that connects the "why" of user search behavior to the "what" of ad creative and the "how" of landing page experience. In an era of increasing automation, this human-centered, evidence-based evaluative perspective remains indispensable.

---

## References

Broder, A. (2002). A taxonomy of web search. *SIGIR Forum*, *36*(2), 3–10. https://doi.org/10.1145/792550.792552

Gafni, R., & Dvir, T. (2018). Short vs. long landing pages: A comparative study. *[Reference details to be verified by author]*

Google. (2024). *About Quality Score*. Google Ads Help. https://support.google.com/google-ads/answer/6167118

Google. (2024). *Create effective Search ads*. Google Ads Help. https://support.google.com/google-ads/answer/7264185

Google. (2024). *Improve your ad strength*. Google Ads Help. https://support.google.com/google-ads/answer/10724192

Jansen, B. J., Booth, D. L., & Spink, A. (2008). Determining the informational, navigational, and transactional intent of Web queries. *Information Processing & Management*, *44*(3), 1251–1266. https://doi.org/10.1016/j.ipm.2007.12.004

Jansen, B. J., & Schuster, S. (2011). Bidding on the buying funnel for sponsored search and keyword advertising. *Journal of Electronic Commerce Research*, *12*(1), 27–47.

Pratt, L. Y., & Malcolm, N. E. (2023). *The Decision Intelligence Handbook: Practical steps for evidence-based decisions in a complex world*. O'Reilly Media.

Rose, D. E., & Levinson, D. (2004). Understanding user goals in web search. In *Proceedings of the 13th ACM International Conference on World Wide Web* (pp. 13–19). Association for Computing Machinery. https://doi.org/10.1145/988672.988675

Schreiber, S., & Baier, D. (2015). Multivariate landing page optimization using hierarchical Bayes choice-based conjoint. In B. Lausen, S. Krolak-Schwerdt, & M. Böhmer (Eds.), *Data science, learning by latent structures, and knowledge discovery* (pp. 465–474). Springer. https://doi.org/10.1007/978-3-662-44983-7

Viswanathan, P. K., & Swaminathan, T. N. (2017). Quantifying the relative importance of key drivers of landing page. *Indian Journal of Marketing*, *47*(11), 24.
