# Fragile States Index (FSI) – Global Dashboard (2022 & 2023)

📌 **Project Overview**

<img width="1122" height="747" alt="image" src="https://github.com/user-attachments/assets/f7f52147-51f3-466e-80b1-e464786e5d66" />


This project analyses the Fragile States Index (FSI) for 2022 and 2023 using Microsoft Power BI. The goal is to compare country-level fragility, identify year-on-year changes, examine the 12 indicators contributing to state fragility, and explore the countries experiencing the highest levels of fragility.

The dashboard provides an interactive overview of global fragility through KPI cards, country comparisons, indicator analysis, ranking charts, and a world map. It aims to make complex data easier to understand and support meaningful comparisons between countries and across years.



## 🛠️ Project Workflow

### 🔹 Steps in Project

- **Requirement Gathering** – Understand the FSI assignment requirements and identify the key areas for analysis, including overall fragility scores, year-on-year changes, indicator performance, country rankings, and geographical distribution.
- **Data Collection** – Obtain the 2022 and 2023 Fragile States Index datasets from The Fund for Peace.
- **Data Cleaning & Quality Check** – Check for missing values, review data types, standardise country names, ensure consistent year formats, and convert ranking values into numeric format.
- **Data Transformation** – Use Power Query to clean and combine the 2022 and 2023 datasets into a single table, including a Year column to distinguish between both periods.
- **Data Modelling** – Prepare the combined FSI dataset for analysis and create the necessary supporting tables and relationships.
- **Exploratory Data Analysis (EDA)** – Examine overall FSI scores, country-level changes, indicator performance, and the distribution of fragility across countries.
- **KPI Development** – Create DAX measures to calculate average FSI score, highest FSI score, lowest FSI score, country-level scores for each year, and year-on-year score changes.
- **Year-on-Year Analysis** – Compare 2022 and 2023 FSI scores to identify countries experiencing increased or reduced fragility.
- **Indicator Analysis** – Analyse the 12 FSI indicators to understand the different social, economic, political, and security-related pressures affecting countries.
- **Country Deep Dive** – Examine individual country performance through year-specific FSI scores and indicator comparisons.
- **Geographic & Ranking Analysis** – Explore global fragility through country maps, ranking comparisons, and Top 10 ranking movements.
- **Dashboard Design** – Develop an interactive Power BI dashboard with KPI cards, slicers, charts, and a world map using a consistent visual theme.
- **Insight Generation** – Interpret the results to highlight changes in fragility scores, countries with significant improvements or deterioration, and key indicators contributing to fragility.

## 📊 Dashboard & Metrics

### 📈 KPI Requirements

- **Average FSI Score** – Overall average FSI score across the selected data.
- **Highest FSI Score** – Highest recorded FSI score, indicating a high level of fragility.
- **Lowest FSI Score** – Lowest recorded FSI score, indicating a relatively more stable condition.

### 🔹 Chart Requirements

- **Top 5 Countries with Greatest Deterioration** (Horizontal Bar Chart)
- **Top 5 Countries with Greatest Improvement** (Horizontal Bar Chart)
- **Average FSI Indicator Scores** (Column Chart)
- **Top 10 Most Fragile Countries** (Horizontal Bar Chart)
- **Global Fragility Distribution by Country** (World Map)
- **Year-on-Year FSI Score Change by Country** (Comparison Chart)
- **Country-Level FSI Comparison** (2022 vs 2023)
- **Indicator Score Comparison** (2022 vs 2023)

### 🎛️ Interactive Features

- **Year Filter** – Explore FSI data for 2022 and 2023.
- **Country Filter** – Focus on an individual country's FSI performance.
- **Dynamic KPI Cards** – View changes in average, highest, and lowest FSI scores based on selected filters.
- **Interactive Charts** – Explore country scores, indicator performance, and ranking comparisons.
- **World Map** – Examine the geographical distribution of FSI scores across countries.

## 💡 Key Analytical Areas

- **Overall Fragility** – Examine average, highest, and lowest FSI scores to understand the overall level of fragility.
- **Year-on-Year Changes** – Identify countries with increased or reduced FSI scores between 2022 and 2023.
- **Indicator Performance** – Compare the 12 indicators to explore the different pressures affecting countries.
- **Country-Level Analysis** – Investigate individual countries and compare their scores across both years.
- **Global Rankings** – Identify the most fragile countries and examine changes in the Top 10 rankings.
- **Geographical Distribution** – Use the world map to explore how fragility scores are distributed across countries.

**Interpreting FSI Changes:**

- A positive score change indicates an increase in fragility.
- A negative score change indicates a reduction in fragility.
- A score change of zero indicates no change in the overall score.

These interpretations follow the FSI scoring direction, where higher scores indicate greater fragility and lower scores indicate greater relative stability.

## 🛠️ Tools & Technologies

- **Microsoft Power BI** – Dashboard development and data visualization.
- **Power Query** – Data cleaning, transformation, and dataset combination.
- **DAX (Data Analysis Expressions)** – KPI calculations, year-specific measures, and year-on-year comparisons.
- **Microsoft Excel** – Dataset inspection and preparation.
- **GitHub** – Project documentation and portfolio presentation.

## 📂 Dataset

The project uses the **Fragile States Index (FSI)** datasets for 2022 and 2023, published by The Fund for Peace.

Source datasets used:

- `fsi-2022-download.xlsx` – Historical FSI dataset filtered to 2022.
- `FSI-2023-DOWNLOAD.xlsx` – FSI dataset for 2023.

The combined dataset contains country information, year, overall FSI score, ranking, and 12 individual indicators:

| Indicator | Description                |
| --------- | -------------------------- |
| C1        | Security Apparatus         |
| C2        | Factionalized Elites       |
| C3        | Group Grievance            |
| E1        | Economic Decline           |
| E2        | Uneven Development         |
| E3        | Human Flight & Brain Drain |
| P1        | State Legitimacy           |
| P2        | Public Services            |
| P3        | Human Rights               |
| S1        | Demographic Pressures      |
| S2        | Refugees and IDPs          |
| X1        | External Intervention      |

Each indicator is scored from 0 to 10. The overall Total score has a maximum of 120, with higher scores representing greater fragility. Rank 1 represents the most fragile country.

**Official Data Source:** [The Fund for Peace – Download FSI Data](https://fragilestatesindex.org/excel/)

## 🎯 Project Objectives

- Develop practical skills in Microsoft Power BI and DAX.
- Apply data cleaning and transformation techniques using Power Query.
- Understand and analyse the Fragile States Index and its 12 indicators.
- Perform year-on-year comparisons using real-world country-level data.
- Develop an interactive dashboard for data analysis and reporting.
- Improve data visualization and analytical storytelling skills.
- Build a portfolio project demonstrating foundational data analytics and business intelligence skills.

📢 **Note:** This is a personal portfolio project developed to practise data analytics, data visualization, and business intelligence using Power BI. The analysis is based on the 2022 and 2023 Fragile States Index datasets published by The Fund for Peace. The dashboard presents comparisons and patterns in the available data and should not be interpreted as a complete explanation of the political, economic, social, or security conditions of individual countries.
