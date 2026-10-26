# Analytical data structure — proposed, not implemented

## Primary grain
One eligible respondent record per selected QLFS reference wave/quarter, respecting survey rules. Do not assume cross-quarter records are independent.

## Candidate variables
Respondent/household or survey identifiers if supplied; education qualification level; employment/labour force classification; age; province; gender; documented weights and sampling-design variables. Optional study field and earnings only if supported.

## Recommended flow
Official microdata + codebooks → validated categorical mappings and eligibility rules → survey-design-aware analytical frame → weighted estimates/regression outputs → tables/figures and final report.

## Controls
Validate the education codes and employment denominators; preserve survey design identifiers where needed; check unweighted subgroup counts; keep missing/unknown groups explicit; avoid joining multiple waves without understanding respondent overlap.

**This is a survey-research dataset, not a mandatory Power BI star schema.** SQL use should serve real transformation/verification needs rather than be decorative.
