# Rare event detection and dashboarding for industrial applications

| Presenter | Date | Slides | Code |
|:---------:|:----:|:------:|:----:|
| Brandon Bagley | 2019-02-22 | [slides](2019_02_22_KnoxData_Talk.pdf) | [code](2019_02_22_KnoxData_Code.ipynb) |

## Abstract

Gauges, sensors, and IOT devices in industrial production facilities such as water treatment have been Key Performance Indicators (KPI's) used to measure and optimize performance. With modern data ingestion platforms and analytic solutions we can decrease the time between alarming KPI's and action, increase performance through increased optimization and reduce down-time by predicting failures before they occur. Working with a large water treatment company, Cloudreach implemented these performance improvements, and built a production environment that predicts rare cleaning events using historical device readings, institutional knowledge, and predictive analytics. Working with the subject matter experts within the clients' organization we identified the minimum number of sensors at sites within the portfolio to detect events, engineered features, and created an XGBoost logistic regression binary classification model for tagging events with a positive predictive value >= 88% (Note the events have ~0.5% prevalence). From the tagged values, the Cloudreach team was able to create a Tableau dashboard to identify previously unavailable metrics and visualizations to reduce plant downtime at over 200 sites, more accurately allocate on-site resources, and provide additional information for process analysts.

## About Presenter

Brandon Bagley is a Data Scientist at Cloudreach. He obtained his Master's in Geology with a minor in Statistics at the University of Tennessee, Knoxville.

He currently works at Cloudreach to provide machine learning solutions to customers who would like to leverage their big data to add value to their organization.