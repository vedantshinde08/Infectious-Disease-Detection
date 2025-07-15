
---

## 🔍 Problem Statement

Malaria remains a major public health challenge in low- and middle-income countries, with unequal healthcare access and underreporting complicating control efforts. The project aims to leverage data science to:

- Predict malaria incidence using historical surveillance data.
- Classify malaria risk levels by country.
- Visualize temporal, spatial, and socioeconomic factors affecting malaria spread.
- Generate actionable insights and public health recommendations.

---

## 📊 Data Source

- **Dataset:** WHO World Malaria Report 2024 - Annex 4F  
- **Attributes:**  
  - Malaria cases and deaths  
  - Population at risk  
  - Intervention metrics (e.g., bed net coverage)  
  - Country-level metadata and year  
- **Coverage:** 80+ countries across multiple WHO regions  

---

## 🤖 Machine Learning

### Models Used

- **Linear Regression:** Used as a baseline to understand linear patterns.
- **Decision Tree Regressor:** Simple, interpretable non-linear model.
- **Random Forest Regressor & Classifier:** Final models used for robust predictions and feature importance.

### Tasks Performed

- **Regression:** Predict number of malaria cases.
- **Classification:** Categorize risk levels as Low (<1,000), Medium (1,000–9,999), and High (≥10,000).
- **Feature Importance:** Population size was found to be the most influential factor.

### Performance

- **Regression R² Score:** 0.933  
- **Classification Accuracy:** 91%  
- **MAE:** ~3.68 million cases  

---

## 📈 Tableau Dashboard

### Visualizations

- Choropleth Map: Global malaria risk by country
- Bar Chart: Top 10 affected countries
- Area Chart: Year-wise trend of cases
- Scatter Plot: GDP vs Malaria Incidence
- Heatmap: Temporal incidence by region
- Treemap: Proportional burden of cases

### Key Features

- **Interactivity:** Filters by country and year
- **What-If Analysis:** Simulate impact of changes in GDP or clean water access
- **Integration:** ML-predicted values visualized alongside real data

### 📎 View Dashboard

🔗 [Click here to view on Tableau Public](https://public.tableau.com/views/Book1_17493343980400/Dashboard1)

---

## 🧩 Integration & Storytelling

- Combined predicted and actual malaria case data over time
- Mapped risk categories across countries
- Explained key determinants: economic status, water access, healthcare infrastructure, environmental conditions
- 
---

## 💡 Key Insights

- Population size is the most influential predictor of malaria incidence.
- Poor water access and low GDP correlate strongly with high malaria risk.
- ML models enable early identification of high-risk regions for proactive intervention.
- Interactive dashboards empower public health officials to explore data dynamically.

---

## 📚 References

- World Health Organization. (2024). World Malaria Report 2024
- Bhatt et al. (2015), Chirico et al. (2021), Rao & Krishnan (2021), Zou et al. (2018), and others

See full references in [`Global Infectious Disease Detection.pdf`](./Global%20Infectious%20Disease%20Detection.pdf)

---

## 📌 Author
**Vedant Shinde**  

