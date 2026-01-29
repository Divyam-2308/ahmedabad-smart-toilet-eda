# Ahmedabad Smart Toilet Usage – Infrastructure Stress Analysis

## Project Overview
This project analyzes smart public toilet usage data from Ahmedabad for August 2022.  
The objective is to understand how demand is distributed across toilets, identify high-usage infrastructure under operational stress, and highlight potential inefficiencies in asset utilization.  
Due to the absence of recorded failure signals in the dataset, the analysis focuses on usage-based risk assessment and preventive planning rather than reactive failure analysis.

---

## Dataset Description
- **Source:** [data.gov.in](https://www.data.gov.in/)
- **City:** Ahmedabad  
- **Time Period:** August 2022  
- **Granularity:** Monthly, per toilet  
- **Rows:** 58  
- **Columns:** Location, toilet type (gender), total monthly usage, power failure count, water failure count  

Each row represents a single smart toilet with aggregated usage and failure counts for the month.

---

## Key Analysis Questions
- How uneven is toilet usage across the city?
- Is usage demand concentrated in specific locations?
- How does average usage per toilet differ by gender?
- Which toilets experience the highest operational stress?
- Are there underutilized infrastructure assets?

---

## Key Insights
- A small subset of toilets handles a disproportionate share of total usage, with the top 10% accounting for approximately 27% of overall demand.
- Most toilets operate under moderate, stable usage conditions, indicating broadly adequate city-wide infrastructure.
- High-stress toilets are few in number but critical in impact due to sustained high usage load.
- Several toilets show consistently low usage, suggesting potential inefficiencies in placement or awareness.
- No power or water failure signals were recorded in the dataset, limiting validation of usage-based risk against actual breakdowns.

---

## Risk Categorization Approach
Toilets were classified into **High**, **Medium**, and **Low** stress categories based on relative usage percentiles.  
Risk is defined as sustained operational stress due to high usage, not observed failures.  
This relative categorization supports maintenance prioritization under limited data availability.

---

## Limitations
- The analysis is based on a single month of aggregated data and does not capture seasonal or event-driven variation.
- No failure data was recorded, preventing direct linkage between usage stress and infrastructure breakdowns.
- Factors such as cleanliness, accessibility, and maintenance quality were not available in the dataset.

---

## Future Improvements
- Extend the analysis to multiple months to identify long-term usage trends.
- Improve failure data logging to enable validation of risk indicators.
- Develop predictive maintenance models using enriched operational data.

---

## Tools Used
- Python
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook

---

## Conclusion
This project demonstrates how meaningful insights can be extracted from incomplete civic infrastructure data by focusing on usage patterns, risk framing, and honest analytical boundaries.  
It emphasizes decision-oriented analysis over forced conclusions, supporting practical infrastructure planning.
