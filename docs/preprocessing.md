# **Dataset and preprocessing**

we decided to search for two datasets that can be linked to eachother, so we could make interesting visuals. By searching google scholar we found two datasets from the chicago police department, which ensured integrity and validity since it's from a government installation that we can trust.

## Cleaning
since the two datasets use records by day, we first changed this to contain records by year, which made it easier to then later on create the visuals. the 'crime-data' dataset now contains multiple records per year, while the 'sentiment-data' dataset contains one record per year per district, using mean to merge.

By doing so, the 'crime-data' dataset contains 144761 records, while the 'sentiment-data' dataset now only contains 133 records.

## Variable descriptions
after selecting the variables that we want to use and dropping all irrelevant variables we are left with 11 variables: `Year`, `District`, `Date`, `Primary Type`, `Location Description`,`Safety`,`Trust`,`S_INCOME_LOW`,`S_INCOME_MEDIUM`,`S_INCOME_HIGH`

Discrete / Ordinal: `Safety`,`Trust`,`S_INCOME_LOW`,`S_INCOME_MEDIUM`,`S_INCOME_HIGH`
Discrete / Nominal: `District`,`Primary Type`,`Location Description`
Discrete / Interval: `Date`, `Year`