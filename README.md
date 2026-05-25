# 📊 Student Performance Analysis - Mathematics Grades

## 📋 Project Overview

This project analyzes student performance in Mathematics using the student-mat.csv dataset from two Portuguese schools. The analysis answers key questions about grades, study habits, and gender differences using Python data analysis libraries.

### 🎯 Analysis Questions Answered

1. What is the average final grade (G3)?
2. How many students scored above 15/20?
3. Is study time correlated with performance?
4. Which gender performs better on average?

---

## 📁 Repository Files

- student_analysis.ipynb - Main Jupyter notebook with complete analysis
- student-mat.csv - Dataset (student math grades)
- README.md - Project documentation

---

## 🔧 Technologies Used

- Python 3.x
- Pandas - Data manipulation
- NumPy - Mathematical operations
- Matplotlib - Basic visualizations
- Seaborn - Advanced visualizations
- SciPy - Statistical testing
- Jupyter Notebook - Development environment

---

## 📊 Dataset Information

### Source
Student Performance Data Set from UCI Machine Learning Repository

### Details
- Subject: Mathematics
- Schools: 2 Portuguese schools
- Students (original): 395
- Variables: 33
- Target Variable: G3 (final grade, 0-20 scale)

### Key Columns Used
| Column | Description | Values |
|--------|-------------|--------|
| G3 | Final grade | 0 - 20 |
| studytime | Weekly study time | 1=<2h, 2=2-5h, 3=5-10h, 4=>10h |
| sex | Student gender | F (Female), M (Male) |

---

## 🚀 How to Run This Project

### Option 1: View Online (No Installation)
Simply click on student_analysis.ipynb in this repository - GitHub will automatically render the notebook!

### Option 2: Run Locally

Step 1: Clone the repository
git clone https://github.com/jalaksood/-student-performance-analysis.git
cd -student-performance-analysis

Step 2: Install required libraries
pip install pandas numpy matplotlib seaborn scipy jupyter

Step 3: Launch Jupyter Notebook
jupyter notebook

Step 4: Open and run student_analysis.ipynb

### Option 3: Google Colab
1. Upload student_analysis.ipynb to Google Colab
2. Upload student-mat.csv to the Colab environment
3. Run all cells

---

## 📈 Analysis Steps Performed

1. Data Loading - Used pd.read_csv() to load the dataset
2. Data Cleaning - Checked for missing values and removed duplicates
3. Exploratory Data Analysis - Examined dataset shape, types, and statistics
4. Statistical Analysis - Calculated mean, median, mode, correlation, and t-test
5. Data Visualization - Created histograms, scatterplots, bar charts, and box plots

---

## 📊 Results & Findings

### Question 1: Average Final Grade (G3)

- Mean (Average): ___ /20
- Median (Middle): ___ /20
- Mode (Most Common): ___ /20
- Minimum Grade: ___ /20
- Maximum Grade: ___ /20

### Question 2: Students Scoring Above 15

- Students above 10: ___ students (___%)
- Students above 13: ___ students (___%)
- Students above 15: ___ students (___%)
- Students above 18: ___ students (___%)

### Question 3: Study Time Correlation

- Correlation Coefficient: ___
- Strength: [Very Weak/Weak/Moderate/Strong/Very Strong]

Average Grade by Study Time:
- Less than 2 hours/week: ___ /20
- 2-5 hours/week: ___ /20
- 5-10 hours/week: ___ /20
- More than 10 hours/week: ___ /20

### Question 4: Gender Performance

| Gender | Sample Size | Mean Grade | Median Grade |
|--------|-------------|------------|---------------|
| Female (F) | ___ | ___ /20 | ___ /20 |
| Male (M) | ___ | ___ /20 | ___ /20 |

- T-statistic: ___
- P-value: ___
- Statistically significant at p < 0.05? [Yes/No]

---

## 📊 Visualizations Included

1. Histogram - Distribution of final grades with mean and median lines
2. Scatterplot - Study time vs grades with trend line
3. Bar Chart - Gender performance comparison with error bars
4. Box Plot - Grade distribution by gender (bonus)

---

## 💡 Key Insights

- Overall Performance: [Add your finding here]
- High Achievers: [Add your finding here]
- Study Habits: [Add your finding here]
- Gender Gap: [Add your finding here]

### Recommendations

- For Students: [Add recommendation here]
- For Teachers: [Add recommendation here]
- For Schools: [Add recommendation here]

### Limitations

- Data comes from only two schools (may not generalize)
- Correlation does not imply causation
- Other important factors not analyzed

---

## 👩‍💻 Author

Jalak Sood
GitHub: @jalaksood
Project: https://github.com/jalaksood/-student-performance-analysis

---

## ✅ Task Completion Checklist

- [x] Load dataset using pandas
- [x] Check for missing values
- [x] Remove duplicates
- [x] Inspect dataset shape & dtypes
- [x] Calculate average final grade (G3)
- [x] Count students scoring above 15
- [x] Analyze study time correlation
- [x] Compare gender performance
- [x] Create histogram of grades
- [x] Create scatterplot (study time vs grades)
- [x] Create bar chart (gender comparison)
- [x] Add markdown explanations
- [x] Upload to GitHub

---

## 📅 Date

May 2026

---

**Project Status: COMPLETE ✅**
