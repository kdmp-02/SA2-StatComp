## **V. Summary Report**

### **Beyond the Numbers: A Resampling & Bayesian Perspective on Dengue Burden in the Philippines by Age, Sex, and Region (2011–2015)**

In this project, we embarked on a rigorous statistical investigation into the burden of dengue in the Philippines, analyzing disaggregated case and death data from 2011 to 2015 across **age groups**, **sex**, and **regions**. Leveraging a powerful combination of **resampling techniques** and **Bayesian inference**, we explored disparities, modeled severity, and quantified uncertainty in dengue outcomes to support a more data-informed understanding of this pressing public health issue.

Our analysis was structured around five key components, each targeting a specific aspect of the data through different statistical lenses:

### **1. Temporal-Regional Burden**

We began by analyzing how dengue cases and deaths varied over time across regions. Using **bootstrap** and **jackknife resampling**, we estimated the average yearly burden in each region and generated **confidence intervals** around those estimates. The analysis revealed consistent regional disparities—particularly high burdens in densely populated and urbanized regions such as NCR and Regions IV-A and III. The uncertainty intervals helped contextualize apparent differences, identifying which trends were statistically robust versus possibly due to sampling variability.

### **2. Sex-Based Differences in Dengue Outcomes**

To assess whether dengue severity varied by sex, we compared case fatality rates (CFRs) between males and females. Using **permutation testing** and **bootstrap confidence intervals**, we tested the null hypothesis of no difference in CFR by sex. Results indicated subtle but statistically significant differences in certain years and regions, with males occasionally showing higher fatality rates. However, these effects were not uniform across space or time, highlighting the importance of localized, granular analysis.


### **3. Age Group Vulnerability and Mortality**

This component examined vulnerability to infection and death across different age groups. Bayesian logistic regression models, using **MCMC sampling**, estimated the posterior probability of death by age group. We found disproportionately higher CFRs among the **elderly (65+)** and **infants (<1 year)**, with tight credible intervals confirming these trends as credible signals rather than noise. This insight is critical for guiding age-targeted interventions and health prioritization.


### **4. Modeling and Predicting Severity**

To generalize and predict fatal outcomes, we built **predictive models** of death probability using predictors like **Region**, **Year**, and **log-transformed case counts**. We first employed **frequentist logistic regression** with **bootstrap validation** to understand model stability. Then, we transitioned to a **Bayesian framework (via MCMC)** to generate full posterior distributions of the model coefficients. The strongest predictor of fatality was the total number of cases (log-transformed), suggesting systemic strain during outbreaks contributes to death risk. The Bayesian approach provided richer interpretations through posterior probabilities and credible intervals, giving a more complete picture of model uncertainty and effect direction.


### **5. Statistical Inference of Group Differences**

Finally, we performed **groupwise statistical inference** using **permutation tests** and **bootstrapped difference in means** to formally test whether observed differences in CFR across age, sex, and region were statistically significant. These tests reinforced earlier findings and allowed us to make cautious, evidence-based claims about which group-level disparities were robust versus inconclusive.


### **Overall Reflections and Contributions**

This project highlights the value of combining **resampling methods** (e.g., bootstrap, permutation tests) with **Bayesian inference** to go beyond simple point estimates. Through these methods, we were able to **quantify uncertainty**, **validate models**, and **test hypotheses** with minimal reliance on unrealistic assumptions. Bayesian methods, in particular, proved powerful in modeling complex real-world relationships and providing interpretable, probabilistic outputs—ideal for public health decision-making.

Our findings underscore several critical points:

* Dengue burden is not uniformly distributed—it varies significantly by region, sex, and age.
* Older adults and infants are most at risk of death from dengue.
* High case counts likely overwhelm healthcare systems and contribute to increased fatality risk.
* Data-driven methods can illuminate inequities and guide targeted health policy.

This work demonstrates the power of **collaborative, multidisciplinary statistical analysis** in addressing real-world problems and supports a vision of public health informed by **rigorous, transparent, and reproducible analytics**.

