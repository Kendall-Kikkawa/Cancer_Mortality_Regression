# Cancer Mortality Regression

---

Built Linear Regression model to predict death rate in different counties across the U.S. Data was collected from the American Community Survey (census.gov), clinicaltrials.gov, and cancer.gov (see https://data.world/nrippner/ols-regression-challenge for more detail).

---

## Summary

Cancer has a large impact on society, affecting people from all different walks of life across the United States. In this report, we created a regression model that can be used to predict cancer mortality rate for counties across the U.S.  We chose this topic due to a common interest in national healthcare and healthcare policy.  The research objective of this project was twofold:

1. Identify key characteristics that are associated with cancer death rates
2. Build a model to predict the cancer death rate in each county (death rates normalized according to population)

Through building a regression model and analyzing the predictions of our model, we hoped to glean some insight into the characteristics of cancer mortality rates in the United States (see "Discussion and Future Improvements" section of final report for further discussion of model applications).

## File Structure

- `Final Report.Rmd`, `Final-Report.pdf`: All code from start to finish, final report submission
- `Project Proposal.Rmd`, `Project-Proposal.pdf`: Proposal for the final project

### Data
- `cancer_reg.csv`: original dataset downloaded from OLS challenge linked above (see Appendix A of report for full data dictionary)
- `regions.csv`: dataset mapping states to their geographic region and division
- `State_Abbreviation_Mapping.csv`: dataset maping states to their abbreviations
- Other datasets: intermediate datasets produced during cleaning and preprocessing (can ignore if looking at only Final Report)

### Archive
Contains intermediate files used to create the Final Report

---

**Kendall Kikkawa, Jonathan Luo, and Andre Sha's final project UC Berkeley's Stat 151A (Linear Modeling: Theory and Applications) in Fall 2020.**
