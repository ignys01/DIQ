# 🏢 Data Preparation Pipeline for Public Businesses in Milan

This project provides a **data preparation pipeline** for a dataset related to public businesses in the city of Milan. The goal is to clean, transform, and enrich the dataset to make it ready for advanced analysis or machine learning models.

## 📋 Performed Operations

### 1. **Data Loading**
- **Description:** The dataset is imported from a source file (CSV) into a manipulable structure, such as a Pandas DataFrame.
- **Technologies Used:**  
  - Python (libraries: Pandas).
- **Objective:** Make the data accessible for subsequent operations.

---

### 2. **Data Exploration**
- **Description:** Preliminary analysis of the dataset to understand:
  - Number of rows and columns.
  - Data types present.
  - Missing or inconsistent values.
  - Variable distributions.
- **Techniques and Tools:**
  - Pandas methods: `df.head()`, `df.info()`, `df.describe()`.
  - **Data profiling** using libraries such as `ydata-profiling`.
  - Quick visualizations with Matplotlib or Seaborn.
- **Objective:** Identify potential quality issues or inconsistencies in the data.

---

### 3. **Data Cleaning**
- **Description:** Improving data quality by:
  - Removing or imputing missing values.
  - Eliminating duplicates.
  - Standardizing formats and correcting errors (e.g., duplicate names, inconsistent formatting).
- **Objective:** Ensure consistent and error-free data.

---

### 4. **Data Transformation**
- **Description:** Modifying the data to make it more useful and ready for analysis:
  - Creating new columns (e.g., extracting the year from a date).
  - Transforming categorical variables into numerical values (One-Hot Encoding).
  - Converting dates into standardized formats.
  - Normalizing or standardizing numerical variables.

---

### 5. **Error Detection and Correction**
- **Description:** Identifying and resolving data issues:
  - **Outlier Detection:** Finding anomalies using statistical methods (e.g., Z-scores, IQR).
  - Correcting invalid or inconsistent values based on predefined rules.

---

### 6. **Data Deduplication**
- **Description:** Identifying and removing duplicate records:
  - Exact matching for key attributes.
  - Fuzzy matching using techniques such as Levenshtein distance for text fields.
- **Objective:** Ensure the dataset contains only unique and reliable records.
