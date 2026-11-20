## Clinical Trial Data Analysis – Diabetes Medication



### Project Overview

This project explores data from a fictional Phase III clinical trial investigating a new medication for Type 2 diabetes. The analysis examines changes in HbA1c levels across treatment and placebo groups, explores participant characteristics and reviews recorded adverse events.

The aim was to apply Python data analysis techniques to assess the dataset, identify patterns and compare outcomes between the two trial groups.



### Project Objectives

* Inspect and assess the quality and structure of the dataset.
* Explore participant demographics and baseline characteristics.
* Analyse changes in HbA1c levels over the recorded trial period.
* Compare outcomes between the treatment and placebo groups.
* Examine recorded adverse events.
* Apply appropriate statistical tests to investigate differences between groups.
* Identify limitations and communicate findings responsibly.
* 

### Dataset

The dataset contains 1,400 records representing 200 participants, with 100 participants in each trial group.

Each participant has seven recorded measurements across seven time points, from 0 to 24.

The dataset includes:

* Participant ID
* Treatment group
* Age and gender
* Diabetes duration
* Initial HbA1c
* Recorded HbA1c measurements
* Time point
* Recorded adverse events

The dataset is fictional and was provided for learning and portfolio purposes.



### Tools and Technologies

* **Python** – data analysis
* **Pandas** – data manipulation and exploration
* **NumPy** – numerical operations
* **Matplotlib** – data visualisation
* **Seaborn** – statistical visualisation
* **SciPy** – statistical testing
* **Jupyter Notebook** – analysis and documentation
* 

### Analysis and Methodology

The project followed a structured exploratory data analysis (EDA) process:

1. Initial data inspection and quality assessment.
2. Data cleaning and preparation.
3. Exploration of participant demographics and baseline characteristics.
4. Analysis of HbA1c changes over time.
5. Comparison of treatment and placebo outcomes.
6. Patient-level response analysis.
7. Exploration of recorded adverse events.
8. Statistical testing and interpretation.
9. Identification of key findings and limitations.

Welch's independent t-tests and paired t-tests were used to investigate differences between groups and changes within each group.



### Key Findings

* The treatment and placebo groups had broadly similar average ages, diabetes duration and baseline HbA1c levels, although there was a difference in gender composition.
* Both groups showed a reduction in average HbA1c over the recorded period.
* The treatment group showed a larger average reduction in HbA1c than the placebo group.
* The treatment group showed an identical reduction for every participant, which raised concerns about the artificial nature of the dataset.
* Fatigue, nausea, headache and dizziness were the recorded adverse event categories.



### Limitations

Several limitations affect the interpretation of the findings:

* The treatment group showed identical HbA1c reductions across all participants, suggesting a simplified or artificially generated dataset

