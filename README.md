# Statistical Analysis: A/B Testing and Machine Learning

This Data Analytics Project focuses on the application of A/B testing and Machine Learning methodologies.

## Project Objective

- The objective is to explore the application of A/B testing and Machine Learning techniques to determine the popularity of different versions among users and uncover relationships between variables.

## Methods Used

- Inferential Statistics
- Data Visualization
- Probability Calculation
- A/B Testing
- Machine Learning

## Model Used

- **Statistical Analysis:**
  - A/B Testing
  
- **Machine Learning:**
  - Logistic Regression
  
## Technologies and Packages Used

- Python, Jupyter Notebook
- Numpy, Matplotlib.pyplot
- Pandas, Statsmodels.api

## Project Description

### Motivation:

- A/B testing is a common practice in data analysis and data science. This project aims to analyze the results of an A/B test conducted by an e-commerce website to assist in decision-making regarding the implementation of a new page or the retention of the old page.

### Data and Scope:

- The dataset consists of approximately 300,000 variables with 5 independent factors initially used in A/B testing. Additional factors are incorporated for analysis using Logistic Regression. The dataset requires no additional cleaning as it is well-organized. Calculating probabilities is a critical step in building a robust model.

### Methodology Approach:

#### Calculated Probability: 
1. Compute the proportion of users converted.
2. Group the dataset with treatment into with/without the new version.
3. Check for duplicates and remove them.
4. Calculate probabilities for each assigned group.
  
#### A/B Testing: 
1. Determine required probabilities for A/B testing.
2. Visualize results with histogram plots.
3. Compute p-value and interpret results.
4. Apply A/B testing with statistical packages to determine testing outcomes.
  
#### Modeling Approach: 
1. Utilize Logistic Regression for categorical dataset.
2. Summarize the Logistic Regression model.
3. Merge with countries data and summarize the model again.
4. Test with additional factors and interpret results.

## Conclusion:

Based on the Calculated Probability, over half of the users show interest in visiting the new_pages, lending credibility to the model. While the conversion rate to the new_pages is approximately 11.96%, it remains acceptable in a business context. Additionally, both the "control" and "treatment" groups have a similar likelihood of receiving the new page, around 12%, suggesting comparable group sizes and conversion rates. Hence, the experimental model appears robust and compelling.

In the A/B Testing results, the p-value stands at approximately 9.6%, exceeding the Type I error threshold of 5%. Consequently, I should retain the null hypothesis (H0). Notably, the control group's actual p-value surpasses that of the treatment group, indicating no overfitting. Given the higher p-value for the old version compared to the new, sticking with the old version is advisable. Moreover, since the probabilities for both new_pages and old_pages usage align, no bias is evident.

Regarding the Modeling Approach, Logistic Regression proves a fitting method, given the categorical nature of the response variables. Incorporating new variables like 'timestamp' could strengthen the results. Specifically, time-based classifications such as 'morning', 'afternoon', and 'evening', as well as 'weekday' versus 'weekend', could be added for improved performance. However, this may introduce complexity, requiring careful scrutiny to ensure variable interdependence. If confirmed, incorporating higher-order terms could enhance predictive accuracy, otherwise, the results remain reliable.


References:
1. https://www.analyticsvidhya.com/blog/2020/10/ab-testing-data-science/
2. https://github.com/alenyeh1014/DataAnalytics-AB_Testing
