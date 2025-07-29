## Titanic Survival Prediction 

![Titanic](C:/Users/mahes/Downloads/Codsoft/titanic-img.jpg)

#  📌 Internship Project at **CodSoft** - 🚢 Titanic Survival Prediction - Task 1

---

## 📝 Overview

This project focuses on predicting the survival of passengers aboard the **Titanic** using machine learning techniques. By analyzing features like **age, gender, class, fare**, and **embarkation point**, a classification model was trained to determine whether a passenger survived or not.

---

## 🎯 Objective

To build and evaluate a machine learning model that predicts whether a passenger survived the Titanic disaster, using the dataset provided in the [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data).

---

## 🔧 Tools & Libraries Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib & Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**
- **Tableau** *(for visualization)*

---

## 🔍 Process

1. **Data Cleaning & Preprocessing**
   - Dropped irrelevant columns like `Name`, `Cabin`, and `Ticket`
   - Filled missing values:
     - `Age`: Replaced with mean
     - `Embarked`: Replaced with mode
   - Converted `Sex` to binary (0 for male, 1 for female)
   - One-hot encoded the `Embarked` column

2. **Exploratory Data Analysis (EDA)**
   - Heatmaps and correlation plots to understand data relationships
   - Bar plots for feature-wise survival distribution

3. **Model Training**
   - Used **Logistic Regression** and evaluated using:
     - **Accuracy Score**
     - **Confusion Matrix**
     - **Precision, Recall, F1-score**

4. **Visualization**
   - Created advanced visualizations in **Tableau**
   - Plots include:
     - Class-wise survival rate
     - Gender-wise survival
     - Fare distribution & survival pattern
     - Embarked vs Survival relationships

---

## 📈 Model Performance

- ✅ **Accuracy Score**: ~81% on test data
- 📊 **Evaluation Metrics**: Precision, Recall, and F1-Score visualized
- 🧩 **Confusion Matrix** plotted using Seaborn

---

## 📊 Tableau Dashboard Highlights

> Included Tableau visuals like:
- Survival distribution by class & gender
- Age and Fare correlation with survival
- Embarked port analysis

---

## 📁 Project Structure

├── titanic_survival_prediction.ipynb
├── dataset/
│ └── train.csv
├── visuals/
│ └── Tableau screenshots
├── README.md


---

## 🌟 Key Takeaways

- Reinforced understanding of **data preprocessing** and **feature engineering**
- Gained hands-on experience with **classification models**
- Built dynamic visual dashboards in **Tableau**
- Strengthened skills in **EDA**, **model evaluation**, and **presentation**

---

## 🔗 Links

- 📂 View Notebook on GitHub : https://github.com/MAHI2005V/CodSoftTask-1/blob/main/Titanic-Survival-Predicition-checkpoint.ipynb
- 💼 Connect on LinkedIn : www.linkedin.com/in/maheshwari-d-378aab325

---

## 📌 Hashtags

#DataScience #MachineLearning #LogisticRegression #TitanicDataset
#CodSoftInternship #Kaggle #Python #Tableau #MLProjects
