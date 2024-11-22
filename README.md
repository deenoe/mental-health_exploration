# Mental Health Dataset - Exploratory Data Analysis (EDA)

This repository contains an exploratory data analysis (EDA) on a synthetic mental health dataset. The goal of this analysis is to uncover patterns and relationships between various factors such as therapy types, medication, age groups, and treatment outcomes.

## Dataset Overview
Link: https://www.kaggle.com/datasets/uom190346a/mental-health-diagnosis-and-treatment-monitoring
The dataset includes the following key columns:
- **Patient ID**: Unique identifier for each patient.
- **Age**: Patient's age.
- **Gender**: Gender of the patient.
- **Diagnosis**: Diagnosis of the patient (e.g., MDD, BPD).
- **Symptom Severity, Mood Score, Sleep Quality**: Numeric ratings (1-10) reflecting the patient's condition.
- **Physical Activity**: Hours of physical activity per week.
- **Medication**: Type of medication prescribed.
- **Therapy Type**: Type of therapy the patient is undergoing.
- **Treatment Data**: Start date, duration (weeks), and progress.
- **Stress Level**: Self-reported stress level (1-10).
- **Outcome**: Outcome of the treatment (e.g., improved, worsened).
- **Adherence to Treatment**: Percentage adherence to the prescribed treatment.

## Key Findings
- **Age and Treatment Response**: Age group plays a significant role in how patients respond to treatments.
- **Therapy Effectiveness**: Certain therapies were associated with better outcomes (CBT/DBT), while others, like Mindfulness-Based Therapy, had mixed results.
- **Medication Impact**: Different medications showed varying levels of effectiveness. Mood stabilizers showed the best results while antidepressants showed the worst.
- **Symptom Severity**: Younger patients generally reported more severe symptoms compared to older patients.

## Visualizations

- **Stacked Barplots**: Comparing Medication/Therapy Type to their Patient Outcomes
- **Box and Whisker Plots**: Distribution of effects of MDD and BPD across different age groups
