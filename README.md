## Overview

It involves analyzing data related to **GDP**, **population**, and **vehicle sales** for three countries: **United Kingdom (UK)**, **United Arab Emirates (UAE)**, and **Malaysia**. The data is sourced from different datasets, and various analyses and visualizations are conducted to derive meaningful insights using **pandas** and **matplotlib.pyplot**.

## Datasets Used

1. **GDP Data (GDP.xls)**
   - Contains GDP data for various countries over the years.
   - Columns: `Country Name`, `Country Code`, `Indicator Name`, `Indicator Code`, and yearly data from 1960 to 2023.

2. **World Population Prospects (WPP2024_ByAge.csv)**
   - Contains population data categorized by country, year, age groups, and gender.
   - Columns of interest: `Location`, `Time`, `MidPeriod`, `AgeGrpStart`, `PopMale`, `PopFemale`, `PopTotal`.

3. **Vehicle Sales Data (vehicle.json)**
   - Contains data on vehicle sales for various countries.
   - Columns: `Nation`, `Year`, and the number of vehicles sold.

## Objectives

- Analyze and visualize GDP data for the selected countries (UK, UAE, Malaysia).
- Explore the population data by age group, gender, and country, with a focus on the working-age population.
- Visualize and compare vehicle sales data across countries.
- Merge datasets to compare GDP with population and find the GDP per capita for each country.

## Analysis and Visualizations

### GDP Analysis:
- Filtered and visualized GDP data for the countries of interest (UK, UAE, Malaysia) from 1960 to 2023.
- Created bar charts and pie charts to represent the relative GDP for 2023.
- Analyzed the GDP growth trends over the years, with a focus on the UK's rapid growth and the relatively slow growth of the UAE and Malaysia.

### Population Analysis:
- Filtered population data by working-age group (15-64 years for Malaysia/UAE and 16-64 years for the UK).
- Visualized the working-age population trends for the three countries over time.
- Created pie charts to compare the gender distribution of the working-age population in 2023.
- Analyzed the age distribution of the population for each country, identifying unique trends like the UAE's male-dominant population and the UK's aging population.

### Vehicle Sales Analysis:
- Visualized the number of vehicles sold by country over time, identifying trends and outliers (such as the UAE's 0 vehicle sales in 2017 and 2018).
- Created pie charts to show the proportion of vehicles sold in 2022.

### Merged Analysis:
- Merged the GDP and population data to calculate the **GDP per capita** for each country.
- Visualized the comparison of GDP and population for each country in 2023.

## Key Findings

1. **GDP Comparison**:
   - The UK leads in GDP, significantly ahead of both the UAE and Malaysia in 2023.
   - The UK's GDP is more than 3.5 times larger than the combined GDP of Malaysia and the UAE.

2. **Population Trends**:
   - The UK has an aging population with significant growth in older age groups.
   - The UAE has a youthful population with a peak in the 30-32 age group, driven by migration for work.
   - Malaysia has a youthful population, with a significant proportion of individuals in their late 20s and early 30s.

3. **Gender Distribution**:
   - The gender ratio in the UAE is male-dominated (64.1% male), likely due to the high number of male migrant workers.
   - The UK and Malaysia have relatively balanced gender ratios.

4. **Vehicle Sales**:
   - The UK dominates vehicle sales in 2022, while Malaysia and the UAE have smaller shares.
   - The UAE had a significant drop in vehicle sales in 2017 and 2018, which may be due to economic conditions or reporting issues.

5. **GDP per Capita**:
   - By merging the GDP and population data, the **GDP per capita** for each country was calculated. The UK, with its higher GDP, has a much higher GDP per capita compared to the UAE and Malaysia.

This will generate various visualizations, including bar charts, pie charts, and line graphs, which will be displayed on the screen.

## Conclusion

This project demonstrates how to analyze and visualize multiple datasets, gain insights, and merge data from different sources. It highlights the differences in GDP, population, and vehicle sales for the selected countries and provides a comprehensive understanding of their economic and demographic trends.

---
