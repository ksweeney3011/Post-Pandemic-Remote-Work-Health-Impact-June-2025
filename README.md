# Post Pandemic Remote Work Health Impact 2025 – Capstone Project
 # Overview

This repository contains the full Capstone Project for CSU Global, analyzing the long-term health implications of remote and hybrid work in the post-pandemic era. Using the Post Pandemic Remote Work Health Impact 2025 dataset, the project examines the relationships between work arrangements, burnout, work-life balance, social isolation, and mental health outcomes.

The goal is to provide data-driven insights and recommendations to help organizations design healthier and more sustainable remote/hybrid work environments.

# Research Objectives

RQ1: Do burnout levels differ across work arrangements (Remote, Hybrid, Onsite)?

RQ2: Is there a correlation between weekly hours worked and work-life balance scores?

RQ3: Do burnout levels and social isolation scores predict the presence of mental health conditions?

RQ4: Are there significant differences in work-life balance by gender or region?

#Dataset

File: post_pandemic_remote_work_health_impact_2025.csv
Key Variables:

Survey_Date

Age, Gender, Region

Industry, Job_Role

Work_Arrangement (Remote, Hybrid, Onsite)

Hours_Per_Week

Burnout_Level (Low, Medium, High → numeric coding: 1–3)

Work_Life_Balance_Score (1–5)

Social_Isolation_Score (1–5)

Mental_Health_Status (None, Stress Disorder, Anxiety, PTSD)

Physical_Health_Issues (multi-label)

Salary_Range

# Tools & Technologies

Python: pandas, NumPy, SciPy, statsmodels, matplotlib

Jupyter Notebook: for exploratory analysis and reproducibility

Tableau: for interactive dashboards and data visualization

GitHub: for version control and project sharing

# Methods

Data Preparation

Encoded categorical and ordinal variables.

Tokenized multi-label health issues into binary indicators.

Descriptive Statistics

Computed means, medians, standard deviations, and frequencies.

Visualized distributions of key variables.

Hypothesis Testing

ANOVA: Burnout by Work Arrangement

Spearman Correlation: Hours vs Work-Life Balance

Logistic Regression: Predicting Mental Health Outcomes

t-test / ANOVA: Gender and Regional Differences in Work-Life Balance

Visualization

Boxplots, scatterplots, bar charts (Python + Tableau).

Interactive Tableau dashboards for stakeholders.

# Key Findings

Remote employees report significantly higher burnout than hybrid or onsite employees.

Weekly hours worked are not significantly correlated with work-life balance.

Burnout and isolation did not significantly predict diagnosed mental health conditions, pointing to measurement gaps.

Gender showed no significant differences in balance, but regional disparities were significant (Asia/Europe higher; Oceania/South America lower).

# Recommendations

Adopt intentional hybrid models with ergonomic and social support.

Focus on quality of hours (flexibility, autonomy, boundaries) rather than just total hours.

Implement proactive mental health monitoring beyond diagnoses.

Tailor wellness strategies to regional contexts and cultural norms.

Expand data collection to include longitudinal and multi-item well-being measures.
