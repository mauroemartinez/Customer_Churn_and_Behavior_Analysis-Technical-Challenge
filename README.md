# 📉 Customer Churn & Behavior Analysis (Technical Challenge)

### [📊 View Dashboard Preview (GIF)](https://raw.githubusercontent.com/mauroemartinez/Customer_Churn_and_Behavior_Analysis-Technical-Challenge/main/Pictures/Preview.gif)
**Context:** This project was developed as part of a Technical Challenge for a Business Intelligence / Data Analyst position.

<p align="center">
  <img src="https://raw.githubusercontent.com/mauroemartinez/Customer_Churn_and_Behavior_Analysis-Technical-Challenge/main/Pictures/Preview.gif" alt="Churn Analysis Demo" width=85%>
</p>

**Stack:** ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) ![Power Query](https://img.shields.io/badge/Power_Query-217346?style=flat-square&logo=powerbi&logoColor=white) ![DAX](https://img.shields.io/badge/DAX-0176D3?style=flat-square&logo=microsoft&logoColor=white)

## 📋 Executive Summary
The goal of this analysis was to identify patterns in customer retention and churn for a digital platform. I processed raw user data to extract insights regarding demographics, geographical concentration, and platform-specific behavior, providing actionable recommendations to reduce attrition.

## 🧠 Strategic Insights (Business Case)
* **Platform Disparity:** **Android** represents the vast majority of the user base. This sparked two key hypotheses:
    * **Market Positioning:** Is the product perceived as "non-premium," failing to attract iOS users?
    * **Technical Gap:** Is the iOS app poorly optimized or missing from the App Store?
* **Peak Engagement:** Installation peaks occur between **11:00 PM and 1:00 AM**, suggesting a late-night consumer profile. I recommended shifting marketing efforts to these "golden hours" to maximize conversion.
* **Geographical Concentration:** Over **50% of the customer base** is concentrated in Buenos Aires, CABA, and Córdoba, suggesting a need for regional expansion or hyper-localized loyalty programs.
* **Churn Critical Point:** The data shows zero churn in Month 1, but a significant drop-off (82 customers) between Month 2 and Month 3, identifying a critical window for re-engagement campaigns.

## 🎨 User Experience (UX) & Navigation
To ensure high usability for non-technical stakeholders, I designed a **Navigation Hub** on the main page.
* **Interactive Menu:** Using bookmarks and action buttons, users can seamlessly navigate between demographic visualizations, geographical heatmaps, and final business conclusions.
* **Drill-through Logic:** The dashboard is built to guide the user from macro-trends (national churn) to micro-insights (city-level behavior) with just a few clicks.

## 🛠️ Data Engineering & Modeling
* **Data Cleaning:** Implemented a robust mapping system in **Power Query (M)** to standardize Argentinian province names (e.g., fixing accents and CABA nomenclature) for better maintenance and reporting.
* **Gender Analysis:** Identified a slight female majority. Recommended specialized segments (similar to *Santander Women*) to leverage this trend.
* **Automation:** Designed a process to handle raw CSV exports and transform them into a Star Schema for real-time analysis.

## 🏗️ Data Model
The report utilizes a specialized Star Schema to track cohorts and installation timing, allowing for granular filtering by province and city.

<p align="center">
  <img src="https://raw.githubusercontent.com/mauroemartinez/Customer_Churn_and_Behavior_Analysis-Technical-Challenge/main/Pictures/Data%20Model.png" alt="Churn Data Model" width=90%>
</p>

---
**Author:** Mauro Ezequiel Martínez  
**Focus:** Data Analytics | Business Intelligence | Customer Success
