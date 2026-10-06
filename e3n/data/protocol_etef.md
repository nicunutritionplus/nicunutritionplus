# Protocol — Early total / exclusive enteral feeding in preterm infants
## A Cochrane-style systematic review and meta-analysis

**Registered:** this session. **Status:** protocol fixed before screening and extraction.

---

## 1. Review question

In preterm infants, what are the effects of **early total (exclusive, full) enteral feeding**
— milk feeds begun on day 1–2 of life and advanced to full enteral volumes rapidly, with
**no parenteral nutrition and no or only brief intravenous fluid supplementation** — compared
with **conventional incremental enteral feeding**, in which feeds start at trophic or low
volumes and are advanced gradually while nutritional deficits are covered by parenteral
nutrition or maintenance intravenous fluids?

### Relationship to the review already in this project

This project already contains a completed review of **early versus delayed introduction of
progressive enteral feeding volumes** (the CD001970 question: does volume advancement begin
within 96 h of birth, or on day 4 or later?). That review explicitly excluded the trial family
addressed here, recording it as exclusion trap #1: *"Both arms start milk early, differing only
in volume trajectory (e.g. full enteral feeds day 1 vs gradual feeds plus parenteral nutrition).
This is the largest recent trial family and the easiest to misclassify as eligible."*

The present review takes that excluded family as its subject. **The two reviews are
complementary and by construction non-overlapping**: no trial may appear in both. Any trial
appearing in the included-studies table of the earlier review is ineligible here, and the
fourteen trials of that review (Abdelmaaboud 2012, Armanian 2013, Arnon 2013, Bozkurt 2020,
Davey 1994, Dinerstein 2013, Karagianni 2010, Khayata 1987, Leaf 2012 [ADEPT], Ostertag 1986,
Pérez 2011, Salas 2018, Srinivasan 2017, Tewari 2018) are checked against every candidate
before inclusion. The reciprocal check is applied in the Discussion.

## 2. Eligibility criteria

### Population
Preterm infants (<37 weeks' gestation), with the trial population predominantly very preterm
(<32 weeks) and/or low or very low birth weight. Trials restricted to small-for-gestational-age
or growth-restricted preterm infants are eligible and are pre-specified as a subgroup. Trials
enrolling only infants who are haemodynamically unstable, ventilated from birth with
contraindication to feeding, or with major congenital gastrointestinal anomaly are excluded;
where a trial enrols "clinically stable" infants by its own definition, that definition is
recorded in Table 1.

### Intervention (experimental arm)
**Early total enteral feeding (ETEF)** — enteral milk feeding begun within the first 48 hours
of life at a substantial starting volume (typically ≥60–80 mL/kg/day) and advanced to full
enteral volumes over the following days, **without parenteral nutrition**. Intravenous fluids
may be given briefly for glucose or as a vascular access holding measure; the defining feature
is that the trial arm is designed to meet nutritional requirements enterally from the outset.
Trials describing the arm as "early full enteral feeding", "early exclusive enteral feeding",
"total enteral feeding from day 1", or "near-full enteral feeding" are eligible provided the
arm avoids parenteral nutrition.

### Comparator
**Conventional incremental feeding** — feeds begun at trophic/minimal or low volumes and
advanced by a protocol-specified daily increment, with parenteral nutrition or maintenance
intravenous fluid supplementation covering the shortfall until full enteral feeds are reached.

### Design
Randomised or quasi-randomised controlled trials. Cluster-randomised trials are eligible with
an effective-sample-size adjustment; cross-over designs are not applicable and are excluded.

### Explicitly excluded comparisons (declared before screening)
1. **Timing of onset of volume progression** (early vs delayed introduction; CD001970) — the
   subject of the companion review in this project.
2. **Rate of advancement** where both arms begin at the same postnatal age and both receive
   parenteral support (slow vs fast advancement; CD001241).
3. **Feeds timed around another intervention** — therapeutic hypothermia, PDA treatment,
   transfusion, indomethacin/ibuprofen — where feeding was already established at randomisation.
4. **Sibling or secondary reports** of trials already included (microbiome, body-composition,
   neurodevelopmental follow-up, cost analyses). These are linked to the parent trial and add
   no infants.
5. Milk type (donor vs formula vs mother's own milk), fortification timing or fortifier type,
   probiotics/prebiotics/glutamine, feeding route (transpyloric vs gastric), bolus vs
   continuous, oropharyngeal colostrum, gastric-residual policy, non-nutritive sucking.
6. Trials in term infants only, or in infants with surgical gastrointestinal disease.
7. Trials of parenteral amino-acid or lipid dose where the enteral protocol is common to
   both arms.

## 3. Outcomes

### Primary
1. **Necrotising enterocolitis**, Bell stage ≥II or trial-defined, before discharge.
2. **All-cause mortality** before hospital discharge.

### Secondary
3. Time to reach full enteral feeds (days; trial-defined threshold, typically 120–180 mL/kg/day).
4. Feed intolerance (trial-defined).
5. Culture-proven late-onset sepsis / invasive infection.
6. Duration of hospital stay (days).
7. Weight gain or growth at discharge (g/kg/day, or weight/z-score at discharge or 36 weeks PMA).
8. Hypoglycaemia (trial-defined).
9. Duration of parenteral nutrition and/or of central venous access (days).
10. Time to regain birth weight (days).
11. Composite of NEC or death.

## 4. Search

Databases: PubMed/MEDLINE, searched through six pre-specified field-tagged strands
(total/full/exclusive enteral feeding terminology; parenteral-nutrition-avoidance terminology;
a MeSH-anchored enteral-nutrition × preterm × RCT strand; a necrotising-enterocolitis feeding-
regimen strand; an early-enteral-feeding terminology strand; a time-to-full-feeds strand), plus
an author/landmark strand and an LMIC-literature strand. ClinicalTrials.gov is screened for
completed and ongoing registered trials. Reference lists of all existing syntheses on this
question are hand-searched. No date or language restriction is applied at the search stage.

**Deviations from Cochrane standard, declared in advance:** CENTRAL, Embase, CINAHL, Maternity
and Infant Care, ISRCTN and WHO ICTRP are not reachable from this environment. Screening is
single-reviewer with a machine-assisted lexical and LLM prefilter, not dual independent
screening. Both limitations are reported in the review; neither is described as more rigorous
than it is.

## 5. Statistical methods (pre-specified)

- **Orientation (load-bearing):** *early total enteral feeding is the experimental arm.*
  **RR > 1 means more events with early total enteral feeding**; MD < 0 means a lower value
  (fewer days, lower weight) with early total enteral feeding. Every extracted 2×2 table is
  oriented this way before pooling.
- Dichotomous outcomes: risk ratio, **Mantel–Haenszel fixed-effect as the primary model**
  (events are sparse), with DerSimonian–Laird random-effects reported alongside. Risk
  difference reported for the primary outcomes.
- Continuous outcomes: mean difference, inverse-variance, random-effects primary (clinical
  heterogeneity in feeding protocols and full-feed thresholds is expected), fixed-effect
  alongside.
- Heterogeneity: Cochran Q with its P value, tau², I²; interpreted per Cochrane Handbook
  thresholds rather than by I² cut-point alone.
- Medians with IQR or range are converted to mean and SD by the methods of Wan et al. (2014)
  and **every converted value is flagged as imputed in the extraction file** and removed in a
  sensitivity analysis.
- Trials with zero events in both arms contribute no weight to a risk-ratio analysis; they are
  **named** rather than silently dropped from the trial count.
- Pre-specified subgroups: (i) birth weight <1250 g vs ≥1250 g entry criterion; (ii)
  SGA/growth-restricted vs unselected preterm; (iii) low- and middle-income vs high-income
  setting. Subgroup differences tested by Q for interaction.
- Sensitivity analyses: fixed vs random effects; leave-one-out; exclusion of high-risk-of-bias
  trials; exclusion of trials with imputed or secondary-source data; Hartung–Knapp; Peto odds
  ratio and MH without continuity correction for sparse NEC; restriction to trials with a
  primary report obtained in full.
- Small-study effects: contour-enhanced funnel plot with Egger and Harbord tests **only if ≥10
  trials contribute to the primary outcome**; otherwise declared uninterpretable.
- Risk of bias: Cochrane RoB 1, seven domains, with a written justification per judgement.
- Certainty: GRADE, with a Cochrane-format summary-of-findings table and absolute effects.

## 6. Reproducibility

Every screening decision is logged with a reason code in `screening_log.csv`. Every extracted
number carries a source field naming the primary report, a secondary synthesis analysis table,
or the abstract. Pooling is performed in R with `meta`/`metafor`; the analysis script is saved
as an artifact.
