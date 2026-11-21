# Project
hcl project(data analysis)
# Gym Member Fitness Score Analysis

## Project Overview

This project analyses gym membership data to understand the factors associated with members' fitness scores.

The project uses Python libraries such as Pandas, NumPy, Matplotlib and Seaborn.

## Work Flow

gym-member-fitness-analysis/
│
├── data/
│   ├── raw/
│   │   └── gym_data.csv
│   │
│   └── processed/
│       └── gym_data_clean.csv
│
├── notebooks/
│   ├── draft1.ipynb
│   └── draft2.ipynb
│
├── images/
│   ├── q1_fitness_distribution.png
│   ├── q1_fitness_boxplot.png
│   ├── q2_visits_vs_fitness.png
│   ├── q2_session_vs_fitness.png
│   ├── city_fitness_comparison.png
│   ├── gender_fitness_comparison.png
│   ├── membership_type_fitness_comparison.png
│   ├── workout_preference_fitness_comparison.png
│   └── q4_risk_distribution.png
│
├── script/
│
├── README.md
│
└── requirements.txt


## Business Problem

A regional gym chain wants to understand why some members achieve higher fitness scores than others. The analysis examines workout habits, membership types and member characteristics to identify patterns and members who may need additional attention.

## Research Questions

1. What does Fitness_Score look like overall?
2. Do Visits_Per_Week and Avg_Session_Minutes affect Fitness_Score?
3. Does Fitness_Score differ by Membership_Type, City, Gender and Workout_Preference?
4. Which members need attention? Members with Fitness_Score below 40 are labelled At Risk.

## Dataset Information

- Dataset: gym_data.csv
- Original records: 255
- Unique original records: 250
- Domain: Gym Members
- Location: Five Indian cities
- Outcome variable: Fitness_Score

## Data Cleaning

The following cleaning operations were performed:

- Removed duplicate records.
- Standardized inconsistent categorical values.
- Identified impossible numerical values.
- Handled missing numerical values using median.
- Handled missing categorical values using mode.
- Converted date values into datetime format.

## New Columns

1. Weekly_Workout_Minutes
2. Engagement_Level
3. Age_Group
4. Risk_Status

## Analysis

### Question 1
Overall Fitness Score Analysis

### Question 2
Relationship between workout frequency, session duration and fitness scores.

### Question 3
Fitness score comparison across membership types, cities, gender and workout preferences.

### Question 4
Identification and analysis of members with fitness scores below 40.

## Visualizations

Charts are saved in the images folder.

## Key Findings

To be completed after running the analysis notebook.

## Recommendations

To be completed based on the actual analysis findings.

## Author
**SAVANT**
**2026B01011126**

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook