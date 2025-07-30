# Customer Segmentation & Behavior Insights

## 📚 Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Strategic Challenges Tackled](#strategic-challenges-tackled)
- [Tools Used](#tools-used)
- [Data Cleaning and Transformation Procedures](#data-cleaning-and-transformation-procedures)
- [Dashboard Preview](#dashboard-preview)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [Conclusion](#conclusion)
- [Project File](#project-file)

---
## Project Overview

This data analysis project showcases a professional-grade Customer Analytics Dashboard, which analyzes customer demographics, purchase patterns, and tenure segmentation to support data-driven marketing and retention strategies for Sprocket Central Pty Ltd.

---
## Data Sources

- New Customer List data: The primary dataset used for this analysis is the “KPMG Virtual Internship_ Sprocket Central Pty Ltd Data set.xlsx” file (1,000 rows × 23 columns).
- Content: Customer demographic information, bike purchase history, job industry, tenure, and wealth segments.

---
## Strategic Challenges Tackled

- Aggregate Customer Volume
- Cumulative Bike Purchases
- Age Segment with Highest Potential
- State with Maximum Purchases
- Top Purchasing Gender
- Tenure Category with Strongest Impact
- Top Performing Industry
- Priority Wealth Segment

---
## Tools Used

- Excel – Data preparation, structure, and formulas 
- Power BI – Interactive dashboards and visuals

---
## Data Cleaning and Transformation Procedures

- Raw data was converted to Excel Table format
- Irrelevant columns were removed
- Replaced missing values with `"Not Specified"`
- Created columns with formulas for:
  - Age = `YEAR(TODAY()) - YEAR(D2; row number)`
  - Age groups & Age Category = used Nested IF logic as formula and WHO standard for age classification.
  - Tenure range & bucket = used IFS logic as formula to group customers into various tenure groups `(<=2, “Newbie”, <=11, “Regular” ………  >=21, “Legacy”)`. 

| Raw/Dirty Data | Cleaned Data |
|----------------|--------------|
| <img width="1336" height="692" alt="Raw Data" src="https://github.com/user-attachments/assets/48474df8-68da-4d14-a118-f00ac075dddf" /> | <img width="1360" height="708" alt="Cleaned Data" src="https://github.com/user-attachments/assets/8fdfabbb-e538-4e58-9b5a-596f6de01614" /> |

---
## Dashboard Preview
<img width="720" height="1461" alt="CA Dashboard" src="https://github.com/user-attachments/assets/2caf2abc-ecbc-4749-83af-ad08c96d3265" />
<img width="720" height="1600" alt="CA Dashboard _ Affluent Customer" src="https://github.com/user-attachments/assets/9170f011-2e2b-430d-87a0-a000470eedf5" />
<img width="719" height="1441" alt="CA Dashboard _ High Net Worth" src="https://github.com/user-attachments/assets/cf8b7985-25f5-45cc-abe7-e35833af8c21" />
<img width="720" height="1413" alt="CA Dashboard _ Mass Customer" src="https://github.com/user-attachments/assets/17e51567-d09d-427b-b1d6-268fe007d85d" />

---
## Results and Findings

The analysis results are summarized as follows:

| Indicators | Results/Findings |
|------------|------------------|
| **Total number of bikes purchased** | 49,000 |
| **Aggregate customer volume (Cleaned)** | 983 |
| **Top Gender** | Female |
| **Top State** | New South Wales |
| **Top Age Category** | Pre-reitrees (46-60) |
| **Top Job Industry** | Financial Services |
| **Top Wealth Tier** | Mass Segment |
| **Top Tenure Group** | From Settler – Advocate shows higher purchasing activities, but there is a decline in purchase towards Veteran and Legacy |

---
## Recommendations

Based on the analysis, the following actions are recommended for Sprocket Central Pty Ltd to embark on:
1. **For Gender**: Gender-targeted marketing campaigns will help optimize outreach strategies.
2. **For States**: Focus on sales efforts on high-performing regions (New South Wales) and boost marketing campaigns for under-performing states (Victoria and Queensland).
3. **For Wealth Tier**: Diversifying product offerings to meet various income levels.
4. **For Job Industry**: Partnership with companies in these industries for corporate sales programs will help boost purchase level.
5. **For Age Category**: Refining marketing structures for the dominant age segments (Pre-retirees and Retirees), will help increase purchase rate, and extra strategic market attention need to be channeled to Youth, Young workforce and Established Adult.
6. **For Tenure Group**: Introducing healthy customer retention strategies (loyalty programs) which will in turn have great impact on purchase pattern and tenure retention. 

---
## Limitations

I had to remove certain columns that where not consistent with the dataset, and certain incomplete rows that would have altered the accuracy of my conclusions. 

---
## Conclusion

Understanding customer behavior is no longer optional! it's essential for building lasting relationships, improving retention, and maximizing lifetime value. This project provides a foundation for Sprocket Central and other businesses to move from generic outreach to precision-driven engagement.

---
## Project File

[Downlaod Power BI Report (.pbix)](https://github.com/ICE-Analyst/Customer-Trend-Xray/blob/main/Sprocket%20Ltd_Customer_Analytics_Dashboard.pbix) - Power BI Dashboard

[Download New Customer List Dataset.xlsx](https://github.com/user-attachments/files/21498762/New.Customer.List.Dataset.xlsx) - Cleaned and Transformed Excel File

---
## Author

**Ihedioha Chima Emmanuel**

---

![Coporate-Thank-You-Note-JPEG-Image](https://github.com/user-attachments/assets/4cc86051-d1b9-4819-8ff0-05d296444475)
