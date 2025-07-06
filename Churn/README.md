# 📉 Customer Churn Analysis

Welcome to my project on analyzing customer churn in a telecom company! 
Have you ever wondered why some customers leave a service while others stay for years? In this project, I dive into real customer data to find out what drives churn, visualize important patterns, and build a machine learning model that predicts which customers are likely to leave.
The goal? To help the company reduce churn by understanding who’s at risk and suggesting strategies like offering better contracts or personalized promotions.

---

## What I did

- **Exploratory Data Analysis (EDA)** to spot patterns between customer behavior and churn.
- **Feature engineering** to prepare the data for modeling.
- **Built and evaluated classification models** (logistic regression, decision tree, random forest) to predict churn.
- **Visualized insights** to make the results easy to understand for both technical and non-technical audiences.

---

## Highlights of the analysis

- **Total customer overview**
  - Calculated the total number of customers, how many churned (`Churn=Yes`), and how many stayed (`Churn=No`).
  - Computed the churn rate as:
    ```
    churn rate = number of churned customers / total customers
    ```

- **Feature insights**
  - Plotted histograms and boxplots to compare key features like tenure, monthly charges, and more against churn.
  - Explored questions such as:
    - Do males and females churn at different rates?
    - Are seniors more likely to churn?
    - How does the type of contract (month-to-month vs one/two years) affect churn? Spoiler: churn tends to be higher for month-to-month contracts.

---

## 📸 Example visualization

Here’s a sample plot from the analysis — it shows churn rate by contract type (replace this with your actual plot if needed):

![download](https://github.com/user-attachments/assets/4d04e820-f8ad-4681-a466-f541108cd262)

---

## Technologies used

- Python 
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- Jupyter Notebook

---

Thanks for checking out this project! Feel free to clone the repo, run the notebooks, and explore the data yourself.
