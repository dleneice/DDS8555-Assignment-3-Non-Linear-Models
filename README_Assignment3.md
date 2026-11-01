# DDS 8555 Assignment 3: Build Non-Linear Models Part 1

This repository contains the Python notebooks for Assignment 3 in DDS 8555: Predictive Analysis.

## Files

- `MonroeD_DDS8555-3_Part_3.ipynb` — Abalone Kaggle analysis using Lasso regularization and principal components regression (PCR), with multicollinearity diagnostics, cross-validation, residual diagnostics, validation metrics, and Kaggle submission-file generation.

## Modeling Summary

The Abalone analysis retains the complete substantive predictor set initially so that the modeling methods determine how correlated information is handled. Lasso uses an L1 penalty and cross-validation to identify a regularization-informed subset of predictors. PCR standardizes the same predictors, transforms them into orthogonal principal components, and selects the number of components by cross-validated RMSLE. Both models are evaluated on the same validation split and generate competition-ready submission CSV files.

## Course

DDS 8555: Predictive Analysis  
National University  
Assignment 3
