# Stat151A_Final_Project

Performing Regression to predict death rate in different counties across the U.S. Data was collected from the American Community Survey (census.gov), clinicaltrials.gov, and cancer.gov. 

## Datasets
- cancer_reg.csv: original dataset downloaded from web
- temp.csv: dataframe after initial cleaning by Andre, but without having dropped any variables with high VIF
- temp2.csv: same as temp, but with variables with high VIF dropped
- temp3.csv: temp2 after applying box-cox transformation to all explanatory variables
- temp4.csv: same as temp3, but with additional geography columns (county, state, state abr., fips)
