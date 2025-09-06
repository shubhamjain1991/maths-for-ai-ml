# Combinatorics

## Overview
Fundamental concepts in combinatorics essential for AI/ML applications, including counting principles, permutations, combinations, and their applications in probability and machine learning.

## Topics

### 1. Basic Counting Principles
- **Addition Principle (Sum Rule)**
  - Mutually exclusive events
  - Applications in discrete probability
- **Multiplication Principle (Product Rule)**
  - Independent selections
  - Tree diagrams and counting paths
- **Inclusion-Exclusion Principle**
  - Counting overlapping sets
  - Venn diagram applications

### 2. Permutations
- **Basic Permutations**
  - Arrangements of n distinct objects
  - Formula: P(n,r) = n!/(n-r)!
- **Circular Permutations**
  - Arrangements in a circle
  - Applications in cyclic structures
- **Permutations with Repetition**
  - Identical objects
  - Multiset permutations

### 3. Combinations
- **Basic Combinations**
  - Selections without regard to order
  - Formula: C(n,r) = n!/(r!(n-r)!)
- **Combinations with Repetition**
  - Stars and bars method
  - Applications in sampling with replacement
- **Properties of Binomial Coefficients**
  - Pascal's triangle
  - Symmetry and recurrence relations

### 4. Advanced Counting Techniques
- **Generating Functions**
  - Ordinary generating functions
  - Applications in counting problems
- **Recurrence Relations**
  - Linear recurrence relations
  - Fibonacci sequence and applications
- **Catalan Numbers**
  - Definition and properties
  - Applications in tree structures

### 5. Graph Theory Basics
- **Graph Counting Problems**
  - Counting paths and cycles
  - Trees and spanning trees
- **Matching and Assignment Problems**
  - Bipartite graphs
  - Perfect matchings

### 6. Applications in AI/ML
- **Feature Selection**
  - Counting possible feature subsets
  - Combinatorial optimization
- **Neural Network Architecture**
  - Counting network configurations
  - Hyperparameter combinations
- **Algorithm Analysis**
  - Time complexity analysis
  - Counting operations and states
- **Data Sampling**
  - Sampling strategies
  - Bootstrap methods

### 7. Practice Problems
- **Basic Counting Scenarios**
  - Password generation problems
  - Committee selection problems
- **Probability Applications**
  - Card and dice problems
  - Birthday paradox variations
- **ML-Specific Problems**
  - Cross-validation combinations
  - Model ensemble counting

## Key Formulas
- Permutations: P(n,r) = n!/(n-r)!
- Combinations: C(n,r) = n!/(r!(n-r)!)
- Inclusion-Exclusion: |A∪B| = |A| + |B| - |A∩B|
- Stars and Bars: C(n+k-1, k-1) for k identical objects in n bins

## Prerequisites
- Basic algebra and factorials
- Set theory fundamentals
- Elementary probability concepts

## Learning Outcomes
By the end of this module, students will be able to:
1. Apply fundamental counting principles to solve complex problems
2. Distinguish between permutation and combination scenarios
3. Use combinatorial methods in probability calculations
4. Apply combinatorial concepts to machine learning problems
5. Analyze algorithmic complexity using combinatorial methods
