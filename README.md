# Global Health Data Dashboard — Tableau
An interactive Tableau dashboard project visualising simulated global health data across 16 countries, built as part of my transition from clinical medicine into health data analytics.
## Project Overview
This project uses a curated, realistic health dataset to explore disease burden, patient outcomes, and health system indicators across Africa, the Americas, Asia, and Europe. It demonstrates end-to-end data visualisation skills in Tableau — from raw data to a polished, interactive dashboard.
## Dataset
Three interconnected tables simulating real-world health data:
- Patient_Records Table: 500 rows; Individual patient admissions with clinical and demographic variables
- Country_Indicators Table: 16 rows; Population-level health system metrics per country
- Disease_Surveillance Table: 1,008 rows; monthly disease case counts and deaths over 24 months (2022-2023)

Key variables include: diagnosis, disease category, severity, outcome, length of stay, cost, age, sex, BMI, haemoglobin, insurance status, latitude/longitude, U5 mortality, maternal mortality, TB/HIV/malaria incidence, health expenditure % GDP, physician density, life expectancy.

## Charts Built
Dashboard 1 — Epidemiological Overview
	- Heatmap — Seasonal disease case patterns by month
	- Choropleth Map — Under-5 mortality rate by country
	- Area Chart — Disease burden trends over 24 months
	- Scatter Plot — Health expenditure vs. life expectancy (with trend line)
	- Dual Axis Chart — Monthly malaria cases vs. deaths
Dashboard 2 — Patient Clinical Summary
	- Symbol Map — Patient distribution across countries
	- Bar Chart — Diagnoses ranked by patient volume
	- Histogram — Patient age distribution (5-year bins)
	- Box Plot — Length of hospital stay by severity level
	- Packed Bubble Chart — Patient volume by region and diagnosis
## Tools Used
- Tableau Public — Data visualisation and dashboard design
- Microsoft Excel — Dataset storage (3-sheet workbook)

## Key Insights
	- Nigeria carries the highest under-5 mortality burden (114 per 1,000 live births) among all 16 countries
	- A positive correlation exists between health expenditure (% GDP) and life expectancy — with African nations clustering in the low-spend, low-life-expectancy quadrant
	- Malaria, cholera and dengue show clear seasonal peaks, consistent with known transmission patterns
	- Severe cases have a median length of stay 3–4x longer than mild cases, with significant outliers
	- Sepsis and HIV/AIDS account for the highest patient volumes in the dataset

## Learning Objectives
This project was built to develop proficiency in:
	- Connecting and relating multiple data tables in Tableau
	- Choosing appropriate chart types for different data structures
	- Building cohesive, multi-chart dashboards with consistent formatting
	- Using Tableau’s Analytics pane (trend lines, reference lines, forecasting)
	- Applying health data storytelling principles to visual design

## Project Files
- <a href="https://public.tableau.com/app/profile/patricia.mbabazi.mugabe/viz/Globalhealthdashboard-PatientClinicalSummary/PatientClinicalSummary">Patient Clinical Summary Dashboard</a>
- <a href="https://public.tableau.com/app/profile/patricia.mbabazi.mugabe/viz/Globalhealthdashboards/EpidemiologicalOverview">Epidemiological Overview Dashboard</a>

## About
I am a medical doctor (MBChB) transitioning into health data analytics. This project is part of my ongoing portfolio development combining clinical domain knowledge with data skills in Excel, SQL, and Tableau.

Dataset is simulated for learning purposes. Values are based on real-world epidemiological benchmarks but do not represent actual patient data.
  
