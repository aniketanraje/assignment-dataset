# assignment-dataset
Public datasets for IIT Guwahati – E&amp;ICT Academy Data Science &amp; ML Pandas assignment.

# 📊 Pandas Assignment Datasets – IIT Guwahati E&ICT Academy

This repository contains the datasets used for the **Pandas Assignment** as part of the *Advanced Certification in Applied Data Science, Machine Learning & AI* course by **E&ICT Academy, IIT Guwahati** in collaboration with **The IoT Academy**.

## 📂 Contents
- `Netflix.csv` – Dataset for Netflix-related data analysis tasks.
- `student.csv` – Student demographic data.
- `marks.csv` – Marks data for students.

## 🎯 Purpose
These datasets are hosted publicly to ensure:
- Seamless access from Jupyter Notebooks without manual uploads.
- Version-controlled and reproducible workflows.
- Easy integration for course assignments.

## 🔗 Usage
Example Python snippet to load datasets directly from GitHub:
```python
import pandas as pd

netflix_url = "https://raw.githubusercontent.com/aniketanraje/assignment-dataset/main/Netflix.csv"
df_netflix = pd.read_csv(netflix_url)

