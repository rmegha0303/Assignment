# Assignment
**Aim:** To build a model using publicly available data for key *supply-demand* factors that could influence U.S. Home Prices. Use that factors to explain how these factors impacted home prices over last 20 years.

**Solution:**
Here I have created the dataset with following features.
1.	observation_date : 
These are the dates of observations (Annual observation from the year 2000 to year 2020)

2.	Unemployment_RATE: 
This feature gives the unemployment rate of USA from year 2000 to 2022
Source of data: https://fred.stlouisfed.org/series/UNRATE

3.	GDP:
This feature gives the Gross Domestic Product value of USA from year 2000 to 2022
Source of data: https://fred.stlouisfed.org/series/GDP

4.	PERMIT:
This feature gives the values of total housing permits passed in USA over the year 2000 to 2022 (UNIT: Thousands of unit)
Source of data: https://fred.stlouisfed.org/series/PERMIT

5.	POPTHM:
This feature gives the information about the population growth of USA (UNIT: Thousands)
Source of data: https://fred.stlouisfed.org/series/POPTHM#0

6.	Recession:
These features represent weather the year was going through Recession or not
(0 -> represents Recession, 1-> represents no Recession)
Source of data: https://fred.stlouisfed.org/series/JHDUSRGDPBR

7.	house_tax:
This feature gives the values of taxes the owner had to pay during the observation date
(UNIT: Thousands)
Source of data: https://fred.stlouisfed.org/series/CXUSTATETAXLB1702M

8.	TTLCONS:
This feature gives the values of total construction spending in USA during the observation date (Unit: Millions of Dollars)
Source of data: https://fred.stlouisfed.org/series/TTLCONS 

9	Life_expectancy:
This feature gives the value of life Expectancy at birth total for United States 
(Unit: Years)
Source of data: https://fred.stlouisfed.org/series/SPDYNLE00INUSA

10.	MORTGAGE_RATE_US:
This feature gives the values of mortgage average rate in United States 
(Unit: Percent)
Source of data: https://fred.stlouisfed.org/series/MORTGAGE30US

11.	CPI:
The CPI stands for Consumer Price Index it measures change over time in the prices paid by consumers for a representative basket of goods and services.
Source of data: https://fred.stlouisfed.org/series/CPIHOSSL

12.	Home_price_Index:
This feature basically serves the purpose of target variable in the dataset
Source of data: https://fred.stlouisfed.org/series/CSUSHPISA
 
