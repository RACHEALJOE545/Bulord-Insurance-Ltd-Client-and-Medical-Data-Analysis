# Bulord-Insurance-Ltd-Client-and-Medical-Data-Analysis


<img width="792" height="412" alt="Screenshot 2025-10-21 105317" src="https://github.com/user-attachments/assets/f89690c1-b041-44f8-a657-6b9238df40ba" />


## Introduction:

This project explores and analyzes the client and medical datasets of Bulord Insurance Ltd to uncover factors that may influence insurance charges.

The goal is to identify the relationships between client demographics, health metrics (like BMI and age), and insurance costs — providing data-driven insights that can guide fairer pricing models and customer segmentation.


## Problem Statement:

- Insurance providers often struggle with balancing affordability and profitability due to poor understanding of client       risk profiles.
  
- This analysis was conducted to:

1. Examine how demographic and health variables (age, gender, BMI, smoking habits, region) influence insurance charges.

2. Identify key risk factors contributing to higher medical costs.

3. Explore client patterns that can inform future predictive models for risk assessment.
   

## Objectives:

- Perform data cleaning and handle missing values effectively.

- Conduct univariate, bivariate, and multivariate analyses to explore relationships among variables.

- Apply visualization techniques using Python libraries to interpret client and medical data.

- Prepare the dataset for potential machine learning modeling in later stages.
  

## Key Metrics:

- How many clients and medical records were analyzed in total?

- What is the average age and BMI distribution among clients?

- Which regions have the highest number of insured clients?

- How do gender proportions vary across the dataset?

- What is the relationship between age and medical charges?

- Do smoking habits significantly impact insurance costs?

- Which factors jointly (e.g., age, BMI, smoking) influence charges the most?
  

## Skills and Concepts Demonstrated:

- Data Cleaning & Preprocessing: Handling missing data using fillna() and dropna() methods.

- Data Encoding: Transforming categorical variables using LabelEncoder.

- Exploratory Data Analysis (EDA):

1. Univariate Analysis — distributions and frequencies.

2. Bivariate Analysis — correlations between two variables.

3. Multivariate Analysis — joint relationships between three or more variables.

- Visualization Techniques: Histograms, boxplots, scatter plots, count plots, and pie charts using matplotlib and seaborn.

- Statistical Understanding: Central tendency (mean, median), variability (standard deviation), and category proportions.


## Libraries Used:

- pandas
- numpy
- matplotlib
- seaborn
- sklearn.preprocessing (LabelEncoder)


## Data Visualizations:

<img width="523" height="414" alt="Screenshot 2025-10-21 105629" src="https://github.com/user-attachments/assets/64110ff1-0ab0-4067-873c-7792e871c133" />

<img width="690" height="461" alt="Screenshot 2025-10-21 105604" src="https://github.com/user-attachments/assets/a5f30932-0818-4fa4-a771-ae03b9376b25" />

<img width="786" height="541" alt="Screenshot 2025-10-21 105513" src="https://github.com/user-attachments/assets/dd7dda03-5a02-4691-aae9-62426ea889e0" />



## Analysis Interpretation:

- Age Distribution: Most clients are middle-aged, suggesting active working-class participants.

- BMI Insights: Slight right-skew indicating higher BMI levels in some clients, which may relate to higher risk.

- Gender Distribution: Fairly balanced with no extreme dominance of a gender group.

- Regional Distribution: Some regions (like Southeast and Northwest) show higher client counts, implying strong market        penetration.

- Smoking and Charges: Smokers tend to have significantly higher medical charges, aligning with expected health risks.

- Multivariate Findings: Combined effects of BMI, smoking status, and region strongly influence charges.


## You can interact with the notebook here: 
https://colab.research.google.com/drive/1EmggnnbKWJAriyWUd9PYkdn_2DqzPV0J?usp=sharing


## Conclusions:

- Health risk factors such as BMI and smoking play major roles in driving up insurance costs.

- Regional and demographic variables can serve as proxies for risk segmentation.

- The analysis highlights the importance of personalized insurance pricing models rather than flat rates.

- Data cleaning and visualization form a critical foundation before deploying predictive models.


 ## Recommendations:

- Adopt a tiered pricing model based on lifestyle and region.

- Encourage non-smoking policies through lower premiums or health reward programs.

- Further modeling: Train a regression or classification model to predict insurance charges more accurately.

- Continue data enrichment to include more health indicators for better predictive power.
