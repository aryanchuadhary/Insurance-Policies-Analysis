Insurance Policies Analysis
### Dashboard 1 - Total Claim Amount
![Dashboard 1 - Total Claim Amount](https://raw.githubusercontent.com/aryanchuadhary/Insurance-Policies-Analysis/main/Screenshot%202025-09-19%20220035.png)

### Dashboard 2 - Total Policies
![Dashboard 2 - Total Policies](https://raw.githubusercontent.com/aryanchuadhary/Insurance-Policies-Analysis/main/Screenshot%202025-09-19%20222251.png)

Project Overview

This project provides a comprehensive analysis of insurance policyholders, their vehicles, and claim patterns to enable data-driven business decisions. The analysis focuses on understanding customer demographics, vehicle characteristics, and claims behavior through interactive Power BI dashboards.

Business Objective

An insurance company seeks to better understand its policyholder base and claim patterns by consolidating scattered policy and claims data into a centralized interactive dashboard. This enables stakeholders to track performance, identify trends, and optimize business decisions.

Dataset Description

The dataset contains detailed information about car insurance policyholders including:

Customer Demographics: Age, gender, marital status, education, income, parental status

Vehicle Information: Make, model, color, year, usage type, coverage zone

Claims Data: Claim amounts, claim frequency, household driving behavior

Each record represents an individual customer with comprehensive attributes for risk profiling and customer segmentation.

Key Performance Indicators (KPIs)

Total Policies - Measures the size of the active customer base

Total Claim Amount - Tracks overall financial impact of claims

Claim Frequency - Analyzes how often claims are made

Average Claim Amount - Assesses claim severity and risk exposure

Gender-wise Total Policies - Understands customer distribution for segmentation

Visualizations & Analysis

The dashboard includes the following charts built around two key dynamic measures: Total Claim Amount and Total Policies:

Primary Analysis Charts

By Car Use (Donut Chart) - Policy distribution and claims by vehicle usage

By Car Make (Bar Chart) - Brand-based risk analysis

By Coverage Zone (Donut Chart) - Geographic risk assessment

By Age Group (Histogram) - Age-based claim patterns

By Car Year (Area Chart) - Vehicle age impact on policies and claims

By Kids Driving (Ribbon Chart) - Young driver impact analysis

By Education (Pie Chart) - Education level correlation with claims

By Education & Marital Status (Matrix Heat Grid) - Combined demographic analysis

Data Dictionary
Field	Type	Description	Business Use
ID	Numeric	Unique policyholder identifier	Data integrity and tracking
Birthdate	Date	Policyholder's date of birth	Age-based risk assessment
Car Color	Categorical	Vehicle exterior color	Pattern analysis and fraud detection
Car Make	Categorical	Vehicle manufacturer/brand	Brand-based claim analysis
Car Model	Categorical	Specific vehicle model	Detailed risk profiling
Car Use	Categorical	Primary vehicle purpose	Usage-based pricing
Car Year	Numeric	Vehicle manufacturing year	Age-based risk assessment
Coverage Zone	Categorical	Geographic risk area	Regional analysis
Education	Categorical	Highest education level	Customer segmentation
Gender	Categorical	Policyholder gender	Demographic analysis
Marital Status	Categorical	Marital status	Risk behavior correlation
Parent	Boolean	Has children (Yes/No)	Family-based risk factors
Claim Amt	Numeric	Total claim amount filed	Loss calculation
Claim Freq	Numeric	Number of claims filed	Risk frequency assessment
Household Income	Numeric	Annual household income	Income-based segmentation
Kids Driving	Numeric	Number of licensed kid drivers	Household risk assessment
Project Structure
insurance-policies-analysis/
├── data/
│   ├── raw/                    # Original datasets
│   ├── processed/              # Cleaned datasets
│   └── README.md               # Data documentation
├── notebooks/                  # Jupyter notebooks for analysis
├── scripts/                    # Python/R scripts for data processing
├── dashboards/                 # Power BI dashboard files (.pbix)
├── docs/                       # Documentation
│   ├── Business Requirements.docx
│   └── Domain Doc.docx
├── results/                    # Analysis outputs and insights
├── requirements.txt            # Python dependencies
└── README.md                   # This file
Key Business Insights

This analysis enables insurance companies to:

Risk Profiling: Identify high-risk customer segments and vehicle types

Premium Optimization: Design fairer pricing models based on risk factors

Customer Segmentation: Target marketing strategies effectively

Fraud Detection: Identify unusual patterns in claims data

Regional Analysis: Understand geographic risk variations

Product Development: Create policies tailored to customer needs

Technologies Used

Power BI - Interactive dashboard development

Python / Pandas - Data processing and analysis

Excel - Data storage and initial analysis

Git - Version control

Installation & Setup

Install dependencies:

pip install -r requirements.txt
Data Setup:

Place raw data files in data/raw/

Run preprocessing scripts from scripts/ folder

Power BI Dashboard:

Open the .pbix files from dashboards/ folder

Connect to processed data sources

Refresh data connections

README updated: Dashboard image links embedded at the top. If you want different image sizes, captions, or to host images elsewhere, tell me which URLs to use and I'll update the file.
