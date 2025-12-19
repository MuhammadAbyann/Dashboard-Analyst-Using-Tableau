# 📊 US Flight Delay Analysis (2017–2022)

## 1. Project Overview
This project analyzes **flight delays in the United States** between **January 2017 and July 2022** to identify:
- The most dominant causes of delays
- Airlines with the highest arrival delays
- Geographic distribution of delays across the US
- Trends in carrier-related delays over time

The final output of this project is an **interactive Tableau dashboard** designed to support **data-driven decision making** in aviation operations and performance evaluation.

---

## 2. Dataset Description

### 📂 Original Dataset
- **File Name:** `Airline_Delay_Cause.csv`
- **Source:** Public aviation delay dataset
- **Description:** Raw flight delay data containing multiple delay categories such as carrier delay, weather delay, NAS delay, security delay, and late aircraft delay.

### 📂 Processed Dataset
- **File Name:** `airportdelaydata.xlsx`
- **Description:** Cleaned and processed dataset after:
  - Removing inconsistencies
  - Aggregating delay metrics
  - Formatting date and categorical fields
  - Preparing data structure optimized for Tableau analysis

---

## 3. Data Preparation & Cleaning
The data preparation process included:
- Handling missing and inconsistent values
- Standardizing carrier and airport codes
- Aggregating delay minutes by:
  - Airline (Carrier)
  - State / Airport
  - Time (Month & Year)
- Calculating delay percentages for carrier-related delays

All data preprocessing was performed **before visualization** to ensure accuracy and performance in Tableau.

---

## 4. Dashboard Components

### 🗺️ 1. Geographic Delay Distribution (Map)
- Displays delay intensity across US states
- Bubble size represents total delay volume
- Color gradient indicates overall arrival delay magnitude
- Helps identify **delay hotspots** geographically

### 📊 2. Arrival Delay by Carrier (Bar Chart)
- Compares total arrival delay across airlines
- Highlights airlines with the most operational delay impact
- Useful for benchmarking airline performance

### 📈 3. Carrier Delay Percentage Trend (Line Chart)
- Shows monthly trend of average carrier delay percentage
- Covers period from 2017 to 2022
- Reveals impact of external events (e.g. operational disruptions)

### 🔢 4. KPI Summary Cards
Key delay metrics displayed at the top:
- Arrival Delay
- Carrier Delay
- Late Aircraft Delay
- NAS Delay
- Security Delay
- Weather Delay

---

## 5. Key Insights
- **Carrier Delay** and **Late Aircraft Delay** are among the dominant contributors to total arrival delays.
- Certain airlines consistently show higher arrival delays, indicating operational inefficiencies.
- Delay intensity is concentrated in high-traffic states and major aviation hubs.
- Carrier delay percentage shows a noticeable increase during certain periods, suggesting systemic operational challenges.

---

## 6. Tools & Technologies
- **Tableau Desktop**
- Microsoft Excel
- CSV & XLSX data formats
- Data visualization & analytical storytelling techniques

---

## 7. Files Included
| File Name | Description |
|---------|------------|
| Airline_Delay_Cause.csv | Raw dataset |
| airportdelaydata.xlsx | Cleaned & processed dataset |
| US_Flight_Delay.twbx | Tableau packaged workbook |
| US_Flight_Delay_Dashboard.png | Final dashboard image |
| Documentation.md | Project documentation |

---

## 8. Conclusion
This project demonstrates my ability to:
- Clean and transform real-world datasets
- Design interactive dashboards
- Translate complex data into clear insights
- Apply analytical thinking to operational problems

The dashboard can be used by stakeholders to monitor airline performance and understand key drivers of flight delays in the US.

---

📌 *This project is part of my Tableau Data Visualization Portfolio.*
