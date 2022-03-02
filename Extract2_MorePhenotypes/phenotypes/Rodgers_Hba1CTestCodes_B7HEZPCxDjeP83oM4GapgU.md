---
layout: phenotype
title: Type 2 Diabetes (Hba1C Test Codes)
phenotype_id: B7HEZPCxDjeP83oM4GapgU
name: Type 2 Diabetes (Hba1C Test Codes)
type: Disease or Syndrome
group: Endocrine
sources: 
    - clinicalcodes
data_sources:
    - Clinical Practice Research Datalink GOLD
clinical_terminologies:
    - Read Version 2
validation:
codelists: Rodgers_Hba1CTestCodes_B7HEZPCxDjeP83oM4GapgU_Read2.csv
valid_event_data_range: 01/01/1900 - 08/08/2016
sex:
    - Female
    - Male
author:
    - Lauren L Rodgers
    - Michael N Weedon
    - William E Henley
    - Andrew T Hattersley
    - Beverley M Shields       
publications:
    - Lauren L Rodgers, Michael N Weedon, William E Henley, Andrew T Hattersley, Beverley M Shields, Cohort profile for the MASTERMIND study using the Clinical Practice Research Datalink (CPRD) to investigate stratification of response to treatment in patients with type 2 diabetes. BMJ Open, 7:e017989, 2017.
status: FINAL
date: 2017-10-12
modified_date: 2017-10-12
version: Revision 1
---

### Primary Care

{% include csv.html csvdata=site.data.codelists.Rodgers_Hba1CTestCodes_B7HEZPCxDjeP83oM4GapgU_Read2 %}

### Implementation
Purpose:
This is a retrospective cohort study using observational data from anonymised primary care records. We identify and extract all patients with type 2 diabetes and associated clinical data from the Clinical Practice Research Datalink (CPRD) to inform models of disease progression and stratification of treatment.

Participants:
Data were extracted from CPRD on 8 August 2016. The initial data set contained all patients (n=313 485) in the database who had received a type 2 diabetes medication. Criteria were applied to identify and exclude those with type 1 diabetes, polycystic ovarian syndrome or other forms of diabetes (n=40 204), and for data quality control (n=12). We identified 251 338 patients for inclusion in future analyses of diabetes progression and treatment response.

Findings to date:
For 6-month response to treatment, measured by change in glycated haemoglobin (HbA1c), we have 91 765 patients with 119 785 treatment response episodes. The greatest impact on reduction of HbA1c occurs with first-line and second-line treatments, metformin and sulfonylurea. Patients moving to thirdline treatments tend to have greater weights and higher body mass index. We have investigated the impact of non-adherence to commonly used glucose-lowering medications on HbA1c. For baseline-adjusted HbA1c change over 1 year, non-adherent patients had lower HbA1c reductions than adherent patients, with mean and 95% CI of −4.4 (−4.7 to −4.0) mmol/mol (−0.40 (−0.43 to −0.37) %).

Future plans: 
Findings from studies using these data will help inform future treatment plans and guidelines. Additional data are added with updates from CPRD. This will increase the numbers of patients on newer medications and add more data on those already receiving treatment. There are several ongoing studies investigating different hypotheses regarding differential response to treatment and progression of diabetes. For side effects, links to Hospital Episode Statistics data, where severe events such as hypoglycaemia will be recorded, will also be explored.

### Publications

<pre>
Lauren L Rodgers, Michael N Weedon, William E Henley, Andrew T Hattersley, Beverley M Shields, Cohort profile for the MASTERMIND study using the Clinical Practice Research Datalink (CPRD) to investigate stratification of response to treatment in patients with type 2 diabetes. BMJ Open, 7:e017989, 2017.
</pre>