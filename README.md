# Machine Learning Assignment 2 – Customer Personality Analysis

## Student Information

* **Name:** Falastine Abu Serrya
* **University ID:** 2320222142

---

## Project Overview

This project applies supervised and unsupervised machine learning techniques to the **Customer Personality Analysis** dataset. The notebook demonstrates the complete machine learning workflow, including data preprocessing, feature engineering, exploratory data analysis (EDA), regression, classification, and clustering.

---

## Dataset

**Dataset:** `marketing_campaign.csv`

The dataset contains customer demographic information, purchase history, campaign responses, and household characteristics.

Place the dataset in the same directory as the notebook (or update the file path accordingly).

---

## Project Structure

```
.
├── Ass2_ML_Falastine.ipynb
├── marketing_campaign.csv
├── README.md
└── requirements.txt (optional)
```

---

## Project Tasks

### 1. Data Preprocessing

* Load and inspect the dataset.
* Handle missing values using median imputation.
* Create new features:

  * Age
  * TotalSpending
  * TotalChildren
* Remove unrealistic ages and zero-income records.
* Encode categorical variables.

### 2. Exploratory Data Analysis (EDA)

* Correlation Heatmap
* Total Spending Distribution
* Response Class Distribution

### 3. Regression

Predict customer **TotalSpending** using:

* Linear Regression
* Ridge Regression
* Decision Tree Regressor

Evaluation metrics:

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

### 4. Classification

Predict whether a customer accepted the last marketing campaign (**Response**) using:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Random Forest Classifier

Evaluation metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

### 5. Clustering

Customer segmentation using K-Means clustering based on:

* Income
* TotalSpending
* Age
* TotalChildren

The project includes:

* Feature scaling
* Elbow Method
* PCA visualization
* Cluster profiling

---

## Technologies Used

* Python 3
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## How to Run

1. Clone the repository.

```bash
git clone <your-github-repository-link>
```

2. Navigate to the project folder.

```bash
cd <repository-name>
```

3. Install the required libraries.

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

4. Launch Jupyter Notebook.

```bash
jupyter notebook
```

5. Open:

```
Ass2_ML_Falastine.ipynb
```

6. Run all cells from top to bottom.

---

## Results

The notebook compares multiple machine learning models for regression and classification and performs customer segmentation using K-Means clustering. Performance is evaluated using standard machine learning metrics and visualizations.

##
