# LSE_DA_C2_COVID_analysis

Data analysis performed to identify trends and patterns that can be used to inform its marketing approach to increase the number of fully vaccinated people, taking into account the COVID-19 UK data (from January 2020 to October 2021) provided:

- covid_19_uk_cases.csv: cases data, including the number of deaths, cases, recovered, and hospitalised cases.
- covid_19_uk_vaccinated.csv: vaccination data, including the number of first and second dose cases.


1.	KEY INSIGHTS
	
2.1.	VACCINATION
-	The number of people with only the first dose has been decreasing, with the lowest values in the last two months. 
-	The percentage of people with only the first dose of the vaccine is below 5% in all regions, with residual variations of the percentage between regions.
-	Gibraltar shows the highest number of people who have only had the first dose with 264,745:
-	Gibraltar also presents the highest number of people fully vaccinated with almost 6 million. 

2.2.	DEATHS, CASES AND RECOVERIES

-	“Others” province stands out in the total cases and deaths, probably due to a higher population.
-	“Others” province also stands out the average death toll per day with almost 219 cases. The remaining provinces have a residual value.
-	The death toll from March 2021 doesn’t show a relevant increase, not even when there was a relevant increase in the number of cases, contrary to what happened before. This can be explained by the vaccination campaign that started in 2021, which was especially effective from the second quarter of 2022.
-	As expected, “Others’ region” stands out with a much higher death toll and a maximum value of 32,646 deaths. Below shows the death toll monthly pattern, with Gibraltar standing out at the end of January 2021, Bermuda and the Island of Man show an increase at the beginning of October.
 
2.3.	RELATIONSHIP BETWEEN VACCINATION AND DEATHS/CASES/RECOVERIES

-	The heatmap shows the relationship between variables from April to October 2021, highlighting: 
▪	Very high correlation between Cases/Deaths
▪	Negative correlation between Vaccines/Deaths and a positive correlation between Vaccines/Recoveries (evidencing the positive effects of vaccination). 

2.4.	HOSPITALISATION

-	The first figure, including boxplots per region based on hospitalisation data up to April 2021 (previous second dose taking effect), evidenced a right skewed distribution without outliers. Applying the same scale on the boxplots using data from April 2021, shows a decrease in hospitalisations and a less skewed distribution without outliers.
 
2.5.	TWITTER

-	Hashtags containing “covid” dominated the top5 hashtag usage, with only one case that does not include this word.
 

3.	CONCLUSIONS AND RECOMMENDATIONS
	
Based on the data provided:
-	There is no evidence to support prioritisation of vaccinations in regions with less fully vaccinated people (residual differences in the percentage of people with only the first dose per region). 
-	Bermuda and British Virgin Islands show an increase of deaths at the end of September that should be monitored and focus your marketing campaign here.

However, the data provided presents the following inconsistencies:
-	“Others’” province stands out in the number of cases and deaths, but the number of people vaccinated does not follow this line where it is the second-to-last.
-	 There is no information regarding recoveries from August 2021

Further analysis
-	Examination and clarify data incoherencies to increase the assurance of the conclusion.
-	Analyze the population number per region could improve the analysis.
