# Analyzing-The-Impact-of-COVID-19-on-Education
An analysis of multiple data sets with international data on COVID cases/deaths and test scores before and after the pandemic to assess its impact on test scores. Uses PISA scores from before the pandemic to scores from 2022 and compares the two. Used a data set with country codes to convert country names to format that was constant across all data sets. 

Only the countries that were included in this OECD data set and had data for both 2018 and 2022 PISA scores are graphed. Used bar graphs to demonstrate the difference in PISA scores over time per country. Overall, we can observe a negative trend in PISA scores internationally from 2018 to 2022. This is most evident with math scores, less so with reading, and even less so with the science scores. 

Also mapped oldest recorded PISA scores per country to most recent (2018 and earlier) to demonstrate how scores fluctuated over the years prior to the pandemic. Removed the data from ‘RUS’ (Russia) and ‘LVA’ (Latvia) because they only had data from one year so a trend could not be mapped/observed. This data was taken from another OECD data set that mapped scores across years, ranging from 2000 to 2018. To compare this to the differences from the 2018 to 2022 data, I compared the oldest data available to the newest. In comparison to the previous slide, this data is much more variable and shows a less definite trend.

For the final visual, I created scatter plots with Total Deaths/1 Million in Population or Total Cases/1 Million in Population on the x-axois and differences in PISA scores from 2018 to 2022 on the y-axis. The scatter plots were then color-coded by the severity of COVID restrictions in each country being plotted with a legend to go with them. Filtered out the data set to not include Macedonia and Montenegro (COVID data for both countries was in original data set) because data on government measures during COVID was unavailable from data set used.
We can observe that most countries were mild in their restrictions on COVID. The scatter plots show a slight downward trend in PISA scores as the deaths and cases increase. Governments with stricter restrictions seemed to demonstrate less changes in the PISA score while the countries with low or mild restrictions had much more varied results.  

These data sets helped visualize and draw conclusions on the impact of COVID-19 on education. Across the world, test scores seemed to go down due to the impact of the COVID-19 pandemic, which was evident through PISA testing. This data is important so we can quantify the effects of the pandemic on the next generation and it reflects on the state of education as a whole.

2018 and previous PISA data was collected from Kaggle data set: https://www.kaggle.com/code/julioam/pisa-score-by-country-analysis/input from Julio Antonio Megu
Data set with 3-letter country-codes and full country names collected from Kaggle: https://www.kaggle.com/datasets/wbdill/country-codes-iso-3166 from bdill
World-wide COVID data collected from Kaggle: https://www.kaggle.com/datasets/imdevskp/corona-virus-report?select=worldometer_data.csv from Devakumar K. P.


