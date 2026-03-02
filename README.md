# AI-Driven Supply Chain Performance and Risk Analytics
Project Overview

This project presents a data-driven supply chain analytics system built using machine learning techniques. The objective is to analyze supply chain operational data, evaluate product performance, identify potential risks, and support data-informed decision-making.

The system processes real-world supply chain data and transforms it into actionable insights through performance scoring, predictive modeling, and clustering.

Objectives
Evaluate supply chain performance using key operational metrics
Predict high-risk products using machine learning
Rank products using a weighted performance scoring model
Segment products into performance categories using clustering
Generate structured output suitable for business analysis

Dataset Description
The dataset contains real-world supply chain information including:
Product type
SKU
Price
Availability
Number of products sold
Revenue generated
Stock levels
Lead time
Manufacturing lead time
Production volumes
Manufacturing costs
Defect rates
Transportation modes
Routes
Costs
Inspection results
Location

Methodology
1. Data Preprocessing
Standardized and cleaned column names
Handled numerical features
Performed feature engineering to create new performance indicators

2. Feature Engineering
Created additional business metrics including:
On-time delivery indicator
Production efficiency
Profit margin
Risk flag variable

3. Performance Scoring Model
Developed a weighted multi-criteria scoring system based on:
Lead time
Defect rate
Cost
Efficiency
Profit margin
This score ranks products based on overall operational performance.

4. Risk Prediction Model
Implemented a Random Forest classifier to predict high-risk products using:
Lead time
Defect rate
Cost
Availability
Model performance was evaluated using classification metrics.

5. Clustering
Applied K-Means clustering to segment products into performance groups:
High performers
Moderate performers
High-risk group
Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Google Colab

Key Outcomes
Ranked performance table based on weighted scoring
Predictive model for identifying risky products
Feature importance analysis
Product segmentation using clustering
Exportable analytical output file
How to Run the Project
Open the notebook in Google Colab
Upload the dataset
Run all cells sequentially
Download the generated analysis file

