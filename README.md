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
- [Key Findings and Recommendations](#key-findings-and-recommendations)
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

## Key Findings and Recommendations
### 1. Coca-Cola was the Dominant Brand
* Coca-Cola recorded the highest distribution presence and sales volume across all surveyed outlets, outperforming competitors such as Pepsi, Bigi, 7Up, etc.
* This observation may be due to the following:
    - Strong distribution network and logistics capabilities.
    - High brand loyalty built from decades of marketing and sponsorship
    - Price flexibility.
* My findings also suggests that retailers may prioritize stocking Coca-Cola to drive revenue and attract customers.
* Smaller brands may face difficulty gaining shelf space or negotiating pricing.

**Recommendations:**
* Competing brands should improve brand visibility through promotions, pricing, and community events.
* Launch targeted campaigns where Coca-Cola dominance is lowest.

### 2. Shops Sold the Highest Number of Products
* Among outlet types (shops, restaurants, kiosks, supermarkets, etc.), shops recorded the highest product sale frequency. This suggests shops are the most profitable outlet channel for distribution optimisation and marketing focus.
* Possible reason for the above observation may be because shops offer accessibility within local communities unlike supermarkets or restaurants located in premium or destination areas.

**Recommendations:**
* Prioritize shops in distribution planning and promotional campaigns.
* Implement loyalty programs for shop owners.
* Improve promotional displays within shops.

### 3. Stock Availability in Outlets: 39.4% Well Stocked, 43.6% Partially Stocked, 0.92% Out of Stock
* More than half of outlets do not have full product availability. This is possibly due to logistic delays, poor stock forecasting, or unequal product distribution.
* Low product availability can lead to revenue losses due to unmet demand

**Recommendations:**
* Introduce automated demand forecasting in outlets
* Improve route planning and delivery frequency where possible
* Create vendor performance metrics to track availability by location

### 4. Stock Condition by Brand: 40.2% Fully Stocked, 28.8% Partially Stocked, 6.2% Out of Stock.
* While most brands remain well distributed, certain brands face stock-outs and uneven distribution. This guides strategic resource allocation and identifies distribution gaps.

**Recommendations:**
* Increase delivery frequency for weaker brands
* Develop minimum stock level agreements with distributors

5. PET Bottles Were the Predominant Packaging Type
Interpretation

PET bottles are the most widely distributed packaging format.

Importance

Indicates packaging preference trends that influence marketing, manufacturing, and pricing.

Implication

Convenience and portability drive consumer preference.

PET demand may influence recycling ecosystem development.

Possible Reasons

Cheaper to produce and transport

Safer and easier to store in small shops

Recommendations

Introduce PET-based promotional bundles

Partner with recycling initiatives for sustainability branding

6. Viju, Fanta, Smoov Were the Least Sold Drinks
Importance

Shows weak market positioning and identifies opportunities or risk points.

Implication

Shelf space allocation may drop

Vendors may reduce orders leading to reduced visibility

Possible Causes

Weaker marketing campaigns

Narrower consumer audience (e.g., Viju milk targeted age groups)

Packaging or pricing issues

Recommendations

Targeted promo campaigns, sampling, or bundle pricing

Improve visibility with branded displays

7. Most Out-of-Stock Products Used Glass Bottle Packaging
Interpretation

Higher stock-outs exist among glass bottled beverages.

Importance

Reveals packaging-based supply chain constraints.

Implication

Inefficient transportation leading to breakage

Higher storage and return logistics costs

Possible Reasons

Glass bottles require return-cycle management

Higher logistic restrictions

Recommendations

Increase PET alternatives for high-demand SKUs

Optimize reverse-logistics for glass packaging

8. Perceived Shelf-Life: Coca-Cola & Pepsi Highest; Maltina, Pop, Pop Cola Lowest
Importance

Perception influences purchasing decisions and stocking confidence.

Implication

Products with perceived short shelf-life face reduced stocking volume.

Possible Causes

Packaging type differences

Past experience with spoilage

Recommendations

Educate retailers using shelf-life training brochures

Improve packaging materials and labeling

9. Display Stands & Shelves/Cartons Were Most Preferred Display Methods
Interpretation

Retailers prefer structured product presentation for visibility.

Importance

In-store visibility influences impulse purchase rate.

Implication

Manufacturers should invest in branded display stands.

Possible Reasons

More organized, visually appealing layout

Space optimization

Recommendations

Provide branded display stands to high-performing outlets

Sponsorship and placement negotiation programs

## Conclusion
This analysis underscores both progress and challenges within Palmora Group's workforce structure. While the organisation demonstrates pockets of gender balance and female excellence in performance, persistent gender pay gaps and departmental disparities remain. Proactive, data-driven actions, combined with a commitment to equity and inclusivity, will position Palmora Group as a model employer, fostering a diverse, high-performing, and compliant workforce.
