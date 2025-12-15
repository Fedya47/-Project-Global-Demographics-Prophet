[![ru](https://img.shields.io/badge/lang-ru-green.svg)](README.ru.md)
*Read this in [Russian](README.ru.md)*

# 🌍 Global Population Forecast 2030: Linear vs. Polynomial Regression

![Project Status](https://img.shields.io/badge/Status-Completed-success)
![Tools](https://img.shields.io/badge/Tools-Python%20|%20Tableau%20|%20Pandas-blue)

## 📖 Overview

This project is dedicated to analyzing demographic trends and forecasting the global population up to the year 2030. The core objective is to compare two machine learning models—**Linear Regression** (the naive approach) and **Polynomial Regression** (Degree 2)—to demonstrate why simple linear growth fails to reflect the reality of the decelerating demographic boom.

The result is an interactive Tableau dashboard that visualizes the "forecast gap" between the two models.

**🔗 [View Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/arsen.bobilak/viz/GlobalPopulationForecastLinearvs_PolynomialModelComparison/Dashboard1)**

---

## 📊 Key Findings

* **Model Divergence:** By 2030, the "naive" linear model overestimates the global population by approximately **32.7 million people** compared to the more accurate polynomial model.
* **Deceleration Trend:** The data confirms that while the population continues to grow, the *rate* of growth is slowing down. The Polynomial model successfully captures this curvature.
* **2030 Forecast:** According to our model, the global population will reach approximately **8.66 billion** people by 2030.

---

## 🖼️ Dashboard Preview

*<img width="820" height="809" alt="Dashboard 1" src="https://github.com/user-attachments/assets/974b196c-465a-461d-915d-ce2dde12addc" />*

### Visualization Includes:
1.  **History & Forecast:** A continuous timeline showing historical data (1990–2023) and the forecast (2024–2030).
2.  **Model Divergence:** A bar chart highlighting the accumulating error of the linear model.
3.  **Growth Rate Analysis:** An annual increase chart demonstrating the historical peak and subsequent decline in growth speed.

---

## 🧰 Technologies & Libraries Used

* **Python 3.x:** Primary programming language.
* **Pandas & NumPy:** Data manipulation, cleaning, and numerical operations.
* **Scikit-Learn:** Machine Learning (LinearRegression) and polynomial feature transformation.
* **Matplotlib & Seaborn:** Data visualization and Exploratory Data Analysis (EDA).
* **Tableau:** Interactive dashboard creation.
* **Re (Regular Expressions):** String processing and cleaning "dirty" data.

---

## 🛠️ Methodology

The project follows a standard Data Science pipeline:

1.  **Data Collection:** Historical population data sourced from the World Bank (1990–2023).
2.  **Preprocessing:** Cleaning missing values and structuring the dataset for time-series analysis.
3.  **Modeling (Python):**
    * **Linear Regression:** Baseline model assuming constant growth.
    * **Polynomial Regression (Degree 2):** Model accounting for the non-linear nature and growth deceleration.
4.  **Visualization:** Results exported to Tableau for the final report.

---

## ⚠️ Notes & Limitations

* **2024-2025 Transition:** A structural break ("jump") may be observed on the charts between historical data and the start of the forecast. This is due to the model correcting back to the long-term mathematical trend following the slowdown period during the COVID-19 pandemic.
* **Data Source:** World Bank Open Data.

---

## 🚀 How to Run

1.  Clone the repository:
    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
    ```
    *(Note: Replace URL with your actual repository link)*
2.  Install dependencies:
    ```bash
    pip install pandas scikit-learn matplotlib
    ```
3.  Run the analysis script:
    ```bash
    python main.py
    ```

---

## 📬 Contact

**Fedya** *Aspiring Data Scientist*
Telegram: [@Fedia_47](https://t.me/Fedia_47)
