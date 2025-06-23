# CODTECH Internship – Task 1: Big Data Analysis Using PySpark
## ✅ Overview
As part of my internship at **CODTECH IT SOLUTIONS PRIVATE LIMITED**, I completed Task 1, which involved performing big data analysis using **PySpark** in **Google Colab**. This task was focused on analyzing a large retail dataset with millions of records, where I applied key data processing techniques to extract meaningful business insights.
The goal of this task was to demonstrate my ability to clean, transform, and analyze large-scale data using a distributed computing approach. I used PySpark for its scalability and Google Colab as the development environment to handle the analysis smoothly without system limitations.
---
## 🧰 Tools Used
- Python
- PySpark
- Google Colab
- Google Drive
---
## 📁 Files Included
| File Name              | Description                                                   |
|------------------------|---------------------------------------------------------------|
| `BigDataAnalysis.ipynb` | Google Colab notebook with full PySpark code                  |
| `sample_output.csv`     | First 1000 rows of cleaned data (GitHub-friendly)             |
| `large_data.csv`        | ⚠️ Not included (file exceeds 100MB GitHub limit)             |
---
## 🧠 What I Did
- Loaded a multi-million row CSV file from Google Drive
- Dropped missing values to clean the data
- Performed grouping and aggregation:
  - Count by `Item Type`
  - Average `Unit Price` by `Region`
  - Max and Min of `Total Profit`
- Exported:
  - Full cleaned dataset as `cleaned_output.csv`
  - A sample of 1000 rows as `sample_output.csv` (for GitHub)
---
## ⚠️ Notes
- The full cleaned dataset is too large for GitHub (>100MB).
- A sample of 1000 cleaned rows is included as `sample_output.csv`.
- You can reproduce the full analysis by running the notebook in Google Colab.
  
