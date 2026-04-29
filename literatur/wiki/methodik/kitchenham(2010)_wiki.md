---
title: "Kitchenham et al. (2010) — Systematic Literature Reviews in Software Engineering: A Tertiary Study"
type: source
tags: [SLR, systematic-review, tertiary-study, EBSE, mapping-study, quality-assessment, DARE-criteria, software-engineering]
sources: ["Kichtenha_SLR_2010.pdf"]
created: 2026-04-06
updated: 2026-04-06
---

# Systematic Literature Reviews in Software Engineering — A Tertiary Study

**Authors:** Barbara Kitchenham, Rialette Pretorius, David Budgen, O. Pearl Brereton, Mark Turner, Mahmood Niazi, Stephen Linkman
**Venue:** Information and Software Technology, Vol. 52, pp. 792–805 (2010)
**DOI:** 10.1016/j.infsof.2010.03.006
**Method:** Tertiary study (SLR of SLRs); broad automated search of 4 digital libraries + SCOPUS, Jan 2004–June 2008

---

## Research Objective

Update a previous tertiary study (manual search, Jan 2004–June 2007) by performing a broad automated search to provide an annotated catalogue of SLRs available to software engineering researchers and practitioners.

## Key Concepts

### SLR vs. Mapping Study
- **Conventional SLRs** aggregate results related to a specific research question (e.g., "Is technique *a* better than *b*?"). Can use meta-analysis if sufficient comparable primary studies exist (rare in SE)
- **Mapping studies** aim to find and classify primary studies in a topic area. Coarser-grained questions ("What do we know about topic *x*?"). More tabulation, less aggregation. Often a precursor to conventional SLRs

The distinction can be fuzzy — some mapping studies provide detailed reviews of each primary study.

### Evidence-Based Software Engineering (EBSE)
- Framework derived from evidence-based medicine, proposed by Kitchenham, Dyba & Jorgensen
- Relies on aggregating best available evidence to address engineering questions
- The most reliable evidence comes from aggregating all empirical studies on a topic
- SLR is the recommended methodology for this aggregation

## Method

### Research Questions
- **RQ1:** How many SLRs were published Jan 2004–June 2008?
- **RQ2:** What research topics are being addressed?
- **RQ3:** Which individuals/organizations are most active?
- **RQ4:** Are limitations from the original study still an issue?
- **RQ5:** Is the quality of SLRs improving?

### Search Process
- 4 digital libraries: IEEE Computer Society Digital Library, ACM, Citeseer, SpringerLink
- 1 indexing service: SCOPUS (searched by Kitchenham)
- 15 search strings combining "Software engineering" AND various review-related terms
- Automated search validated against manual search results (found 15 of 18 from original study)

### Study Selection
- Initial screening of 1,757 papers → 161 candidates → 119 full copies → 40 SLRs from automated search → 33 unique studies (after removing duplicates and out-of-timeframe papers)
- 3 additional papers known to researchers added → 23 unique SLRs in data extraction

### DARE Quality Criteria
Quality assessed using York University Centre for Reviews and Dissemination (DARE) criteria — 4 questions:

| Question | Scoring |
|----------|---------|
| **Q1:** Inclusion/exclusion criteria described and appropriate? | Y=1, P=0.5, N=0 |
| **Q2:** Literature search likely to have covered all relevant studies? | Y=1, P=0.5, N=0 |
| **Q3:** Quality of included studies assessed? | Y=1, P=0.5, N=0 |
| **Q4:** Basic data/studies adequately described? | Y=1, P=0.5, N=0 |

Maximum quality score: 4.0. Data extraction used a "consensus and minority report" process for papers after June 2007.

## Key Results

### RQ1: Volume
- 53 SLRs found in the Jan 2004–June 2008 period (including 54 literature reviews without defined search strategy)
- Number increasing: 0.5/month (2004) → 2.0/month (first half 2008)
- More studies positioning themselves as EBSE SLRs over time

### RQ2: Topics (Tables 1, 4, 5)
- Broader range than original study — no longer dominated by cost estimation
- Topics mapped against SE undergraduate curriculum and SWEBOK
- Coverage of curriculum topics remains sparse
- 17 of 33 studies relevant to undergrad education; 12 of possible interest to practitioners

### RQ3: Active Researchers
- Magne Jorgensen most prolific (8 studies, Jan 2004–June 2007)
- Simula Laboratory dominant institution initially; more distributed later
- 51 researchers in total; few co-authored more than two studies
- SLRs transitioning from "innovators" to "early adopters" (Rogers adoption curve)

### RQ4: Limitations Still Present
- Mapping studies analyze more primary studies (median 92.5–133) than SLRs (median 20–26)
- **Primary study quality assessment still lacking** — few SLRs evaluate quality of included studies
- Only 6 SLRs performed full quality evaluation; only 4 provided practitioner-oriented advice

### RQ5: Quality Improving?
- Overall quality appears to have improved, particularly for studies citing SLR guidelines
- Papers citing guidelines: mean quality 2.70–3.00 vs. not citing: mean 1.75–2.42
- Regression analysis: citing guidelines (positive, p<0.05) and being a mapping study (negative, p<0.01) were only significant quality predictors
- Conference/workshop paper quality increased in later period

## Key Limitations
- Automated search missed some papers using non-standard terminology ("study aggregation" instead of "literature review")
- Grey literature (technical reports, theses) excluded
- One person (Kitchenham) reviewed all papers — potential bias, but justified by expertise

## Relevance to the Proseminar Paper

- **Methodological awareness:** Understanding the distinction between SLR and mapping study helps position the proseminar's literature review correctly — it is closer to a *selective conceptual review* (not a formal SLR or mapping study)
- **Quality criteria:** The DARE criteria provide a checklist for ensuring minimum quality in the proseminar's own literature review process
- **Transparent search documentation:** Reinforces [[source-vombrocke-2009-reconstructing-giant]]'s call for rigour — even a proseminar paper benefits from documenting its search strategy
- **Scope calibration:** A formal SLR is beyond the scope of a 3 ECTS proseminar paper, but the principles (defined search, inclusion/exclusion criteria, quality assessment) can be applied at a lighter scale
