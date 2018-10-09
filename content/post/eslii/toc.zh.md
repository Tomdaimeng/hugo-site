+++
title = "统计学习基础：目录索引"
summary = "“统计学习基础”（ESL）一书的章节目录索引，随完成进度更新。"

date = 2018-08-27T15:18:10+08:00
lastmod = 2018-10-04T16:21:07+08:00
draft = false
math = true

authors = ["Butters"]

tags = ["2018"]
categories = ["统计学习基础（译注）"]

[header]
image = ""
caption = ""
preview = true
+++

1. [序言]({{< ref "/post/eslii/ch01/ch01_00.zh.md" >}})
2. 监督学习概述
  1. [引言]({{< ref "/post/eslii/ch02/ch02_01.zh.md" >}})
  2. [变量类型和术语]({{< ref "/post/eslii/ch02/ch02_02.zh.md" >}})
  3. [两个简单的预测方法：最小二乘和最近邻域]({{< ref "/post/eslii/ch02/ch02_03.zh.md" >}})
  4. [统计决策理论]({{< ref "/post/eslii/ch02/ch02_04.zh.md" >}})
  5. [局部方法中的高维度问题]({{< ref "/post/eslii/ch02/ch02_05.zh.md" >}})
  6. [统计模型、监督学习和函数逼近]({{< ref "/post/eslii/ch02/ch02_06.zh.md" >}})
  7. [有结构的回归模型]({{< ref "/post/eslii/ch02/ch02_07.zh.md" >}})
  8. [有约束的估计模型类型]({{< ref "/post/eslii/ch02/ch02_08.zh.md" >}})
  9. [模型选择和偏差方差权衡]({{< ref "/post/eslii/ch02/ch02_09.zh.md" >}})
3. 回归问题的线性方法
  1. [引言]({{< ref "/post/eslii/ch03/ch03_01.zh.md" >}})
  2. [线性回归模型和最小二乘法]({{< ref "/post/eslii/ch03/ch03_02.zh.md" >}})
  3. [变量子集选择]({{< ref "/post/eslii/ch03/ch03_03.zh.md" >}})
  4. [收缩方法]({{< ref "/post/eslii/ch03/ch03_04.zh.md" >}})
  5. [衍生输入变量的方法]({{< ref "/post/eslii/ch03/ch03_05.zh.md" >}})
  6. [讨论：子集选择和收缩方法的比较]({{< ref "/post/eslii/ch03/ch03_06.zh.md" >}})
  7. [多输出变量的收缩和变量选择 😱]({{< ref "/post/eslii/ch03/ch03_07.zh.md" >}})
  8. [更多关于套索回归和类似的路径算法]({{< ref "/post/eslii/ch03/ch03_08.zh.md" >}})
  9. [计算量考量]({{< ref "/post/eslii/ch03/ch03_09.zh.md" >}})
4. 分类问题的线性方法
  1. [引言]({{< ref "/post/eslii/ch04/ch04_01.zh.md" >}})
  2. [对指示变量矩阵的线性回归]({{< ref "/post/eslii/ch04/ch04_02.zh.md" >}})
  3. [线性判别分析]({{< ref "/post/eslii/ch04/ch04_03.zh.md" >}})
  4. [对数几率回归（逻辑回归）]({{< ref "/post/eslii/ch04/ch04_04.zh.md" >}})
  5. [Separating Hyperplanes]
5. Basis Expansions and Regularization
  1. [Introduction]
  2. [Piecewise Polynomials and Splines]
  3. [Filtering and Feature Extraction]
  4. [Smoothing Splines]
  5. [Automatic Selection of the Smoothing Parameters]
  6. [Nonparametric Logistic Regression]
  7. [Multidimensional Splines]
  8. [Regularization and Reproducing Kernel Hilbert Spaces]
  9. [Wavelet Smoothing]
6. Kernel Smoothing Methods
  1. [One-Dimensional Kernel Smoothers]
  2. [Selecting the Width of the Kernel]
  3. [Local Regression in $\mathbb{R}^p$]
  4. [Structured Local Regression Models in $\mathbb{R}^p$]
  5. [Local Likelihood and Other Models]
  6. [Kernel Density Estimation and Classification]
  7. [Radial Basis Functions and Kernels]
  8. [Mixture Models for Density Estimation and Classification]
  9. [Computational Considerations]
7. Model Assessment and Selection
  1. [Introduction]
  2. [Bias, Variance and Model Complexity]
  3. [The Bias–Variance Decomposition]
  4. [Optimism of the Training Error Rate]
  5. [Estimates of In-Sample Prediction Error]
  6. [The Effective Number of Parameters]
  7. [The Bayesian Approach and BIC]
  8. [Minimum Description Length]
  9. [Vapnik–Chervonenkis Dimension]
  10. [Cross-Validation]
  11. [Bootstrap Methods]
  12. [Conditional or Expected Test Error?]
8. Model Inference and Averaging
  1. [Introduction]
  2. [The Bootstrap and Maximum Likelihood Methods]
  3. [Bayesian Methods]
  4. [Relationship Between the Bootstrap and Bayesian Inference]
  5. [The EM Algorithm]
  6. [MCMC for Sampling from the Posterior]
  7. [Bagging]
  8. [Model Averaging and Stacking]
  9. [Stochastic Search: Bumping]
9. Additive Models, Trees, and Related Methods
  1. [Generalized Additive Models]
  2. [Tree-Based Methods]
  3. [PRIM: Bump Hunting]
  4. [MARS: Multivariate Adaptive Regression Splines]
  5. [Hierarchical Mixtures of Experts]
  6. [Missing Data]
  7. [Computational Considerations]
10. Boosting and Additive Trees
  1. [提升方法]()
  2. [Boosting Fits an Additive Model]()
  3. [Forward Stagewise Additive Modeling]()
  4. [Exponential Loss and AdaBoost]()
  5. [Why Exponential Loss?]()
  6. [Loss Functions and Robustness]
  7. ["Off-the-Shelf" Procedures for Data Mining]
  8. [Example: Spam Data]
  9. [Boosting Trees]
  10. [Numerical Optimization via Gradient Boosting]
  11. [Right-Sized Trees for Boosting]
  12. [Regularization]
  13. [Interpretation]
  14. [Illustrations]
11. Neural Networks
12. Support Vector Machines and Flexible Discriminants
13. Prototype Methods and Nearest-Neighbors
14. Unsupervised Learning
15. Random Forests
16. Ensemble Learning
17. Undirected Graphical Models
18. High-Dimensional Problems: p ≫ N
