# Insurance Analysis Documentation


## Introduction

This work aim to investigate the relationship between liquidity risk and the financial performance indicators (return on assets and return on equity) of selected insurance companies in Lagos. The primary goal is to evaluate the impact of liquidity risk on the profitability and solvency of these companies.

## Objectives


The objective aim of this study is to examine the effect of liquidity risk on the financial performance of selected insurance companies in Lagos. The specific objectives include
* To assess the impact of liquidity risk on insurance companies' return on assets.
* To investigate the influence of liquidity risk on insurance companies' return on equity.
  
## Data Collection

The data for this study were collected from financial reports and databases of insurance companies operating in Lagos. The variables of interest include liquidity risk, return on assets (ROA), and return on equity (ROE) for the years under consideration.

## Descriptive Analysis

The descriptive analysis suggests that liquidity risk varies considerably across the insurance companies, while ROA and ROE exhibit moderate levels of profitability with some variations. 
Descriptive statistics were computed for the key variables, including measures of central tendency (mean, median), dispersion (standard deviation). These statistics provide insights into the distribution and characteristics of the data.


The descriptive statistics for liquidity risk, return on assets, and return on equity are presented in the following table:


| Variable           | Mean    | Standard Deviation | Minimum | Maximum | 
|--------------------|---------|--------------------|---------|---------|
| Liquidity Risk     | 766.51  | 7658.84            | 0.0789  | 76589.0 |
| Return on Assets   | 0.3278  | 0.2077             | 0.0453  | 0.9818  |
| Return on Equity   | 0.2441  | 0.2074             | 0.0227  | 0.9818  |


## Hypothesis Testing

The t-test results indicate that there is no significant relationship between liquidity risk and return on assets (ROA) or return on equity (ROE) of insurance companies. The p-values for both ROA and ROE are greater than the significance level of 0.05, suggesting that we fail to reject the null hypothesis. Therefore, based on the available evidence, there is insufficient statistical support to conclude that liquidity risk has a significant impact on the financial performance indicators considered in this study.

In contrast, the ANOVA results for comparing means of ROA and ROE across insurance companies reveal significant differences in the mean values of these variables. The low p-values (< 0.05) indicate that there are statistically significant variations in ROA and ROE among the different insurance companies. This suggests that factors other than liquidity risk may be influencing the financial performance of these companies.

## Regression Analysis

Regression results suggest that liquidity risk is not a significant predictor of the financial performance indicators (ROA and ROE) for the selected insurance companies in Lagos. The low R-squared values and non-significant F-statistics indicate that the regression models do not adequately explain the variation in the dependent variables, and the coefficients for liquidity risk are not statistically significant. Therefore, liquidity risk may not be a reliable predictor of financial performance for these insurance companies.

The regression analysis provides further insights into the relationship between liquidity risk and the financial performance indicators. The coefficients for liquidity risk in both regression models are statistically insignificant (p > 0.05), indicating that liquidity risk does not have a significant impact on either return on assets or return on equity.

# Conclusion

In conclusion, this study investigated the relationship between liquidity risk and financial performance indicators (ROA and ROE) of insurance companies in Lagos. While descriptive and inferential analyses were conducted, the results did not provide evidence to support the hypotheses that liquidity risk significantly affects the profitability and solvency of these companies. Further research incorporating additional variables and a larger sample size may provide more robust insights into the determinants of financial performance in the insurance industry.

Tools Used

* Microsoft Excel For initial stage of data cleaning
* Pandas for Accessing and manipulation of the data
* Matplotlib and Seaborn for Visualization and generating insights
