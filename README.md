# 🦠 COVID-19 Analysis

**Data visualization and analysis of global COVID-19 cases using Python**

---

## 📌 Introduction

This project visualizes and analyzes the global spread of COVID-19 using Python. It focuses on trends in confirmed cases, deaths, and recoveries across countries over time.

---

## 📂 Dataset

The analysis is based on the `covid_19_clean_complete.csv` dataset from Kaggle, which provides global COVID-19 data including:

- Date  
- Country/Region  
- Province/State  
- Confirmed, Deaths, and Recovered cases  

---

## 🔍 Methodology

- Load and clean the dataset (handle missing values, format dates)
- Visualize key insights:
  - Top affected countries
  - Time series trends
  - Correlations between key variables
- Display global totals and trends over time

---

## 📊 Visualizations

- **Top Countries**: Horizontal bar chart of total confirmed cases  
- **Time Series**: Line plots for selected countries (e.g., India, US, Italy)  
- **Correlation**: Heatmap of confirmed, deaths, and recoveries  
- **Summary**: Latest global totals printed in table format  

---

## ▶️ How to Run

1. Open the notebook in **Google Colab**  
2. Upload `covid_19_clean_complete.csv` to a `/data/` folder  
3. Run all cells to view results

---

## 🚀 Technologies Used

- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Google Colab  

---

## 📈 Future Improvements

- Add interactive visualizations (e.g., using Plotly or Streamlit)  
- Incorporate vaccination data for deeper insights  
- Develop predictive models to forecast future COVID-19 trends  
