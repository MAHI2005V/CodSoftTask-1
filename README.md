# 🚢 Titanic Survival Prediction – CodSoft Internship

 <p align="center">
  <img src="titanic-img.jpg" alt="Titanic" width="500">
    <em><strong>RMS Titanic departing Southampton for the only time on 10 April 1912</strong></em>
</p>


---

## 📌 Project Overview

This project is part of my **Data Science Internship with [CodSoft](https://www.codsoft.in/)**.
The objective is to **analyze and predict** the survival of passengers aboard the Titanic using historical data.

Using various preprocessing and classification techniques, we build a machine learning model that predicts whether a passenger survived or not based on key features like age, fare, sex, class, etc.

---

## 🧰 Tools & Libraries Used

| 🧠 Machine Learning                              | 📊 Visualization                       | 🧼 Preprocessing                      | 🐍 Language  |
| ------------------------------------------------ | -------------------------------------- | ------------------------------------- | ------------ |
| `LogisticRegression`<br>`RandomForestClassifier` | `Matplotlib`<br>`Seaborn`<br>`Tableau` | `pandas`<br>`scikit-learn`<br>`NumPy` | `Python 3.x` |

---

## 🔄 Project Workflow
Below is a step-by-step breakdown of how the Titanic Survival Prediction project was executed:

📁 1. Data Cleaning & Preprocessing
🔍 Removed irrelevant/sparse columns: Name, Ticket, and Cabin

🧹 Handled missing values:

Age: Filled with mean

Embarked: Filled with mode

🔄 Converted categorical columns (Sex, Embarked) to numerical using Label Encoding


🧠 2. Feature Engineering
✅ Ensured all features were numeric and model-ready

🛠️ Selected relevant features to train the model


🤖 3. Model Building
🔬 Algorithms used:

Logistic Regression

Random Forest Classifier

📊 Split the dataset:

75% for training

25% for testing


📏 4. Evaluation Metrics
✔️ Accuracy Score

✔️ Confusion Matrix

✔️ Classification Report

✔️ Cross-Validation (to validate performance robustness)


📊 5. Visualization
🎯 Used Seaborn to plot a Confusion Matrix Heatmap

📉 Created rich interactive dashboards in Tableau for in-depth insights


---

## ## 📈 Model Performance

- ✅ **Accuracy Score**: ~81% on test data
- 📊 **Evaluation Metrics**: Precision, Recall, and F1-Score visualized
- 🧩 **Confusion Matrix** plotted using Seaborn
---

## 🗂️ Project Structure

```
├── titanic_survival_prediction/
│   ├── titanic_dataset.csv
│   ├── titanic_notebook.ipynb
│   ├── README.md
│   └── images/
│       └── titanic.png (used in README)
```

---

## 📊 Tableau Dashboard Highlights

 <p align="center">
  <img src="Tableau Public - titanic 7_24_2025 10_07_06 PM.png" alt="Titanic" width="500">
  <em><strong>Titanic Dataset - Survival Analysis Overview</strong></em>
</p>

<p align="center">
  <img src="Tableau Public - titanic 7_24_2025 10_07_29 PM.png" alt="Titanic" width="500">
  <em><strong>Titanic Dataset - Survival by Age </strong></em>
</p>

<p align="center">
  <img src="Tableau Public - titanic 7_24_2025 10_07_33 PM.png" alt="Titanic" width="500">
  <em><strong>Titanic Dataset - Male and Female Passengers Survived</strong></em>
</p>

<p align="center">
  <img src="Tableau Public - titanic 7_24_2025 10_08_02 PM.png" alt="Titanic" width="500">
  <em><strong>Titanic Dataset - Passengers family abroad</strong></em>
</p>

<p align="center">
  <img src="Tableau Public - titanic 7_24_2025 10_08_55 PM.png" alt="Titanic" width="500">
  <em><strong>Titanic Dataset - Passenger's Port of Embarkation who survived</strong></em>
</p>

<p align="center">
  <img src="Tableau Public - titanic 7_24_2025 10_09_04 PM.png" alt="Titanic" width="500">
  <em><strong>Titanic Dataset - Passengers survived  based on fare </strong></em>
</p>

<p align="center">
  <img src="Tableau Public - titanic 7_24_2025 10_09_52 PM.png" alt="Titanic" width="500">
  <em><strong>Titanic Dataset - Survival of passengers categorized by class</strong></em>
</p>

---

## 🌟 Key Takeaways

* Improved understanding of **data preprocessing techniques**
* Explored **classification models** and evaluated them
* Developed hands-on experience with **model interpretability**
* Created **interactive visualizations** using Tableau

---

## 🔗 Links

📂 View Notebook on GitHub : https://github.com/MAHI2005V/CodSoftTask-1/blob/main/Titanic-Survival-Predicition-checkpoint.ipynb
💼 Connect on LinkedIn : www.linkedin.com/in/maheshwari-d-378aab325
---

## 🔖 Hashtags

`#DataScience` `#MachineLearning` `#TitanicDataset` `#CodSoftInternship` `#Python` `#Tableau` `#LogisticRegression` `#RandomForest` `#Visualization` `#GitHubProjects`

---
