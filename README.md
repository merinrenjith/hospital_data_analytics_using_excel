# 🏥 Healthcare Analytics Dashboard (Excel Project)

### 👩‍💻 Author: Merin Renjith  
### 📅 Completed: October 2025  
### 💾 Tools Used: Microsoft Excel (2016), PivotTables, PivotCharts, Slicers  

---

## 🎯 Objective
To clean, analyze, and visualize a healthcare dataset to uncover trends in **billing**, **admission types**, and **test outcomes**, demonstrating Excel-based analytical and visualization skills for a healthcare analyst role.

---

## 📊 Dataset
**Source:** [Kaggle – Healthcare Dataset by Prasad 22](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)  
**Size:** 55,000 rows × 15 columns  
**Key Fields:** Patient Name, Age, Gender, Hospital, Admission Type, Insurance Provider, Billing Amount, Medical Condition, Medication, Test Results, Admission & Discharge Dates.

---

## ⚙️ Steps Performed
### 1. Data Cleaning
- Removed 5,000+ duplicate records (exact & logical).
- Checked for blanks/missing values.
- Applied `PROPER()` for name capitalization.
- Derived new columns:
  - **Length of Stay (Days)**
  - **Age Group (Child / Adult / Senior)**
  - **Billing Category (High / Medium / Low)**
  - **Billing per Day**
  - **Insurance Status**

### 2. Data Standardization
- Added **Data Validation dropdowns** for Gender, Admission Type, Test Results.  
- Defined **Named Ranges** for dynamic validation lists.  
- Used **Conditional Formatting** to highlight:
  - Bills in the top 10%
  - Long Hospital Stays (>15 days)
  - Abnormal/Inconclusive Test Results.

### 3. Data Analysis
- Created **PivotTables** to summarize metrics:
  - Billing by Age Group
  - Avg Length of Stay by Admission Type
  - Billing per Day by Insurance Provider
  - Billing by Category
  - Test Result Distribution (%)
- Added **Slicers** for dynamic filtering by Admission Type, Insurance, Age Group, and Test Results.

### 4. Visualization & Dashboard
- Designed interactive **Excel Dashboard** combining PivotCharts and KPIs:
  - Total Patients
  - Avg Billing Amount
  - Avg Length of Stay
  - % Abnormal Test Results

---

## 💬 Key Insights
- **Adults** contribute the highest total billing.  
- **Emergency admissions** show slightly longer average stays.  
- **Medicare** has the largest billing per day among insurers.  
- **High Billing Category** accounts for ~70% of total charges.  
- Dataset exhibits uniformity typical of synthetic data.

---

## 🧾 Deliverables
- **Healthcare_Analytics_Project_MerinRenjith.xlsx**
- **Dashboard Preview (PDF)**
- **Data Cleaning Log Sheet**
- **Project Summary Sheet**

---

## 🧠 Learning Outcomes
- Hands-on practice with end-to-end data analysis in Excel.
- Understanding of healthcare data structure (billing, admissions, insurance).
- Developed storytelling and visualization skills using PivotCharts and slicers.

---

## 🗂 Repository Structure
- Healthcare_Data_Analytics_Dashboard.xlsx  
  → Main Excel workbook containing:
    - Raw data
    - Cleaned data
    - PivotTables
    - Interactive dashboard with KPIs and slicers

- README.md  
  → Project overview, objectives, methodology, key insights, and deliverables
