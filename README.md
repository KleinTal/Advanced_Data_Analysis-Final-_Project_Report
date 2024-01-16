# Advanced Data Analysis in R Final Project Report

## Table of Contents
1. [Team Members](#team-members)
2. [Introduction](#introduction)
   - [General Data Science Question](#general-data-science-question)
   - [Focus Area](#focus-area)
   - [Importance](#importance)
3. [Data](#data)
   - [Source](#source)
   - [Characteristics](#characteristics)
   - [Analysis Exclusions](#analysis-exclusions)
4. [Methods and Results](#methods-and-results)
   - [Part 1: Model Selection](#part-1-model-selection)
   - [Part 2: Feature Importance](#part-2-feature-importance)
   - [Part 3: Model Verification](#part-3-model-verification)
5. [Observations](#observations)
   - [Educational Background](#educational-background)
   - [Language Skills](#language-skills)
   - [Age](#age)
   - [Grade](#grade)
6. [Limitations and Future Work](#limitations-and-future-work)
   - [Limitations](#limitations)
   - [Future Work](#future-work)
7. [Conclusion](#conclusion)
   - [Key Findings](#key-findings)
   - [Impact](#impact)
8. [Link to the Data](#link-to-the-data)

## Team Members
- **Tal Klein**
- **Ariel Siman Tov**
- **Ido Villa**

## Introduction

### General Data Science Question
"What are the key personal attributes and qualifications that significantly contribute to a candidate being hired for an office job in the Netherlands?"

### Focus Area
This analysis centers on the office work market in the Western world, with a specific emphasis on the Netherlands, represented by Utrecht. Utrecht is chosen due to its diverse job market, strong economy, and developed infrastructure.

### Importance
The study aims to identify attributes and qualifications valued in the Dutch job market, providing insights for job seekers, recruiters, and employers to enhance hiring processes and refine job descriptions.

## Data

### Source
The dataset comprises recruitment decisions from four major companies in Utrecht, Netherlands, available on Kaggle [here](https://www.kaggle.com/datasets/ictinstitute/utrecht-fairness-recruitment-dataset).

### Characteristics
- **Size:** 4000 samples (1000 per company)
- **Columns:** 15, including a unique identifier, gender, age, nationality, main sport, university grade, club participation, programming experience, international experience, entrepreneurial experience, language fluency, study background, highest degree, company applied to, and decision outcome.

### Analysis Exclusions
- **Excluded Columns:** "Id" (unique identifier), "Company" (used in Part 3 for model verification).

## Methods and Results

### Part 1: Model Selection
Comparison of "Logistic Regression" and "Random Forest" models revealed the Random Forest as superior. Cross-validation ensured model robustness.

### Part 2: Feature Importance
Utilizing "MeanDecreaseGini," the top 5 parameters influencing the hiring decision were identified: grade, number of languages, age, degree, and sport.

### Part 3: Model Verification
Comparison across four companies validated the model's consistency. Key features (grade, degree, languages) remained significant in all companies.

## Observations 

### Educational Background
- A master's degree significantly increases the chance of job acceptance.

### Language Skills
- Proficiency in multiple languages positively correlates with higher hiring probability.

### Age
- Age's influence on hiring decisions varies across companies.

### Grade
- Higher grades increase the likelihood of being hired.

## Limitations and Future Work

### Limitations
- Limited company and candidate numbers within each company.
- Data specific to the Dutch employment economy.
- Lack of information about specific industries impacting findings.

### Future Work
- Increase sample size for more precise results.
- Explore additional datasets with information on other companies and supplementary features.

## Conclusion

### Key Findings
Attributes significantly contributing to candidate hiring: grade, degree, and proficiency in multiple languages. These findings align with prevailing industry beliefs.

### Impact
Insights benefit job seekers, recruiters, and employers, enhancing hiring processes and candidate assessment.

