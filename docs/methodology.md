# Planned methodology — Does a Degree Still Matter?

**Stage:** Research design only. No statistical estimates have been produced.

## Research question
How are educational qualifications associated with labour-market outcomes among comparable demographic groups in South Africa?

## Data, population and measurement
- Use official Stats SA QLFS microdata and codebook for a defined reference quarter/period.
- Clearly separate **employment-to-population ratio**, **unemployment rate among the labour force**, and **labour-force participation**. Denominators are not interchangeable.
- Predefine eligible age groups, qualification categories, sex/province comparisons and handling of missing/unknown codes.
- Check observation periods, rotating survey sample, repeated respondents and correct population weights; do not naïvely append quarters as independent people.

## Statistical plan
1. Confirm sample design metadata (sampling weights, clustering, stratification) and rules for analysis.
2. Audit unweighted group sizes, missingness and possible disclosure risks.
3. Produce design-weighted estimates and appropriate uncertainty intervals.
4. Use survey-aware regressions/adjusted associations as warranted by sample sizes and documented methodology.
5. Assess robustness of age/province and any field-of-study subgroup claims.
6. Include earnings only if a separately audited source supports interpretable measures, imputation handling and temporal comparisons.

## Tool roles
**Python + Jupyter** for reproducible preparation and figures; **R survey** or another validated complex-survey toolkit for design-aware inference where appropriate; SQL only for sensible structured transformations.

## Interpretation limits
Observed differences do **not** prove that a degree causes employment. Cross-sectional data do not support typical time-to-first-job or contemporary graduate longitudinal trajectories.

**Final output:** defensible statistics, reproducible scripts and a PDF research paper/case study. Power BI and Streamlit are not required.
