# Soft Drink Market Insight
This is an analysis of a real-world survey data from Alimosho Local Government Area, Lagos, Nigeria.

---

## Aim
The aim of the analysis is to reveal meaningful insights from the data and tell a clear story about soft drink distribution, brand dominance, and consumer trends.

---

## Dashboard
The interactive report for this analysis can be accessed [here]().  

---

## 📁 Table of Contents
- [Aim](#aim)
- [Dashboard](#dashboard)
- [Data Overview](#data-overview)  
- [Methodology](#methodology)
- [Technologies Used](#technologies-used)
- [Data Cleaning](#data-cleaning)
- [Analysis and Recommendations](#analysis-and-recommendations)
- [Overall Recommendations](#overall-recommendations)  
- [Conclusion](#conclusion)  

---

## Data Overview
- **Source:** The dataset can be accessed [here]()
- Raw data has the following columns:
  1. Outlet Name and Type (e.g., supermarkets, kiosks, restaurants, shops)
  2. Coordinate of Outlet (Latitude and Longitude)
  3. Product Type(e.g., Coca-Cola, Pepsi, Bigi, etc.)
  4. Product Display Type (e.g On shelf/carton In refridgerator/cooler, etc)
  5. Package Type (e.g., PET bottle, can, glass)
  6. Product Shelf Presence
  7. Stock Condition
- Data Shape (1500, 38) | Data format: Comma Delimited (.csv)  
---

## Methodology
- Datasets were imported into and cleaned in Microsoft PowerBI as detailed in [Data Cleaning](#data-cleaning).
- Write DAX measures to calculate each of the following:
  * Dominant Brand
  * Total Brands
  * Total products
- Analysis was grouped into three pages on the dashboard: Overview, Stock level analysis, and Product analysis.

---

## Technologies Used
- Power BI  
- DAX  
- Git & GitHub  

---

## Data Cleaning  
- Trim all columns
- Split columns into tables: Shops, Products, Stock level, Display type, etc.
- Standardize all column entries, E.g. Change 'Fantai' to 'Fanta'; 'Coke', 'Coca cola', and 'Coca Cola' to 'Coca-cola'
- Remove invalid entries as they are very few.
- Merge/join tables into one (on the unique ID), or use modeling to connect all tables.
---

## Analysis and Recommendations
### 1. Gender Distribution by Region
The gender composition across Palmora Group reveals a modest gender imbalance. Out of the total workforce, 430 are males and 406 are females, indicating approximately 51% male dominance. Regionally:
* Kaduna and Lagos exhibit noticeable male dominance.
* Abuja displays a commendable gender balance, serving as a positive outlier.

Such imbalances may limit diversity-driven innovation and may indicate barriers to female recruitment or retention in specific regions.

**Recommendations:**
* Launch targeted female recruitment campaigns, prioritising Kaduna and Lagos.
* Conduct exit interviews and employee feedback sessions to understand regional gender-specific challenges.
* Utilise Abuja as a benchmark for gender inclusivity practices to be replicated across other locations.

---

### 2. Gender Distribution by Department
Gender distribution within departments is disproportionate, with the males dominating most departments, especially Legal, Support, and Accounting departments. However, there was a strong female representation in Services, Business Development, Human Resource, and Research and Development. The analysis also show near gender parity in Engineering and Marketing departments. However, a portion of the workforce still has an undisclosed gender, potentially masking deeper gaps.

**Recommendations**:  
- Improve female representation in most departments, especially in the **Accounting** department.  
- Engineering department shows good gender balance, however, the undisclosed gender data should be clarified. Review and improve data collection processes to minimise undisclosed gender records.
- Recognise and reward departments like Marketing and Engineering for maintaining gender balance, reinforcing these as internal best practices.

---

### 3. Performance Ratings by Gender
Analysis of performance ratings uncovers encouraging patterns: A higher proportion of Females are represented within the top-performing groups ("Good" and "Very Good" ratings). However, the majority of both Male and Female employees are clustered within the "Average" rating band, suggesting organisational performance stagnation.

**Recommendations**:  
- Establish mentorship and leadership pathways to retain and promote high-performing females.
- Strengthen performance review processes to ensure objectivity and eliminate potential unconscious bias.
- Introduce targeted training and development programs to uplift average performers and support underperforming staff with tailored improvement plans.
- Identify the poor performing staff and provide support tailored to their needs. 

---
### 4. Salary Structure and Gender Pay Gap
A notable, albeit modest, gender pay gap persists: Average salary for Males ($74.5K) is slightly higher than that of Females ($72.6K). This was distilled across all regions, showing that Males had higher pay advantage than Females in these regions. Suprisingly, staff (Male and Female) in Lagos had the highest average salary, even though this region had the least number of staff compared to the other regions. This disparity may be a reflection of the high cost of living in Lagos.  

Department-wise, Males had higher average salaries in 9 out of the 12 departments, except in **Marketing, Training and Engineering** departments where Females had slightly higher pay than their Male counterparts. 

**Recommendations**:  
- Commission an independent, data-driven salary equity audit across regions and departments.
- Design structured, transparent pay frameworks linked to objective performance metrics.
- Address unjustified gender-based pay gaps while considering regional economic factors, such as Lagos' higher living costs. 

---

### 5. Regulatory Compliance Check
Given the new regulation that mandates all manufacturing companies to pay their staff a minimum annual salary of **$90,000**, the analysis reveals that Palmora is non-compliant. A total of 599 staff (213 in Abuja, 232 in Kaduna, and 154 in Lagos) earn less than $90k.

**Recommendation**:
- Immediately identify affected employees across all regions.
- Develop a phased salary adjustment plan to achieve full compliance within stipulated timelines.
- Engage with legal and regulatory experts to ensure all future compensation structures align with evolving policy requirements.  

---

## Overall Recommendations
- **Diversity & Inclusion:** Implement a comprehensive gender diversity and inclusion strategy targeting both recruitment and retention, especially in underrepresented regions and departments.
- **Data Quality:** Improve employee data collection, specifically for gender disclosure, to enhance the accuracy of diversity reporting.
- **Performance Development:** Invest in performance improvement initiatives to reduce the concentration of "Average" performers, with particular attention to supporting underperformers.
- **Pay Equity:** Conduct regular salary audits, link pay to transparent performance metrics, and actively work to close unjustified gender pay gaps.
- **Regulatory Compliance:** Establish a compliance task force to monitor salary structures and ensure alignment with all current and future industry regulations.
---

## Conclusion
This analysis underscores both progress and challenges within Palmora Group's workforce structure. While the organisation demonstrates pockets of gender balance and female excellence in performance, persistent gender pay gaps and departmental disparities remain. Proactive, data-driven actions, combined with a commitment to equity and inclusivity, will position Palmora Group as a model employer, fostering a diverse, high-performing, and compliant workforce.
