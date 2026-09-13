# NumPy Data Analysis & Processing Projects

A collection of mini data analysis projects built using **Python** and **NumPy** to demonstrate array manipulation, statistical analysis, vectorization, and data preprocessing techniques.

---

## 🛠️ Projects Included

### 1. Temperature Sensor Data Analyzer
Processes a time-series dataset of 100 temperature sensor readings[cite: 1] to perform statistical evaluation, anomaly detection, and data transformation[cite: 1].

* **Statistical Metrics:** Computes Mean, Minimum, Maximum, and Standard Deviation across readings[cite: 1].
* **Anomaly Detection:** Identifies readings outside safe operational thresholds ($15^\circ\text{C} - 25^\circ\text{C}$)[cite: 1].
* **Data Normalization:** Applies Min-Max scaling to map temperature values between `0` and `1`[cite: 1].
* **Categorization:** Classifies individual readings into `Low`, `Normal`, and `High` ranges[cite: 1].
* **Differential Analysis:** Calculates rate-of-change between consecutive readings to detect sudden thermal spikes[cite: 1].
* **Dataset Splitting:** Splits the readings into an 80/20 train-test split for modeling[cite: 1].

---

### 2. Student Marks Analyzer
Analyzes academic performance data for 10 students across 5 subjects using multi-dimensional array operations[cite: 2].

* **Aggregate Metrics:** Calculates total marks and average scores per student, as well as subject-wise averages[cite: 2].
* **Pass/Fail Evaluation:** Implements multi-subject condition checking ($\ge 50$ passing score per subject)[cite: 2].
* **Ranking Engine:** Dynamically ranks students based on overall average performance[cite: 2].
* **Grade Assignment:** Maps performance to letter grades (`A`, `B`, `C`, `D`, `Fail`) using vectorized conditional operations[cite: 2].
* **Min-Max Scaling:** Normalizes student average scores to a `0` to `1` range[cite: 2].
* **Dataset Splitting:** Partitions the student dataset into a 70/30 train-test split[cite: 2].

---

## 💻 Tech Stack

* **Language:** Python 3.x
* **Core Library:** NumPy
* **Environment:** Jupyter Notebook / Google Colab

---

## 🚀 Getting Started

### Prerequisites
Make sure you have Python and NumPy installed:
```bash
pip install numpy notebook
