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

### Interpretation:
Since p = 0.2161 is greater than 0.05, we fail to reject the null hypothesis.
This means there is no statistically significant difference between the conversion rates of the control and treatment groups.
The new layout did not lead to a meaningful improvement in conversions based on this test.

Cohen’s h = 0.005, suggesting a small effect size, meaning that while the difference is significant, the impact may not be substantial in practical terms.

## Tools Used
- Python: Pandas, SciPy, Statsmodels, Seaborn, Matplotlib
- SQL for querying conversion rates
- Git for version control


------------------------------------------------------------------------------------------------------------------------------------------------

Project Overview
This project analyzes an A/B test conducted on an e-commerce website to determine if a new webpage layout increases conversion rates. Using statistical hypothesis testing (Z-test) and effect size measurement (Cohen’s h), we assess whether the difference in conversions between the control and treatment groups is statistically significant.

📂 Dataset
The dataset contains user interactions with the website, including:

Number of users in the control and treatment groups
Conversions (purchases made) for both groups
Total users exposed to each version of the webpage
Dataset Summary:
Group	Total Users	Conversions	Conversion Rate
Control	147,276	17,514	11.89%
Treatment	147,202	17,723	12.04%
🔬 Hypothesis Formulation
Null Hypothesis (H₀): The new webpage layout does not significantly affect conversion rates.
Alternative Hypothesis (H₁): The new layout leads to a significant change in conversion rates.
🛠️ Methodology & Statistical Analysis
Exploratory Data Analysis (EDA) – Checking data integrity and basic statistics.
Statistical Hypothesis Testing – Using a Z-test for proportions to compare conversion rates.
Effect Size Measurement – Calculating Cohen’s h to measure the practical impact.
Result Interpretation – Analyzing the p-value and confidence intervals.
Visualization – Using Matplotlib & Seaborn to plot conversion distributions.
📊 Results & Findings
Z-Statistic: -1.237
P-Value: 0.2161
Cohen’s h: 0.007 (very small effect size)
Key Takeaways:
✅ The p-value (0.2161) is greater than 0.05, meaning we fail to reject the null hypothesis.
✅ This indicates no statistically significant difference between the control and treatment groups.
✅ The new webpage layout did not significantly impact conversions.
✅ Future improvements could include segmenting users, running a longer experiment, or A/B testing with additional features.

🖥️ Technologies & Tools Used
Python: Pandas, NumPy, SciPy, Statsmodels
Data Visualization: Matplotlib, Seaborn
Statistical Analysis: Z-test, Cohen’s h
Version Control: Git, GitHub
📌 How to Run the Project
Clone this repository:
bash
Copier
Modifier
git clone https://github.com/your-username/AB-Testing-Ecommerce-Conversion.git
cd AB-Testing-Ecommerce-Conversion
Install dependencies:
bash
Copier
Modifier
pip install pandas numpy scipy statsmodels matplotlib seaborn
Run the Jupyter Notebook to perform analysis:
bash
Copier
Modifier
jupyter notebook
Open AB_Testing_Ecommerce.ipynb and execute the cells.
📜 Future Work & Recommendations
Run the experiment for a longer duration to capture more user behavior.
Segment users based on location, device type, or purchase history.
Perform Bayesian A/B Testing for more robust insights.
Evaluate user engagement metrics (time spent, pages visited) along with conversions.
📄 License
This project is open-source under the MIT License.
