# 🚢 Titanic Survival Prediction – CodSoft Internship

![Titanic Image](titanic-img.jpg)

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

```mermaid
graph TD;
A[Load Dataset] --> B[Clean & Preprocess Data];
B --> C[Handle Missing Values];
C --> D[Convert Categorical to Numerical];
D --> E[Split Data (Train/Test)];
E --> F[Model Training];
F --> G[Evaluate Performance];
G --> H[Visualize Results];
```

---

## 🔍 The Process (Step-by-Step)

✅ **1. Data Cleaning:**

* Removed columns like `Name`, `Ticket`, and `Cabin` (irrelevant or too sparse)
* Handled missing values in:

  * `Age` → filled with **mean**
  * `Embarked` → filled with **mode**

✅ **2. Feature Engineering:**

* Converted `Sex` and `Embarked` columns using `LabelEncoder`
* Ensured all inputs are numeric

✅ **3. Model Building:**

* Used **Logistic Regression** and **Random Forest** classifiers
* Data split into **75% training** and **25% testing**

✅ **4. Evaluation Metrics:**

* Accuracy Score
* Confusion Matrix
* Classification Report
* Cross-Validation (optional)

✅ **5. Visualization:**

* Confusion Matrix heatmap using `Seaborn`
* Tableau Dashboards for deep visual insights

---

## 📈 Model Performance

| Model               | Accuracy | Notes                        |
| ------------------- | -------- | ---------------------------- |
| Logistic Regression | \~81%    | Simple & fast baseline model |
| Random Forest       | \~85%    | Better generalization        |

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

🚨 *You can insert your content or a Tableau Public link here once published.*

---

## 🌟 Key Takeaways

* Improved understanding of **data preprocessing techniques**
* Explored **classification models** and evaluated them
* Developed hands-on experience with **model interpretability**
* Created **interactive visualizations** using Tableau

---

## 🔗 Links

📂 [View Notebook on GitHub](#)
📊 [View Tableau Dashboard (if available)](#)

---

## 🔖 Hashtags

`#DataScience` `#MachineLearning` `#TitanicDataset` `#CodSoftInternship` `#Python` `#Tableau` `#LogisticRegression` `#RandomForest` `#Visualization` `#GitHubProjects`

---
