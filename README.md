# diabetes_mellitus_predict
This is the 2021 datathon challenge hosted by Women in Data Science on https://www.kaggle.com/c/widsdatathon2021/overview/datathon-phase-2-excellence-in-research-award. 

# Purpose:
Develop a classification model that use ICU data to predict diabetes mellitus. 

# Steps:
1. Cleaning data
    * Delete NANs
    * Delete duplications
    * Turn categorical variables to dummy variables
    * Not all medical tests are done in each patients. Therefore, there are a lot of NAN values in medical test columns. Create dummpy variables for these medical tests to indicate whether these medical tests are done (0 is not done and 1 is done).

2. Data Analysis
    * How many patients are diagnosed with diabete mellitus? (more non-diagnosed than diagnosed)
    * Correlation between features?
    * Logistics regression vs. Random Forests 

