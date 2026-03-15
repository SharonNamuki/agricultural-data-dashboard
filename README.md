# Agricultural Data Dashboard and Visualization System
## Project Overview

This project demonstrates the development of a data pipeline, analytical dashboard, and visualization system for agricultural production data. The system extracts, cleans, and analyzes crop production data to generate insights on agricultural trends in Africa, with a focus on root and staple crops such as potatoes, sweet potatoes, cassava, and maize.

The project uses publicly available agricultural datasets to demonstrate how data engineering workflows, visualization dashboards, and analytical tools can support agricultural research, food security analysis, and data-driven decision making.

This type of analytical system can support organizations working in agricultural research and development by transforming raw agricultural datasets into actionable insights and interactive visualizations.

### Objectives

The objectives of this project are to:

Develop a data pipeline to ingest and process agricultural datasets

Perform data cleaning and transformation to prepare datasets for analysis

Analyze crop production trends across East African countries

Build visualization dashboards that communicate agricultural insights

Demonstrate the use of data engineering, data analysis, and visualization systems for agricultural data

### Dataset

The dataset used in this project comes from the Food and Agriculture Organization FAOSTAT database.

#### Dataset: Crops and Livestock Products

The dataset contains agricultural production statistics including:

Country / Region

Crop Type

Production Quantity

Harvested Area

Yield

Year of Production

For this analysis, the dataset was filtered to include:

Selected East African countries

Key staple crops including potatoes, sweet potatoes, cassava, and maize

Production data from 2004 to 2024

These crops are important for food security and agricultural development across East Africa.

### Project Workflow

The project follows a structured data engineering and analysis workflow:

#### 1. Data Acquisition

Agricultural production data was downloaded from the FAOSTAT database and imported into Python for analysis.

#### 2. Data Cleaning and Transformation

Using Python and Pandas:

Missing values were checked and handled

Data types were standardized

Relevant variables were selected

Crops and countries of interest were filtered

The dataset was transformed into a structured format suitable for analysis

#### 3. Data Analysis

Exploratory Data Analysis (EDA) was conducted to identify patterns and trends in crop production across different countries and time periods.

#### 4. Visualization and Dashboard Development

Data visualization tools were used to generate charts and dashboards that communicate key insights about agricultural production trends as shown below.
http://localhost:8888/tree/Images
### Technologies Used

This project uses the following technologies:

#### Programming Language

Python

#### Data Analysis Libraries

Pandas

NumPy

#### Data Visualization

Matplotlib

Seaborn

#### Dashboard Tools

Tableau 
https://public.tableau.com/app/profile/sharon.nyakeya/viz/east_africa_agriculture_dashboard/Dashboard1

Development Environment

Jupyter Notebook
http://localhost:8888/notebooks/East_Africa_Agriculture_Analysis.ipynb
Version Control

GitHub

#### Key Visualizations

The project includes several visualizations designed to highlight important agricultural trends.

Examples include:

1. Total agricultural Production by Country(2004-2024)

A time series visualization showing production changes for key crops across multiple years.

2. Top Crop Producing Countries

A comparison of the leading African countries in crop production.

3. Crop Comparison Analysis

A visualization comparing production levels across different staple crops such as potatoes, cassava, maize, and sweet potatoes.

4. Country-Level Agricultural Production

A breakdown of crop production by country to identify regional patterns.

Repository Structure
agricultural-data-dashboard
│
├── data
│   └── faostat_agriculture_data.csv
│
├── notebooks
│   └── agricultural_data_analysis.ipynb
│
├── dashboards
│   └── dashboard_screenshots.png
│
├── README.md
│
└── requirements.txt

The project implements a simple data pipeline consisting of the following stages:

Data ingestion from the FAOSTAT dataset

Data cleaning and transformation

Filtering relevant crops and countries

Data analysis and feature preparation

Visualization and dashboard generation

This workflow demonstrates the use of data engineering and analytics pipelines for processing agricultural datasets.

Potential Applications

This type of system can support organizations involved in:

Agricultural research

Food security monitoring

Crop production analysis

Agricultural policy planning

Development programs

By transforming raw agricultural data into structured analytics and dashboards, stakeholders can make more informed decisions about agricultural production and food systems.

Future Improvements

Future improvements to this project could include:

Building automated API data pipelines to continuously update datasets

Deploying interactive dashboards online

Integrating machine learning models to forecast crop production trends

Adding geospatial visualizations of agricultural data

Expanding the analysis to include climate and weather datasets

### Author

Sharon Namuki Nyakeya

Data Scientist | Data Analyst | Data Platform Developer

LinkedIn:
https://www.linkedin.com/in/mkism-sharon-b3a668192/

GitHub:
https://github.com/SharonNamuki

### License

This project is for educational and research purposes and uses publicly available agricultural datasets.