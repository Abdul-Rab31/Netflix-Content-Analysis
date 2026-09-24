# Netflix Content Analytics Dashboard
### End-to-End Data Analytics Project

## 📊 Dashboard Preview

![Netflix Content Analytics Dashboard](3_Dashboard%20Screenshot/Netflix%20Content%20Analysis.png)

> An interactive Power BI dashboard for analyzing Netflix movies and TV series based on content type, release year, genres, ratings, and production countries.

## 📑 Table of Contents

- [📌 Project Overview](#-project-overview)
- [🎯 Project Objective](#-project-objective)
- [❓ Business Problem](#-business-problem)
- [📂 Dataset Information](#-dataset-information)
- [🛠️ Tools & Technologies](#-tools-&-technologies)
- [⚙️ Project Workflow](#-project-workflow)
- [📊 Dashboard Pages & Features](#-dashboard-pages--features)
- [📈 Key Insights](#-key-insights)
- [💡 Business Recommendations](#-business-recommendations)
- [📁 Project Structure](#-project-structure)
- [💼 Skills Demonstrated](#-skills-demonstrated)
- [📚 Key Learnings](#-key-learnings)
- [🔮 Future Improvements](#-future-improvements)
- [📸 Dashboard Screenshots](#-dashboard-screenshots)
- [👤 Author](#-author)
- [⭐ Closing Note](#-closing-note)

## 📌 Project Overview

The Netflix Content Analytics Dashboard is an interactive Power BI project designed to analyze Netflix movies and TV series across different dimensions such as content type, release year, genres, ratings, and production countries.

The project follows an end-to-end data analytics workflow, including data cleaning and transformation using Power Query, data modeling, DAX calculations, and interactive dashboard development.

The dashboard provides a clear visual overview of Netflix's content library and helps users explore content trends through interactive charts, KPI cards, and slicers.

## 🎯 Project Objective

The main objective of this project is to build an interactive Power BI dashboard that provides meaningful insights into Netflix's content library.

The project aims to:

- Analyze the distribution of Movies and TV Series on Netflix.
- Identify content trends across different release years.
- Analyze the most common genres available on the platform.
- Understand the distribution of content across different rating categories.
- Identify the countries with the highest number of Netflix titles.
- Calculate key KPIs such as Total Titles, Movies, TV Series, Genres, Countries.
- Provide interactive filters that allow users to explore the data based on Type, Rating, Genre, Release Year, and Production Country.

## ❓ Business Problem

Netflix has a large and diverse content library consisting of Movies and TV Series from different genres, countries, release years, and rating categories.

Analyzing this large dataset manually can make it difficult to identify important content trends and patterns.

This project addresses the following business questions:

- How many total titles are available on Netflix?
- What is the distribution between Movies and TV Series?
- How has Netflix content changed across different release years?
- Which genres have the highest number of titles?
- Which rating categories are most common?
- Which countries produce the highest number of Netflix titles?
- How can users interactively explore Netflix content using filters?

The dashboard transforms raw Netflix data into an interactive visual analytics solution to make these questions easier to explore and understand.

## 📂 Dataset Information

The project uses a Netflix content dataset containing information about Movies and TV Series available on the platform.

### Dataset Includes

The dataset contains information such as:

- Show ID
- Title
- Type
- Rating
- Rating Category
- Duration
- Genre
- Production Country
- Release Year
- Release Date
- Movie Duration (Hours)
- Number of Seasons

### Data Preparation

The raw dataset was cleaned and transformed using Power Query before being used for dashboard development.

The data preparation process included:

- Cleaning and standardizing column values.
- Handling missing and unavailable values.
- Creating calculated columns required for analysis.
- Converting duration information into numerical movie duration in hours.
- Creating the Rating Category field.
- Creating the Number of Seasons field for TV Series.
- Creating a separate Date Table for time-based analysis.
- Establishing a relationship between the Date Table and Netflix Dataset using Release Date.

The cleaned dataset was then used to create the Power BI data model, DAX measures, and dashboard visualizations.

## 🛠️ Tools & Technologies

The following tools and technologies were used to develop this project:

| Tool / Technology | Purpose |
|---|---|
| **Microsoft Power BI** | Dashboard development and data visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | KPI calculations and analytical measures |
| **Microsoft Excel / CSV** | Dataset storage and initial data handling |
| **GitHub** | Project version control and portfolio hosting |
| **Visual Studio Code** | README and project documentation |

### Power BI Features Used

- KPI Cards
- Line Chart
- Donut Chart
- Bar Charts
- Column Chart
- Slicers
- Data Model & Relationships
- DAX Measures
- Date Table

## ⚙️ Project Workflow

The project was developed through an end-to-end data analytics workflow:

### 1. Data Collection
- Imported the Netflix dataset into Power BI.
- Reviewed the available columns and data types.

### 2. Data Cleaning & Transformation
- Cleaned and standardized the dataset using Power Query.
- Handled missing and unavailable values.
- Prepared duration-related fields for analysis.
- Created Rating Category and Number of Seasons fields.
- Created Movie Duration (Hours) for movie analysis.

### 3. Data Modeling
- Created a dedicated Date Table for time-based analysis.
- Added Date, Year, Month, Month Number, and Year Month fields.
- Created a relationship between the Date Table and Netflix Dataset using Release Date.

### 4. DAX Calculations
Created DAX measures for key performance indicators, including:
- Total Titles
- Total Movies
- Total TV Series
- Total Genres
- Total Countries

### 5. Dashboard Development
Created interactive Power BI visualizations including:
- KPI Cards
- Line Chart
- Donut Chart
- Bar Charts
- Column Chart
- Interactive Slicers

### 6. Dashboard Validation
- Checked visual interactions and filters.
- Verified KPI calculations.
- Reviewed chart sorting and formatting.
- Ensured the dashboard provides a clear overview of Netflix content.

## 📊 Dashboard Pages & Features

### 📄 Dashboard Page 1 — Netflix Content Analytics

The dashboard provides a single-page interactive view of Netflix content.

### KPI Cards

The dashboard includes key performance indicators for:

- Total Titles
- Total Movies
- Total TV Series
- Total Genres
- Total Countries

### Visualizations

#### 📈 Titles by Release Year
A line chart showing the distribution of Netflix titles across different release years.

#### 🍩 Movies vs TV Series
A donut chart comparing the proportion of Movies and TV Series in the dataset.

#### 📊 Top 10 Genres
A bar chart highlighting the most frequently occurring genres.

#### ⭐ Titles by Rating Category
A column chart showing the distribution of Netflix titles across rating categories.

#### 🌎 Top 10 Production Countries
A bar chart showing the countries contributing the highest number of Netflix titles.

### 🎛️ Interactive Filters

Users can interact with the dashboard using slicers for:

- Type
- Rating
- Genre
- Release Year
- Production Country

These filters allow users to explore specific segments of Netflix's content library.

## 📈 Key Insights

The dashboard provides several useful insights into Netflix's content library:

- Movies represent a larger share of the content library compared with TV Series.
- The dataset contains a diverse collection of genres, ratings, and production countries.
- Netflix content distribution varies significantly across release years.
- A relatively small group of genres contributes a large portion of the available titles.
- The production country analysis highlights the geographic diversity of Netflix content.
- Rating categories provide an overview of the type of content available for different audience segments.
- Interactive slicers make it possible to analyze Netflix content from multiple perspectives.
- KPI measures provide a quick summary of the overall content library.

## 💡 Business Recommendations

Based on the analysis provided by the dashboard, the following areas can be considered for further business analysis:

- Monitor content trends across release years to understand changes in the Netflix content library.
- Analyze popular genres when planning future content acquisition and production strategies.
- Compare Movies and TV Series to understand the overall content mix.
- Use production country analysis to identify opportunities for regional content expansion.
- Analyze rating categories to understand the distribution of content across different audience segments.
- Use interactive dashboard filters to perform targeted content analysis for specific genres, countries, ratings, or years.
- Track changes in the content library over time to support data-driven content planning.

## 📁 Project Structure

```text
Netflix Project/
│
├── 1_Dataset/
│   └── Netflix Dataset.csv
│
├── 2_PowerBI/
│   └── Netflix Content Analytics.pbix
│
├── 3_Dashboard Screenshot/
│   └── Netflix Content Analysis.png
│
└── README.md
```
## 💼 Skills Demonstrated

This project demonstrates the following technical and analytical skills:

- Data Cleaning and Transformation
- Power Query
- Data Modeling
- Data Visualization
- DAX
- KPI Development
- Time-Based Analysis
- Business Intelligence
- Interactive Dashboard Development
- Data Analysis and Interpretation
- Dashboard Design and Formatting
- GitHub Project Documentation

## 📚 Key Learnings

Through this project, I gained practical experience in:

- Understanding and cleaning real-world datasets.
- Using Power Query for data transformation and preparation.
- Creating a structured data model in Power BI.
- Building and connecting a Date Table with the main dataset.
- Writing DAX measures for business KPIs.
- Using filter context and CALCULATE for analytical calculations.
- Designing interactive dashboards using different visualization types.
- Creating meaningful charts to communicate data insights.
- Using slicers to enable interactive data exploration.
- Structuring and documenting a complete data analytics project.

## 🔮 Future Improvements

The project can be further enhanced with additional analysis and features such as:

- Adding more detailed content-level analysis.
- Creating trend analysis for newly added and removed titles.
- Adding advanced genre and country-level comparisons.
- Including additional KPIs and analytical measures.
- Adding more advanced DAX calculations.
- Introducing drill-through pages for detailed content analysis.
- Adding tooltip pages for enhanced visual insights.
- Automating data refresh with an updated data source.
- Publishing the dashboard to Power BI Service for online access.

## 📸 Dashboard Screenshots

### Netflix Content Analytics Dashboard

![Netflix Content Analytics Dashboard](3_Dashboard%20Screenshot/Netflix%20Content%20Analysis.png)

> Interactive Power BI dashboard showcasing Netflix content analysis across Movies, TV Series, Genres, Ratings, Release Years, and Production Countries.

## 👤 Author

### ABDUL RAB

Aspiring Data Analyst passionate about transforming raw data into meaningful insights using data analytics and visualization tools.

**Skills:** Power BI | SQL | Excel | Python | Data Analytics | Data Visualization

---

🔗 **GitHub:** [ABDUL RAB](https://github.com/Abdul-Rab31)

🔗 **LinkedIn:** [Connect with me](https://www.linkedin.com/in/abdul-rab-b1a88837b/?isSelfProfile=true)

## ⭐ Closing Note

Thank you for exploring the Netflix Content Analytics Dashboard!

This project represents my practical application of data cleaning, data modeling, DAX, data visualization, and business intelligence using Microsoft Power BI.

I hope this project demonstrates how raw data can be transformed into an interactive and meaningful analytics solution.

⭐ If you find this project useful, feel free to explore the repository and share your feedback.
