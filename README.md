<<<<<<< HEAD
# Oil & Gas Field Performance Analysis

## Project Overview

This project presents a comprehensive analysis of oil and gas field operations using Power BI, DAX, SQL, and Python integration. The objective is to evaluate production efficiency, operational costs, downtime impact, equipment utilization, and establish predictive insights for gas production.

The solution provides both operational and strategic insights to support data-driven decision-making in upstream oil and gas operations.

---

## Data Source

The dataset was extracted from Azure Blob Storage.  

Data was ingested, cleaned, and transformed prior to modeling. Preprocessing steps included handling missing values, validating production records, and structuring the data for analytical reporting.

---

## Tools and Technologies Used

- Power BI (Data Modeling and Visualization)
- DAX (Measures and KPIs)
- SQL (Data Cleaning and Transformation)
- Python (Correlation Analysis and Predictive Modeling)
- Azure Blob Storage (Data Source)

---

## Project Components

### 1. Production Analysis

- Average Gas-Oil Ratio (GOR) trend across year, quarter, month, and day
- Oil production by well
- Gas production by well
- Water production by well

The analysis highlights production variability across wells and identifies the highest-performing assets.

---

### 2. Cost Analysis

- Operating cost trend over time
- Operating cost distribution by downtime reason
- Operating cost contribution by well

This section evaluates cost drivers and identifies areas of operational inefficiency.

---

### 3. Downtime Analysis

- Downtime distribution by reason
- Average downtime hours by cause
- Equipment utilization analysis

Findings identify power issues and mechanical failures as key contributors to downtime impact.

---

### 4. Correlation Analysis

A correlation heatmap was developed using Python to evaluate relationships between operational variables. The strongest relationship observed was between gas production and operating cost (correlation coefficient: 0.98).

---

### 5. Predictive Modeling

A linear regression model was developed in Python to predict gas production using operating cost as the primary independent variable.

- Model Type: Linear Regression
- R² Score: 82%

The model demonstrates strong explanatory power and can support forecasting and budget planning.

---

## Key Insights

- Gas production is the primary driver of operating cost.
- Mechanical failures result in the longest downtime duration.
- Power issues contribute the highest frequency of downtime events.
- High-producing wells also account for higher cost contribution.
- Increasing water production may indicate reservoir maturity.

---

=======
# Oil-Gas-Data-Analysis
This is an analysis on a dataset related to oil and gas industry which consists of various different parameters. This project is done using Powerbi and data is imported using Azure blob storage. 

Powerbi report link - https://app.powerbi.com/links/E3QlbbcQcl?ctid=b87386c8-9083-4a27-9ddf-63a3dfa33850&pbi_source=linkShare
>>>>>>> c0b986ec90a2962bc27b21b97e59d15d200cabff
