# 🏥 National Healthcare Analytics Dashboard | Power BI

An interactive **Healthcare Analytics Dashboard** developed using **Microsoft Power BI** to analyze patient demographics, hospital performance, admission trends, billing metrics, medical conditions, and operational efficiency.

The dashboard transforms healthcare data into meaningful business insights through interactive visualizations, helping administrators and decision-makers monitor key healthcare metrics and identify trends.

---

# 📌 Problem Statement

Healthcare organizations generate large volumes of patient, clinical, operational, and financial data. Analyzing this information efficiently is essential for improving hospital performance, monitoring patient admissions, understanding medical condition trends, and evaluating operational efficiency.

This project provides an interactive Power BI dashboard that consolidates healthcare data into a single reporting solution, enabling users to explore healthcare metrics and make data-driven decisions.

---

# 🎯 Project Objectives

- Analyze patient demographics across different age groups and genders.
- Monitor hospital admissions and patient distribution.
- Compare medical conditions across hospitals.
- Analyze admission trends over time.
- Monitor Length of Stay (LOS) patterns.
- Evaluate billing performance.
- Analyze Emergency, Elective, and Urgent admissions.
- Create an interactive dashboard for healthcare analytics.

---

# 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel
- Data Modeling
- Git & GitHub

---

# 📂 Dataset

The dashboard is built using a healthcare dataset containing **approximately 55,000 patient records** stored in Excel workbook.

## Dataset Columns

| Category | Columns |
|----------|----------|
| Patient Information | Patient ID, Age, Gender, Blood Type |
| Medical Information | Medical Condition, Medication, Test Results |
| Admission Details | Date of Admission, Discharge Date, Admission Type |
| Hospital Information | Hospital, Doctor, Room Number |
| Financial Information | Insurance Provider, Billing Amount |
| Geographic Information | Hospital Latitude, Hospital Longitude |

---

# 🧹 Data Preparation

The dataset was imported into Power BI using **Power Query**.

The following transformations were performed:

- Validated data types
- Formatted date columns
- Cleaned categorical values
- Removed inconsistencies
- Created calculated columns
- Prepared data for analysis

### Calculated Column

**Length of Stay (LOS)**

```
LOS = Discharge Date - Date of Admission
```

Patients were grouped into LOS categories:

| LOS Bucket | Days |
|------------|------|
| Short Stay | 1–3 Days |
| Moderate Stay | 4–7 Days |
| Long Stay | 8–14 Days |
| Extended Stay | 15+ Days |

---

# ⭐ Data Model

The dashboard uses a **star schema** with the healthcare admission records as the central fact table.

Additional supporting objects were created in Power BI including:

- Calendar Table
- DAX Measures
- Calculated Columns
- Field Parameters

These improve report performance and enable time intelligence and interactive reporting.

---

# 📊 Key Performance Indicators

- 👥 Total Admitted Patients
- 👨‍⚕️ Total Doctors
- 🏥 Rooms / Bedspace
- 💰 Average Billing Amount
- 🎂 Average Patient Age
- 📅 Average Length of Stay (LOS)

---

# 📈 Dashboard Features

## 📄 Page 1 – Demographics Overview

### Executive KPIs

- Total Admitted Patients
- Doctors
- Rooms / Bedspace
- Average Billing Amount
- Average Age
- Average Length of Stay

### Interactive Filters

- Year
- Month
- Medical Condition

### Visualizations

- Age Group vs Gender Analysis
- Medical Condition Distribution
- Hospital-wise Patient Distribution
- Hospital × Medical Condition Matrix
- Test Result Summary
- Medical Condition Profile

### Interactive Features

- Bookmark Navigation
- Age Group View
- Medical Condition View
- Blood Group View

---

## 📄 Page 2 – Key Trends & Behavior Analysis

### Trend Analysis

Dynamic trend chart allowing users to switch between:

- Admitted Patients
- Average Billing Amount
- Average LOS

using **Power BI Field Parameters**.

### Additional Visualizations

- Admission Type Comparison
- LOS Bucket Distribution
- Admission Heatmap
- Hospital Filter
- Medical Condition Filter

---

# 🔄 Interactive Features

### Bookmarks

Implemented bookmark buttons allowing users to switch between multiple analytical views without changing slicer selections.

### Field Parameters

Implemented Field Parameters to dynamically change the KPI displayed in the trend chart.

### Reset Button

A universal Reset button clears all slicers and restores the dashboard to its default state.

---

# 📊 Key Insights

The dashboard enables healthcare stakeholders to:

- Monitor hospital performance.
- Analyze patient demographics.
- Compare medical conditions.
- Track admission patterns.
- Understand Length of Stay behaviour.
- Evaluate billing performance.
- Analyze admission types.
- Explore healthcare trends interactively.

---

# 💡 Skills Demonstrated

- Power BI Dashboard Development
- Power Query (ETL)
- DAX Measures
- Calculated Columns
- Data Cleaning
- Data Transformation
- Data Modeling
- Star Schema Design
- Time Intelligence
- Interactive Reporting
- KPI Development
- Bookmarks
- Field Parameters
- Healthcare Analytics
- Business Intelligence

---

# 📁 Repository Structure

```
National-Health-Dashboard/
│
├── README.md
│
├── Dashboard/
│   ├── National Health Dashboard.pbix
│   └── National Health Dashboard.pdf
│
├── Dataset/
│   └── Healthcare_Analysis_Dataset.xlsx
│
└── Images/
    ├── Dashboard_Page1.png
    └── Dashboard_Page2.png
```

---

# 📸 Dashboard Preview

## Demographics Overview

![Dashboard Page 1](Images/Dashboard_Page1.png)

---

## Key Trends & Behaviour Analysis

![Dashboard Page 2](Images/Dashboard_Page2.png)

---

# 🚀 Future Enhancements

- Predictive Healthcare Analytics
- Readmission Rate Analysis
- Department-wise Performance Dashboard
- Real-time Database Integration
- Healthcare Resource Utilization Analysis
- Machine Learning-based Admission Forecasting

---

# 👤 Author

**Harshita Dhiman**

**Lead Associate – Data Engineering**

### Connect with Me

- LinkedIn: *Add your LinkedIn profile URL here*
- GitHub: *Add your GitHub profile URL here*

---

⭐ If you found this project interesting, consider giving this repository a star!
