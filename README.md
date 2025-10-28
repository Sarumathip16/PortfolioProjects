Financial & COVID-19 Impact Analysis Using SQL & Tableau

Author: Sarumathi Palanisamy

📊 Overview

This project analyzes the global financial and health impact of the COVID-19 pandemic using SQL for data analysis and Tableau for visualization.
It highlights how COVID-19 affected total cases, death rates, and the percentage of population infected across continents — providing actionable insights into regional resilience and recovery patterns.

The dashboard visualizes key metrics such as:

Global Totals: Cases, Deaths, and Death Percentage

Continental Trends: Total Deaths per Continent

Country-Level Insights: Percent Population Infected per Country (Geospatial View)

Time-Series Analysis: Monthly infection trends and recovery trajectories

📁 Dataset

The dataset includes COVID-19 case and death statistics sourced from open global repositories (e.g., WHO, Johns Hopkins).
Key Columns:

Location – Country/Region

Date – Timeline of record

Total_Cases – Confirmed cases till date

Total_Deaths – Recorded fatalities

Population – Total population by country

Continent – Regional grouping

🧮 Tools & Technologies

SQL (PostgreSQL / MySQL) – Data extraction, cleaning, and aggregation

Tableau – Dashboarding and visualization

Excel / CSV – Initial data structuring and validation

🧠 Steps Followed
1. Data Preparation (SQL)

Cleaned and standardized global COVID-19 data.

Created calculated fields for:

Death Percentage = (Total_Deaths / Total_Cases) * 100

Percent Population Infected = (Total_Cases / Population) * 100

Aggregated results by Continent and Month for temporal comparison.

2. Data Visualization (Tableau)

Developed a comprehensive interactive dashboard featuring:

KPI Cards: Global Total Cases, Deaths, and Death Percentage

Bar Chart: Total Deaths per Continent

Map View: Percent Population Infected per Country

Line Chart: Infection Growth over Time (Month-wise, by Country)

📈 Insights & Findings

Europe and North America recorded the highest total deaths.

United States, United Kingdom, and India showed significant infection growth between 2020–2021.

Death rate remained around 2% globally, despite regional fluctuations.

Visualized data revealed a strong correlation between population density and infection rate.

🎯 Outcomes

Delivered a global COVID-19 dashboard for executive and research use.

Enabled data-driven understanding of pandemic spread and recovery timelines.

Demonstrated data storytelling through visualization connecting SQL-based metrics to real-world public health outcomes.

🛠️ Skills Demonstrated

SQL, Tableau, Data Cleaning, Aggregation, Time-Series Analysis, KPI Design, Data Visualization, Storytelling
