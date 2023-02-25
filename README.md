# Predicting One's Risk of Heart Disease Attack using CDC's Questionnaire
Question/Need:
Heart disease is one of the most common leading causes of death in the US. An early diagnosis can help prevent the majority from succumbing to the disease. With a classification model, it will provide more insight on what influences an individual to be of high risk and give information on preventative measures.
Data:
Data will be collected from the CDC’s annual Behavioral Risk Factor Surveillance System Survey Data for 2021. The data contains information on factors linked to health related chronic injuries, diseases and infectious diseases collected from telephone surveys. https://www.cdc.gov/brfss/annual_data/annual_2021.html
The data contains 438,693 rows each pertaining to a randomly selected individual’s response on multiple factors related to indicators for chronic illness and diseases. Only features related to determining heart disease risk will be used. These features include: blood pressure, cholesterol, diabetes mellitus, BMI, smoking, stroke, diet, physical activity, alcohol consumption, heredity, age, sex, and race/ethnicity. The target is whether an individual has had heart disease or heart attack (myocardial infarction).
Feature selection was determined by CDC’s article on heart disease risk factors.
Tools:
- Pandas
- Matplot lib and Seaborn for visualizations
- Sklearn to build classification model
Pipeline:
1. Data acquisition: CSV file download, clean with pandas
2. Load into SQL database
3. SQL Query to read in pandas
4. EDA: Matplot Lib & Seaborn
5. SkLearn: Build Classification Model
MVP Goal:
To identify individuals who have a high risk of getting a heart attack/heart disease using a predictive classification model.
