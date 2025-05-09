# Titanic - Machine Learning from Disaster 🚢

This is a mini-project using Python and machine learning to solve the classic [Kaggle Titanic competition](https://www.kaggle.com/competitions/titanic). The goal is to predict survival outcomes on the Titanic using passenger data like age, gender, class, etc.

## 📌 Project Goals

- Demonstrate a full machine learning workflow in Python.
- Practice data preprocessing, feature engineering, and model training.
- Apply basic classification algorithms and compare their performance.
- Generate predictions in the correct Kaggle submission format.

## 🛠 Technologies Used

- Python
- NumPy, Pandas for data manipulation
- Matplotlib, Seaborn for data visualization
- Scikit-learn for machine learning models and evaluation

## 📊 Key Steps

### 1. Data Handling
- Load `train.csv` and `test.csv` using Pandas.
- Handle missing values (e.g. Age, Cabin, Embarked).
- Encode categorical variables (e.g. Sex, Embarked).
- Feature engineering (e.g. Title extraction from Name, Family size).

### 2. Data Visualization
- Explore survival rates across different features like Pclass, Sex, Age.
- Use Seaborn and Matplotlib for bar plots and histograms.

### 3. Model Building
We tested and evaluated multiple supervised ML models:
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Random Forest Classifier**

Each model was trained using the training set and evaluated using cross-validation accuracy.

### 4. Model Evaluation
- Use **cross-validation** to get local validation scores.
- Compare models and select the best performing one for final prediction.

### 5. Submission
- Generate predictions on the test set.
- Export results to `submission.csv` in the format required by Kaggle:
