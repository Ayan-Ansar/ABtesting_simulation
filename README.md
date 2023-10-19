# A/B Testing and Hypothesis Testing with Python

This repository contains a Python notebook that demonstrates how to perform A/B testing, hypothesis testing, and regression analysis using Python libraries such as pandas, numpy, statsmodels, and seaborn. The notebook provides step-by-step explanations and code for conducting these analyses.

## Contents

The notebook is divided into several sections:

1. **Power Analysis**: This section discusses power analysis and how to determine the sample size required for an A/B test.

2. **Data Generation**: The notebook simulates data for an A/B test with variables such as user ID, group assignment, and conversion status. Two dataframes for the control and treatment groups are created.

3. **Sample Ratio Mismatch (SRM) Check**: A chi-square test is performed to check for Sample Ratio Mismatch. The null hypothesis is that the observed data follows the expected distribution.

4. **A/B Testing**: The notebook formulates null and alternative hypotheses for A/B testing, calculates observed conversion rates, and simulates a null hypothesis distribution. The p-value is calculated to determine if there's a statistically significant difference.

5. **Regression Approach**: Logistic regression is used to analyze the impact of group assignment on conversion rates. The notebook explains how to set up the regression model and interpret the results.

## Conclusion

The Python notebook demonstrates how to perform A/B testing and hypothesis testing, including power analysis and regression analysis. The results indicate a statistically significant difference in conversion rates between the control and treatment groups. The repository can be used as a reference for conducting similar analyses and understanding the statistical concepts involved.

Feel free to explore the notebook and use it as a resource for your own A/B testing projects.

## Getting Started

To run the notebook and reproduce the analysis, you'll need to have Python and the required libraries installed. Here are the steps:

1. Clone the repository to your local machine.
2. Open the Python notebook in a Jupyter Notebook or Jupyter Lab environment.
3. Run the cells in the notebook sequentially to perform the analysis.

Make sure you have the necessary libraries installed by running:

```bash
pip install -r requirements.txt


## Author

[Ayan Ansar](http://https://github.com/Ayan-Ansar)

