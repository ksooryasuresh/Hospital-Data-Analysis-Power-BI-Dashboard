# Hospital-Data-Analysis-Power-BI-Dashboard

### Tools: Microsoft Excel · Power BI · DAX · Power Query

An end-to-end healthcare analytics project: raw hospital records were cleaned and validated in Excel, enriched with financial calculated fields, and turned into an interactive Power BI dashboard that surfaces insights on patients, diseases, treatments, costs and hospital performance.


## 📌 Project Objective

Hospitals generate large volumes of patient, treatment and billing data, but raw records are often incomplete and inconsistent. The goal of this project was to:

- Turn messy healthcare data into a clean, reliable dataset
- Build financial metrics that explain where costs come from
- Give decision-makers a single interactive view of patient, disease, treatment and hospital-level performance

## 🗂️ Dataset Overview

The dataset contains hospital admission records with fields such as:

| Category	| Example Fields
|--------|------|
| Patient |	Patient ID, Age, Gender, Blood Group |
| Clinical  |	Disease / Diagnosis, Treatment Type, Doctor |
| Admission	| Admission Date, Discharge Date, Length of Stay|
| Hospital	| Hospital Name, City / Region, Department|
| Financial |	Room Charges, Medicine Cost, Treatment Cost, Discount, Insurance |

## 🧹 Data Cleaning & Validation (Excel)

- Missing values – identified blanks and handled them by imputation or removal depending on the field
- Inconsistencies – standardised text (disease names, gender, hospital names), fixed date formats and corrected invalid entries
- Duplicates – detected and removed duplicate patient/admission records
- Validation – checked that discharge dates fall after admission dates and that costs are non-negative

## 📊 Power BI Dashboard

Features

- KPI cards – Total Patients, Total Revenue, Average Bill, Average Length of Stay, Average Cost per Day
- Bar charts – Patients and revenue by disease, department and hospital
- Line charts – Admission and cost trends over time
- Pie / donut charts – Gender split, age groups, treatment types
- Slicers – Filter by hospital, disease, gender, age group and date
- Drill-down – Move from hospital → department → disease → treatment level

## 💡 Key Insights

- Identified the diseases with the highest patient volume and how they trend over time
- Highlighted treatments and diseases that drive the highest average and per-day costs
- Revealed patient profile patterns across age groups and gender
- Compared hospitals on patient load, revenue, average bill and length of stay to spot high and low performers

 

## Dashboard 


<img width="1102" height="586" alt="hospital data img 1" src="https://github.com/user-attachments/assets/a9063c5c-5395-4718-802d-cc79c264441b" />

<img width="1102" height="583" alt="hospital data img 2" src="https://github.com/user-attachments/assets/109699a2-d82d-447e-8102-d61840250428" />

<img width="1106" height="586" alt="hospital data img 3" src="https://github.com/user-attachments/assets/d5ef775e-5439-4e54-a888-caf7d1da4743" />

## 🚀 How to Use

1. Download or clone this repository
2. Open the .pbix file in Power BI Desktop
3. Use the slicers and drill-down to explore the data


## 📬 Connect With Me

Soorya Suresh  LinkedIn: www.linkedin.com/in/sooryasureshk     Email: ksooryasuresh@gmail.com

⭐ If you found this project useful, feel free to star the repository!






