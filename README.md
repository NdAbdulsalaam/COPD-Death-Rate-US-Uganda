# **Chronic Obstructive Pulmonary Disease (COPD)**
### Countries: United States & Uganda

## **Goal**
The task is to write a Python script that calculates both the **crude death rate** and the **age-standardized death rate** for all ages in both the United States and Uganda for 2019.

## **Overview**
In this data analysis journey, I collected data both from the United Nations' [website](https://population.un.org/wpp/Download/Standard/Population/), and a table provided by Our World in Data. The definitions of crude and ASDR are taken from WHO Standard Population — Table 1 in 'Ahmad OB, Boschi-Pinto C, Lopez AD, Murray CJ, Lozano R, Inoue M (2001). Age standardization of rates is a new WHO standard. 

**Crude Death Rate** tells us how many deaths per 100,000 people occurred in each country *without considering the age distribution*.  
**Age-Standardized Death Rate** adjusts for differences in the age distribution between the two populations, making it easier to compare the mortality rates. It tells us how many deaths per 100,000 people *you would expect if the age distribution in both countries were the same*.

## **Approach**
1. Data Collection: Population data for crude death downloaded as csv from UN Population Estimates, then imported to Colab. Population data per age group also downloaded from above and imported. Table simply copied from the Notion page and saved as csv.
2. Data consistency: Population data is per thousands, while the death rates are per 100,000.
3. Calculation: Define crude and age-standardized death rates and calculate outcomes
4. Analyze outcomes and communicate findings
5. Make note of any assumptions, or comments

## **Findings**
| No. | Indicator            | Location | Rate      |
|-----|----------------------|----------|-----------|
| 1.  | Crude Death Rate     | USA      | 2164.74   |
| 2.  | Crude Death Rate     | Uganda   | 2058.62   |
| 3.  | ASDR                  | USA      | 5159699.30|
| 4.  | ASDR                  | Uganda   | 574075.35 |


## **Skills and Tools**
- Data Importing
- Data Wrangling
- Statistical Analysis
- Python: Sctipting
- Pandas: Data Analysis
- Matplotlib: Data Vizualization

## **Analysis and Conclusion**

In both metrics, the number of deaths are higher in the USA, which seems contradictory due to the socioeconomic status and general infrastructural difference between the two countries.
Analysis of the reasons are beyond the scope of this project, and the time however, the median age of each population may be a significant factor to consider.

- If given more time, I would have liked to webscrape the table. Simply copying it was not the most elegant, but the fastest solution.
- Looking back, I should have not downloaded to csv's but got the population by summing the age groups.
- I would have liked to visualize some of the results, for example the death rates per age group compared to the population. 

## **Credits**
This task is part of a Data Analysis Exercise posted by Our World in Data. All resources are public and cited below. 
