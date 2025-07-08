# Student Performance Analytics Dashboard

This project analyzes student academic data to identify performance trends and highlight students at academic risk. The analysis is presented in a clean and visual format using a Jupyter Notebook.

## 📌 Objective

To explore and analyze various academic and behavioral factors influencing student performance, and identify struggling students who may need intervention.

## 📊 Dataset Used

**File**: `Students_Grading_Dataset_Biased.csv`  
The dataset includes the following features:

- **Scores**: Midterm, Final, Assignments, Quizzes, Projects
- **Attendance (%)**
- **Participation & Study Hours**
- **Sleep Hours, Stress Level**
- **Demographics**: Gender, Department, Parent Education, Family Income
- **Other**: Internet Access, Extracurricular Activities

## 🛠️ Workflow Overview

1. **Data Loading & Cleaning**
   - Removed unnecessary columns (like names and emails)
   - Converted relevant features to appropriate data types

2. **Feature Engineering**
   - Computed a composite `Academic_Score`
   - Labeled students as **Top** or **Struggling**

3. **Exploratory Analysis**
   - Correlation matrix of influencing factors
   - Visual impact of attendance, study hours, and sleep

4. **Visualizations**
   - Scatter plots: Attendance vs Score, Study Hours vs Participation, Sleep vs Stress
   - Box plot: Department-wise performance
   - Heatmap: Feature correlations

## 🔍 Key Insights

- High attendance and participation are strong indicators of good academic performance.
- Students with better sleep patterns and lower stress levels tend to perform better.
- Department-level trends show varying distributions of top and struggling students.

## 💻 Tech Stack

- Python (Pandas, NumPy)
- Seaborn & Matplotlib for visualization
- Jupyter Notebook for analysis

## 📁 Files Included

| File Name                                     | Description                                |
|----------------------------------------------|--------------------------------------------|
| `Student_Performance_Analytics_Dashboard.ipynb` | Jupyter notebook with full analysis         |
| `Students_Grading_Dataset_Biased.csv`          | Input dataset                               |
| `README.md`                                  | Project overview and instructions           |

## 🚀 How to Run

1. Clone this repository or download the files.
2. Make sure the file `Students_Grading_Dataset_Biased.csv` is in the same directory.
3. Open the notebook in **Jupyter**, **Colab**, or **VS Code**, and run all cells.

---

📌 *This project is focused on exploratory analysis and academic insight. It is not deployed but can be extended into a web dashboard using Streamlit or Flask.*

