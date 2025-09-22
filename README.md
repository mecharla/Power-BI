# 🏥 Patient Waiting List Dashboard – Power BI

## 📌 Project Overview

This Power BI dashboard provides a comprehensive analysis of patient waiting lists, focusing on both Inpatient and Outpatient categories. It offers insights into historical trends, specialty-level analysis, age profiles, and summary metrics, enabling data-driven decision-making for healthcare administrators.

---

## 🎯 Objectives

- **Track Current Status**: Monitor the real-time status of patient waiting lists.
- **Analyze Historical Trends**: Examine monthly trends from 2018 to 2021.
- **Specialty-Level Analysis**: Assess waiting times across various medical specialties.
- **Age Profile Analysis**: Understand waiting times segmented by patient age groups.
- **Key Metrics**: Calculate average and median waiting times, along with total waitlist counts.

---

## 🔄 Process Overview

### 1. Requirement Gathering

- **Stakeholder Identification**: Engage with domain experts and team leads to determine primary stakeholders.
- **Business Objectives Understanding**: Conduct meetings to define goals and understand how the dashboard will support business decisions.
- **High-Level Data Study**: Review data sources, column descriptions, data types, volume, frequency, and data quality (missing values, anomalies).
- **Scope Definition**: Establish key metrics, KPIs, and deployment timelines. Document calculations, time frames, and scope, including a 20% buffer in deadlines.

### 2. Data Collection

- **Data Sources**: Utilize various connectors such as Excel/CSV, SQL Server, Power BI Service, Cloud Platforms (Azure, AWS, GCP), ERP Systems (Salesforce, SAP), SharePoint, and Web or JSON connectors.
- **Data Import**: Import data into Power BI using appropriate connectors and combine datasets as needed.

### 3. Data Transformation

- **Power Query Editor**: Perform data transformations including renaming columns, rearranging columns, adding missing columns, and appending datasets.
- **Data Cleaning**: Address data quality issues by replacing inconsistent values and trimming trailing blanks.

### 4. Data Modeling

- **Relationships**: Create relationships between tables to ensure proper data modeling.
- **Specialty Mapping**: Implement specialty mapping to categorize data effectively.

### 5. Dashboard Design

- **Wireframing**: Create wireframes or sketches of dashboard layout.
- **Stakeholder Approval**: Obtain approval from stakeholders before development.
- **Visual Elements**: Incorporate various visual elements such as KPIs, charts, and tables to represent data effectively.

---

## 📊 Dashboard Insights

### Summary Page

- **Key Metrics**: Display current and previous month's patient wait list counts.
- **Visualizations**:
  - **Donut Chart**: Illustrates the distribution of case types (Inpatient, Day Case, Outpatient).
  - **Bar Chart**: Displays the age profile distribution across different time bands.
  - **Multi-Row Card**: Highlights the top 5 waiting list specialties.
  - **Line Chart**: Shows the monthly trend analysis of Day Case, Inpatient, and Outpatient.

### Detailed View

- **Matrix View**: Showcases the count of outpatients, inpatients, and day cases across specialties, age profiles, and time bands.
- **Filters**: Allows filtering by case type, time duration, and specialty name for granular analysis.

### Tooltip Page

- **Specialty vs. Total Wait List**: Displays a chart illustrating the relationship between specialty and total wait list.
- **Total Sum Card**: Shows the total sum of the wait list.

---

## 📸 Dashboard Screenshots

### Summary Page

![Summary Page](https://github.com/mecharla/Power-BI/blob/main/Output.jpg)

---

## ✅ Conclusion

The Patient Waiting List Dashboard empowers hospital management to make data-driven decisions for optimizing resource allocation, improving patient care, and enhancing operational efficiency. By leveraging insights from the dashboard, stakeholders can prioritize interventions, streamline processes, and ensure timely access to healthcare services for patients.

---
