# Basics of Statistics

## Overview
Fundamental statistical concepts and methods essential for data analysis, hypothesis testing, and statistical inference in AI/ML applications.

## Topics

### 1. Descriptive Statistics
- **Measures of Central Tendency**
  - Mean (arithmetic, geometric, harmonic)
  - Median and its properties
  - Mode and multimodal distributions
  - When to use each measure
- **Measures of Dispersion**
  - Range and interquartile range (IQR)
  - Variance and standard deviation
  - Coefficient of variation
  - Mean absolute deviation
- **Distribution Shape**
  - Skewness (left, right, symmetric)
  - Kurtosis (leptokurtic, mesokurtic, platykurtic)
  - Box plots and five-number summary
  - Outlier detection methods

### 2. Data Visualization and Exploration
- **Univariate Visualization**
  - Histograms and density plots
  - Box plots and violin plots
  - Q-Q plots for normality testing
  - Stem-and-leaf plots
- **Bivariate Visualization**
  - Scatter plots and correlation
  - Line plots for time series
  - Cross-tabulation tables
  - Heat maps for correlation matrices
- **Multivariate Techniques**
  - Pair plots and correlation matrices
  - Principal component biplots
  - Parallel coordinate plots

### 3. Probability Distributions in Statistics
- **Discrete Distributions**
  - Bernoulli and binomial applications
  - Poisson distribution for count data
  - Hypergeometric distribution
  - Negative binomial distribution
- **Continuous Distributions**
  - Normal distribution and empirical rule
  - Student's t-distribution
  - Chi-square distribution
  - F-distribution
- **Distribution Properties**
  - Parameters and moments
  - Probability density/mass functions
  - Cumulative distribution functions
  - Quantile functions

### 4. Sampling and Sampling Distributions
- **Sampling Methods**
  - Simple random sampling
  - Stratified sampling
  - Cluster sampling
  - Systematic sampling
- **Sampling Distributions**
  - Distribution of sample mean
  - Distribution of sample proportion
  - Standard error concept
  - Finite population correction
- **Central Limit Theorem Applications**
  - Conditions for CLT
  - Normal approximation to binomial
  - Sample size requirements

### 5. Statistical Inference
- **Point Estimation**
  - Method of moments
  - Maximum likelihood estimation
  - Properties of estimators (unbiased, consistent, efficient)
  - Bias-variance tradeoff
- **Interval Estimation**
  - Confidence intervals for mean
  - Confidence intervals for proportion
  - Confidence intervals for variance
  - Interpretation of confidence levels
- **Bootstrap Methods**
  - Bootstrap sampling procedure
  - Bootstrap confidence intervals
  - Bias correction and acceleration (BCa)

### 6. Hypothesis Testing
- **Fundamentals**
  - Null and alternative hypotheses
  - Type I and Type II errors
  - Significance level and p-values
  - Power of a test
- **One-Sample Tests**
  - Z-test for population mean
  - t-test for population mean
  - Test for population proportion
  - Chi-square test for variance
- **Two-Sample Tests**
  - Independent samples t-test
  - Paired samples t-test
  - Two-sample proportion test
  - F-test for equality of variances
- **Non-parametric Tests**
  - Mann-Whitney U test
  - Wilcoxon signed-rank test
  - Kruskal-Wallis test
  - Chi-square test of independence

### 7. Analysis of Variance (ANOVA)
- **One-Way ANOVA**
  - Between-group vs within-group variation
  - F-statistic and F-distribution
  - Post-hoc tests (Tukey, Bonferroni)
  - Assumptions and diagnostics
- **Two-Way ANOVA**
  - Main effects and interaction effects
  - Factorial designs
  - Interpretation of results
- **ANOVA Assumptions**
  - Normality testing
  - Homogeneity of variance (Levene's test)
  - Independence of observations

### 8. Correlation and Regression
- **Correlation Analysis**
  - Pearson correlation coefficient
  - Spearman rank correlation
  - Kendall's tau
  - Partial and semi-partial correlation
- **Simple Linear Regression**
  - Least squares estimation
  - Regression assumptions
  - Coefficient interpretation
  - R-squared and adjusted R-squared
- **Regression Diagnostics**
  - Residual analysis
  - Outlier and influence detection
  - Multicollinearity assessment
  - Model validation techniques

### 9. Categorical Data Analysis
- **Chi-Square Tests**
  - Goodness of fit test
  - Test of independence
  - Test of homogeneity
  - Effect size measures (Cramér's V, Phi)
- **Odds and Odds Ratios**
  - Definition and interpretation
  - Confidence intervals for odds ratios
  - Relative risk vs odds ratio
- **Logistic Regression Basics**
  - Logit transformation
  - Maximum likelihood estimation
  - Interpretation of coefficients

### 10. Applications in AI/ML
- **Exploratory Data Analysis**
  - Data profiling and quality assessment
  - Feature distribution analysis
  - Correlation analysis for feature selection
  - Handling missing data
- **Model Evaluation Statistics**
  - Confusion matrix metrics
  - ROC curves and AUC
  - Precision, recall, and F1-score
  - Cross-validation techniques
- **Statistical Learning Foundations**
  - Bias-variance decomposition
  - Overfitting and underfitting
  - Statistical significance in ML
  - A/B testing for model comparison
- **Experimental Design**
  - Randomized controlled trials
  - Power analysis and sample size calculation
  - Multiple comparison corrections
  - Causal inference basics

### 11. Time Series Basics
- **Time Series Components**
  - Trend, seasonality, and irregular components
  - Stationary vs non-stationary series
  - Autocorrelation and partial autocorrelation
- **Descriptive Time Series Analysis**
  - Moving averages
  - Exponential smoothing
  - Seasonal decomposition
- **Time Series Visualization**
  - Line plots and trend analysis
  - Seasonal plots
  - Lag plots and autocorrelation plots

## Key Formulas
- Sample Mean: x̄ = (Σxi) / n
- Sample Variance: s² = Σ(xi - x̄)² / (n-1)
- Standard Error: SE = s / √n
- Confidence Interval: x̄ ± t(α/2) × SE
- t-statistic: t = (x̄ - μ₀) / SE
- Correlation: r = Σ[(xi - x̄)(yi - ȳ)] / √[Σ(xi - x̄)²Σ(yi - ȳ)²]
- Chi-square: χ² = Σ[(Oi - Ei)² / Ei]

## Statistical Software Tools
- **R Programming**
  - Basic statistical functions
  - Data manipulation with dplyr
  - Visualization with ggplot2
- **Python Libraries**
  - NumPy and SciPy for calculations
  - Pandas for data manipulation
  - Matplotlib and Seaborn for visualization
  - Statsmodels for statistical modeling

## Prerequisites
- Basic probability theory
- Descriptive statistics concepts
- Elementary calculus
- Basic understanding of mathematical functions

## Learning Outcomes
By the end of this module, students will be able to:
1. Calculate and interpret descriptive statistics
2. Create appropriate data visualizations
3. Perform statistical hypothesis tests
4. Construct and interpret confidence intervals
5. Conduct basic regression analysis
6. Apply statistical methods to real-world datasets
7. Use statistical concepts in machine learning contexts
8. Critically evaluate statistical claims and results
