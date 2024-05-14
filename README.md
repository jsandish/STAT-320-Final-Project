# Analysis of Factors Influencing Self-Perceived Quality of Life
## Overview
This project utilizes the language R to conduct data analysis. The quarto file with R code is in the files which will allow code to be run locally. Ensure filepath to local dataset is changed to fit expectations.

## Abstract
This project delves into understanding the factors influencing self-perceived quality of life using data from the General Social Survey (GSS) for adults in the United States in 2021. The goal was to construct a multi-linear regression model and draw inferences about how individuals rank themselves within society based on socioeconomic factors. Backwards elimination was utilized to refine predictor variables, leading to a final model that includes marital status, education level, and income. While the model meets the Independence condition for inference, it's crucial to note its limitations in predicting self-ranking values for individuals outside the United States or beyond 2021.

## Introduction
The study aims to uncover common variables affecting personal happiness, potentially aiding decision-making for improved quality of life. Insights gained may assist policymakers in designing supportive policies and healthcare professionals in addressing mental health challenges. Understanding what influences self-ranking on a 100-point scale provides valuable societal context.

## Data
The GSS, conducted biennially since 1972, provided data on attitudes and behaviors. Initial data wrangling involved handling errors, selecting suitable variables, and renaming for clarity. The response variable, self-ranking, underwent normalization and filtering to ensure data integrity.

## Analysis
An initial multi-linear regression model encompassed various predictor variables. Backwards elimination refined the model to include only marital status, education, and income due to their statistical significance.

## Model Evaluation and Results
Checks for multicollinearity, normality, linearity, and variance equality were performed. While the model showed deviations from ideal conditions, it provided interpretable results. The final model explained 12.3% of rank variability. Marital status showed the most significant impact, followed by education and income. However, the model's small coefficients highlight the scale's impact on interpretations. The model's applicability is limited to US residents in 2021. It highlights societal values like education and income. Future studies could explore cross-cultural comparisons to understand global perspectives on self-perceived quality of life.
