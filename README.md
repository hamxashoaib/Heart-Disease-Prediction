# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction and diagnosis can significantly improve patient outcomes and reduce healthcare risks.

This project uses Machine Learning techniques to predict whether a person is at risk of heart disease based on clinical and demographic health data. The project covers the complete machine learning workflow, including data cleaning, exploratory data analysis (EDA), model training, evaluation, and feature importance analysis.

---

## 🎯 Objective

To develop a classification model capable of predicting the likelihood of heart disease using patient health indicators and medical attributes.

---

## 📊 Dataset

### Heart Disease UCI Dataset

The dataset contains patient health records and medical measurements commonly used for cardiovascular disease diagnosis.

### Features Included

| Feature | Description |
|----------|------------|
| age | Age of the patient |
| sex | Gender |
| cp | Chest pain type |
| trestbps | Resting blood pressure |
| chol | Cholesterol level |
| fbs | Fasting blood sugar |
| restecg | Resting ECG results |
| thalach | Maximum heart rate achieved |
| exang | Exercise-induced angina |
| oldpeak | ST depression induced by exercise |
| slope | Slope of peak exercise ST segment |
| ca | Number of major vessels colored by fluoroscopy |
| thal | Thalassemia |
| target | Heart Disease Presence (0 = No, 1 = Yes) |

---

## 🔍 Data Preprocessing

The following preprocessing steps were performed:

- Dataset inspection
- Missing value analysis
- Duplicate record detection and removal
- Feature selection
- Data scaling using StandardScaler

---

## 📈 Exploratory Data Analysis (EDA)

Several visualizations were created to understand patterns and relationships within the dataset:

- Target variable distribution
- Age distribution
- Heart disease occurrence by gender
- Correlation heatmap
- Feature relationship analysis

EDA helped identify the most influential factors associated with heart disease risk.

---

## 🤖 Machine Learning Models

Two classification models were trained and evaluated:

### 1️⃣ Logistic Regression

A statistical classification model used as the primary baseline model.

### 2️⃣ Decision Tree Classifier

A tree-based model capable of capturing non-linear relationships in the dataset.

---

## ⚙️ Project Workflow

1. Load dataset
2. Inspect and clean data
3. Perform exploratory data analysis
4. Prepare features and target variable
5. Split dataset into training and testing sets
6. Standardize feature values
7. Train classification models
8. Evaluate model performance
9. Analyze feature importance
10. Visualize results

---

## 📊 Model Evaluation

The models were evaluated using multiple performance metrics:

### Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC Curve
- Area Under Curve (AUC)

### Results

| Model | Accuracy |
|---------|---------|
| Logistic Regression | 80.33% |
| Decision Tree | 77.05% |

The Logistic Regression model achieved the highest accuracy and demonstrated better generalization performance on the testing dataset.

---

## 📉 Visualizations

The project includes:

- Target Distribution Plot
- Correlation Heatmap
- Age Distribution Analysis
- Gender vs Heart Disease Analysis
- Confusion Matrix
- ROC Curve
- Feature Importance Visualization

These visualizations provide insights into the factors contributing to heart disease prediction.

---

## 🧠 Feature Importance Analysis

Feature importance analysis was performed to identify the most influential predictors affecting heart disease risk.

Examples of important features include:

- Chest Pain Type (cp)
- Maximum Heart Rate (thalach)
- Number of Major Vessels (ca)
- ST Depression (oldpeak)
- Thalassemia (thal)
- Age

Understanding feature importance improves model interpretability and supports medical decision-making.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📂 Project Structure

``` id="hfjlwm"
Heart-Disease-Prediction/
│
├── heart_disease_prediction.ipynb
├── heart.csv
├── requirements.txt
├── README.md
└── screenshots/
```

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/hamxashoaib/Heart-Disease-Prediction.git
```

Navigate to project directory:

```bash
cd Heart-Disease-Prediction
```

Install required packages:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

``` id="utukng"
heart_disease_prediction.ipynb
```

Run all cells sequentially.

---

## 🎓 Skills Demonstrated

This project demonstrates practical experience in:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Machine Learning Classification
- Feature Engineering
- Model Evaluation
- Healthcare Data Analytics
- Predictive Modeling

---

## 🚀 Future Improvements

Potential enhancements include:

- Random Forest Classifier
- XGBoost Classifier
- Hyperparameter Tuning
- Cross Validation
- Model Deployment using Streamlit
- Real-Time Health Risk Assessment Dashboard

---

## 💡 Conclusion

This project successfully predicts the likelihood of heart disease using machine learning techniques and healthcare data. Logistic Regression achieved the best performance with an accuracy of approximately 80%, demonstrating the effectiveness of machine learning in supporting healthcare decision-making and risk assessment.

---

## 👨‍💻 Author

**Hamza Shoaib**

BS Artificial Intelligence  

The Islamia University of Bahawalpur

---

## 📄 License

This project is intended for educational, research, and portfolio purposes.
