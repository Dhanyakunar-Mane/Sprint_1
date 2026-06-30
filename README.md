# 📊 Sprint 1: Data Architecture, ETL & Foundational Analytics

<p align="center">
  <b>Data Analytics Pipeline Blueprint & KPI Prototyping in Excel & Power BI</b><br><br>

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Power BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Analytics](https://img.shields.io/badge/Domain-Data%20Analytics-blue?style=for-the-badge)
![Focus---ETL](https://img.shields.io/badge/Focus-Data%20Modeling%20%26%20ETL-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Sprint--Complete-success?style=for-the-badge)

</p>

---

## 📌 Overview

**Sprint 1** establishes the core data infrastructure, structural ETL (Extract, Transform, Load) pipelines, and initial analytical baselines for the project. 

Instead of jumping straight to final dashboard cosmetics, this milestone focuses on transforming raw data into a cleaned, structured, and high-performance data model within both **Microsoft Excel** and **Power BI**. This sprint lays down the foundational metrics and dynamic relationships required to power all subsequent reporting and visual storytelling.

---

## 🎯 Sprint Objectives

* Establish reproducible data extraction and cleaning protocols across raw source files.
* Design a robust, scalable relational data model (Star Schema / Snowflake Schema) in Power BI.
* Construct the core DAX measures and Excel formulas for foundational KPI calculations.
* Build initial exploratory layout mockups to map out the user experience (UX) journey.
* Eliminate data redundancies, handle missing values, and optimize data types for fast query execution.

---

## 🖼️ Architecture & Model Preview

<p align="center">

### 📐 Data Model & Relationship View (Power BI)

<img src="path_to_data_model_image.png" width="95%" alt="Sprint 1 Data Model Architecture"/>

<br><br>

### 📈 Initial Layout Mockup & Pivot Wireframe

<img src="path_to_mockup_image.png" width="95%" alt="Sprint 1 Dashboard Layout Wireframe"/>

</p>

---

## 📊 Core Milestone Matrix

| Track / Metric            | Status     | Target Deliverable Description       |
| ------------------------- | ---------- | ------------------------------------ |
| **Data Rows Cleaned**     | Complete   | Successfully parsed and profiled raw data rows |
| **Data Modeling**         | 1:Many Verified | Core tables correctly related via key fields |
| **Core DAX / Formulas**   | Operational| Basic measures (Sums, Averages, Counts) written |
| **Refresh Latency**       | Optimized  | Data types minimized to reduce memory footprint |
| **Power Query Steps**     | Documented | Transformation steps organized for easy maintenance |

---

## ⚙️ Core Deliverables & Data Engineering

### 1. 🧹 Advanced Data Cleaning & Transformation
* **Implementation:** Power Query (M Language) & Excel Data Tools.
* **Focus:** Standardizing date formats, handling null/blank values, splitting text strings, and removing duplicates.
* **Outcome:** Pristine, structured datasets ready for analytical computations without calculation errors.

---

### 2. 📐 Data Modeling & Star Schema Blueprint
* **Implementation:** Power BI Relationship View / Power Pivot in Excel.
* **Focus:** Establishing clear 1-to-many relationships between Fact tables and Dimension tables.
* **Outcome:** Fast cross-filtering across visuals and completely accurate multi-dimensional reporting.

---

### 3. 🧮 Foundational KPI Metrics
* **Implementation:** DAX Measures (Power BI) & Core Statistical Functions (Excel).
* **Focus:** Writing primary metrics like Total Records, Running Averages, Year-over-Year baselines, and Group Segmentations.
* **Outcome:** A reliable, centralized calculation matrix that ensures identical values across both software platforms.

---

## 🔍 Interactivity & Control Architecture

### Excel Setup
* **Pivot Wireframes:** Early-stage pivot structures mapping data distributions.
* **Initial Slicer Links:** Establishing preliminary report connections to test filtering boundaries.
* **Data Formatting:** Strict currency, decimal, and location tagging rules configured.

### Power BI Setup
* **Dynamic Measure Folders:** All calculated DAX metrics organized into dedicated measure tables.
* **Preliminary Visual Scaffolding:** Draft cards and coordinate grids mapping out visual real estate.
* **Cross-Filter Tuning:** Visual interactions customized to prevent unhelpful chart behavior.

---

## 🛠️ Tools, Techniques & Frameworks

### 📊 Data Manipulation & Transformation
* **Power Query Editor:** M-code optimization and applied step sequencing.
* **Excel Power Pivot:** Data modeling and analytical hierarchies within spreadsheets.
* **Data Profiling:** In-depth analysis of column quality, distribution, and value profiles.

### 📐 Analytics & Calculations
* **DAX (Data Analysis Expressions):** Time intelligence functions, filter modifiers (`CALCULATE`), and basic aggregations.
* **Advanced Excel Formulas:** Complex logic chains (`INDEX/MATCH`, `XLOOKUP`, `IFS`, and array manipulation).

---

## 🧱 Project Directory Structure

```text
📦 Dhanyakumar-Mane-Sprint_1
┣ 📂 Data
┃ ┣ 📄 Raw_Dataset_Source.csv        # Untouched source data files
┃ ┗ 📄 Cleaned_Dataset_Output.xlsx   # Processed data post-ETL stage
┣ 📂 Dashboards
┃ ┣ 📄 Sprint1_Model_Prototype.pbix  # Power BI file housing model & DAX base
┃ ┗ 📄 Sprint1_Pivot_Analysis.xlsx   # Excel workbook containing core pivot models
┣ 📂 Documentation
┃ ┗ 📄 Data_Dictionary.md            # Metadata and column definitions
┣ 📂 Mockups
┃ ┗ 📄 Wireframe_Layout_Drafts.png   # Dashboard UI/UX visual concepts
┗ 📄 README.md                       # Comprehensive sprint documentation
🚀 How to Open and Review
Reviewing the Power BI Build
Clone the project repository instance cleanly:

Bash
git clone [https://github.com/Dhanyakumar-Mane/Sprint_1.git](https://github.com/Dhanyakumar-Mane/Sprint_1.git)
Open the .pbix file located inside the Dashboards folder using Power BI Desktop.

Navigate to the Model View tab to examine the relationships and table configurations.

Open the Power Query Editor to audit the sequential data cleaning steps.

Reviewing the Excel Build
Open the .xlsx file from the Dashboards folder using Microsoft Excel (2019 or later).

Press Data -> Queries & Connections to inspect the background ETL architecture.

Access the Power Pivot Window (Power Pivot -> Manage) to analyze the inner data model.

💼 Skills & Analytics Competencies Demonstrated
🏗️ Data Engineering & Architecture
ETL Pipeline Design

Data Modeling & Schema Normalization

Data Profiling & Quality Assurance

🧮 Business Intelligence Foundations
DAX Formula Authoring

Key Performance Indicator (KPI) Blueprinting

Structure Mapping & Dashboard Wireframing

🏁 Conclusion
Sprint 1 successfully establishes the analytical backbone of this project. By prioritizing deep data cleaning, star-schema relational modeling, and scalable metric calculations, we have created a high-performance engine. This rock-solid foundation ensures the upcoming visualization and dashboard design phases will be smooth, accurate, and completely production-ready.

👩‍💻 Author
Dhanyakumar Mane

📊 Data Analyst | Business Intelligence Developer | Excel & Power BI Specialist

⭐ Support & Tracking
If you find this analytics sprint blueprint structured effectively:

⭐ Star the repository tracking branch

📢 Share actionable optimization feedback

🤝 Connect for further data collaboration
