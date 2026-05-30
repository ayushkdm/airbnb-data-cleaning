# 🏠 Airbnb Data Cleaning Project

A general-purpose data cleaning applied to a real-world Airbnb dataset containing **102,000+ rows**. This project demonstrates practical data wrangling skills essential for any data science or machine learning workflow.

[View notebook] (https://nbviewer.org/github/ayushkdm/airbnb-data-cleaning/blob/main/notebook/Airbnb.ipynb)
---

## 📌 Project Overview

Raw data is rarely ready to use. This project takes a large, messy Airbnb dataset and transforms it into a clean, analysis-ready format using Python. The focus is on building a reusable, well-documented cleaning process — not tied to any specific ML goal — making it applicable as a preprocessing template for similar datasets.

---

## 📁 Repository Structure

```
airbnb-data-cleaning/
│
├── data/
│   ├── raw/
│   │   └── airbnb_raw.csv          # Original, unmodified dataset
│   └── cleaned/
│       └── airbnb_cleaned.csv      # Final cleaned output
│
├── notebook/
│   └── data_cleaning.ipynb         # Step-by-step cleaning notebook
│
├── .gitignore
├── requirements.txt
└── README.md
```

---

## 🧹 Cleaning Steps Performed

| Step | Description |
|------|-------------|
| **Duplicate Removal** | Identified and dropped duplicate rows to ensure data integrity |
| **Null Value Handling** | Detected missing values per column; applied imputation or dropping based on context |
| **Data Type Fixing** | Converted columns to appropriate types (e.g., strings to numerics) |
| **Invalid Value Removal** | Removed logically inconsistent values |
| **Column Renaming** | Standardized column names for readability and consistency |
| **& more...** | eg. Data visualization |

---

## 📊 Dataset

- **Source:** Kaggle
- **Raw Size:** ~102,000 rows
- **Format:** CSV

> ⚠️ The raw dataset is included for reference. Do not use it directly for analysis — use the cleaned version in `data/cleaned/`.

---

## 🛠️ Tech Stack

| Library | Purpose |
|---------|---------|
| `pandas` | Core data manipulation and cleaning |
| `numpy` | Numerical operations |
| `matplotlib` | Visualizing distributions and data patterns |
| `xlsxwriter` | Exporting cleaned data to Excel format |
| `re` | Regex-based string cleaning and pattern matching |
| `warnings` | Suppressing non-critical warnings |

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/ayushkdm/airbnb-data-cleaning.git
cd airbnb-data-cleaning
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the notebook
```bash
jupyter notebook notebook/data_cleaning.ipynb
```

---

## 💡 Key Takeaways

- Real-world datasets require multi-step cleaning before they're usable
- A structured, documented cleaning pipeline improves reproducibility
- This workflow is transferable to any tabular dataset with similar issues

---

## 👤 Author

**Ayush Kadam**
[LinkedIn](https://www.linkedin.com/in/ayush-kadam-07009439b/) • [GitHub](https://github.com/ayushkdm)
