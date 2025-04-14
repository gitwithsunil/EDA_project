# 📊 Telecom Customer Churn Analysis

This project explores customer churn behavior using service-related features from a telecom dataset. It provides valuable insights into what factors influence a customer's decision to leave or stay, helping businesses improve customer retention strategies.

---

## 👨‍💻 Author

**G. Sunil Kumar Reddy**  
[GitHub Profile](https://github.com/gitwithsunil)

---

## 📁 Files Included

- **Customer Churn.csv**: The main dataset used for analysis.
- **EDA.ipynb**: Jupyter Notebook containing all the data analysis and visualizations.

---

## 🎯 Objective

To analyze and visualize how different telecom services affect customer churn, and identify patterns that can help reduce churn rates.

---

## 🔍 Key Insights

✅ **Higher churn** is commonly observed among customers who:

- Use **fiber optic internet service**.
- **Do not subscribe** to:
  - Online Security  
  - Tech Support  
  - Device Protection  

✅ **Lower churn** is observed in customers who:

- Use **multiple active services**.
- Have **no internet service at all**, i.e., labeled as `"No internet service"`.

These observations suggest that customers using minimal or insecure services are more likely to leave, whereas fully engaged customers tend to stay.

---

## 📈 Visual Analysis

The EDA notebook uses **Seaborn** and **Matplotlib** to create grouped countplots for each service feature. Each plot compares churned (`Yes`) vs non-churned (`No`) customers:

Features analyzed include:
- `PhoneService`
- `MultipleLines`
- `InternetService`
- `OnlineSecurity`
- `OnlineBackup`
- `DeviceProtection`
- `TechSupport`
- ...and more.

---

## 🔧 Tools Used

- **Python 3.x**
- **Jupyter Notebook**
- **Pandas** – Data manipulation
- **Seaborn** – Visualization
- **Matplotlib** – Plotting

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/telecom-churn-analysis.git
   cd telecom-churn-analysis
