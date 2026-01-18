# 🎓 MACHINE LEARNING CLASSIFICATION OF EMPLOYABILITY OUTCOMES AMONG GAMUDA AI ACADEMY GRADUATES IN THE MALAYSIAN TECH SECTOR

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

---

## 🧐 About The Project

This project analyzes data from the **Gamuda AI Academy (GAIA)** to understand what factors drive employment success in the Malaysian tech sector. We utilize Machine Learning to predict outcomes and analyze socioeconomic impacts.

### 🎯 Key Objectives
* **Analyze** participant demographics and academic performance.
* **Identify** key drivers of employment (e.g., Capstone Scores, Attendance).
* **Predict** employability using **Logistic Regression** and **Random Forest**.
* **Evaluate** the program's impact on socioeconomic equity (B40/M40/T20).

---

## 📊 Dataset Features

The analysis is based on **239 records** containing the following features:

| Feature | Description |
| :--- | :--- |
| 📍 `cohort_region` | Location of the cohort (e.g., KL, Sabah) |
| 🎓 `education_level` | Highest qualification obtained |
| 📅 `attendance_pct` | Percentage of classes attended |
| 📈 `capstone_score` | Final project assessment score |
| 💰 `group_income` | Socioeconomic group (B40, M40, T20) |
| 💼 `employed_success` | **Target Variable** (1 = Employed, 0 = Unemployed) |

---

## ⚙️ Methodology

1.  **Data Cleaning:** Handling missing values in industry columns and standardizing text data.
2.  **EDA (Exploratory Data Analysis):** Visualizing distributions of scores, attendance, and income groups.
3.  **Preprocessing:** One-Hot Encoding for categorical variables and Standard Scaling for numerical features.
4.  **Modeling:**
    * `LogisticRegression` (Baseline)
    * `RandomForestClassifier` (Ensemble)
5.  **Evaluation:** Confusion Matrix, ROC-AUC, and Classification Reports.

---

## 📈 Key Findings

* **Overall Success:** The program achieved a **73.2%** employment rate.
* **Top Industries:** Energy (10.9%), Manufacturing (10.3%), and Tech (9.1%).
* **Equity:** The analysis confirms that the training effectively neutralizes socioeconomic barriers, offering equitable outcomes regardless of income group.

---

## 💻 Getting Started

### Prerequisites
* Python 3.x
* Jupyter Notebook or Google Colab

### Installation

1.  Clone the repo
    ```sh
    git clone [https://github.com/your_username/gaia-employability-analysis.git](https://github.com/zuhairnasir/gaia-employability-analysis.git)
    ```
2.  Install requirements
    ```sh
    pip install -r requirements.txt
    ```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

---

<p align="center">
  <br>
  Made with 🫶🏻 using Python by Muhammad Zuhair Afham Bin Mohd Nasir (P153944)
</p>
