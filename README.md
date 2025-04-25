# LinkedIn Job Analysis - Business Analyst Listings

This project focuses on **data cleaning and preprocessing** of a LinkedIn dataset containing **Business Analyst job listings**. The goal is to prepare the dataset for deeper analysis and visualization.

---

## Objective

To clean and structure raw job listing data scraped from LinkedIn, making it ready for further **exploratory data analysis**, **visualizations**, and **insights extraction**.

---


---

## Dataset Summary

- File: `Business_analyst_job_listings_linkedin.csv`
- Total Rows: 921
- Columns: 10
- Attributes include: job title, location, date posted, company name, description, applications count, contract type, experience level, work type, and sector.

---

## Work Done

### 1️⃣ Dataset Loading
- Used `pandas` to load the CSV file into a DataFrame.
- Previewed the top 5 rows using `.head()`.

### 2️⃣ Initial Data Exploration
- Used `.info()` to understand column types and missing values.
- Used `.describe()` to analyze unique values, frequency distributions, and categorical spread.

### 3️⃣ Data Type Conversion
- Converted the `publishedAt` column from string to `datetime` format.
- Cleaned the `applicationsCount` column by extracting numerical values and converting them to `float`.

### 4️⃣ Handling Missing Values
- Identified missing values using `.isna().sum()`.
- Filled missing `companyName` entries with `"Unknown"` to retain row integrity.

### 5️⃣ Basic Data Cleaning
- Ensured all columns had consistent and meaningful data types.
- Removed or handled any unnecessary characters or formatting issues.

### 6️⃣ Light Visual Exploration (EDA)
- Used `seaborn` and `matplotlib` to visualize:
  - Top job titles
  - Most common job locations

---

##Libraries Used

- `pandas` – for data handling
- `matplotlib` – for visualization
- `seaborn` – for aesthetic plotting

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/MadadAllah/linkedin-job-analysis.git
   cd linkedin-job-analysis
