![JanataHack-HR-Analytics-thumbnail-1200x1200](https://user-images.githubusercontent.com/25604111/81655259-bbab8d00-9453-11ea-9b99-209a919133c1.png)


# HR_Analytics_AnalyticsVidhya

Link to the competition [here](https://datahack.analyticsvidhya.com/contest/janatahack-hr-analytics/).

## Problem Statement
A training institute which conducts training for analytics/ data science wants to expand their business to manpower recruitment (data science only) as well.

Company gets large number of signups for their trainings. Now, company wants to connect these enrollees with their clients who are looking to hire employees working in the same domain. Before that, it is important to know which of these candidates are really looking for a new employment. They have student information related to demographics, education, experience and features related to training as well.

To understand the factors that lead a person to look for a job change, **the agency wants you to design a model that uses the current credentials/demographics/experience to predict the probability of an enrollee to look for a new job.**

## Data Dictionary

| __Variable__ | __Description__ |
|-------------|------------|
| enrollee_id         | Unique ID for enrollee     |
| city         | City code |
| city_development_index | Developement index of the city (scaled) |
| gender | Gender |
| relevent_experience | Relevent experience |
| enrolled_university | Type of University course enrolled if any |
| education_level | Education level |
| major_discipline | Major discipline |
| experience | Total experience in years |
| company_size | No of employees in current employer's company |
| company_type | Type of current employer |
| last_new_job | Difference in years between previous job and current job |
| training_hours | training hours completed |
| target | 0 – Not looking for job change, 1 – Looking for a job change |


## Evaluation Metric
The evaluation metrics for this competition is [ROC AUC Score](http://scikit-learn.org/stable/modules/generated/sklearn.metrics.roc_auc_score.html).

## Leaderboard
**Public Leaderboard:** 37/326

**Private Leaderboard:** 49/326



