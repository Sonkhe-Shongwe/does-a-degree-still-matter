# Does a Degree Still Matter?

### Education and Employment Outcomes in South Africa

> **Status (26 October 2026): Planning and dataset feasibility review. No statistics, results or completed research are claimed.**

## Core research question
How do employment outcomes differ by education level among comparable demographic groups in South Africa, and how do the associations vary by age, province and other supported characteristics?

This is an **observational, survey-aware investigation**. Differences by qualification are associations, **not causal effects**. Earnings comparisons and field-of-study analyses are **conditional** on data quality and subgroup sample sizes.

## Intended end-to-end deliverable
A reproducible statistical investigation, documented code and a polished **research report (PDF)**, with concise visualisations and a portfolio website case study. No standalone Streamlit app is planned; Power BI is optional, not the primary deliverable.

## Proposed technology
- **Core:** Python, pandas, NumPy, Jupyter, matplotlib, SQL for well-justified analytical preparation.
- **Statistical methods:** survey-weighted employment measures, confidence intervals, comparisons and survey-aware regression when supported.
- **Specialist tool:** R's `survey` package or another correctly implemented complex-survey framework if warranted by design metadata.
- **Presentation:** PDF research report, GitHub documentation and portfolio case study.

## Data position
- **Primary:** [Statistics South Africa Quarterly Labour Force Survey (QLFS)](https://isibaloweb.statssa.gov.za/pages/surveys/pss/qlfs/2026/qlfs2026.php). Official education, labour-market, demographic and weighting documentation have been identified **at source level**; actual microdata still require profiling.
- **Conditional earnings:** [Labour Market Dynamics](https://isibaloweb.statssa.gov.za/pages/surveys/pss/lmd/lmdp.php). Earnings quality, imputation and comparability must be evaluated before use.
- **Optional historical context:** [National Income Dynamics Study (NIDS)](https://saldru.uct.ac.za/nids/data-access), historical waves only.

Do not claim time-to-first-job, causal degree effects or reliable degree earnings premiums without appropriate supporting data and methods.

## Delivery stages (planned for 2027)
1. Acquire and audit official microdata, codebooks, survey design fields and licence terms.
2. Define precise employment denominators and education categories.
3. Profile missingness and subgroup sample sizes; apply design-aware weighting and uncertainty.
4. Analyse comparable demographic groups; use regression carefully.
5. Produce charts, a research report and reproducibility notes.

## Repository guide
- `data/`: documented acquisition, never private or restricted raw microdata.
- `sql/`: optional structured analyses with defensible use.
- `src/`, `notebooks/`, `tests/`: reproducible preparation, estimates and checks.
- `docs/`, `reports/`, `assets/`: methodology, findings, report and visuals.
- `powerbi/`: scaffold only; no mandatory Power BI deliverable.

**Portfolio context:** [PilotODIN](https://github.com/Sonkhe-Shongwe/PilotODIN) · [Banking Fraud Intelligence](https://github.com/Sonkhe-Shongwe/banking-fraud-intelligence) · [Financial consumer complaints BI](https://github.com/Sonkhe-Shongwe/financial-consumer-complaint-analysis)

**Planning documentation only. No empirical findings have been produced.**
