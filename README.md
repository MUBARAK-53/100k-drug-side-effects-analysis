# 100k-drug-side-effects-analysis
Healthcare data analysis project exploring drug side effects, severity, outcomes, and recovery trends using Python and Pandas.
# Drug Side Effects Analysis using Python, Pandas and Matplotlib

## Overview

This project performs Exploratory Data Analysis (EDA) on a healthcare dataset containing 100,000 drug side effect reports.

The goal is to identify patterns in drug usage, adverse reactions, severity levels, patient outcomes, and recovery times. The project demonstrates practical data analysis skills using Python, Pandas, and Matplotlib.

---

## Project Objective

The objective of this project is to answer important healthcare-related questions such as:

* Which drugs are reported most frequently?
* What are the most common side effects?
* How severe are the reported side effects?
* How do smoking and alcohol use affect severity?
* What outcomes do patients experience after adverse drug reactions?
* How long does recovery typically take?

---

## Dataset Information

The dataset contains patient-level adverse drug reaction reports with the following features:

| Feature              | Description                   |
| -------------------- | ----------------------------- |
| patient_id           | Unique patient identifier     |
| age                  | Patient age                   |
| gender               | Patient gender                |
| country              | Patient country               |
| drug_name            | Drug taken by patient         |
| dosage_mg            | Drug dosage                   |
| side_effect          | Reported side effect          |
| severity             | Mild, Moderate, Severe        |
| outcome              | Patient outcome               |
| report_date          | Date side effect was reported |
| treatment_start_date | Treatment start date          |
| chronic_condition    | Existing chronic disease      |
| smoker               | Smoking status                |
| alcohol_use          | Alcohol consumption status    |
| hospitalized         | Hospitalization status        |
| recovery_days        | Recovery duration             |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

## Data Cleaning Performed

* Missing value analysis
* Duplicate record detection
* Data type verification
* Date conversion using datetime
* Feature engineering
* Data consistency checks

---

## Exploratory Data Analysis

### Patient Analysis

* Gender Distribution
* Age Distribution
* Country Distribution
* Smoking Status Analysis
* Alcohol Use Analysis
* Chronic Condition Analysis

### Drug Analysis

* Number of Unique Drugs
* Top 10 Most Used Drugs
* Drug Distribution Analysis

### Side Effect Analysis

* Most Common Side Effects
* Side Effects by Gender
* Side Effects by Age Group

### Severity Analysis

* Severity Distribution
* Mild, Moderate, and Severe Case Percentages
* Smoking Status vs Severity
* Alcohol Use vs Severity
* Chronic Condition vs Severity

### Outcome Analysis

* Outcome Distribution
* Recovery Rate
* Hospitalization Rate
* Recovery Time Analysis

---

## Visualizations

The project includes:

* Gender Distribution Chart
* Age Distribution Histogram
* Top 10 Drugs Chart
* Top 10 Side Effects Chart
* Severity Distribution Chart
* Outcome Distribution Chart
* Smoking Status vs Severity Chart
* Alcohol Use vs Severity Chart
* Drug vs Severity Chart
* Recovery Days Histogram

---

## Key Findings

* A small group of drugs accounted for a large percentage of reports.
* Several side effects appeared consistently across multiple drugs.
* Most reported side effects were Mild or Moderate.
* Severe side effects represented a smaller portion of total reports.
* Recovery was the most common patient outcome.
* Adults contributed the highest number of reports.
* Smoking status showed differences in severity distribution.
* Alcohol use showed variations in severity levels.
* Recovery time varied significantly across patients.
* Some drugs were associated with longer recovery periods.

---
## Project Structure

```text
drug-side-effects-analysis/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   └── Drug_Side_Effects_Analysis.ipynb
│
├── images/
│   ├── gender_distribution.png
│   ├── age_distribution.png
│   ├── top_10_drugs.png
│   ├── top_10_side_effects.png
│   ├── severity_distribution.png
│   ├── outcome_distribution.png
│   ├── smoker_vs_severity.png
│   ├── alcohol_vs_severity.png
│   └── recovery_days_histogram.png
│
├── README.md
│
└── requirements.txt
```


## Future Improvements

* Predict severity using Machine Learning
* Predict hospitalization risk
* Predict recovery duration
* Build a Drug Severity Checker
* Create an interactive dashboard using Streamlit

---

## Conclusion

This project demonstrates practical healthcare data analysis using Python, Pandas, and Matplotlib. Through data cleaning, exploratory analysis, and visualization, meaningful insights were extracted regarding drug usage, side effects, severity levels, patient outcomes, and recovery trends.

The project serves as a strong foundation for future machine learning applications in healthcare analytics and pharmacovigilance.

