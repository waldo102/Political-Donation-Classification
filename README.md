# Political-Donation-Classification
Goal: Classify higher-income earners based on personal characteristics for the purposes of fundraising the most amount of money for a political campaign

Data: adult_data.txt
  * contains 15 variable and 32k observations

Files:
  * political_donation_classification.ipynb - performs data cleaning, data preparation, data analysis, and also model specifications and hyperparameter tuning.
  
Models:
  * Decision Tree Classifier
  * Support Vector Classifier
  * Ada Boost Classifier

Performance Metrics:
  * Classification Accuracy
  * Precision
  * Recall
  * F-Score
  
Results:

The three models performed very similarily:

 * Decision Tree (81% Accuracy, 0.61 F-Score)
 * Support Vector (84% Accuracy, 0.68 F-Score).
 * AdaBoost (86% Accuracy, 0.71 F-Score)

Conclusions:

The AdaBoost model edged out the other models in terms of accuracy and runtime performance. It is a very accurate model that scales well to 
larger amounts of data. A naive model would perform with 76% accuracy. The improvement in accuracy of 10% is significant enough to
use the AdaBoost model to predict high-income earners in order to target them for political fundraising purposes.

In addition, according to the data, the most important variables that predict high-income earners are the following:

 1. Age
 2. Capital Gain/Loss
 3. Work hours (per week)
 
This political campaign should target older people, that work longer hours and are involved in the buying and selling of asseets.
Intuitively, it makes sense and the data corroborates the intuition. 
In the future, it would beneficial to narrow down the pool of potential donors by analyzing, by demographics, which people are more likely to support the campaign.
Coupled with this analysis, the research would be effective in maximizing campaign contributions and keeping costs down by targeting promotional information more effectively.  

For more details on the analysis of this project, please read and follow the analysis in the jupyter notebook file political_donation_classification.ipynb 

*Resources: This project was part of Rajeev D. Ratan's course, Data Science & Deep Learning for Business™ 20 Case Studies as presented in udemy.com*
