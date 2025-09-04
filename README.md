# Customer Churn Prediction 📉👥  

## 📌 Project Overview  
This project applies **Machine Learning** techniques to predict **Customer Churn** — whether a customer will leave or stay with a service provider. Predicting churn helps businesses reduce losses and improve customer retention strategies.  

The project was developed as part of my **Internshala Data Science Training**.  

---

## 📂 Dataset  
- **Source**: Provided by Internshala platform during training.  
- **Details**:  
  - Stored in `Customer_data.xlsx`  
  - Contains customer demographic, account, and service-related features  
  - Target variable → `Churn` (Yes / No)  
  - No missing values  

---

## ⚙️ Data Preprocessing  
Steps performed on raw data:  
- Handled missing values  
- Converted categorical variables into numeric form using **encoding**  
- Feature scaling for numerical attributes  
- Created train-test split (80-20)  

---

## 🧑‍💻 Feature Engineering  
- Extracted customer demographic and service usage features  
- Engineered key features such as:  
  - Tenure length  
  - Service subscriptions  
  - Contract type  
  - Payment method type  
  - Monthly charges & total charges  

---

## 🔀 Train-Test Split  
- 80% Training → used for model building  
- 20% Testing → used for evaluation  
- Stratified split to preserve churn distribution  

---

## 🤖 Models Implemented  
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  

---

## 🏆 Model Performance  
- **Best Model**: Random Forest Classifier  

**Performance Metrics on Test Set:**  
- Accuracy → **0.7839**  
- Precision → **0.6182**  
- Recall → **0.4893**  
- F1-Score → **0.5463**
[[920 113]
[191 183]]


---

## 📊 Results  
- The model achieved ~**78.4% accuracy** in predicting churn.  
- Identified key churn indicators such as **service subscriptions, contract type, and payment methods**.  
- Showed a trade-off between **precision and recall** → indicating room for improvement in correctly identifying churners.  

---

## 📌 Future Enhancements  
- Apply **ensemble methods** like XGBoost, LightGBM, CatBoost for higher accuracy  
- Use **deep learning (ANNs)** for better feature learning  
- Perform **feature importance analysis** to identify strongest churn drivers  
- Deploy as a **Flask/Streamlit web app** for business use  

---


**Confusion Matrix:**  
