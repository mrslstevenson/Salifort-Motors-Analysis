# Salifort-Motors-Analysis
Analysis of Staff Attrition

# Overview
The goal of this project is to identify factors that could assist  management of Salifort Motors in analyzing why they are currently experiencing high staff attrition. A model - Random Forest or XGBoast - was to be created to predict whether or not someone wants to leave the company. 

Both models performed well, with 98% accuracy and 97% precision in the case of the Random Forest model, and 98% accuracy and 96.5% precision in the case of the XGBoost model. Using the model, the company will be able to predict who is likely to leave.

# Business Understanding

Salifort Motors is experiencing high staff turnover and wishes to understand why staff are leaving the company. The immediate requirement is to be able to identify who is likely to leave, so that the appropriate remedial actions can be taken. The cost of staff replacement is high and is a lengthy process.

# Data Understanding

A dataset of 12,000 staff records has been provided for analysis. It includes details of satisfaction level, performance rating, promotions, hours worked per month, projects allocated, salary category, and a flag indicating whether or not the person is still working for the company. 

One of the most puzzling graphs is the following:

![image](https://github.com/user-attachments/assets/e8e378df-6132-4637-8f1c-2ecc1cd457b4)

which shows a strange attrition of staff with excellent performance reviews. Staff with high satisfaction levels leave, as do staff who are incredibly dissatisfied.

There is also a serious imbalance in the number of projects assigned to staff.

![image](https://github.com/user-attachments/assets/4027718e-f93b-4944-b729-9fa0f5e1777a)

All of those who are working on 7 projects leave, and a significant number working on 6 projects leave. They work long hours. Conversely, staff who have only 2 projects to work on and work less hours per month leave. Those with 6 - 7 projects who have left amount to 516 staff, and those who 2 projects amount to 857. This accounts for 69% of the staff who have left!

The Random Forest model selected the follow features of prime importance:
![image](https://github.com/user-attachments/assets/bcbc03de-c021-40fa-b754-7c38a7ba67bf)

This supports the above findings. 

# Conclusion

The model can benefit the company to rapidly identify staff who are most likely to leave. 

The distribution of projects is a serious concern and needs to be further investigated, as does the matter of staff leaving who have good performance reviews. Staff typically leave after between 3 and 5 years. 

The analyis carried out leads to the following questions:
-  Are staff not being adequately rewarded for their hard work?
-  Why have so few staff been promoted? Promotions over the past five years amount to 1.7%.
-  Why is there such disparity between people who have excellent performance reviews? Are staff being correctly accessed?
-  Are staff not correctly skilled that some work such low hours, while others are overworked? One needs further information regarding project complexity to be able to fully understand project demands. The data suggests that being given the many projects requires long working hours. 

It was found that salary has little influence on attrition, as does the department in which staff work. An analysis shows that staff in all departments who are overworked leave. 

No information was provided as to why staff left, and whether the resignation was voluntary. There is also no information about when someone resigned. Is there any periodicity in the data? This could identify a management problem.

Information on project complexity is missing. Such information is necessary to provide a more holistic picture. It would also be interesting to look at the category of staff leaving. 

Support graphs and further insights are provided in the Jupyter notebook. 
