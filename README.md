
In this project our group analyzed data related to country happiness across the world from 2015 to 2022.
We exported the raw data from Kaggle.
The raw data contains categorical data on GDP, Family, Life Expectancy, Freedom, Trust in the Government, Generosity, and Dystopia Residual in each country related to the citizens Happiness.

The categories are defined by The World Happiness Report as follows:

1. GDP per capita is in terms of Purchasing Power Parity (PPP) adjusted to constant 2011 international dollars, taken from the World Development Indicators (WDI) released by the World Bank in December 2015. See the appendix for more details. GDP data for 2015 are not yet available, so we extend the GDP time series from 2014 to 2015 using country-specific forecasts of real GDP growth from the OECD Economic Outlook No. 98 (Edition 2015/2) and World Bank’s Global Economic Prospects (December 2014 release), after adjustment for population growth. The equation uses the natural log of GDP per capita, since that form fits the data significantly better than does GDP per capita.

2. The time series of healthy life expectancy at birth are constructed based on data from the World Health Organization (WHO) and the World Development Indicators (WDI). WHO publishes the data on healthy life expectancy for the year 2012. The time series of life expectancies, with no adjustment for health, are available in WDI. We adopt the following strategy to construct the time series of healthy life expectancy at birth: first we generate the ratios of healthy life expectancy to life expectancy in 2012 for countries with both data. We then apply the country-specific ratios to other years to generate the healthy life expectancy data. See the appendix for more details. 

3. Social support (or having someone to count on in times of trouble) is the national average of the binary responses (either 0 or 1) to the Gallup World Poll (GWP) question “If you were in trouble, do you have relatives or friends you can count on to help you whenever you need them, or not?” 

4. Freedom to make life choices is the national average of binary responses to the GWP question “Are you satisfied or dissatisfied with your freedom to choose what you do with your life?” 

5. Generosity is the residual of regressing the national average of GWP responses to the question “Have you donated money to a charity in the past month?” on GDP per capita. 

6. Perceptions of corruption are the average ofbinary answers to two GWP questions: “Is corruption widespread throughout the government or not” and “Is corruption widespread within businesses or not?” Where datafor government corruption are missing, the perception of business corruption is used as the overall corruption-perception measure. 

7. The dystopia residual column estimates the extent to which each of the six factors – economic production, social support, life expectancy, freedom, absence of corruption, and generosity – contribute to making life evaluations higher in each country than they are in Dystopia, a hypothetical country that has values equal to the world’s lowest national averages for each of the six factors. They have no impact on the total score reported for each country, but they do explain why some countries rank higher than others.


Our group made the following hypotheses from the raw data:
1. We believe that the locations with consistently high happines scores share common characteristics. 
2. Trust in each government correlates/contritbutes resident's happiness.
3. The extent of resident freedon correlates to resident happiness.
4. The level of gov. funded social support correlates to happiness.
5. The level of happiness correlates to life expectancy and health.
6. GDP correlates to happiness

We used the python libraries pandas, scipy, numpy, and matplotlib, to analyze test the above hypotheses and formulate a new one.

Hypothesis #1 was too broad for the dataset, so we replaced it with the following hypothesis: The COVID-19 Pandemic had an impact on happiness scores.
Comparing average annual happiness from 2015 to 2022 showed that the COVID-19 Pandemic did not have an impact on the overall world happiness. 

Hypothesis #2 could not be rejected by statistical analysis. According to the scatter plots, the COVID-19 Pandemic reversed the relationship between citizens trust in government and happiness.

Hypothesis #3 could not be rejected by statistical analysis. According to the scatter plots citizens' sense of freedom had a direct relationship with the country's happiness score. The degree of the direct relationship between the two stayed relatively consistent before and after the COVID-19 pandemic.

We did not test Hypothesis #4 due to inconsistencies in the category of data.

Hypothesis #5 could not be rejected by statistical analysis. According to the scatter plots life expectancy in each country had a direct relationship with the country's happiness score. The degree of the direct relationship between the two was different before and after the COVID-19 pandemic. The scatter plots indicate life expectancy more significantly impacted country happiness outside of the COVID-19 pandemic years.

Hypothesis #6 could not be rejected by statistical analysis. According to the scatter plots GDP had a direct relationship with the country's happiness score. The degree of the direct relationship between the two was different before and after the COVID-19 pandemic. The scatter plots indicate GDP more significantly impacted country happiness during COVID-19 pandemic years.


Contributers:
* Peter Ferguson 
* Dave Freiberg 
* Jessica Ferraro 
* Kelsey Richards 
* Nate Beathea-Martinez 