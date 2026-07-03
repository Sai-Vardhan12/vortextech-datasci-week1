# Week 1 – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project contains the Week 1 data analysis task completed as part of a Data Science internship. The notebook performs Exploratory Data Analysis (EDA) on a student performance dataset to understand the relationship between study habits, exam scores, and placement status.

## 🎯 Objectives
- Load and explore the dataset.
- Understand the dataset structure.
- Check for missing values and duplicate records.
- Generate descriptive statistics.
- Visualize relationships between different variables.
- Draw insights from the data.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Dataset
The dataset contains student-related information, including:
- Study Hours
- Exam Score
- Placement Status

> **Note:** Update the dataset path in the notebook before running it, as it currently uses a local file path.

## 📊 Analysis Performed

### Data Loading
- Imported dataset using Pandas.

### Data Exploration
- Displayed first and last records.
- Examined dataset information.
- Generated summary statistics.

### Data Cleaning
- Checked for missing values.
- Identified duplicate records.
- Removed duplicates.

### Data Visualization
The notebook includes the following visualizations:

- Bar plot: Study Hours vs Exam Score (grouped by Placement Status)
- Bar plot: Placement Status vs Study Hours
- Line plot: Study Hours vs Placement Status
- Count plot: Distribution of Placement Status
- Pie chart: Percentage of placed and non-placed students

## 📈 Key Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

## ▶️ How to Run

1. Clone the repository.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Update the dataset path in the notebook:

```python
df = pd.read_csv("path/to/dataset.csv")
```

4. Open the notebook:

```bash
jupyter notebook Week-1.ipynb
```

5. Run all cells.

## 📁 Project Structure

```
Week-1/
│── Week-1.ipynb
│── dataset.csv
└── README.md
```

## 📚 Learning Outcomes

- Data preprocessing
- Data cleaning
- Exploratory Data Analysis (EDA)
- Data visualization
- Understanding relationships between variables
- Using Pandas and Seaborn effectively

## 🚀 Future Improvements

- Add correlation heatmaps.
- Perform feature engineering.
- Build a predictive machine learning model.
- Create an interactive dashboard using Plotly or Streamlit.

## 👨‍💻 Author

**Sai Madani**

Data Science Intern