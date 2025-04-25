# Credit Score Classification Project

## Overview

This project aims to predict the **credit score category** of individuals using machine learning models. We preprocess the data, build multiple classifiers, and evaluate their performance based on standard classification metrics.

The project is structured as a Jupyter Notebook and walks through data cleaning, preprocessing, model building, evaluation, and comparison.

---

## Project Structure

- `GROUP14_FINAL_PROJECT_CODE.ipynb`: Main notebook containing the full codebase (data loading, preprocessing, modeling, evaluation).
- `credit_score_cleaned_train.csv`: Cleaned dataset used for training (should be provided separately if not included).

---

## Python Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## How It Works

1. **Data Loading & Cleaning**

   - Irrelevant features like `id`, `name`, `ssn`, etc., are dropped.
   - Missing values are removed.

2. **Data Preprocessing**

   - Categorical features are encoded.
   - Features are standardized using `StandardScaler`.

3. **Model Training**  
   The following models are trained:

   - Logistic Regression
   - Linear Discriminant Analysis (LDA)
   - Decision Tree Classifier
   - Random Forest Classifier
   - Multi-Layer Perceptron (MLP) Classifier

4. **Model Evaluation**  
   Models are evaluated using:

   - **Accuracy**
   - **Precision**
   - **Recall**
   - **F1 Score**

5. **Comparison**  
   A summary table is generated comparing the performance of all models.

---

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/credit-score-classification.git
   cd credit-score-classification
   ```
2. Install required packages
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook: Open GROUP14_FINAL_PROJECT_CODE.ipynb using Jupyter Notebook.
