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

link: https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2/about_data


### Dataset 2
The 'Police sentiment scores' dataset contains various variables such as: race, gender, district, income, education and alot more usefull variables, that in combination with Datasets 1 and/or 2 can give interesting insights. 

link: https://catalog.data.gov/dataset/police-sentiment-scores



## Visuals
### Visuals 1-4
These visuals are all made using the Preprocessed dataset 1, containing only the data from the years 2018-2023. This selection gives plenty of records to ensure reliable results. This timespan also gives an interesting insight on the influence of the COVID-19 pandemic on Chicago's crime life.

#### Visual 1
 The most common crime types are counted where empty rows are ignored. At last, this result is presented as percentages of the total amount of crimes committed during 6-year time span.

#### Visual 2
 The total number of rows are counted for each one of the six years, and put into a line-diagram. This is a quick and effective way to count crimes per year, as each record represents one crime.

#### Visual 3
 The most common crime-scenes are counted and put into a pie-chart. This pie chart clearly shows the most popular crime-scenes, together with some less-popular crime-scenes. This pie-chart shows the average of the years 2018-2023. Finally the Pie-chart is transformed into a donut-chart for aestetic purposes.

#### Visual 4
 The amount of times each police district presents itself in the dataset is counted, as each record represents one crime. This Bar chart gives a clear visual of the difference in crime rates in various districts. For visual clearness, the bars in the chart are descending from high-crime districts to low-crime districts. Since the number connected to each district has no numerical meaning, it does not matter that these numbers are not consecutive on the x-axis. 


### Visuals 5 & 6
These visuals rely on Dataset 2, this dataset is aggregated to only contain data from 2018-2023. To make sure each record contains one year per district, we merged on year and district using mean. This results in a dataset where each entry has a different district and year, with all other values being the mean of all values from that district in that year.

#### Visual 5
This grouped bar-chart uses various variables from the previously aggregated dataset 2. the 'SAFETY' variable, 'S_INCOME_LOW', 'S_INCOME_MEDIUM' and 'S_INCOME_HIGH' variables are shown for each of the districts, with the safety score descending from high to low, from the left side of the chart to the right. A dropdown menu is added to make it possible to view the different safety scores for each year. 

please note that all of these variables are in percentages, while in reality this is linked to a survey that residents of each district have filled in, scoring safety on a scale of 0-10. When a score of 7 is given, this correlates to 70%. This makes it so that the percentages of low, medium and high income do not make up 100%, but more. As people with a high income rank their safety differently as people with a low income. the safety-score that is not linked to income is the total average safety score, calculated from all various variables in the dataset together.

#### Visual 6
This bar-chart uses the trust variable from dataset 2, incombination with the crime-rate calculated by counting the occurrences of each district per year from dataset 1. combining two bars into one gives a clear insight that a decrease in crime-rate is accompanied by an increase in trust score and vice versa. A dropdown menu is added to make it possible to select for which year the user wants to view this information.

please note that for the trust-score, the same measurement system is used as noted in visual 5.


### Visual 7
This box-plot shows the timeframe of when most crimes are committed. using mean, median, Q1, Q3, min and max; it gives a clear insight on when most crimes are committed. adding a dropdown menu to make it possible to view this data for each year in the dataset. Adding a hover popup when hovering your mouse over the center of the box-plot, all previously mentioned values are shown, making it easy to compare the values between years.