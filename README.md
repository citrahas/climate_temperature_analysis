# 🌍 Global Temperature Analysis & Forecast

## 📌 Overview
This project analyzes global temperature trends and predicts future temperature using regression models.

## 🎯 Objective
- Understand long-term temperature trends  
- Compare linear and polynomial regression  
- Forecast future temperature  

---

## 📊 Dataset
- Source: Global Land Temperature dataset  
- Features used:
  - Year
  - Average Temperature  

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Converted year into numerical feature  
- Applied feature scaling (year → year_scaled)

### 2. Models Used
- Linear Regression  
- Polynomial Regression  

---

## 📈 Results
For all data
| Model | MAE |
|------|------|
| Linear Regression | > 1.0 |
| Polynomial Regression | ~0.41 |

--> Polynomial regression performs significantly better.

For selected data
| Model | MAE |
|------|------|
| Linear Regression | 1.0 |
| Polynomial Regression | 1.5 |

 --> Linear regression performs significantly better.
---

## Key Insights
- Temperature increase follows a **non-linear trend**  
- Post-2000 warming shows **acceleration**  
- Models trained on older data fail to capture modern trends  

---

##  Future Prediction
The model forecasts continued temperature increase in upcoming years.

 Note:
This is a trend-based model and does not include climate variables such as CO₂ emissions.

---

##  Visualization


---

## Future Improvements
- Add CO₂ emission data  
- Use time-series models (ARIMA)  
- Improve feature engineering  

---

## 🛠️ Tools & Libraries
- Python  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## 👤 Author
Citra Hasanah
