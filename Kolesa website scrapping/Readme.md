# Dataset Overview
--- 
## 🚗 Kolesa.kz Car Price Analysis

This project is a review and analysis of data scraped from [Kolesa.kz](https://kolesa.kz), a popular car marketplace in Kazakhstan where users can buy and sell vehicles and auto parts.

---

## 🔍 What Was Done

Using **BeautifulSoup** and **pandas**, I scraped data such as:

- Car brand and model  
- Year of production  
- Engine size  
- Price  
- Location and more

After cleaning and processing, the dataset contains:

- ✅ **952 rows**  
- ✅ **16 columns**

---

## 🧪 Analysis & Modeling

I applied both statistical and machine learning models to understand price trends and make predictions:

### 🔹 OLS Regression (statsmodels)

- **R² = 0.595**
- Shows that over **59%** of price variation can be explained by the model

### 🔹 Linear Regression (scikit-learn)

- Features: year, engine size  
- **R² = 0.63** — better fit for prediction

### 🔹 Logistic Regression (scikit-learn)

- Used for price category classification  
- **Accuracy: 79.6%**  
- **Confusion Matrix**:
  - True Positives: 119  
  - True Negatives: 33  
  - False Positives: 8  
  - False Negatives: 31  

---

## 🛠 Libraries Used

- `BeautifulSoup`, `requests` — for scraping  
- `pandas`, `numpy` — for data handling  
- `statsmodels`, `patsy` — for statistical modeling  
- `scikit-learn` — for machine learning

---

## 📎 Note

This project is for **educational purposes only**. All data was collected from public listings.


---
### 📈 Graphic Example:
<img width="1369" height="449" alt="image" src="https://github.com/user-attachments/assets/e616227e-2db5-4e44-95f4-ae3a44d1e3c6" />

