# 🚆 UK Train Rides – Data Analysis & Insights

## ✨ Project Overview
This project, developed as part of the **Digital Egypt Pioneers Initiative (DEPI)**, undertakes a comprehensive analysis of UK railway data. The primary objective is to transform raw, complex data into actionable insights, identifying key drivers of train delays and cancellations, understanding passenger booking behavior, and enhancing operational efficiency through data-driven recommendations.

The project encompasses the full data analysis lifecycle, from meticulous data preprocessing to the development of an interactive business intelligence dashboard.

## 👥 Team Members
- **Hamed Abdelaziz** --> Lead Data Analyst, Data Model Design, Data Cleaning, Visualization Lead, Project Manager
- **Ahmed Sayed** --> Data Engineer (Data Collection & Preprocessing)
- **Amira Reda** --> Database & Analytics Support
- **Ethar Mostafa** --> BI Developer (Dashboard & Presentation)
- **Shahd Mohamed** --> Data Analyst (Exploratory Analysis & Insights)
- **Mohamed Saber** --> Data Analyst (Exploratory Analysis)

## 📌 Detailed Project Description
This project goes beyond basic reporting, diving deep into UK Train Rides data to extract strategic insights. Key aspects include:
-   **Robust Data Cleaning & Preprocessing:** Extensive handling of missing values, data type conversions, and standardization of categorical data (e.g., delay reasons) using Python (Pandas) and Power Query to ensure data quality.
-   **Advanced Feature Engineering:** Creation of over 10 insightful new features such as `Delay_Minutes`, `Booking_Lead_Time`, `Part_of_Day`, `Is_Weekend`, and a unique `Journey_Route` identifier to enrich the dataset for deeper analysis.
-   **Star Schema Data Modeling:** Designed a robust Star Schema within Power BI, establishing a central Fact table (`railway_cleaned`) linked to various Dimension tables (e.g., `Dim_Dates`, `Dim_Journey`, `Dim_Status`) for efficient query performance and comprehensive analysis.
-   **Interactive Dashboard Development:** Creation of a multi-page Power BI dashboard, leveraging advanced functionalities like **dynamic Navigation Panels, Bookmarks, interactive Buttons, Custom Tooltips, and thematic Icons** to provide an intuitive and engaging user experience. The dashboard's diverse visual styles were intentionally designed to showcase a wide range of Power BI capabilities.
-   **Key Performance Indicator (KPI) Analysis:** Development of critical DAX measures for KPIs like `Total Delay (Minutes)`, `Cancellation Rate`, `Average Delay (per Journey)`, and `Revenue` to monitor and assess railway performance.

## 💡 Key Insights Uncovered
-   **Top Delay Causes:** Identified the most frequent reasons for train delays (e.g., Signal Failures, Weather Conditions) and their specific impact on different routes.
-   **Time-Based Patterns:** Revealed significant variations in average delays and cancellation rates during specific times of day (e.g., Rush Hours) and days of the week (e.g., higher delays on Fridays).
-   **Route Performance:** Pinpointed critical routes exhibiting the highest average delays and cancellation rates, enabling targeted operational improvements.
-   **Booking Behavior:** Analyzed the correlation between `Booking_Lead_Time` and journey reliability, providing insights into passenger planning versus service punctuality.

## 📊 Deliverables
-   Cleaned and Feature-Engineered Dataset (`.csv`)
-   Python Analysis Notebooks (`.ipynb`)
-   Power BI Dashboard (`.pbix`)
-   Comprehensive Data Model Documentation
-   Final Project Report & Presentation

## 🔗 Raw Data
[https://drive.google.com/drive/folders/10qkQ_meaAc-xPzfNngZDwpeieyj3tDBh?usp=drive_link](https://drive.google.com/drive/folders/10qkQ_meaAc-xPzfNngZDwpeieyj3tDBh?usp=drive_link)

## 🛠️ Tech Stack
-   **Python:** Pandas (Data Manipulation), Matplotlib & Seaborn (Exploratory Analysis)
-   **Microsoft Excel:** Data Cleaning, Basic Transformation
-   **SQL:** (If used for initial data extraction/querying)
-   **Microsoft Power BI:** Power Query (ETL), DAX (Measures & Calculations), Data Modeling (Star Schema), Visualization & Dashboard Design
-   **Git & GitHub:** Version Control & Collaboration

---

## 📅 Project Timeline (15th September - 15th November)

This timeline outlines the key phases and milestones achieved during the project development.

| Phase                | Start Date   | End Date     | Key Activities & Deliverables                                                                                              |
| :------------------- | :----------- | :----------- | :----------------------------------------------------------------------------------------------------------------------- |
| **1. Data Exploration** | 15/09/2023   | 25/09/2023   | - Initial data loading and inspection (shape, dtypes, missing values).<br>- Basic descriptive statistics.<br>- Identify initial data quality issues. |
| **2. Data Cleaning** | 26/09/2023   | 10/10/2023   | - Handle missing values (imputation/removal).<br>- Correct data types.<br>- Standardize categorical entries (e.g., `Reason for Delay`).<br>- Address outliers and inconsistencies.<br>- **Deliverable:** `cleaned_railway.csv`                                                      |
| **3. Feature Engineering & EDA** | 11/10/2023   | 25/10/2023   | - Create new insightful columns (`Delay_Minutes`, `Booking_Lead_Time`, `Route`, `Day Name`, `Is_Weekend`, `Part_of_Day`, `Is_Rush_Hour`, `Is_Cancellation`, `Month`).<br>- Perform in-depth Exploratory Data Analysis (EDA) to uncover preliminary insights and patterns using Python.<br>- **Deliverable:** Analysis Notebooks with new features. |
| **4. Data Modeling** | 26/10/2023   | 05/11/2023   | - Design and implement a Star Schema in Power BI.<br>- Create Dimension tables (e.g., `Dim_Dates`, ``Dim_Journey`, `Dim_Status`).<br>- Establish relationships between Fact and Dimension tables.<br>- **Deliverable:** Power BI Data Model Structure. |
| **5. Visualization & Dashboard Development** | 06/11/2023   | 15/11/2023   | - Develop key DAX measures for KPIs and Time Intelligence.<br>- Design and build interactive dashboards and reports in Power BI.<br>- Incorporate advanced UI elements (Nav Panels, Bookmarks, Tooltips, Thematic Icons).<br>- **Deliverable:** Final Power BI Dashboard (`.pbix`). |
