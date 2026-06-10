# 🚚 Delhivery Feature Engineering & Logistics Analytics

## 📌 Overview

This project analyzes Delhivery's shipment and logistics data to transform raw operational records into business insights and machine-learning-ready features. The work includes data cleaning, trip-level aggregation, exploratory data analysis, feature engineering, statistical testing, and operational performance evaluation.

---

## 🎯 Objective

The main goals of this project are to:

* Clean and validate shipment data
* Aggregate segment-level records into trip-level observations
* Engineer meaningful logistics features
* Compare actual performance with OSRM estimates
* Identify delivery bottlenecks and route inefficiencies
* Generate business recommendations for operational improvement

---

## 📊 Dataset

The dataset contains information related to:

* Shipment Trips
* Source & Destination Locations
* Actual vs Estimated Delivery Time
* Actual vs Estimated Distance
* Route Type (FTL / Carting)
* Scan Start & End Times

The raw data consists of more than 26,000 shipment records that were processed and aggregated for analysis.

---

## 🔧 Project Workflow

### Data Preprocessing

* Missing value treatment
* Duplicate removal
* Datetime conversion
* Data validation

### Feature Engineering

Created features such as:

* Source & Destination States
* Shipment Corridors
* Weekday Information
* Trip Duration Metrics
* Route Performance Indicators

### Exploratory Data Analysis

* Distribution Analysis
* Correlation Analysis
* Route Performance Evaluation
* Corridor-Based Analysis

### Statistical Analysis

* Hypothesis Testing
* Outlier Detection & Treatment
* Feature Encoding
* Feature Scaling

---

## 📈 Key Insights

* Carting shipments dominate the logistics network compared to FTL routes.
* High-delay corridors include:

  * Punjab → Karnataka
  * Maharashtra → Assam
  * Delhi → Assam
  * Karnataka → Haryana
* Actual delivery performance differs significantly from route estimates, indicating operational delays beyond travel distance.
* Engineered duration features showed strong correlation and consistency.

---

## 💡 Business Recommendations

* Improve ETA prediction models using historical operational data.
* Focus optimization efforts on high-delay interstate corridors.
* Monitor route-type performance for better resource allocation.
* Leverage engineered features for predictive logistics models.

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Scikit-Learn
* Jupyter Notebook

---

## 🚀 Skills Demonstrated

* Data Cleaning
* Feature Engineering
* Exploratory Data Analysis
* Statistical Testing
* Data Visualization
* Logistics Analytics
* Business Insight Generation

---

## 📌 Conclusion

This project converts raw logistics shipment data into a structured analytical dataset, uncovering delivery patterns, operational bottlenecks, and opportunities for improving route efficiency and ETA prediction. The final dataset is suitable for both business analysis and future machine learning applications.

## Author

Ritesh
Data Scientist
