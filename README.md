# Salifort-Motors-Analysis
Analysis of Staff Attrition

# Overview
The goal of this project was to identify factors that could assist  management of Salifort Motors in analyzing why they are currently experiencing high staff attrition. A model - Random Forest or XGBoast - was to be created to predict whether someone wants to leave the company. 

An analysis of the data was carried out and several factors of concern identified. The company has a high level of people leaving who receive an excellent performance review and are highly satisfied, which is unusual. Staff are also not correctly utilized, in that some have few projects and work minimal hours, while others have 6 - 7 projects and work very long hours.

Both models performed well, with 98% accuracy and 97% precision in the case of the Random Forest model, and 98% accuracy and 96.5% precision in the case of the XGBoost model. Using the model, the company can predict who is likely to leave.

# Business Understanding

Salifort Motors is experiencing high staff turnover and wish to understand why staff are leaving the company. The immediate requirement is to be able to identify who is likely to leave, so that the appropriate actions can be taken. The cost of staff replacement is high and replacement is probably a lengthy process.

# Data Understanding

A dataset of 12,000 staff records has been provided for analysis. It includes details of satisfaction level, performance rating, promotions, hours worked per month, projects allocated, salary category, and a flag indicating whether or not the person is still working for the company. There is no indication given though as to whether the person left voluntarily or not. 

One of the most puzzling graphs is the following:

![image](https://github.com/user-attachments/assets/e8e378df-6132-4637-8f1c-2ecc1cd457b4)

which show that high attrition of staff with high satisfaction levels and excellent performance. 

A full analysis is available in the accompanying report and in the Jupyter notebook.

The Random Forest model selected the follow features of prime importance:
![image](https://github.com/user-attachments/assets/bcbc03de-c021-40fa-b754-7c38a7ba67bf)

# Conclusion

The model can benefit the company to rapidly identify staff who are most likely to leave. 

The points of concern highlighted are worth investigating further to identify the underlying problems and to build a holistic picture of the issues within the company.
