### Summative Assessment 2: Statistical Computing

#### Data Meets Method: Collaborative Exploration of Advanced Resampling & Interference

We are a team of student data scientists working in a multidisciplinary research initiative that explores real-world phenomena using advanced statistical methods. Our focus lies on applying resampling and inferential techniques to uncover insights from data in domains such as public health, finance, and climate science. For this project, we investigate the **burden of duenge in the Philippines** using a comprehensive dataset spanning several demographic dimensions.

**Group Members:**
* Team Leader: Kyte Daiter Percia
* Team Member: Lindsay Faith Bazar
* Team Member: Jade Marco Morillo

## Title of Research

# Beyond the Numbers: A Resampling & Bayesian Perspective on Dengue Burden in the Philippines by Age, Sex, and Region (20011-2015)

## Outline:

### **I. Introduction and Dataset Overview**

Dengue fever remains a persistent and growing public health concern in tropical regions, particularly in the Philippines (Villejo et al., 2025). Characterized by seasonal urges, regional disparities, and demographic-specific risks, dengue's complex dynamics make it an ideal case for rigorous statistical exploration.

In this project, we utilize a dataset comprising monthly dengue case and death counts across all 17 administrative regions of the Philippines from 20011 to 2015. What sets this dataset apart is its multidimensional disaggregation by:

* **Age group**: `<1`, `1–4`, `5–14`, `15–24`, `25–39`, `40–64`, `65+`, and `Unspecified`
* **Sex**: `Male`, `Female`
* **Region**: All official regions in the Philippines

*See `Datasets` folder above* 

Each observation represents a unique combination of these attributes per year, allowing for an in-depth temporal and demographic analysis. The dataset contains both **dengue cases and deaths**, enabling the computation of important metrics such as the **case fatality rate (CFR)**. This detail provides a foundation for statistical analysis that spans descriptive analytics, uncertainty quantification, hypothesis testing, and Bayesian inference.

To fully leverage this dataset, we begin by exploring its structure and performing preliminary analysis in the next section. This **Exploratory Data Analysis (EDA)** phase will help identify trends, outliers, and potential data quality issues. We will also prepare and clean the dataset to ensure it is suitable for the advanced statistical procedures that follow in the subsequent components of this project.

### **II. Exploratory Data Analysis (EDA)**

*See `Exploratory Data Analysis (EDA)` folder above*

### **III. Problem Statement**

In this research, we aim to quantify and explain disparities in dengue bruden in the Philippines using half a decade of surveillance data disaggregated by sex, age, region, and time. Our central goal is to understand whether these disparities are statistically significant and stable over time, and to quantify the uncertainty in key summary metrics using resampling and Bayesian inference. We apply a range of statistical techniques - from bootsrap estimation to permutation testing and MCMC - to build a rigorous, multi-faceted view of dengue severity and distribution.

With that, we aim the answer the problem:

**1. How does the burden and severity of dengue fever vary across regions, sexes, and age groups in the Philippines from 2008 to 2015, and how reliably can these patterns be modeled and inferred using advanced resampling and Bayesian techniques?**

**Sub-Questions for Problem Statements**
1. Temporal-Regional Burden
* * *Are certain regions consistently more affected over time in terms of both dengue cases and deaths?*
* * *What is the uncertainty in regional averages of yearly cases/deaths?*

→ Use for: **Bootstrap & Jackknife**, **Probability Density Estimation**
 
2. Sex-Based Differences in Dengue Outcomes
* * *Do males and females exhibit significantly different dengue case fatality rates across regions?*
* * *Is the sex effect stable or variable across regions and time?*
 
→ Use for: **Permutation Tests**, **Bootstrap CI**, **Model Validation**

3. Age Group Vulnerability and Mortality
* * *Which age groups are most vulnerable to infection and death?*
* * *Is CFR disproportionately higher in older or younger age groups?*
* * *How much uncertainty is there in these rates?*

→ Use for: **Bayesian Modeling (e.g., logistic regression)**, **Bootstrap**, **MCMC**

4. Modeling and Predicting Severity
* * *Can we predict dengue deaths from case counts and demographic variables (sex, age, region)?*
* * *Which predictors (age, sex, region) contribute most to death probability?*

→ Use for: **Resampling for Model Validation**, **MCMC for Bayesian Inference**

5. Statistical Inference of Group Differences

* * Are differences in dengue outcomes between any two regions statistically significant, or could they be due to chance?*

→ Use for: **Permutation Tests**, **Bootstrap**

### **IV. Components & Analysis Plan**

#### **1. Bootstrap & Jackknife: Estimating Uncertainty of the Mean Dengue Cases**

*See `Bootstrap & Jackknife` folder above*

#### **2. Resampling for Model Validation: Predicting Dengue Cases**

*See `Resampling for Model Validation` folder above*

#### **3. Permutation Test: Are Regional Differences in Cases Significant?**

*See `Permutation Test` folder above*

#### **4. MCMC for Bayesian Inference: Linear Regression Model**

*See `MCMC for Bayesian Inference` folder above*

#### **5. Probability Density Estimation: What is the Shape of Dengue Case Distribution?**

*See `Probability Density Estimation` folder above*

### **V. Summary Report**

*See `Summary Report` folder above*

### References:

Villejo, S. J., Martino, S., & Illian, J. (2025). Linking climate and dengue in the Philippines using a two-stage Bayesian spatio-temporal model. *arXiv preprint arXiv:2506.22334*.
