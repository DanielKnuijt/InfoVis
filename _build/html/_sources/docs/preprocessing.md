# **Dataset and Preprocessing**


## Datasets
### Dataset 1
The ‘crimes-2001 to Present’ dataset contains, among others, reasons for arrests, dates,
locations, FBI codes, and community areas. These variables can contribute to detecting a
pattern in the location of different crimes in combination with the frequency of different
crimes. This knowledge can inform Chicago residents about the possible dangers of
different high-risk areas in Chicago. All data in this dataset is collected from the Chicago
police department’s own CLEAR (Citizen Law Enforcement Analysis and Reporting)
system, ensuring optimal credibility.
Screenshot of the result of running pandas.DataFrame.head(n=5) on your dataset:
Choose at least one variable in the dataset that your team wants to explore, explain
what the variables mean, and explain how the variable(s) can help you form
perspectives/arguments.

link: https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2/about_data



### Dataset 2
The 'Chicago Public Schools - Progress Report Cards (2011-2012)' dataset contains information on all public high schools in Chicago for the 2011–2012 school year. It includes factors such as attendance, teacher score, family involvement, and
CFS performance. Together, these factors provide a clear and objective view of each
school’s quality, allowing for meaningful comparisons and analysis. This dataset will be used in the full report (not yet in this draft version)

link": https://catalog.data.gov/dataset/chicago-public-schools-progress-report-cards-2011-2012



### Dataset 3
The 'Police sentiment scores' dataset contains various variables such as: race, gender, district, income, education and alot more usefull variables, that in combination with Datasets 1 and/or 2 can give interesting insights. This dataset will be used in the full report (not yet in this draft version)

link: https://catalog.data.gov/dataset/police-sentiment-scores



## Visuals
### Visuals 1-4
These visuals are all made using the Preprocessed dataset 1, containing only the data from the years 2018-2023. This selection gives plenty of records to ensure reliable results. This timespan also gives an interesting insight on the influence of the COVID-19 pandemic on Chicago's crime life.

#### Visual 1
 The most common crime types are counted where empty rows are ignored. At last, this result is presented as percentages of the total amount of crimes committed during 6-year time span.

#### Visual 2
 The total number of rows are counted for each one of the six years, and put into a line-diagram.

#### Visual 3
 The most common crime-scenes are counted and put into a pie-chart. This pie chart clearly shows the most popular crime-scenes, together with some less-popular crime-scenes. This pie-chart shows the average of the years 2018-2023. Finally the Pie-chart is transformed into a donut-chart for aestetic purposes.

#### Visual 4
 The total amount of crimes are counted for each Police-district in Chicago. This Bar chart gives a clear visual of the difference in crimes in various districts. 

in the Final project we plan to replace the numbers (x-axis) with the actual names of each district, removing the empty spaces (like district 13,21,etc.)

### Visuals 5 & 6
these will be in the final report (they are not finished for this draft version)
