### Summative Assessment 2: Statistical Computing

#### Data Meets Method: Collaborative Exploration of Advanced Resampling & Interference

We are a team of student data scientists working in a multidisciplinary research initiative that explroes real-world phenomena using advanced statistical methods. Our focus lies on applying resampling and inferential techniques to uncover insights from data in domains such as public health, finance, and climate science. For this project, we investigate the **burden of duenge in the Philippines** using a comprehensive dataset spanning several demographic dimensions.

**Group Members:**
* Team Leader: Kyte Daiter Percia
* Team Member: Lindsay Faith Bazar
* Team Member: Jade Marco Morillo

## Title of Research

# Beyond the Numbers: A Resampling & Bayesian Perspective on Dengue Burden in the Philippines by Age, Sex, and Region (2008-2015)

## Outline:

### **I. Introduction and Dataset Overview**

Dengue fever remains a persistent and growing public health concern in tropical regions, particularly in the Philippines (Villejo et al., 2025). Characterized by seasonal urges, regional disparities, and demographic-specific risks, dengue's complex dynamics make it an ideal case for rigorous statistical exploration.

In this project, we utilize a a dataset comprising monthly dengue case and death counts across all 17 administrative regions of the Philippines from 2008 to 2015. What sets this dataset apart is its multidimensional disaggregation by:

* **Age group**: `<1`, `1–4`, `5–14`, `15–24`, `25–39`, `40–64`, `65+`, and `Unspecified`
* **Sex**: `Male`, `Female`, `Unspecified`
* **Region**: All official regions in the Philippines

*See `Datasets` branch above* 

Each observation represents a unique combination of these attributes per month and year, allowing for an in-depth temporal and demographic analysis. The dataset contains both **dengue cases and deaths**, enabling the computation of important metrics such as the **case fatality rate (CFR)**. This detail provides a foundation for statistical analysis that spans descriptive analytics, uncertainty quantification, hypothesis testing, and Bayesian inference.

To fully leverage this dataset, we begin by exploring its structure and performing preliminary analysis in the next section. This **Exploratory Data Analysis (EDA)** phase will help identify trends, outliers, and potential data quality issues. We will also prepare and clean the dataset to ensure it is suitable for the advanced statistical procedures that follow in the subsequent components of this project.

### **II. Exploratory Data Analysis (EDA)**

*See `Exploratory Data Analysis (EDA)` branch above*

### **III. Problem Statement**

### **IV. Components & Analysis Plan**

#### **1. Bootstrap & Jackknife: Estimating Uncertainty of the Mean Dengue Cases**

*See `Bootstrap & Jackknife` branch above*

#### **2. Resampling for Model Validation: Predicting Dengue Cases**

*See `Resampling for Model Validation` branch above*

#### **3. Permutation Test: Are Regional Differences in Cases Significant?**

*See `Permutation Test` branch above*

#### **4. MCMC for Bayesian Inference: Linear Regression Model**

*See `MCMC for Bayesian Inference` branch above*

#### **5. Probability Density Estimation: What is the Shape of Dengue Case Distribution?**

*See `Probability Density Estimation` branch above*

### **V. Summary Report**

*See `Summary Report` branch above*

### References:

Villejo, S. J., Martino, S., & Illian, J. (2025). Linking climate and dengue in the Philippines using a two-stage Bayesian spatio-temporal model. *arXiv preprint arXiv:2506.22334*.
