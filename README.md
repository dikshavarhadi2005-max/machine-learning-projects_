# machine-learning-projects_
# Linear Regression on Auto Dataset

## Project Overview
This project uses a **Linear Regression** model to predict the price of vehicles using different automobile features from the Auto Dataset.

The notebook includes:
- Data loading and preprocessing
- Encoding categorical features
- Model training using Linear Regression
- Model evaluation
- Saving and loading the trained model using Pickle

---

## Technologies Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- Pickle

---

## Project Workflow

### 1. Import Libraries
Required Python libraries are imported for data analysis, visualization, and machine learning.

### 2. Data Gathering
The automobile dataset is loaded using Pandas.

### 3. Data Preprocessing
- Handling categorical data
- Label Encoding
- One Hot Encoding

### 4. Train-Test Split
The dataset is divided into training and testing data.

### 5. Model Training
A Linear Regression model is trained using the processed dataset.

### 6. Model Evaluation
The model performance is evaluated using regression metrics.

### 7. Save and Load Model
The trained model is saved using Pickle and later loaded for prediction.

---

## Files Included
- `day linear regression auto data set.ipynb` → Main Jupyter Notebook
- `README.md` → Project documentation

---

## Output
The model predicts vehicle prices based on automobile features.

---

## Conclusion
This project demonstrates how Linear Regression can be applied to automobile datasets for price prediction using machine learning techniques.





# 🌸 Iris Flower Classification using Logistic Regression

## 📌 Project Overview

This project uses a Logistic Regression machine learning model to classify iris flowers into different species using the famous Iris Dataset.

The model predicts flower species based on:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The project also includes:
- Data preprocessing
- Data visualization
- Model training
- Model evaluation
- Model saving using Pickle

---

# 🌼 Iris Flower Species

- Iris Setosa
- Iris Versicolor
- Iris Virginica

---

# 🎯 Objective

The main objective of this project is to build a machine learning classification model that predicts the correct iris flower species using flower measurements.

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Pickle
- Jupyter Notebook

---

# ⚙️ Project Workflow

## 1️⃣ Import Libraries

Required libraries for machine learning, data analysis, and visualization are imported.

---

## 2️⃣ Load Dataset

The Iris dataset is loaded using Pandas.

```python
df = pd.read_csv("Iris.csv")

3️⃣ Data Preprocessing

Data preprocessing steps include:

Checking dataset information
Statistical analysis
Handling missing values
Removing unnecessary columns
Separating input and output variables
4️⃣ Data Visualization

Visualization techniques used in the project:

Scatter Plot
Line Plot
Heatmap
Pairplot
Histogram
KDE Plot
5️⃣ Train-Test Split

The dataset is divided into training and testing datasets.

from sklearn.model_selection import train_test_split
6️⃣ Model Training

A Logistic Regression model is trained using the dataset.

from sklearn.linear_model import LogisticRegression
7️⃣ Model Evaluation

The model is evaluated using:

Accuracy Score
Precision Score
Recall Score
Confusion Matrix
Classification Report
✅ Model Accuracy
42/45 Correct Predictions
8️⃣ Save and Load Model

The trained model is saved using Pickle.

pickle.dump(logreg, file)
9️⃣ User Prediction System

The project accepts user input values for:

Sepal Length
Sepal Width
Petal Length
Petal Width

and predicts the flower species.

📂 Files Included
File Name	Description
Day 33 Logistic Regression iris-flower-data.ipynb	Main Jupyter Notebook
iris_model.pkl	Saved Machine Learning Model
README.md	Project Documentation
📈 Output

The model predicts iris flower species based on flower measurements with high accuracy.

🎯 Conclusion

This project demonstrates the implementation of Logistic Regression for classification problems using the Iris Flower Dataset along with data visualization and model deployment using Pickle.
