# A/B Testing on E-commerce Website Conversions

## Overview
This project analyzes the results of an A/B test conducted on an e-commerce website to evaluate whether a new layout increases conversion rates. 

## Dataset
The dataset contains user interactions with the website, including which group (control/treatment) the user belongs to, whether they converted (made a purchase), and other details like the timestamp and landing page.

## Analysis Steps
1. **Exploratory Data Analysis (EDA)**: 
   - Load and inspect the data.
   - Calculate conversion rates for control and treatment groups.
   
2. **Hypothesis Testing**: 
   - Perform a Z-test to assess whether the new layout significantly improves conversions.

3. **Effect Size (Cohen's h)**: 
   - Measure the practical impact of the treatment group compared to the control group.

4. **Visualization**: 
   - Plot conversion rates and distributions.

## Results
- The p-value for the hypothesis test was 0.21612, indicating that the new layout does not significantly improves conversions.
- Cohen's h was -0.005, suggesting a small effect size.

# Interpretation:
Since p = 0.2161 is greater than 0.05, we fail to reject the null hypothesis.
This means there is no statistically significant difference between the conversion rates of the control and treatment groups.
The new layout did not lead to a meaningful improvement in conversions based on this test.

## Tools Used
- Python: Pandas, SciPy, Statsmodels, Seaborn, Matplotlib
- SQL for querying conversion rates
- Git for version control
