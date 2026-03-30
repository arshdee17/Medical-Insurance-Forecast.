# Medical Insurance Cost Forecast 🏥
**An Analysis of Healthcare Risk Factors using Multiple Linear Regression**

## 📌 Project Overview
This project predicts individual medical insurance costs based on demographic and lifestyle factors. By leveraging a dataset of 1,338 records, I built a **Multiple Linear Regression** model to quantify how variables like age, BMI, and smoking status drive healthcare expenses.

The goal of this analysis is to provide "Explainable AI"—moving beyond black-box predictions to offer clear, data-backed justifications for insurance premium adjustments.

## 🛠️ Tech Stack
* **Language:** Python 3.10+
* **Libraries:** `Pandas` (Data Cleaning), `NumPy` (Math), `Scikit-Learn` (Modeling), `Seaborn/Matplotlib` (Visualization)
* **Platform:** Google Colab 

## 📊 Key Insights & Results
* **Model Accuracy:** The model achieved an **$R^2$ score of 0.8295**, explaining ~83% of the variance in costs.
* **Top Predictor:** **Smoking status** is the most significant factor, acting as a massive cost multiplier compared to non-smokers.
* **Demographics:** Age and the number of children show a steady linear correlation with increased premiums, adding approximately 3.4% and 10% respectively to the base cost.
* **Mean Absolute Error (MAE):** On average, predictions are within **$3,755.92** of the actual billed charges.

## 🧪 Data Pipeline
1. **Cleaning:** Handled duplicates and verified data integrity.
2. **EDA:** Used Box Plots and Scatter Plots to identify "cost bands" and non-linear relationships.
3. **Feature Engineering:** Performed **One-Hot Encoding** for categorical data and a **Log Transformation** on charges to normalize the distribution.
4. **Modeling:** Trained a Multiple Linear Regression model

## 🚀 How to Run
1. Clone this repository: `git clone https://github.com/arshdee17/Medical-Insurance-Forecast.git`
2. Open the `Insurance_Forecast_analysis.ipynb` file in **Google Colab** or **Jupyter Notebook**.
3. Ensure all dependencies are installed: `pip install pandas scikit-learn seaborn`
4. Run all cells to see the visualizations and model metrics.
