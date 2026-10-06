# Search strategy — early total / exclusive enteral feeding in preterm infants

**Database:** PubMed/MEDLINE (via NCBI E-utilities). **Date run:** 2 September 2026. **No date or language limit** except where stated in the query string.

## PubMed strands

| Strand | Records | Query |
|---|---|---|
| A. Total / full / exclusive enteral feeding terminology | 1014 | `("total enteral feeding"[tiab] OR "total enteral feeds"[tiab] OR "total enteral nutrition"[tiab] OR "full enteral feeding"[tiab] OR "full enteral feeds"[tiab] OR "full enteral nutrition"[tiab] OR "exclusive enteral feeding"[tiab] OR "exclusive enteral nutrition"[tiab] OR "near-full enteral feeding"[tiab]) AND (preterm[tiab] OR premature[tiab] OR "low birth weight"[tiab] OR VLBW[tiab] OR LBW[tiab] OR neonate[tiab] OR neonates[tiab] OR newborn[tiab] OR newborns[tiab] OR infant[tiab] OR infants[tiab])` |
| B. Parenteral-nutrition-avoidance terminology | 38 | `("enteral feed*"[tiab] OR "enteral nutrition"[tiab] OR "milk feed*"[tiab]) AND ("without parenteral"[tiab] OR "no parenteral"[tiab] OR "avoid* parenteral nutrition"[tiab] OR "parenteral nutrition-free"[tiab] OR "intravenous fluids"[tiab] OR "supplemental parenteral"[tiab]) AND (preterm[tiab] OR premature[tiab] OR "low birth weight"[tiab] OR VLBW[tiab] OR neonate*[tiab] OR newborn*[tiab])` |
| C. MeSH: enteral nutrition x preterm/LBW x RCT (2000-2026) | 1132 | `("Enteral Nutrition"[Mesh] OR "Infant Nutritional Physiological Phenomena"[Mesh]) AND ("Infant, Premature"[Mesh] OR "Infant, Low Birth Weight"[Mesh] OR "Infant, Very Low Birth Weight"[Mesh]) AND (randomized controlled trial[pt] OR controlled clinical trial[pt] OR randomi*[tiab] OR "random allocation"[Mesh]) AND (2000:2026[dp])` |
| D. Necrotising enterocolitis x feeding regimen x randomised | 281 | `("Enterocolitis, Necrotizing"[Mesh] OR "necrotizing enterocolitis"[tiab] OR "necrotising enterocolitis"[tiab]) AND ("feeding regimen*"[tiab] OR "feeding protocol*"[tiab] OR "enteral feed*"[tiab] OR "feeding strateg*"[tiab]) AND (randomi*[tiab]) AND (preterm[tiab] OR "low birth weight"[tiab] OR VLBW[tiab])` |
| E. Early enteral feeding / early feeding terminology | 66 | `("early enteral feeding"[tiab] OR "early enteral nutrition"[tiab] OR "early feeding"[tiab]) AND (preterm[tiab] OR premature[tiab] OR "low birth weight"[tiab] OR VLBW[tiab]) AND (randomi*[tiab] OR trial[tiab])` |
| F. Time-to-full-feeds terminology | 75 | `("time to full feed*"[tiab] OR "days to full feed*"[tiab] OR "full feeds"[tiab]) AND (preterm[tiab] OR "low birth weight"[tiab] OR VLBW[tiab]) AND randomi*[tiab]` |
| G. Author-targeted (landmark ETEF investigators) | 66 | `("Nangia S"[au] OR "Sanghvi K"[au] OR "Nazir M"[au] OR "Vijayan S"[au] OR "Mahmoodi N"[au] OR "Ojha S"[au] OR "Dorling J"[au] OR "Nangia"[au]) AND (enteral[tiab] OR feed*[tiab] OR nutrition[tiab]) AND (preterm[tiab] OR neonat*[tiab] OR "low birth weight"[tiab] OR infant*[tiab])` |
| H. LMIC affiliation-targeted trial literature | 187 | `(enteral[tiab] AND (feeding[tiab] OR nutrition[tiab])) AND (preterm[tiab] OR "low birth weight"[tiab] OR VLBW[tiab] OR LBW[tiab]) AND (India[ad] OR Pakistan[ad] OR Iran[ad] OR Egypt[ad] OR Turkey[ad] OR Nigeria[ad] OR Bangladesh[ad] OR China[ad]) AND (randomi*[tiab] OR trial[tiab])` |
| I. Parenteral nutrition / IV fluid x enteral feeding x randomised (2005-2026) | 98 | `("parenteral nutrition"[tiab] OR "intravenous fluid"[tiab] OR "intravenous fluids"[tiab]) AND (preterm[tiab] OR "low birth weight"[tiab] OR VLBW[tiab]) AND ("enteral feeding"[tiab] OR "enteral nutrition"[tiab]) AND randomi*[tiab] AND (2005:2026[dp])` |

**Total records retrieved:** 2957 (with overlap)
**Unique records after de-duplication:** 2174

## Trial registry

ClinicalTrials.gov searched via four condition x intervention combinations (total/full/exclusive enteral feeding; enteral x parenteral nutrition; necrotising enterocolitis x enteral feeding; VLBW x early enteral feeding). 67 unique NCT records retrieved and screened against the same eligibility criteria.

## Supplementary strategies

- Reference lists of the three existing syntheses on this comparison hand-searched (PMID 31248308, PMID 42586559, and the 2026 near-full-enteral-feeding review).
- Reciprocal check against the 14 included trials of the companion review in this project (early vs delayed introduction of progressive feeds) to enforce non-overlap.
- Related-article (PubMed neighbour) expansion from each trial judged eligible at full text.

## Declared deviations from Cochrane standard

- CENTRAL, Embase, CINAHL, Maternity and Infant Care, ISRCTN and WHO ICTRP were not reachable from this environment. The search is MEDLINE-based plus registry and targeted recovery.
- Screening was **single-reviewer with machine assistance** (lexical prefilter followed by structured LLM abstract classification with human adjudication of every borderline record), not dual independent screening.