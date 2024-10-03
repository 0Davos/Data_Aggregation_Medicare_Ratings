# Comprehensive Data Aggregation for Jibe Consulting
# Medicare Advantage and Star Ratings  

## By Owen Davis

### Introduction:
The Centers for Medicare & Medicaid Services (CMS) produce the advantage ratings and star ratings “each year to measure the quality of health and drug services received by consumers” (CMS.gov). This data can then be used by consumers and health professionals to actively and accurately inform their decisions about their health.
I created this project for Jibe Consulting, a client who was interested in the quickness of a program that could be reused each year with new datasets. They had been manually checking the changes many companies had year to year, and this service would be useful and time saving.

### Objective:
To achieve a program that could be easily used by a non-coder, yearly. It would aggregate data from multiple datasets, and would show clearly the changes each marker measured had from the current year to the previous.

### Data:
The datasets used are publically available, published by CMS.gov online.

### Benefits:
Including but not limited to, central access to data, simplifying analysis, and flexibility surrounding future use.

### Technologies:
Python, pandas library.

### Use / Future:
Each measurement is correctly compared, cleaned, and aggregated from the current and previous year to a new file. Each company has multiple columns for each measurement, including a current percentage, current star rating, and percentage change from the previous year. If a measurement doesn't exist in the previous year, it returns null values for the percentage change. Any cell that doesn't have enough data to fulfill a measurement is also handled appropriately. Each company also has total enrollees included and the states they have those enrollees in, as columns at the end of file.

Because of the semi-common introduction of new measurements or change in name of measurements, my help may be requested in the near future for the newer release of the 2024 datasets.

### Extra Info
Ratings Explanation: https://www.cms.gov/newsroom/fact-sheets/2024-medicare-advantage-and-part-d-star-ratings
Data: 
https://www.cms.gov/medicare/health-drug-plans/part-c-d-performance-data

