# Optimizing-Healthcare-Outcomes-A-Power-BI-Analysis


## Project Overview
This project investigates variations in mortality rates among sepsis patients based on demographics (age, race, gender, and hospital division) and hospital-level factors. Additionally, it explores the relationship between regional GDP and total healthcare charges. Through this analysis, the project aims to provide insights into sepsis-related mortality trends and highlight potential areas for healthcare improvement.

---

## Research Questions
1. How do mortality rates for sepsis patients vary across demographics such as age, race, gender, and region?
2. How do mortality rates differ across hospitals, and which types of hospitals or insurance payers have higher associated charges?
3. What is the relationship between hospital division GDP and average healthcare charges?

---

## Data Sources
- **National Inpatient Sample (NIS 2021):** A comprehensive inpatient healthcare database providing patient demographics, hospital details, and utilization metrics.
- **USAFacts GDP Data (2021):** State-level GDP metrics for economic analysis.

---

## Methodology
1. **Data Preprocessing:**
   - Cleaned and joined datasets using unique identifiers (e.g., `HOSP_NIS` for hospital and patient data, and `Division` for GDP data).
   - Transformed categorical variables (e.g., `Race`) into meaningful labels.
   - Removed unnecessary columns from the original datasets to focus on relevant variables.

2. **Data Analysis:**
   - Explored variations in mortality rates across age, gender, race, and region.
   - Analyzed hospital size, control type, and insurance payer charges to identify cost patterns and disparities.
   - Investigated correlations between regional GDP and total healthcare charges.

3. **Visualizations:**
   - Line graphs, pie charts, and bar graphs to illustrate mortality trends and financial disparities.
   - Interactive animations for dynamic analysis of age and race-related mortality patterns.

---

## Key Insights
1. **Demographics and Mortality:**
   - Mortality rates increase with age, particularly for patients over 60 and under 20.
   - Regional disparities highlight higher mortality rates in Pacific and East South-Central divisions.

2. **Hospital-Level Analysis:**
   - Larger hospitals report lower mortality rates.
   - Medicare accounts for the highest charges among insurance payers.

3. **Economic Analysis:**
   - Higher GDP divisions generally incur higher healthcare charges, but outcomes vary.

---

## Tools and Technologies
- **Data Sources:** NIS 2021, USAFacts GDP
- **Data Processing:** Python, Pandas
- **Visualizations:** Power BI, Matplotlib
- **Interactive Features:** Animations for age and race analysis

---

## Conclusion
This project highlights significant demographic, hospital-level, and economic variations in sepsis mortality rates. Insights derived can help identify policies and practices to improve patient outcomes, reduce financial disparities, and optimize healthcare delivery.

---

## Future Directions
- Explore regional healthcare practices contributing to better outcomes.
- Analyze hospital administrative structures and insurance policies for cost efficiency.
- Assess how economic factors impact patient outcomes in high-GDP regions.

---

## Links
- [NIS Data Specifications](https://hcup-us.ahrq.gov/db/nation/nis/tools/stats/FileSpecifications_NIS_2016_Core.TXT)
- [USAFacts GDP Data](https://usafacts.org/metrics/gross-domestic-product-gdp-by-state/)
