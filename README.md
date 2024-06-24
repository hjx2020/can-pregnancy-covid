# Impact of COVID-19 Concerns on Pregnancy Outcomes

## Overview
Hey there!
This project explores the impact of maternal concerns about COVID-19 on prenatal mental health and pregnancy outcomes using data from Canadian annual birth estimates and a Canadian survey on pregnancy during the COVID-19 pandemic (2020-2021). It first analyzes trends in Canadian birth estimates after the pandemic breakout using prior-pandemic data, and then examines the relationship between COVID-19 concern/fear and prenatal mental health (depression and anxiety symptoms), and a set of birth outcome metrics (birth weight, length, gestational age, delivery mode, and NICU admission).
 

## Project Structure
Here’s how I’ve organized everything:
- `pregnancy_data_analysis.ipynb`: This is the Jupyter Notebook where all the magic happens - data preparation, analysis, and visualization.
- `data/`: This folder contains the datasets I used:
  - `OSFData_Upload_2023_Mar30.csv`: Survey data on pregnancy during the COVID-19 pandemic.
  - `annual_birth_can.csv`: Annual birth estimates in Canada.
  - `conversion_promis.csv`: Conversion table for PROMIS anxiety raw scores to t-scores.
  - `df1.csv`, `df2.csv`, `df3.csv`: Three post-processed data frames used for analysis of the three questions in Section 2, respectively.
- `standardized_sem.png`: The graph of the CFA model created from R-lavaan package (for demonstration).

## Analysis Structure
- Section 1: Canada Birth Data Trend Analysis
  - Data: Annual birth estimates in Canada (1971-2023)
  - Analysis: Trends and anomalies in birth estimates, with a focus on the impact of the COVID-19 pandemic
  - Methods: ARIMA model for forecasting
- Section 2: Maternal COVID-19 Concerns, Mental Health and Birth Outcomes Analysis
  - Data: PdP survey data during COVID-19 (2020-2021)
  - Analysis: Impact of COVID-19 fear on maternal mental health (anxiety, depression) and birth outcomes (gestational age, birth weight, birth length)
  - Methods: Exploratory data analysis, reliability and factor analyses (confirmatory and exploratory), multiple linear and generalized linear regression models

## Key Findings
- Maternal fear/concern related to COVID-19 significantly relates to the presence of prenatal depressive and anxiety symptoms.
- Socioeconomic factors and language differences influence the level of COVID-19 fear.
- Higher level of COVID-19 fear is associated with shorter gestational age, lower birth weight, and shorter birth length.

## Conclusion
This study provides valuable insights into the negative impact of the COVID-19 pandemic on maternal mental health and pregnancy outcomes. Understanding the relationships between COVID concern and mental health and their impacts on birth outcomes can help healthcare providers and policymakers develop more effective outreach and strategies to support expectant mothers, both physically and mentally, during public health crises.

## Contact
If you have any questions or feedback, feel free to reach out!
