# Engineering Performance Metrics Dashboard | Power BI

## Project Overview

The **Engineering Performance Metrics Dashboard** is an interactive analytics solution built using **Power BI** to monitor and analyze engineering and project delivery performance.

This dashboard provides insights into key engineering metrics such as productivity, predictability, team size, and project performance across multiple product groups. The objective is to help stakeholders track engineering efficiency, monitor delivery trends, and support data-driven decision making.

---

## Business Objective

The goal of this project is to provide a centralized dashboard that enables organizations to:

- Monitor engineering team performance
- Track project delivery metrics
- Analyze productivity and predictability trends
- Compare performance across product groups
- Identify potential operational bottlenecks

These insights support engineering leaders and project managers in improving delivery efficiency and project planning.

---

## Dashboard Structure

The Power BI report contains **three main pages**, each designed to analyze different aspects of engineering performance.

### 1. Engineering Performance Overview

This page provides a high-level overview of engineering performance metrics across projects and product groups.

Key insights include:

- Overall engineering performance trends
- Metric comparisons across product groups
- Monthly performance analysis
- High-level KPI monitoring

---

### 2. DAPS Engineering Metrics

This page focuses on engineering performance metrics related to **DAPS projects**.

Key analysis includes:

- Metric trends by month
- Project-level performance analysis
- Product group comparisons
- KPI tracking for engineering performance

---

### 3. BSI Engineering Metrics

This page analyzes engineering metrics related to **BSI projects**.

Key insights include:

- Monthly engineering performance trends
- Product group performance analysis
- Project-level KPI monitoring
- Comparative performance evaluation

---

## Dataset Structure

The dataset used in this project consists of multiple tables that capture engineering metrics and project details.

### Measures Data

Contains performance metrics tracked over time.

Fields include:

- Metrics Type
- Month Name
- Month Number
- Product Group
- Project
- Value
- Trend Line
- Last Refresh

---

### Measures Data BSI

Stores performance metrics specific to BSI projects.

Fields include:

- Metrics Type
- Month Name
- Month Number
- Product Group
- Project
- Value
- Average Value

---

### Project Details

Contains metadata about projects and engineering teams.

Fields include:

- Project
- Project ID
- Product Group
- Product Owner
- HCL Lead
- POD / Non POD classification
- Project Type
- Team Size
- Start Date
- End Date
- Current Milestone

---

### Project Details BSI

Stores project information specific to BSI projects.

Fields include:

- Project
- Project ID
- Product Group
- Product Owner
- HCL Lead
- POD / Non POD
- Project Type
- Team Size
- Start Date
- End Date
- Current Milestone

---

## Key Metrics Analyzed

The dashboard analyzes several engineering performance indicators including:

- Productivity
- Predictability
- Engineering performance metrics
- Project team size
- Monthly performance trends
- Product group performance comparison

---

## Tools & Technologies Used

| Tool | Purpose |
|-----|------|
| Power BI | Dashboard development and visualization |
| DAX | Analytical calculations and KPI measures |
| Power Query | Data transformation |
| Excel | Data source |

---

## Dashboard Features

The dashboard includes several interactive analytics features:

- KPI performance monitoring
- Monthly trend analysis
- Product group comparison
- Project-level performance analysis
- Interactive filters and slicers
- Dynamic data visualization

Users can filter insights by:

- Product Group
- Project
- Metrics Type
- Time period

---

## Repository Structure

```
Engineering-performance-metrics-dashboard
│
├── Dax Measures
├── Dataset.csv
├── README.md
├── Engineering-performance-metrics-dashboard.pbix
└── Engineering-performance-metrics-dashboard.pdf
```

---


---

## Dashboard Preview

A preview of the dashboard is available in the repository:

`Engineering-performance-metrics-dashboard.pdf`

Download the **.pbix file** to explore the full interactive report in **Power BI Desktop**.

---

## Author

Hemavalli Mannemuddu

---

⭐ If you found this project useful, consider giving the repository a star.
