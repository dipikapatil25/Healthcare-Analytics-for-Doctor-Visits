# Healthcare Analytics for Doctor Visits

## Project Overview

This project focuses on analyzing healthcare data related to doctor visits using Python. The main objective is to explore patterns in doctor visits and understand how factors such as gender, age, and illness are related to the recorded number of visits.

The project uses Exploratory Data Analysis (EDA) techniques and data visualizations to identify useful patterns in the dataset.

## Dataset

* **Number of records:** 5,190
* **Number of variables:** 13
* **File format:** CSV

### Main Variables

* `visits` – Recorded number of doctor visits
* `gender` – Gender of the individual
* `age` – Age-related value provided in the dataset
* `income` – Income-related variable
* `illness` – Illness score
* `reduced` – Reduced activity information
* `health` – Health-related variable
* `private` – Private insurance information
* `freepoor` – Free/poor insurance information
* `freerepat` – Free/repatriation information
* `nchronic` – Number of chronic conditions
* `lchronic` – Long-term chronic condition information

## Objectives

The main objectives of this project are:

1. Understand the structure of the healthcare dataset.
2. Check the dataset for missing values.
3. Analyze the distribution of gender.
4. Analyze the distribution of age-related values.
5. Study the distribution of doctor visits.
6. Compare doctor visits across gender.
7. Analyze the relationship between illness score and doctor visits.
8. Explore the relationship between age, visits, and gender using visualizations.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab / Jupyter Notebook

## Data Analysis Performed

### 1. Dataset Exploration

The project includes:

* First five rows of the dataset
* Last five rows of the dataset
* Dataset shape
* Dataset information
* Descriptive statistics
* Missing-value checking

### 2. Univariate Analysis

The following distributions were analyzed:

* Gender distribution
* Age distribution
* Doctor visits distribution

### 3. Gender Analysis

Doctor visits were grouped by gender and analyzed using:

* Number of records
* Mean visits
* Median visits

### 4. Illness Analysis

The average number of doctor visits was analyzed for different illness scores.

The analysis shows that the recorded average visits generally increase as the illness score increases.

### 5. Multivariate Analysis

The project includes:

* Distribution of visits by gender using a box plot
* Relationship between age and doctor visits, with gender represented using different groups

## Key Observations

* The dataset contains **5,190 records and 13 variables**.
* Recorded doctor visits range from **0 to 9**.
* The overall mean of recorded doctor visits is approximately **0.302**.
* In this dataset, the female group has a higher mean recorded number of visits than the male group.
* Average recorded visits generally increase across higher illness-score groups.
* Most recorded visit counts are concentrated at lower values.

## Project Files

The GitHub repository contains:

* `Healthcare Analytics for Doctor Visits.ipynb` – Python/Jupyter Notebook containing the analysis
* `1776250375-P2-Healthcare Analytics for Doctor Visits (1).csv` – Dataset
* `Healthcare Analytics for Doctor Visits.pptx` – Project presentation
* `README.md` – Project documentation

## Future Scope

The project can be extended by:

* Developing a predictive model for doctor visits
* Applying statistical tests
* Adding more healthcare and demographic variables
* Creating an interactive healthcare dashboard
* Applying machine learning techniques
* Analyzing chronic conditions in greater detail
* Using larger healthcare datasets

## Conclusion

This project demonstrates how Exploratory Data Analysis can be used to study healthcare data and identify patterns in doctor visits. Python libraries such as Pandas, Matplotlib, and Seaborn were used to process, analyze, and visualize the dataset.

## Author

Dipika Dnyaneshwar Patil

Healthcare Analytics for Doctor Visits
Python | Pandas | Matplotlib | Seaborn | Google Colab
