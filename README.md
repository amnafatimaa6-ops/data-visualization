# Hypothesis Testing on Human Behavior Data

## Project Overview
This project applies statistical hypothesis testing techniques to analyse patterns in human behaviour.  
The objective is to determine whether observed differences and relationships in the data are statistically significant or due to random variation.

The analysis follows a structured and reproducible workflow suitable for academic and real-world data science applications.

---

## Dataset
- **Source:** GitHub (loaded dynamically via raw URL)  
- **Format:** CSV  
- **Description:** The dataset contains behavioural and demographic variables used to evaluate statistical hypotheses.  

The dataset is downloaded at runtime to ensure reproducibility and to avoid local file dependency issues.

---

## Hypotheses
The analysis is guided by clearly defined null and alternative hypotheses:

- **H₀ (Null Hypothesis):** There is no significant difference or association between selected variables.  
- **H₁ (Alternative Hypothesis):** A statistically significant difference or association exists.  

Each hypothesis is tested using an appropriate statistical method.

---

## Statistical Tests Used
The following hypothesis testing methods are applied based on data type and assumptions:

- **Z-test** – Comparison of a sample mean with a population mean for large sample sizes  
- **t-test** – Comparison of means when population variance is unknown  
- **One-way ANOVA (f_oneway)** – Comparison of means across more than two groups  
- **Chi-square test** – Testing association between categorical variables  

A significance level (α) of **0.05** is used throughout the analysis.

---

## Assumptions
Before applying hypothesis tests, the following assumptions are considered:

- Observations are independent  
- Data is approximately normal or sample size is sufficiently large (Central Limit Theorem)  
- Variance across groups is comparable where required  
- Sample size is appropriate for each statistical test  

---

## Tools & Libraries
- Python  
- Pandas  
- NumPy  
- SciPy  

