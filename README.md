# 🎓 MACHINE LEARNING CLASSIFICATION OF EMPLOYABILITY OUTCOMES AMONG GAMUDA AI ACADEMY GRADUATES IN THE MALAYSIAN TECH SECTOR


![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

> **Machine Learning Classification of Employability Outcomes among Gamuda AI Academy Graduates in the Malaysian Tech Sector.**

---

## 🧐 About The Project

This project leverages Machine Learning to analyze and predict the employability of graduates from the **Gamuda AI Academy (GAIA)**. By examining various demographic and academic factors, we aim to identify key drivers of success in the Malaysian tech sector.

### 🎯 Key Objectives
* **Analyze** historical data of GAIA graduates.
* **Identify** significant features contributing to employment (e.g., Capstone Scores, Attendance).
* **Predict** employment success (`Yes/No`) using classification models.
* **Promote** socioeconomic equity through data-driven insights.

---

## 📊 Dataset Overview

The dataset contains records of **239 participants** with the following key features:

| Feature | Description |
| :--- | :--- |
| 📍 `cohort_region` | Region of the cohort (e.g., KL, Sabah) |
| 🎓 `education_level` | Participant's highest education level |
| 📈 `capstone_score` | Final score achieved in the capstone project |
| 📅 `attendance_pct` | Percentage of classes attended |
| 💼 `group_income` | Socioeconomic income group (B40, M40, T20) |
| 🎯 **Target** | `employed_success` (1 = Employed, 0 = Unemployed) |

---

## 🛠️ Tech Stack

* **Core:** Python 3
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Seaborn, Matplotlib
* **Machine Learning:** Scikit-Learn (Logistic Regression, Random Forest)
* **Statistics:** SciPy, Statsmodels

---

## 🚀 Workflow

1.  **Data Loading & Cleaning**: Handling missing values (e.g., industry data for unemployed graduates) and normalizing string columns.
2.  **Exploratory Data Analysis (EDA)**: Visualizing employment rates across regions, gender, and income groups.
3.  **Feature Engineering**: Encoding categorical variables (One-Hot) and scaling numerical features.
4.  **Model Training**: Implementing `LogisticRegression` and `RandomForestClassifier`.
5.  **Evaluation**: Using Cross-Validation, Confusion Matrices, and ROC-AUC scores.

---

## 📈 Key Insights

* **Employment Rate:** The overall employment rate in the dataset is approximately **73.2%**.
* **Top Industries:** Energy, Manufacturing, and Technology.
* **Impact:** The analysis suggests that GAIA's training effectively neutralizes traditional socioeconomic barriers, providing equitable opportunities across different income groups.

---

## 💻 Getting Started

### Prerequisites
* Python 3.8+
* Jupyter Notebook

### Installation

1.  Clone the repo
    ```sh
    git clone [https://github.com/your_username/gaia-employability-classification.git](https://github.com/your_username/gaia-employability-classification.git)
    ```
2.  Install dependencies
    ```sh
    pip install -r requirements.txt
    ```
3.  Run the notebook
    ```sh
    jupyter notebook
    ```

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<p align="center">
  <br>
  Made with 🫰🏻🫶🏻 by Muhammad Zuhair Afham Bin Mohd Nasir (P153944)
</p>
