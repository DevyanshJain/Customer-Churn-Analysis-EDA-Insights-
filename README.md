# 📉 Customer Churn Analysis (EDA + Insights)

This project explores customer churn behavior using data from a telecom company. It focuses on cleaning raw data, extracting insights through Exploratory Data Analysis (EDA), and asking key business questions to understand churn drivers.

---

## 📌 What is Churn?

**Churn** refers to a customer **cancelling their subscription** or leaving the service. Reducing churn is critical for subscription-based businesses to grow sustainably.

---

## 📊 Key Questions Answered

The `Insights and Solutions.ipynb` notebook addresses several business questions using pandas and visualizations:

| #  | Question                                                                 | Insight |
|----|--------------------------------------------------------------------------|---------|
| 1  | Which contract type has the highest churn rate?                         | Month-to-month contracts have the highest churn. |
| 2  | Are senior citizens more likely to churn?                               | Yes — senior citizens churn more often. |
| 3  | Does having tech support reduce churn?                                  | Yes — having tech support significantly lowers churn. |
| 4  | What is the relationship between monthly charges and churn?             | Customers with higher monthly charges churn more. |
| 5  | Does internet service type affect churn?                                | Fiber optic users churn more than DSL or no internet. |
| 6  | Which payment method is most associated with churn?                     | Electronic checks are linked to higher churn. |
| 7  | How does tenure affect churn behavior?                                  | Customers who churn tend to leave early (within 10 months). |

---

## 🛠️ Tools Used

- `pandas` for data analysis
- `matplotlib` & `seaborn` for visualization
- `Jupyter Notebook` for exploration
- `Python` 3.8+

---

## 📈 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Customer-Churn-EDA.git
   cd Customer-Churn-EDA
   ```
2. Install Dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebooks:
   - notebooks/Cleaning Data and EDA.ipynb — Data cleaning & exploration
   - notebooks/Insights and Solutions.ipynb — Business questions & insights
## 🤔 Future Work

- Build a churn prediction model using logistic regression or tree-based models.
- Create an interactive dashboard in Power BI or Streamlit.
- Segment customers by lifetime value or risk.

## 📬 Contact
Made by [Devyansh Jain] — feel free to connect via [LinkedIn](https://linkedin.com/in/devyansh-jain) or raise issues if you have questions!
