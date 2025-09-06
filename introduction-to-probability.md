# Introduction to Probability

## Overview
Fundamental probability concepts essential for AI/ML applications, including probability theory, distributions, Bayes' theorem, and statistical inference foundations.

## Topics

### 1. Basic Probability Concepts
- **Sample Space and Events**
  - Definition of sample space (Ω)
  - Events as subsets of sample space
  - Complementary and mutually exclusive events
- **Probability Axioms**
  - Non-negativity: P(A) ≥ 0
  - Normalization: P(Ω) = 1
  - Additivity: P(A ∪ B) = P(A) + P(B) for disjoint events
- **Properties of Probability**
  - Complement rule: P(A^c) = 1 - P(A)
  - Union of events: P(A ∪ B) = P(A) + P(B) - P(A ∩ B)

### 2. Conditional Probability and Independence
- **Conditional Probability**
  - Definition: P(A|B) = P(A ∩ B) / P(B)
  - Chain rule of probability
  - Law of total probability
- **Independence**
  - Definition: P(A ∩ B) = P(A) × P(B)
  - Mutual independence
  - Conditional independence
- **Bayes' Theorem**
  - Statement: P(A|B) = P(B|A) × P(A) / P(B)
  - Prior, likelihood, and posterior probabilities
  - Applications in machine learning

### 3. Random Variables
- **Discrete Random Variables**
  - Probability mass function (PMF)
  - Cumulative distribution function (CDF)
  - Expected value and variance
- **Continuous Random Variables**
  - Probability density function (PDF)
  - Relationship between PDF and CDF
  - Expected value and variance for continuous variables
- **Functions of Random Variables**
  - Transformation of random variables
  - Expected value of functions: E[g(X)]

### 4. Common Probability Distributions
- **Discrete Distributions**
  - Bernoulli distribution
  - Binomial distribution
  - Poisson distribution
  - Geometric distribution
- **Continuous Distributions**
  - Uniform distribution
  - Normal (Gaussian) distribution
  - Exponential distribution
  - Beta distribution
- **Distribution Parameters**
  - Mean, variance, and standard deviation
  - Skewness and kurtosis

### 5. Joint Distributions and Multivariate Analysis
- **Joint Probability Distributions**
  - Joint PMF/PDF
  - Marginal distributions
  - Conditional distributions
- **Covariance and Correlation**
  - Covariance: Cov(X,Y) = E[(X-μX)(Y-μY))]
  - Correlation coefficient: ρ = Cov(X,Y)/(σX × σY)
  - Linear dependence vs independence
- **Multivariate Normal Distribution**
  - Properties and applications
  - Bivariate normal distribution

### 6. Limit Theorems
- **Law of Large Numbers**
  - Weak and strong law of large numbers
  - Convergence in probability
  - Applications to sampling
- **Central Limit Theorem**
  - Statement and conditions
  - Normal approximation to binomial
  - Applications in statistical inference
- **Convergence Concepts**
  - Convergence in distribution
  - Convergence in probability

### 7. Applications in AI/ML
- **Bayesian Inference**
  - Bayesian parameter estimation
  - Bayesian model selection
  - Prior and posterior distributions
- **Probabilistic Models**
  - Naive Bayes classifier
  - Hidden Markov Models
  - Gaussian Mixture Models
- **Maximum Likelihood Estimation**
  - Likelihood functions
  - Log-likelihood optimization
  - Properties of MLE estimators
- **Uncertainty Quantification**
  - Confidence intervals
  - Prediction intervals
  - Bayesian credible intervals

### 8. Information Theory Basics
- **Entropy**
  - Shannon entropy: H(X) = -∑ p(x) log p(x)
  - Joint and conditional entropy
  - Properties of entropy
- **Mutual Information**
  - Definition: I(X;Y) = H(X) - H(X|Y)
  - Applications in feature selection
  - Kullback-Leibler divergence
- **Cross-entropy**
  - Definition and properties
  - Applications in machine learning loss functions

### 9. Practical Applications
- **A/B Testing**
  - Hypothesis testing framework
  - Type I and Type II errors
  - Statistical power analysis
- **Monte Carlo Methods**
  - Random sampling techniques
  - Monte Carlo integration
  - Markov Chain Monte Carlo (MCMC) basics
- **Bootstrap and Resampling**
  - Bootstrap sampling
  - Confidence interval estimation
  - Permutation tests

## Key Formulas
- Conditional Probability: P(A|B) = P(A ∩ B) / P(B)
- Bayes' Theorem: P(A|B) = P(B|A) × P(A) / P(B)
- Expected Value (Discrete): E[X] = ∑ x × P(X = x)
- Variance: Var(X) = E[X²] - (E[X])²
- Covariance: Cov(X,Y) = E[(X-μX)(Y-μY)]
- Shannon Entropy: H(X) = -∑ p(x) log p(x)

## Prerequisites
- Basic set theory and counting principles
- Calculus (derivatives and integrals)
- Basic understanding of functions and limits

## Learning Outcomes
By the end of this module, students will be able to:
1. Calculate probabilities using fundamental probability rules
2. Apply Bayes' theorem to solve conditional probability problems
3. Work with random variables and probability distributions
4. Understand and apply limit theorems
5. Use probability concepts in machine learning contexts
6. Apply information theory concepts to ML problems
7. Perform basic statistical inference using probability theory
