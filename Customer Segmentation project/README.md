# Customer Satisfaction Prediction 📊🤖

## 📌 Project Description
This project aims to predict **customer satisfaction** based on historical support ticket data using **Machine Learning**, **Data Analysis**, and **Feature Engineering** techniques. It involves processing a dataset that includes customer demographics, ticket details, resolution info, and satisfaction ratings to build predictive and analytical models.

---

## 🛠️ Tools & Technologies
- **Languages**: Python, SQL, Excel  
- **Libraries**: pandas, numpy, seaborn, matplotlib, scikit-learn  
- **Tools/Platforms**: Jupyter Notebook, VS Code  
- **ML Algorithm**: Random Forest Classifier  
- **Data Source**: [Customer Support Ticket Dataset (Google Drive)](https://drive.google.com/file/d/1DRdLKOinSNuoMwVyFGH86f3xEhkZMrz6/view?usp=sharing)

---

## 📂 Dataset Overview
The dataset includes:
- Customer details (Age, Gender, Email)
- Product purchased and purchase date
- Ticket information (Type, Description, Channel, Priority)
- Support metrics (First Response Time, Time to Resolution)
- **Customer Satisfaction Rating** (1 to 5)

---

## 🧪 Use Cases
- Predict Customer Satisfaction  
- Analyze Support Ticket Trends  
- Segment Customers  
- Identify Common Issues  
- NLP on Ticket Descriptions  
- Predict Resolution Times  
- Build Recommender Systems for Support Automation

---

## 📈 Steps Involved

1. **Data Preprocessing**
   - Handle missing values
   - Encode categorical features
   - Standardize features

2. **Exploratory Data Analysis (EDA)**
   - Ticket trends over time
   - Common issues and subjects
   - Distribution of satisfaction, age, gender, etc.

3. **Feature Engineering**
   - Age Group binning
   - Creating interaction features
   - Text vectorization (CountVectorizer)

4. **Model Building**
   - Train/Test Split
   - Random Forest Classifier for prediction

5. **Model Evaluation**
   - Accuracy, Confusion Matrix, Classification Report
   - Feature importance analysis

6. **Visualization**
   - Satisfaction distribution
   - Ticket type & priority distribution
   - Top purchased products
   - Age vs ticket types using facet grid

---

## 🔍 Key Visual Insights
- 📊 Top 10 customer complaints
- 🧑‍🤝‍🧑 Gender-based satisfaction ratings
- 🛒 Most purchased products by gender
- ⏳ Tickets by response/resolution time
- 🎯 Customer segments based on ticket type & satisfaction level

---

## ✅ Sample Code Snippet

```python
# Model Training
rfc = RandomForestClassifier(random_state=42)
rfc.fit(X_train, y_train)

# Prediction & Evaluation
y_pred = rfc.predict(X_test)
print("Accuracy:", accuracy_score(y_test, y_pred))
print("Confusion Matrix:
", confusion_matrix(y_test, y_pred))
```

---

## ✅ Conclusion

The Customer Satisfaction Prediction project demonstrates the effective application of data analysis and machine learning to solve real-world business challenges. By analyzing customer support ticket data, we identified key drivers behind customer satisfaction and built a predictive model using Random Forest Classifier.

This project highlights the importance of:
- Clean and well-preprocessed data  
- Exploratory analysis to uncover patterns  
- Feature engineering to enhance model performance  
- Visual storytelling to communicate insights  

The resulting insights can empower businesses to:
- Proactively address recurring customer issues  
- Improve support team performance  
- Enhance customer retention strategies  
- Prioritize high-impact tickets based on predicted satisfaction  

In summary, this project is a step toward more intelligent, data-driven customer experience management.

---
