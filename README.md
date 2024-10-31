# Medical Charge Predictions

This R project investigates the factors influencing medical charges using statistical analysis methods. The goal is to provide insights into which features are most predictive of medical expenses, aiding in understanding cost drivers in healthcare.

## Project Overview

This project was undertaken with the aim to dissect and understand the key factors influencing medical charges through rigorous data analysis and predictive modeling. Utilising a dataset encompassing 1,338 individual entries, the study meticulously analysed various demographic and health-related factors to ascertain their impact on health insurance costs.

## Data Description

The dataset contains 1,338 instances and 7 attributes related to health insurance costs (can be viewed [here](./insurance.csv)). Here are the details of each attribute:

- **Age**: The age of the primary beneficiary (numeric; ranging from 18 to 64 years).
- **Sex**: The gender of the insurance contractor, recorded as 'female' or 'male'.
- **BMI**: Body Mass Index, which provides an understanding of body weight relative to height. It is used as a risk indicator for health (numeric; ranging from 15.96 to 53.13).
- **Children**: The number of children covered by health insurance (numeric; ranging from 0 to 5 children).
- **Smoker**: Indicates whether the beneficiary smokes, with values 'yes' or 'no'.
- **Region**: The beneficiary's residential area in the US, categorized into four regions: 'northeast', 'southeast', 'southwest', or 'northwest'.
- **Charges**: Individual medical costs billed by health insurance (numeric; ranging from approximately $1,121.87 to $63,770.43).

## Objectives

1. **Data Preprocessing**: Prepare the data for analysis by cleaning and structuring.
2. **Exploratory Data Analysis (EDA)**: Visualise and summarise data characteristics and relationships.
3. **Predictive Modeling**: Build a linear model to predict medical charges based on the identified predictors.

## Tools and Libraries Used

- **R**: The main programming language used for the analysis.
- **Base R**: Utilised for general data manipulation and analysis tasks.
- **Stats package**: Employed for building and summarising the linear model.

## Conclusion

Throughout this project, a comprehensive analysis of health insurance costs was conducted using a rich dataset of 1,338 individuals. Key insights were revealed through exploratory data analysis, highlighting the significant influence of factors such as age, BMI, smoking status, and the number of children on medical charges. Notably, it was found that smoking status is a significant predictor of higher costs, followed by age and BMI.

Predictive modeling was primarily executed through linear regression, which underscored the impact of these variables on medical charges. The performance of the model, indicated by R-squared values and residual plots, suggested a decent fit, although areas for improvement were identified. These improvements could potentially be achieved through more complex models or by incorporating interaction terms and non-linear relationships.

This project has not only enhanced our understanding of the determinants of health insurance costs but also provided a foundational basis for further research. Future exploratory avenues might include the use of more sophisticated machine learning techniques to improve predictive accuracy and the analysis of additional factors such as geographic differences and lifestyle variables.

The insights gained from this study could prove invaluable for insurance companies in setting premiums, for individuals in managing their health expenses, and for policymakers in designing interventions that target high-risk groups.

In conclusion, this study highlighted the intricate relationship between health-related attributes and medical charges, demonstrating the power of data science in navigating these complexities to make informed decisions. The importance of such research continues to grow as healthcare costs rise and the need for effective risk management strategies becomes more critical.
