# Secure_Life_General_Hospital_Performance_Dashboard
An Interactive dashboard that analyses patient admission, billing and insurance records.

# Introduction

<img width="1670" height="941" alt="Introductory image 1" src="https://github.com/user-attachments/assets/8a960691-3a70-4f48-bb07-eb80342f38e3" />

This project analyses patient admission, billing and insurance records for Secure Life General Hospital and presents the results in an interactive Excel dashboard. The aim is to turn a row-level patient-visit dataset into a consolidated view of service utilisation, departmental activity, billing, payment status and insurance coverage. The analysis is intended to support hospital management monitoring and evidence-informed operational and financial decisions.

# About the Dataset
The supplied workbook contains 1,000 records, with each row representing one patient visit (not necessarily one unique person). Admission dates range from January 1, 2024 to 28 Dec 2025. The dataset includes patient ID and name, age, gender, admission and discharge dates, department, diagnosis, total bill amount, payment status, insurance coverage percentage, estimated insurance coverage amount, patient responsibility amount, length of stay, paid amount and age group.
The six departments represented are General, Emergency, Orthopedics, Pediatrics, Cardiology and Neurology. The payment status is defined as Paid, Pending and Partially Paid. 

# Problem Statement
Hospital management has observed changes in patient admissions, outstanding medical bills and insurance coverage across departments. The hospital lacks a consolidated report that clearly presents operational and financial performance. This analysis therefore examines patient visits, departmental demand and billing, length of stay, payment status, outstanding balances, insurance coverage, age groups and changes over time.

# Visualization
The dashboard brings together headline KPIs and charts for departmental visits, departmental billing, payment status and age-group distribution. 

<img width="1727" height="694" alt="Screenshot 2026-11-04 115614" src="https://github.com/user-attachments/assets/c07de564-89c4-4f38-b0eb-f8c352e871f7" />

# Key Insights
I.The dataset records 1,000 patient visits and total billed charges of $8,053,143.44.
II.General recorded the highest visit volume (252 visits), while Orthopedics generated the highest total bills ($2,553,862.32).
III.Orthopedics had the longest average stay (8.38 days); Emergency had the shortest (2.03 days).
IV.Payment status by visit: Paid 564 (56.73%); Pending 257 (25.86%); Partially Paid 179 (17.41%).
V.The recorded paid amount totals $4,568,527.32. Total bills less this recorded amount gives a calculated outstanding balance of $3,484,616.12.
VI.The 51–65 age group had the highest number of visits (235), closely followed by patients aged 66 and above (232).
VII.Average insurance coverage across all visits was 74.86%. Cardiology had the highest departmental average (76.32%); General had the lowest (73.89%).
VIII.There were 508 visits in 2024 and 492 in 2025. Total billed amount was $4,132,465.36 in 2024 and $3,920,678.08 in 2025.

# Recommendations
a.Prioritise a departmental review of Orthopedics and Cardiology because they account for the largest billed amounts; examine service mix, resource use and billing processes.
b.Review staffing, bed utilisation and discharge processes in General, which has the highest visit volume, and in Orthopedics, which has the longest average stay.
c.Establish a routine receivables follow-up process for Pending and Partially Paid accounts, with clear ownership, ageing reports and escalation timelines.
d.Review insurance arrangements and claim workflows by department and diagnosis to identify areas with lower average coverage and potential reimbursement gaps.
e.Monitor admissions and billed amounts monthly so management can identify changes early and compare service demand with available capacity.
f.Improve data capture by ensuring that actual amounts received are entered for partially paid visits and that payment status is consistent with the recorded paid amount.

# Conclusion
The analysis provides a consolidated overview of patient visits, departmental workload, billed amounts, payment status, insurance coverage and length of stay. It highlights where service demand and billed value are concentrated, while also identifying a payment-recording issue that affects the reliability of the outstanding-balance estimate. With improved payment data quality and regular monitoring, the dashboard can support more informed operational and financial decisions at Secure Life General Hospital.
