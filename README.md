# Cognetix Technology - Data Analytics Internship

## Stage 1: Foundational Level (Consolidated Notebook)

Welcome to the repository for **Stage 1 (Foundational Level)** of the Data Analytics Internship at **Cognetix Technology**[cite: 1]. This repository contains an end-to-end Python notebook covering data processing, statistical analysis, and visual data exploration across three foundational projects[cite: 1].

---

## 📂 Repository Structure

├── Cognetix_FoundationalStage.ipynb
└── README.md


---

## 📌 Stage 1 Task Overview

### 🛒 Task 1: Sales Data Analysis
* **Objective**: Analyze sales data from a CSV file using Python and Pandas to extract core business metrics[cite: 1].
* **Key Steps & Features**:
  * Loaded sample sales dataset and calculated overall summary statistics (`sum`, `mean`, `max`, `min`).
  * Identified top-performing product lines and leading country markets by sales volume.
  * **Visualizations**: Generated a bar chart for product line revenue and a pie chart displaying sales breakdown across top countries.

---

### 🎓 Task 2: Student Performance Dataset Analysis
* **Objective**: Analyze students' academic performance to calculate subject averages and identify top performers[cite: 1].
* **Key Steps & Features**:
  * Conducted data validation checks to ensure no missing values or negative scores were present.
  * Calculated subject-wise score averages across Math, Reading, and Writing.
  * Displayed top 5 performing students based on total cumulative scores.
  * **Visualizations**: Created a subject average bar chart, a pie chart showing total mark share per subject, and score distribution boxplots.

---

### 🦠 Task 3: COVID-19 Data Report
* **Objective**: Process global COVID-19 case data to observe daily progression, trends, and case distributions[cite: 1].
* **Key Steps & Features**:
  * Cleaned time-series data and calculated daily confirmed, death, recovery, and active totals.
  * Computed daily new cases along with a 7-day rolling average trend line.
  * **Visualizations**: Rendered a cumulative line chart, a current case breakdown pie chart, a daily new cases bar chart with a trend line, and an interactive **Plotly** dashboard.

---

## 🛠️ Tools & Libraries Used
* **Language**: Python 3.x
* **Data Manipulation**: Pandas, NumPy
* **Data Visualization**: Matplotlib, Seaborn, Plotly

---

## 🚀 How to Run the Notebook
1. Open Google Colab or Jupyter Notebook.
2. Upload the required datasets to your session:
   * `sales_data_sample.csv`
   * `StudentsPerformance.csv`
   * `covid_19_clean_complete.csv`
3. Run `Cognetix_FoundationalStage.ipynb` sequentially to generate all summary outputs and charts.
