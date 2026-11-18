# hs4002-beagle-2026
HS4002 Team Beagle
Members: Claire, Gabriel, Ryan, Xavier
## Economic Insecurity and Justifiability of Norm Violations in Southeast Asia
Research question: To what extent is deprivation associated with the perceived justifiability of economic norm violations, compared to personal norm violations?
## What this project is

This project examines whether economic insecurity, measured as material deprivation, is associated with how justifiable people find economic norm violations (e.g. cheating on taxes, claiming government benefits one is not entitled to) compared with personal norm violations (e.g. divorce, premarital sex).

We use World Values Survey (WVS) Wave 7 data for seven Southeast Asian countries: Indonesia, Malaysia, Myanmar, the Philippines, Singapore, Thailand and Vietnam.

## Method
We estimate survey-weighted OLS (WLS) regressions for each country and for the pooled sample (with country fixed effects), controlling for income, social class, religiosity, age, gender and education. We also run robustness checks using rank-transformed outcomes, a narrower personal-norms index and alternative religiosity measures.

## Structure of the Repository
- data/raw/:          Trimmed WVS extract (input)
- code/:              Final project code.ipynb (all cleaning, models, tables and figures)
- output/tables/:     Regression tables and robustness checks (.csv / .txt)
- output/figures/:    Figures used in the paper (.png)
- slides/:            Presentation slides

## Data
The data for this assignment was taken from the World Values Survey Wave 7 (2017-2022), v6.0.0 (https://www.worldvaluessurvey.org/WVSDocumentationWV7.jsp).

The file was trimmed to include only the countries and variables of interest. The trimmed extract (`data/raw/WVS_Survey_Trimmed_2.csv`) is in data, raw folder. 

## Code 
https://github.com/clairetanyien/hs4002-beagle-2026/blob/main/code/final%20project%20code.ipynb

Order of the code:
1. Data Cleaning and Rescalling
2. OLS Models
3. Robustness Checks and Controls
4. Data Visualisation and Forest Plots 
