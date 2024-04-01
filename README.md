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

- Calculated Probability results indicate over 50% of users are willing to use the new page, making the model persuasive. Although the conversion rate to the new page is around 11.96%, it is acceptable in the business context. A/B Testing results suggest retaining the old version as the p-value is higher than the Type I error. Additionally, Logistic Regression proves effective for analyzing categorical variables, and adding new variables enhances the model's performance.
