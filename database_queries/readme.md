# 🗄️ Database Queries – NYC School Data Exploration

This folder contains a **Jupyter Notebook** demonstrating how to access and analyze NYC school data by combining **SQL and Python**.  

It is part of a portfolio project showcasing skills in **database querying, Python integration, and exploratory analysis**.

---

## 📂 Contents

| File / Folder | Description |
|---------------|-------------|
| `day3_sql_analysis.ipynb` | Jupyter Notebook with SQL queries, Python integration, and analysis |
| README.md | This file, providing context and overview |

---

## 🧰 What I Did

For this project, I:

1. **Connected to a PostgreSQL database** containing NYC school datasets directly from Python.  
2. **Queried multiple tables** including:  
   - `high_school_directory` – school names, types, and programs  
   - `school_demographics` – enrollment, ELL, FRPL, and disabilities  
   - `school_safety_report` – reported incidents by type and location  
3. **Fetched results into Pandas DataFrames** for further manipulation and analysis.  
4. **Explored patterns across boroughs, demographics, and school safety metrics.**  
5. **Documented insights** with Markdown cells explaining each query and its significance.  

> This task demonstrates the ability to combine **relational databases and Python for real-world data analysis**, making workflows more efficient and reproducible.

---

## 📊 Key Analyses & Takeaways

- **Brooklyn** has the highest number of schools in New York.  
- **English Language Learning (ELL)** data is available only for **Manhattan**, although other boroughs appear to have more foreign/migrant students.  
- **Special Education** data is also only available for **Manhattan**.  

These observations highlight both **patterns in school distribution** and **data availability limitations**, which are important considerations for downstream analysis.

---

## 🧑‍💻 How to Use

1. Ensure you have a **PostgreSQL database** set up with the provided datasets or connection credentials.  
2. Open **`day3_sql_analysis.ipynb`** in JupyterLab or VS Code.  
3. Run the notebook to replicate SQL queries and Python analysis.  
4. Use the notebook as a template for querying and analyzing other relational datasets efficiently.