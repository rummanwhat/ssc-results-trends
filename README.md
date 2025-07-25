📊 SSC Exam Result Trends & Forecast (Bangladesh, 2001–2030)

A time series analysis and forecasting project that explores the Secondary School Certificate (SSC) exam performance trends in Bangladesh from 2001 to 2025, and predicts outcomes till 2030 using Facebook Prophet.



 📁 Dataset Information

- **Source**: [Kaggle: SSC Exam Result Trends in Bangladesh (2001–2025)](https://www.kaggle.com/)
- **Columns:**
  - `Year`: SSC exam year
  - `Total_Examinees`: Number of registered students
  - `Pass_Rate`: Percentage of students who passed
  - `GPA_5_Count`: Number of students who secured GPA 5 (highest grade)

---

## 📌 Key Visualizations & Insights

### 1. 🔄 Time Series Plot: Pass Rate & GPA 5 Count

- **Pass Rate:**  
  Steady growth from ~35% in 2001 to ~91% in 2014, followed by fluctuations; dips to ~68% in 2025.
  
- **GPA 5 Count:**  
  Rises from just 76 in 2001 to 269,602 in 2022 — indicating rising achievement or grade inflation.

---

### 2. 🔮 Forecast: SSC Pass Rate (2026–2030)
- **Model:** Facebook Prophet
- The **blue line** shows the predicted trend.
- The **shaded region** represents the uncertainty interval.
- 🔍 **Insight:** Forecast shows fluctuating performance with no clear upward trajectory.

---

### 3. 🔮 Forecast: GPA 5 Count (2026–2030)
- Also modeled using **Facebook Prophet**.
- **Trend:** Continues rising exponentially.
- **Red shaded area:** Reflects forecast uncertainty.
- 📈 Indicates increasing top-performers but with variability.

---

### 4. 📆 Total Examinees Over Time
- Shows consistent growth in student participation.
- 📌 Possible reasons:
  - Population growth
  - Improved school enrollment
  - Education policy reforms

---

### 5. 🔗 Scatter Plot: Pass Rate vs GPA 5 Count
- A **positive linear relationship**.
- Suggests that better overall performance leads to more top scorers.

---

### 6. 📊 GPA 5 Count Distribution (Box Plot)
- Shows statistical spread (median, IQR, outliers).
- Early years (2001–2005) identified as **outliers**.
- Helps detect abrupt changes and education shifts.

---

### 7. 🔄 Correlation Matrix & Heatmap

| Variable Pair                  | Correlation |
|-------------------------------|-------------|
| Total Examinees ↔ Pass Rate   | 0.69        |
| Total Examinees ↔ GPA 5 Count | 0.85        |
| Pass Rate ↔ GPA 5 Count       | 0.76        |

- 🔥 Strong positive correlations observed.
- Most significant: **Total Examinees ↔ GPA 5 Count (0.85)**
- Reflects systemic connection in education indicators.

---

## 🛠️ Tools & Technologies

- Python (Pandas, Matplotlib, Seaborn, Plotly)
- Facebook Prophet (Time Series Forecasting)
- Google Colab

