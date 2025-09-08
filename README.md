# Influenza_Season_in_USA
This project creates a data-driven staffing plan for U.S. hospitals during influenza season.

## ABOUT THE PROJECT
Each winter, the United States experiences an influenza season in which flu incidence spikes and a portion of patients, especially those in vulnerable populations—develop complications that require hospitalization. Hospitals and clinics face short‑term surges that outstrip normal staffing levels. A national medical staffing agency supplies temporary clinicians to cover these peaks.
This project builds a data‑driven plan to determine when to send staff and how many to dispatch to each state during the upcoming flu season.

## OBJECTIVE 
Determine when to send staff, and how many, to each state.

## SUCCESS FACTORS
- A staffing plan that utilizes all available agency staff per state requirements, without necessitating additional resources 
- Minimal instances of understaffing and overstaffing across states (a state can be considered understaffed if the staff-to-patient ratio is lower than 90% of the required ratio and overstaffed if greater than 110%

## AGE GROUPS ANALYSIS 
I have divided the influenza death numbers into two age groups: under 65 years old and over 65 years old. By making some analysis we decided to concentrate on the second group, since it supposed to be more vulnerable to deaths from influenza. 

## STAKEHOLDERS
- Hospitals and clinics
- Staffing agency administrators
- Medical agency frontline staff (nurses, physician assistants, and doctors)
- Influenza patients

## GEOGRAPHY 
All 50 U.S. states (aggregate at state level; can extend to HHS regions if useful for modeling).

## HYPOTHESES
Age‑severity gradient: Individuals ≥60 exhibit higher influenza mortality than those <60.

## DATA AND PROCESSING 
The analysis uses two main datasets: CDC Influenza Deaths and U.S. Census data. Files included in the repository reflect cleaning, validation, transformation, and integration steps:

1.) CDC_Influenza_Deaths_Cleaned – cleaned mortality records.

2.) CDC_Influenza_Deaths_Completeness_Uniqueness – quality checks for missing/duplicate data.

3.) US Census data_Cleaned__Completeness_Uniqueness – processed demographic data with quality checks.

4.) Transforming_CDC_Influenza_Deaths_and_US Census data – harmonized datasets for merging.

5.) Combined Datasets_and_Statistics – merged dataset with descriptive statistics.

6.) Combined_Dataset_Hypothesis_and_Statistical Tests – analysis and testing of hypotheses.

7.) Interim Report – summary of findings, methods, and next steps.

## TOOLS 
- Excel for combining several data-sheets, hypothesis testing and analysis
- Tableau for data representation, visualization and reporting

## CONCLUSION AFTER ANALYSIS 
To achieve our objective, I conducted a thorough analysis of data and predictions for the year 2018. Following research, I identified two groups of people and determined the most vulnerable one individuals aged 65 and older. The correlation analysis highlighted a robust relationship between the number of deaths and the population size within this age group. Subsequently, I pinpointed states with the highest incidence of influenza deaths. In addition to predicting influenza deaths for those over 65, I extended our forecasts to individuals under 65.
The next crucial step involves planning for staff allocation, a resource-intensive process, particularly during the influenza season. To guide this allocation effectively, I consider all relevant graphs, charts, and maps highlighting vulnerable areas with the highest influenza death rates. 

## TABLEAU PRESENTATION 
https://public.tableau.com/app/profile/anton.grz/viz/2_9INFLUENZADATASTORY/DATASTORY

## NOTE
The analysis was conducted for educational purposes using publicly available data and fully adheres to privacy policy regulations.
