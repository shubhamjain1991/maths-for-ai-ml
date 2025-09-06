# Essentials of Calculus

## Overview
Fundamental calculus concepts essential for understanding optimization, machine learning algorithms, and mathematical modeling in AI/ML applications.

## Topics

### 1. Limits and Continuity
- **Concept of Limits**
  - Informal definition of limits
  - One-sided limits (left and right)
  - Limits at infinity and infinite limits
  - Indeterminate forms and L'Hôpital's rule
- **Limit Laws**
  - Sum, product, and quotient rules
  - Squeeze theorem
  - Limits of composite functions
- **Continuity**
  - Definition of continuity at a point
  - Types of discontinuities
  - Intermediate Value Theorem
  - Continuity of elementary functions

### 2. Derivatives and Differentiation
- **Definition of Derivative**
  - Derivative as a limit
  - Geometric interpretation (slope of tangent)
  - Physical interpretation (instantaneous rate of change)
  - Differentiability vs continuity
- **Basic Differentiation Rules**
  - Power rule: d/dx(x^n) = nx^(n-1)
  - Constant and sum rules
  - Product rule: (fg)' = f'g + fg'
  - Quotient rule: (f/g)' = (f'g - fg')/g²
- **Chain Rule**
  - Composition of functions: (f∘g)' = f'(g(x))·g'(x)
  - Applications to complex functions
  - Implicit differentiation
- **Derivatives of Elementary Functions**
  - Trigonometric functions
  - Exponential functions: d/dx(e^x) = e^x
  - Logarithmic functions: d/dx(ln x) = 1/x
  - Inverse trigonometric functions

### 3. Applications of Derivatives
- **Critical Points and Extrema**
  - First derivative test
  - Second derivative test
  - Absolute vs relative extrema
  - Critical points where derivative doesn't exist
- **Curve Sketching**
  - Increasing and decreasing intervals
  - Concavity and inflection points
  - Asymptotes (vertical, horizontal, oblique)
- **Optimization Problems**
  - Applied maximum and minimum problems
  - Constraint optimization basics
  - Related rates problems
- **Linear Approximation**
  - Tangent line approximation
  - Differentials and error estimation
  - Newton's method for root finding

### 4. Integrals and Integration
- **Antiderivatives**
  - Definition of antiderivative
  - Indefinite integrals
  - Integration as reverse differentiation
  - Constant of integration
- **Basic Integration Rules**
  - Power rule for integration
  - Integration of exponential functions
  - Integration of trigonometric functions
  - Integration by substitution (u-substitution)
- **Definite Integrals**
  - Definition as limit of Riemann sums
  - Fundamental Theorem of Calculus
  - Properties of definite integrals
  - Average value of a function
- **Integration Techniques**
  - Integration by parts: ∫udv = uv - ∫vdu
  - Trigonometric substitution
  - Partial fractions (basic cases)
  - Numerical integration (trapezoidal, Simpson's)

### 5. Applications of Integration
- **Area and Volume**
  - Area between curves
  - Volumes of revolution (disk and washer methods)
  - Volumes by cross-sections
- **Physical Applications**
  - Work and energy
  - Center of mass and moments
  - Arc length and surface area
- **Probability Applications**
  - Continuous probability distributions
  - Expected value and variance using integrals
  - Cumulative distribution functions

### 6. Multivariable Calculus Basics
- **Functions of Several Variables**
  - Domain and range in higher dimensions
  - Level curves and contour plots
  - Limits and continuity in multiple variables
- **Partial Derivatives**
  - Definition: ∂f/∂x = lim[h→0] [f(x+h,y) - f(x,y)]/h
  - Geometric interpretation
  - Higher-order partial derivatives
  - Mixed partial derivatives and Clairaut's theorem
- **Gradient and Directional Derivatives**
  - Gradient vector: ∇f = (∂f/∂x, ∂f/∂y, ∂f/∂z)
  - Directional derivatives
  - Gradient as direction of steepest ascent
- **Chain Rule for Multiple Variables**
  - Chain rule for composite functions
  - Applications to related rates
  - Implicit differentiation in multiple variables

### 7. Optimization in Multiple Variables
- **Critical Points**
  - Finding critical points: ∇f = 0
  - Classification using second derivative test
  - Saddle points and local extrema
- **Lagrange Multipliers**
  - Method for constrained optimization
  - Economic interpretation
  - Multiple constraints
- **Applications to Machine Learning**
  - Least squares optimization
  - Gradient descent algorithm
  - Error surface visualization

### 8. Vector Calculus Fundamentals
- **Vector Fields**
  - Definition and visualization
  - Conservative vector fields
  - Potential functions
- **Line Integrals**
  - Line integrals of scalar functions
  - Line integrals of vector fields
  - Fundamental theorem for line integrals
- **Divergence and Curl**
  - Divergence: ∇·F = ∂P/∂x + ∂Q/∂y + ∂R/∂z
  - Curl: ∇×F
  - Physical interpretations

### 9. Series and Convergence
- **Sequences and Series**
  - Convergence of sequences
  - Geometric series: Σar^n = a/(1-r) for |r| < 1
  - Convergence tests (ratio, root, comparison)
- **Power Series**
  - Radius and interval of convergence
  - Term-by-term differentiation and integration
- **Taylor and Maclaurin Series**
  - Taylor polynomial approximations
  - Common Maclaurin series (e^x, sin x, cos x, ln(1+x))
  - Applications to approximation and error analysis

### 10. Differential Equations Basics
- **First-Order ODEs**
  - Separable equations: dy/dx = g(x)h(y)
  - Linear first-order equations
  - Initial value problems
- **Applications**
  - Growth and decay models
  - Newton's law of cooling
  - Logistic growth model
- **Numerical Methods**
  - Euler's method
  - Runge-Kutta methods (basic)

### 11. Applications in AI/ML
- **Optimization Algorithms**
  - Gradient descent and variants
  - Newton's method for optimization
  - Backpropagation in neural networks
- **Probability and Statistics**
  - Maximum likelihood estimation
  - Probability density functions
  - Bayesian inference
- **Machine Learning Foundations**
  - Loss function minimization
  - Regularization techniques
  - Feature scaling and normalization
- **Signal Processing**
  - Fourier transform basics
  - Convolution operations
  - Image processing applications

### 12. Computational Aspects
- **Numerical Differentiation**
  - Finite difference methods
  - Forward, backward, and central differences
  - Error analysis
- **Numerical Integration**
  - Trapezoidal and Simpson's rules
  - Monte Carlo integration
  - Adaptive quadrature
- **Software Tools**
  - Symbolic computation (SymPy)
  - Numerical libraries (NumPy, SciPy)
  - Automatic differentiation

## Key Formulas
- Derivative Definition: f'(x) = lim[h→0] [f(x+h) - f(x)]/h
- Power Rule: d/dx(x^n) = nx^(n-1)
- Chain Rule: d/dx[f(g(x))] = f'(g(x))·g'(x)
- Product Rule: d/dx[f(x)g(x)] = f'(x)g(x) + f(x)g'(x)
- Fundamental Theorem of Calculus: ∫[a to b] f'(x)dx = f(b) - f(a)
- Integration by Parts: ∫udv = uv - ∫vdu
- Gradient: ∇f = (∂f/∂x, ∂f/∂y, ∂f/∂z)
- Taylor Series: f(x) = f(a) + f'(a)(x-a) + f''(a)(x-a)²/2! + ...

## Common Derivatives
- d/dx(x^n) = nx^(n-1)
- d/dx(e^x) = e^x
- d/dx(ln x) = 1/x
- d/dx(sin x) = cos x
- d/dx(cos x) = -sin x
- d/dx(tan x) = sec²x

## Common Integrals
- ∫x^n dx = x^(n+1)/(n+1) + C (n ≠ -1)
- ∫e^x dx = e^x + C
- ∫(1/x) dx = ln|x| + C
- ∫sin x dx = -cos x + C
- ∫cos x dx = sin x + C

## Prerequisites
- Solid algebra and trigonometry background
- Understanding of functions and graphs
- Basic limit concepts
- Mathematical reasoning skills

## Learning Outcomes
By the end of this module, students will be able to:
1. Calculate limits and determine continuity
2. Compute derivatives using various techniques
3. Apply derivatives to solve optimization problems
4. Evaluate integrals using multiple methods
5. Solve basic differential equations
6. Work with functions of multiple variables
7. Apply calculus concepts to machine learning problems
8. Use computational tools for calculus operations
9. Understand the theoretical foundations behind ML algorithms
10. Implement gradient-based optimization algorithms
