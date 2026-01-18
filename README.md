**Overview**

This repository demonstrates a real-world churn analytics pipeline built using PySpark, covering:

Data profiling & cleaning
Advanced feature engineering
Spark performance concepts (partitioning, skew handling)
Business-driven metrics
End-to-end Spark ML churn prediction model

The project is designed to reflect production-grade data science workflows, not just toy examples.


**Problem Statement**

Customer churn is a critical business metric.
This project aims to:

Understand customer behavior through session, transaction, and service data
Engineer meaningful churn predictors
Build a scalable churn prediction model using Spark ML

**Dataset**

The dataset contains customer-level behavioral and transactional data

**Key Concepts Covered**

**1. Spark Performance**

Hash & range partitioning
Data skew detection
Shuffle minimization
Small file optimization

**2. Feature Engineering**

Session efficiency metrics
Behavioral ratios
Window functions
Categorical encoding

**3. Business Analytics**

Churn risk bucketing
Customer segmentation
KPI-driven metrics

**4. Machine Learning**

Spark ML Pipelines
Feature Vectorization
Logistic Regression churn model
Model evaluation
