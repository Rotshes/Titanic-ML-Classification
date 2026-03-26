# Titanic Dataset - Machine Learning Classification

This project implements a supervised learning workflow to predict passenger survival on the Titanic. Using the classic Titanic dataset, the project explores data preprocessing, feature engineering, and the application of classification algorithms to achieve accurate predictions.

## 📊 Project Overview
The goal of this project is to build a predictive model that answers the question: “What sorts of people were more likely to survive?” using passenger data (ie. name, age, gender, socio-economic class, etc.).

## 📁 Repository Structure
* **`Assignment2_supervised_learning_flow.ipynb`**: The primary Jupyter Notebook containing the end-to-end machine learning pipeline, including data exploration, cleaning, model training, and evaluation.
* **`titanic_train.csv`**: The training dataset containing the labels (Survived).
* **`titanic_test.csv`**: The test dataset used to verify model performance on unseen data.

## 🛠️ Technologies Used
* **Python**: The core programming language.
* **Jupyter Notebook**: For interactive development and documentation.
* **Pandas & NumPy**: For data manipulation and numerical analysis.
* **Scikit-Learn**: For implementing machine learning models and evaluation metrics.
* **Matplotlib / Seaborn**: For data visualization and identifying patterns in survival rates.

## 🚀 Workflow
1.  **Data Exploration (EDA):** Visualizing correlations between features like `Pclass`, `Sex`, and `Age` with the target variable `Survived`.
2.  **Data Preprocessing:** * Handling missing values (e.g., Age, Embarked, Cabin).
    * Encoding categorical variables into numerical format.
3.  **Feature Engineering:** Extracting meaningful information from existing columns to improve model accuracy.
4.  **Model Selection:** Implementing classification algorithms such as Logistic Regression, Decision Trees, or Random Forests.
5.  **Evaluation:** Measuring performance using accuracy scores, confusion matrices, and classification reports.

## ⚙️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Rotshes/Titanic-ML-Classification.git
   ```
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Open `Assignment2_supervised_learning_flow.ipynb` in Jupyter Notebook or VS Code to view the analysis and run the cells.
