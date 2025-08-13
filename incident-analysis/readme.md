# 🏫 NYC School Safety Report – Data Overview & Analysis

This folder contains the **NYC School Safety Report dataset** along with its corresponding **Data Dictionary**. This dataset was used to explore patterns in school safety incidents and to practice **data cleaning, exploration, and database integration**.

---

## 📘 About the Data Dictionary

The file `School_Safety_Report_Data_Dictionary.xlsx` provides essential reference information for working with the dataset. It includes:

### 🗂 Dataset Info
- Purpose and scope of the dataset
- Source and update frequency

### 📑 Column Info
- Column names and descriptions
- Data types and nuances to consider during analysis

### 🕘 Revision History
- Notes on changes to the dataset structure or naming conventions over time

> This file was used as a guide to understand the meaning of each field and to ensure correct handling of the data during cleaning and upload.

---

## 📂 About the Dataset

The file `school-safety-report.csv` contains detailed safety incident data for NYC schools across multiple school years. It can be used to:

- Analyze safety trends over time
- Compare incident rates between schools or boroughs
- Map incidents geographically

### 📊 Key Columns

| Column | Description |
|--------|-------------|
| `Location Name`, `DBN` | Unique identifiers for each school |
| `School Year` | Academic year of the record |
| `Major N`, `Oth N`, `NoCrim N`, `Prop N`, `Vio N` | Counts of different types of incidents |
| `AvgOfMajor N`, `AvgOfOth N`, etc. | Normalized averages of incidents for comparison |
| `Register` | Total number of students registered at the school |
| `Borough Name`, `Latitude`, `Longitude` | Geographic info for mapping and visualization |

---

## 🧰 What I Did

As part of this portfolio project, I:

1. **Explored the dataset** to understand its structure and contents.
2. **Cleaned and preprocessed** columns to ensure consistency and usability.
3. **Mapped key columns** to relational database tables for later integration.
4. **Prepared analysis-ready versions** of the data for visualizations and reporting.
5. **Documented the dataset** in a way that other analysts or developers could understand and reuse it.

This work demonstrates my ability to handle **real-world datasets**, understand data dictionaries, and prepare data for **analysis and database integration**.

---

## 📌 Usage

Use this folder as a reference for:

- Understanding the dataset structure
- Performing exploratory data analysis
- Integrating the data into a database or dashboard