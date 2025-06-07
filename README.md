# Machine-Learning-On-Citation-Count
Citation Count Analysis Using Statistical Learning
Course: ITAO7103 – Advanced Analytics and Machine Learning (Jan–April 2025)
Textbook Reference: An Introduction to Statistical Learning

Overview
This project explores the use of statistical learning techniques to understand the factors influencing the citation counts of scientific articles. Using a customized dataset containing network metrics, funding data, patent associations, and citation metadata, we apply regression-based modeling, feature selection, and classification methods to uncover patterns driving article influence in academic research.

Objectives
The primary goal is to develop, evaluate, and interpret models that explain and predict citation counts. This involves performing exploratory data analysis (EDA), simple and multiple linear regression, feature selection using LASSO and forward selection, as well as model refinement with interaction terms and transformations. Logistic regression is used to classify articles into high or low citation categories based on the median citation count.

Key Components
Part 1: EDA through summary statistics, visualizations, and correlation analysis.

Part 2: Simple linear regression with residual diagnostics.

Part 3: Multiple linear regression including polynomial and subset models, multicollinearity checks, and PubYear effect analysis.

Part 4: Feature selection via LASSO and forward selection with cross-validation.

Part 5: Model refinement using interaction terms (e.g., Grant × Patent), transformations, and subgroup analysis (InGroup1, InGroup2).

Part 6: Binary classification using logistic regression with performance metrics such as accuracy, precision, and recall.

Technologies Used
R (tidyverse, glmnet, caret, ggplot2)

Statistical methods from ISLR (James et al.)

Outcome
The project offers insights into how scientific collaboration, funding, and cross-disciplinary impact affect citation performance. It provides hands-on experience in building interpretable and predictive statistical learning models with real-world data.

