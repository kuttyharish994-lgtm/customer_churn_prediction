# Customer Churn Prediction Using Machine Learning
> **Leveraging Data Science for Customer Retention** > *Presented by: Harish S (Data Science Course)*

---

## 📌 Project Overview
[span_0](start_span)[span_1](start_span)Customer churn—when customers stop doing business with a company—is a critical metric that directly impacts revenue, growth, and long-term sustainability in the telecommunications industry[span_0](end_span)[span_1](end_span). [span_2](start_span)[span_3](start_span)Because acquiring new customers costs **5x to 25x more** than retaining existing ones, predicting and understanding churn patterns allows businesses to implement targeted retention strategies, reduce revenue loss, and optimize marketing spend[span_2](end_span)[span_3](end_span).

### The Problem
[span_4](start_span)Traditional methods of identifying at-risk customers often fail to detect warning signs until it's too late[span_4](end_span). [span_5](start_span)Customer data is complex and multidimensional, making manual pattern analysis highly inefficient[span_5](end_span). 

### Objectives
* **[span_6](start_span)[span_7](start_span)Analyze** customer data to uncover key behavioral characteristics and patterns associated with churn[span_6](end_span)[span_7](end_span).
* **[span_8](start_span)[span_9](start_span)Build** accurate machine learning models capable of forecasting churn probability[span_8](end_span)[span_9](end_span).
* **[span_10](start_span)[span_11](start_span)Develop** actionable, data-driven retention strategies based on model insights[span_10](end_span)[span_11](end_span).

---

## 📊 Dataset Overview
[span_12](start_span)This project utilizes the benchmark **Telco Customer Churn dataset**[span_12](end_span).
* **[span_13](start_span)Size:** 7,043 customer records with 21 features[span_13](end_span).
* **[span_14](start_span)Data Split:** 70% Training, 30% Testing[span_14](end_span).
* **[span_15](start_span)Features Collected:** * **Demographics:** Gender, senior citizen status, partner, and dependents[span_15](end_span).
  * **[span_16](start_span)Account Information:** Tenure (months with company), contract type, payment method, monthly charges, and total charges[span_16](end_span).
  * **[span_17](start_span)Services Subscribed:** Phone, Internet, Security, Backup, Tech Support[span_17](end_span).
  * **[span_18](start_span)Target Variable:** Churn (Yes/No)[span_18](end_span).

---

## 🛠️ Technology Stack
* **[span_19](start_span)[span_20](start_span)Python**: Core language for the pipeline[span_19](end_span)[span_20](end_span).
* **[span_21](start_span)[span_22](start_span)Pandas & NumPy**: Efficient data manipulation, analysis, and numerical computations[span_21](end_span)[span_22](end_span).
* **[span_23](start_span)[span_24](start_span)Matplotlib & Seaborn**: Statistical graphics, interactive charts, and correlation heatmaps[span_23](end_span)[span_24](end_span).
* **[span_25](start_span)[span_26](start_span)Scikit-learn**: Machine learning algorithms, model selection, and performance evaluation metrics[span_25](end_span)[span_26](end_span).

---

## ⚙️ Methodology & Machine Learning Pipeline
Our workflow follows a systematic, standard machine learning framework:

```text
[Data Collection] ➔ [Data Preprocessing] ➔ [Exploratory Data Analysis (EDA)] ➔ [Model Building] ➔ [Evaluation & Monitoring]
