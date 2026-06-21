# Hospital_Patients_Records_SQL
## Dataset
Synthetic data on ~1k patients of Massachussets General Hospital from 2011-2022, including information on patient demographics, insurance coverage, and medical encounters & procedures. [source: Maven Analytics]
Dataset:[link](https://mavenanalytics.io/data-playground/hospital-patient-records)

## Database Design
- Patients
- Encounters
- Procedures
- Payers

## SQL SKills Demonstrated
- Joins
- Aggregations
- Group By
- Date Functions
- Case Statements
- Sorting and Filtering

## Analysis Objectives
### Objective 1: Encounter Analysis
- Q1. How has the number of patient encounters changed over time?
- Q2. Which encounter classes are most frequently recorded?
- Q3. How are encounters distributed across different healthcare payers?
- Q4. Which encounter classes contribute the highest average claim costs?
- Q5. Which encounter classes generate the highest total healthcare expenditure?
- Q6. Which year recorded the highest overall claim costs?

### Objective 2: Procedure Analysis
- Q7. Which medical procedures are performed most frequently?
- Q8. Which medical procedures have the highest average cost and how often are they performed?

### Objective 3: Payer Analysis
- Q9. Which healthcare payers provide the highest average coverage per encounter?

### Objective 4: Patient Demographic Analysis
- Q10. What is the demographic profile of the patient population?
- Q11. How are patients distributed across different age groups?

### Objective 5: Patient Utilisation Analysis
- Q12. Which patients have the highest number of healthcare encounters?

## Major Findings
### Encounter Analysis
- In general, the healthcare encounter volumes can be seen increasing over time.
- 2014 recorded the highest number of encounters (3,885), while 2021 also showed a notable increase (3,530).
- Ambulatory encounters were the most common encounter class (12,537 encounters), accounting for a significant proportion of all healthcare interactions.
- Inpatient encounters were the least frequent (1,135 encounters) but had the highest average claim cost (7761.35).

### Cost Analysis
- Inpatient encounters had the highest average claim cost (7,761.35), followed by urgent care (6,369.16) and emergency encounters (4,629.65).
- Although inpatient encounters were the most expensive on average, ambulatory encounters generated the highest total healthcare cost (1.33 million) due to their substantially higher volume.
- 2014 generated the highest overall claim cost (12.01 million), indicating a combination of high encounter volume and healthcare expenditure during that year.

### Procedure Analysis
- The most frequently performed procedure was Assessment of Health and Social Care Needs, with 4,596 occurrences, followed by Hospice Care and Depression Screening procedures.
- ICU Admission was the most expensive procedure with an average base cost of 206,260.40, significantly higher than all other procedures.

### Payer Analysis
- Medicare was associated with the highest number of encounters (11,371), followed by No Insurance (8,807) and Medicaid (1,443).
- Medicaid provided the highest average coverage per encounter (5,833.66), substantially exceeding the coverage amounts provided by other payers.

### Patient Demographics
- The patient population was concentrated in Boston (541 patients) accounting for more than half of all locations while other locations included Quincy (80 patients), Cambridge (45) and Revere (42).
- The majority of patients were aged over 60 years (678 patients), indicating that older adults represented the largest healthcare-consuming population in the dataset.
