# 🗽 NYC Schools Data Analysis  
*From Raw Data to Insights and Database Integration*

## 📌 Overview
This project is a **complete data workflow** that transforms multiple NYC school datasets into insights and a fully integrated PostgreSQL database.  
It was developed as part of an intensive multi-part program and now serves as a **portfolio project** demonstrating skills in:

- Data exploration
- Data cleaning and preprocessing
- SQL querying through Python
- Database integration and schema design
- Git/GitHub project organization

---

## 🎯 Objectives
The main goals of this project were to:
1. Explore and analyze public datasets on NYC schools and student outcomes.
2. Practice Python and Pandas for data cleaning, filtering, and visualization.
3. Combine SQL and Python to run efficient database queries.
4. Integrate new datasets into an existing relational database with schema-aware design.
5. Package the entire workflow into a clear, reproducible public repository.

---

## 🛠️ Tech Stack
- **Languages:** Python (Pandas, Matplotlib, Seaborn), SQL (PostgreSQL)
- **Tools & Libraries:** Jupyter Notebook, psycopg2, SQLAlchemy, Visual Studio Code
- **Version Control:** Git & GitHub
- **Database:** PostgreSQL
- **OS:** Cross-platform

---

## 📂 Project Structure

```plaintext
nyc-schools-analysis/
├── incident_analysis/              # Data exploration and initial insights
│   ├── README.md
│   ├── data/
│
├── school_directory_exploration/   # Cleaning, grouping, and visualization
│   ├── README.md
│   ├── dataset/                    # Folder containing dataset utilized for analysis
│   ├── analysis.ipynb              # Notebook with analysis and visualizations
│
├── database_queries/                # SQL via Python queries and insights
│   ├── README.md
│   ├── sql_analysis.ipynb
│
├── database_population/             # Data integration and upload scripts
│   ├── README.md
│   ├── sat_cleaned_data.csv
│   ├── sat_modeling.ipynb
│
└── README.md                        # This file
