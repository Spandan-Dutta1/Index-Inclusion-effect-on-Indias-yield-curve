# Index Inclusion Effect on India's Yield Curve

**Research Question:** Does JP Morgan GBI-EM index inclusion causally deform India's sovereign yield curve shape, and through which tenors does the effect transmit?

**Author:** Spandan Dutta  
**Method:** Instrumental Variables / Two Stage Least Squares (IV/2SLS)  
**Data:** April 2021 – January 2026 (58 months, 13 yield tenors)
## Key Results

| Finding | Value |
|---------|-------|
| First Stage F-statistic | 23.69 (instrument validity confirmed) |
| 2SLS 10Y yield effect | −0.1446 per 1% FPI increase |
| OLS coefficient (biased) | +0.1028 (wrong sign — endogeneity confirmed) |
| Logit: JPM weight predicts flat curve | coef = −0.79, p = 0.005 |
| Flat regime months post-inclusion | 5 consecutive months (Jun–Oct 2024) |
| Nelson-Siegel slope change | −4.5 (2021) → 0 (inclusion) → −2.3 (2026) |
## Identification Strategy

Foreign portfolio investor (FPI) flows are endogenous,foreigners buy Indian bonds when conditions are favourable, creating reverse causality. OLS gives a biased positive coefficient (+0.1028).

**Instrument:** JP Morgan GBI-EM weight schedule — mechanical, pre-announced, affects yields only through FPI buying. Not determined by Indian economic conditions.

**Relevance:** First stage F = 23.69 >> 10 threshold
**Exclusion:** Weight schedule determined by JP Morgan market access criteria, not Indian macro
## Regime Classification
Normal (β1 < −0.5): 41 months
Flat (−0.5 to 0.5): 16 months
Inverted (β1 > 0.5): 1 month
Binary Logit — Flat vs Normal:jpmorgan_weight coef= −0.79, p = 0.005, Pseudo R² = 0.499

