# 📊 Student_Habits_vs_Academic_Performance Data Analysis

**Student Performance Data Analysis** is a Python-based data analytics project focused on analyzing **1,000 student records** across academic and behavioral variables. The project uses **Python, Pandas, NumPy, and Matplotlib** to clean, transform, analyze, and visualize student data, uncovering meaningful relationships between daily habits and academic performance.

The analysis focuses on variables such as **study hours, sleep duration, attendance, social media usage, and exam performance**, transforming raw student data into actionable insights through exploratory data analysis and statistical techniques.

---
![alt text](<visualization/Student Habits vs Academic Performance Study.png>)
## 🚀 Core Features

The project implements the complete data analytics workflow:

1. **Data Cleaning & Transformation**

   * Loaded raw student data using Pandas.
   * Identified and handled missing values.
   * Detected and removed duplicate records.
   * Corrected data types and inconsistent values.
   * Performed data transformation and preparation for analysis.

2. **Exploratory Data Analysis**

   * Analyzed **1,000 student records** across **8 behavioral and academic variables**.
   * Used Pandas to explore data distributions and patterns.
   * Calculated descriptive statistics including mean, median, minimum, maximum, and standard deviation.
   * Examined relationships between student habits and academic outcomes.

3. **Correlation Analysis**

   * Performed correlation analysis to identify relationships between behavioral factors and exam performance.
   * Discovered **5+ meaningful correlations** involving study hours, sleep, attendance, social media usage, and academic performance.
   * Used NumPy and Pandas for numerical and statistical analysis.

4. **Data Visualization**

   * Created **5+ publication-ready visualizations** using Matplotlib.
   * Visualized distributions, relationships, comparisons, and correlations.
   * Converted complex numerical findings into easy-to-understand visual insights.

5. **Insight Generation**

   * Identified key behavioral patterns affecting student performance.
   * Transformed analytical findings into clear conclusions.
   * Prepared insights suitable for non-technical audiences.

6. **Insight Presentation**

   * Created a **10-slide insight deck** summarizing the analysis.
   * Presented important findings, visualizations, correlations, and actionable recommendations.

---

## 📈 Key Analysis Areas

| Analysis Area              | Description                                                         |
| :------------------------- | :------------------------------------------------------------------ |
| **Study Hours**            | Analyzed the relationship between study time and exam performance   |
| **Sleep**                  | Examined how sleep duration relates to academic outcomes            |
| **Attendance**             | Investigated the impact of attendance on student performance        |
| **Social Media Usage**     | Analyzed whether social media usage is associated with exam results |
| **Academic Performance**   | Examined exam scores and their relationship with behavioral factors |
| **Correlation Analysis**   | Identified relationships between numerical variables                |
| **Descriptive Statistics** | Summarized and interpreted the student dataset                      |

---

## 🛠️ Technology Stack

| Category                | Technology          | Description                                          |
| :---------------------- | :------------------ | :--------------------------------------------------- |
| **Language**            | **Python**          | Core programming and analysis language               |
| **Data Analysis**       | **Pandas**          | Data loading, cleaning, transformation, and analysis |
| **Numerical Computing** | **NumPy**           | Numerical operations and statistical calculations    |
| **Visualization**       | **Matplotlib**      | Data visualization and graphical analysis            |
| **Dataset**             | **Student Records** | 1,000 student records across 8 variables             |
| **Presentation**        | **Insight Deck**    | 10-slide presentation of analytical findings         |

---

## 📂 Project Structure

```text
student-performance-analysis/
│
├── data/
│    ├── raw dataset/
│    │      └── student_habits_performance.csv       <-- Raw student dataset
│    │
│    └── cleaned dataset/
│             ├── cleaned_dataset00211.csv
│             ├── student_improvement.csv            <-- Cleaned student datasets
│             └── top20_performers.csv
│
├── notebooks/
│   └── Student_Habits_vs_Academic_Performance_Study.ipynb        <-- Complete analysis
│
├── visualizations/
│   ├── Distribution of Exam Scores.png
│   ├── Study Hours VS Exam Score.png
│   ├── Average Exam Score by Gender.png
│   ├── Distribution of Diet Quality.png
│   └── Average Score Across Attendance Ranges.png
│
├── presentation/
│   └── student_performance_insights.pptx
│
├── README.md
└── requirements.txt
```

---

## 🔄 Data Analytics Workflow

```text
Raw Student Dataset
        ↓
Data Loading
        ↓
Data Cleaning
        ↓
Data Transformation
        ↓
Exploratory Data Analysis
        ↓
Descriptive Statistics
        ↓
Correlation Analysis
        ↓
Data Visualization
        ↓
Insight Generation
        ↓
10-Slide Insight Presentation
```

---

## 🔍 Data Cleaning & Transformation

The raw dataset was prepared for analysis through multiple preprocessing steps:

* Checked dataset dimensions and data types.
* Identified missing/null values.
* Handled missing data appropriately.
* Detected and removed duplicate records.
* Standardized inconsistent data values.
* Converted columns into appropriate data types.
* Created derived values where required.
* Validated the cleaned dataset before analysis.

---

## 📊 Exploratory Data Analysis

Exploratory analysis was performed to understand the overall characteristics of the student population.

Key operations included:

```python
df.head()
df.info()
df.describe()
df.shape
df.isnull().sum()
df.duplicated().sum()
```

Statistical analysis was performed to understand:

* Average student performance
* Study-hour distribution
* Attendance patterns
* Sleep duration
* Social media usage
* Minimum and maximum values
* Variability across different student behaviors

---

## 📉 Data Visualization

More than **5 visualizations** were created using Matplotlib to communicate the findings effectively.

Example visualizations include:

* Study Hours vs Exam Score
* Attendance vs Exam Score
* Sleep Duration vs Exam Score
* Social Media Usage vs Exam Score
* Exam Score Distribution
* Behavioral Variable Distributions
* Correlation Visualization

The visualizations were designed to make statistical relationships understandable to both technical and non-technical audiences.

---

## 🔗 Correlation Analysis

Correlation analysis was used to identify relationships between behavioral variables and academic performance.

The analysis investigated relationships such as:

```text
Study Hours       ↔ Exam Performance
Attendance        ↔ Exam Performance
Sleep Duration    ↔ Exam Performance
Social Media      ↔ Exam Performance
```

The analysis uncovered **5+ key correlations and behavioral patterns** that helped explain differences in student academic performance.

> **Important:** Correlation was used to identify relationships between variables and does not necessarily imply causation.

---

## 💡 Key Outcomes

The project successfully transformed raw student records into meaningful analytical insights.

### Major outcomes:

* Analyzed **1,000 student records**.
* Worked with **8 academic and behavioral variables**.
* Performed complete **data cleaning and transformation**.
* Conducted **exploratory data analysis**.
* Applied **descriptive statistics**.
* Identified **5+ meaningful correlations**.
* Created **5+ publication-ready visualizations**.
* Developed a **10-slide insight presentation**.
* Converted technical analysis into actionable insights for non-technical audiences.

---

## 📦 Requirements

```text
Python
Pandas
NumPy
Matplotlib
Jupyter Notebook
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib jupyter
```

---

## ▶️ Running the Project

### 1️⃣ Clone the Repository

```bash
git clone <https://github.com/kagawadesneha1104-ai/Student_Habits_vs_Academic_Performance_Study.git>
cd Student-performance-analysis
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Start Jupyter Notebook

```bash
jupyter notebook
```

### 4️⃣ Open the Analysis Notebook

Open:

```text
notebooks/student_analysis.ipynb
```

Run the notebook cells sequentially to reproduce the complete analysis.

---

## 🎯 Project Objective

The primary objective of this project is to demonstrate a complete **data analytics workflow**, starting from raw student data and progressing through **cleaning, transformation, exploratory analysis, statistical analysis, visualization, and insight communication**.

The project demonstrates how Python-based analytics can be used to transform raw datasets into meaningful insights that support better understanding and decision-making.
