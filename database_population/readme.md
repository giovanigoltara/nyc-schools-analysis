# 🧮 Database Population – NYC High School SAT Data

This folder contains the **SAT results dataset** along with a Python script and analysis notebook demonstrating **data cleaning, preprocessing, and database integration**.  

It is part of a portfolio project showcasing skills in **Python data processing, data quality assessment, and relational database design**.

---

## 📂 Contents

| File / Folder | Description |
|---------------|-------------|
| `cleaned_data.csv` | Cleaned and validated SAT results dataset ready for database insertion |
| `upload_script.py` | Python script for cleaning and appending the dataset to a PostgreSQL database |
| `README.md` | This file, providing context and overview |

---

## 🧰 What I Did

For this project, I:

1. **Assessed the raw SAT dataset** for missing, invalid, and duplicate data.  
2. **Cleaned and normalized** column names for consistency.  
3. **Removed invalid values and duplicates**:
   - Dropped rows with missing or out-of-range SAT scores  
   - Retained only `school_code` as the primary key  
   - Removed unnecessary columns (e.g., school name, contact info, percent students tested)  
4. **Ensured data types and ranges** were correct for numeric columns.  
5. **Designed a SQL-ready schema** optimized for integration with other school datasets.  
6. **Created a Python script** to automate data cleaning and append the cleaned dataset to a PostgreSQL database.  

> This task demonstrates the ability to **transform messy, real-world datasets into clean, relational tables ready for analysis**.

---

## 📊 Key Results & Takeaways

- The cleaned dataset is now **consistent, validated, and normalized** for integration.  
- `school_code` serves as the **primary key** for joining with other datasets.  
- Invalid, redundant, or low-quality columns were removed to **ensure data integrity**.  
- The table is ready for **downstream analysis or joining with other NYC school datasets**.

---

## 📌 How to Use

1. Ensure you have a **PostgreSQL database** set up locally or hosted.  
2. Run **`upload_script.py`** to clean and upload the SAT dataset.  
3. The cleaned CSV (`cleaned_data.csv`) can also be used directly for exploratory analysis or visualizations.  
4. For further integration, join on `school_code` with other school datasets while accounting for dropped columns.

---

This work highlights skills in **data cleaning, schema design, and preparing datasets for scalable analysis and database workflows**.