---
layout: phenotype
title: Hypertension (Drug Code)
phenotype_id: L8Xj47dqHYJdCSZH6Jv4HX
name: Hypertension (Drug Code)
type: Drug
group: Drug
sources: 
    - clinicalcodes
data_sources:
    - Clinical Practice Research Datalink GOLD
clinical_terminologies:
    - Read Version 2
validation:
codelists: Paige_HypertensionDrugCode_L8Xj47dqHYJdCSZH6Jv4HX_Read2.csv
valid_event_data_range: 01/01/1997 - 18/01/2016
sex:
    - Female
    - Male
author:
    - Ellie Paige
    - Jessica Barret
    - David Stevens
    - Ruth H Keogh
    - Michael J Sweeting
    - Irwin Nazareth
    - Irene Peterson
    - Angela M Wood   
publications:
    - Ellie Paige, Jessica Barret, David Stevens, Ruth H Keogh, Michael J Sweeting, Irwin Nazareth, Irene Peterson, Angela M Wood, Landmark Models for Optimizing the Use of Repeated Measurements of Risk Factors in Electronic Health Records to Predict Future Disease Risk. American Journal of Epidemiology, 187(7): 1530-1538, 2018.
status: FINAL
date: 2018-03-23
modified_date: 2018-03-23
version: Revision 1
---

### Primary Care

{% include csv.html csvdata=site.data.codelists.Paige_HypertensionDrugCode_L8Xj47dqHYJdCSZH6Jv4HX_Read2 %}

### Implementation

The benefits of using electronic health records (EHRs) for disease risk screening and personalized health-care decisions are being increasingly recognized. Here we present a computationally feasible statistical approach with which to address the methodological challenges involved in utilizing historical repeat measures of multiple risk factors recorded in EHRs to systematically identify patients at high risk of future disease. The approach is principally based on a 2-stage dynamic landmark model. The first stage estimates current risk factor values from all available historical repeat risk factor measurements via landmark-age–specific multivariate linear mixed-effects models with correlated random intercepts, which account for sporadically recorded repeat measures, unobserved data, and measurement errors. The second stage predicts future disease risk from a sex-stratified Cox proportional hazardsmodel, with estimated current risk factor values from the first stage.We exemplify thesemethods by developing and validating a dynamic 10-year cardiovascular disease risk prediction model using primary-care EHRs for age, diabetes status, hypertension treatment, smoking status, systolic blood pressure, total cholesterol, and high-density lipoprotein cholesterol in 41,373 persons from 10 primary-care practices in England andWales contributing to The Health Improvement Network (1997–2016). Using cross-validation, the model was well-calibrated (Brier score = 0.041, 95% confidence interval: 0.039, 0.042) and had good discrimination (C-index = 0.768, 95%confidence interval: 0.759, 0.777).

### Publications

<pre>
Ellie Paige, Jessica Barret, David Stevens, Ruth H Keogh, Michael J Sweeting, Irwin Nazareth, Irene Peterson, Angela M Wood, Landmark Models for Optimizing the Use of Repeated Measurements of Risk Factors in Electronic Health Records to Predict Future Disease Risk. American Journal of Epidemiology, 187(7): 1530-1538, 2018.
</pre>
