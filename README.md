# 📊 Telecom Customer Churn Prediction

This project uses a real-world telecom dataset to build a machine learning model that predicts whether a customer will churn (leave the service). Churn prediction helps companies take action to improve customer retention and reduce revenue loss.

## 🔍 Objective
Use classification models to predict customer churn based on usage patterns, service features, and customer behavior.

## 📁 Dataset
- 4250 customer records
- 19 input features + 1 target variable (`churn`)
- Features include: call minutes, charges, international plan, voice mail plan, customer service calls, and more

## 🧪 Key Steps
- Exploratory Data Analysis (EDA)
- Feature engineering (skew handling, encoding, scaling)
- Handling missing values and skewed distributions
- Model training: CatBoost, Decision Tree, Random Forest
- Evaluation using Accuracy, Precision, Recall, F1-score
- Encoding comparison: One-Hot Encoding vs. CatBoost Encoding

## 🧠 Results
- Best model: **CatBoostClassifier**
- F1-score on churn class (`churn = 1`): **0.88**
- One-Hot Encoding performed better than CatBoost Encoding in this dataset
- Important predictive features included: `international_plan`, `customer_service_calls`, `voice_mail_plan`

## 💡 Business Insights
- **Customers with international plans** are more likely to churn → Offer better pricing or targeted promotions
- **Frequent customer service calls** may signal dissatisfaction → Improve support processes to reduce churn
- **Users without a voicemail plan** are less engaged → Promote value-added services to improve retention

## 🛠️ Tech Stack
- Python
- pandas, NumPy, Seaborn, Matplotlib
- scikit-learn, CatBoost
- category_encoders
- Jupyter Notebook

---

👩‍💻 **Author**: [Kristina Aleksov](https://www.linkedin.com/in/kristina-stoimilova/)  
📫 Contact: kristina_stoimilova@yahoo.com
