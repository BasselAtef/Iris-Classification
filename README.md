# DecodeLabs-Project2-Iris-Classification

# Iris Flower Classification Project

A concise machine learning project that visualizes the Iris dataset and trains basic classification models (K-Nearest Neighbors and Support Vector Machine) to predict iris flower species.

---

## If review fails to load on github:
* **Go to this link**
`https://nbviewer.org/`
* **Then paste the github repo link**

## 📈 Features

* **Exploratory Data Analysis:** Computes dataset shapes and generates a correlation heatmap using `seaborn`.
* **Data Preprocessing:** Splits the dataset into training and testing sets ($70/30$ split).
* **Machine Learning Pipelines:** Includes templates for both KNN (`KNeighborsClassifier`) and SVM (`SVC`) classifiers.

---

## 🛠️ Requirements & Libraries

The project requires Python 3 and the following dependencies:

* `numpy`
* `pandas`
* `matplotlib`
* `seaborn`
* `scikit-learn`

---

## 🚀 Quick Start

1. **Dataset:** Ensure the `IRIS.csv` file is placed in your project root directory.
2. **Execution:** Run the notebook cells sequentially to:
* Load and parse the dataset.
* Generate feature correlation matrices.
* Train and evaluate the models.



---

## 📊 Dataset Overview

* **Total Samples:** 150
* **Features:** 4 (Sepal Length, Sepal Width, Petal Length, Petal Width)
* **Target Classes:** 3 (`Iris-setosa`, `Iris-versicolor`, `Iris-virginica`)
