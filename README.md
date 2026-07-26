# Loan Default Prediction - README

## Overview
This project aims to predict loan default using machine learning techniques. The dataset undergoes preprocessing, feature engineering, and model training using XGBoost. The project is divided into six steps (B1 to B6), each covering a crucial aspect of data preprocessing and model training.

---

## 1. Requirements

### 1.1 Software Requirements
- Python 3.11+
- Jupyter Notebook
- Required Python libraries:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `xgboost`
  - `matplotlib`
  - `seaborn`
  - `warnings`

Install all dependencies using:
```sh
pip install -r requirements.txt
```

### 1.2 Hardware Requirements
- Minimum:
  - 8GB RAM
  - Dual-core processor (Intel i5 or AMD equivalent)
  - 10GB free disk space
- Recommended:
  - 16GB RAM
  - Quad-core processor
  - GPU (for faster computations)
  - SSD storage

---

## 2. Project Structure
```
├── B1.ipynb  # Data Cleaning
├── B2.ipynb  # Missing Values Handling
├── B3.ipynb  # Feature Engineering
├── B4.ipynb  # Categorical Encoding
├── B5.ipynb  # Model Training
├── B6.ipynb  # Hyperparameter Tuning
├── loan_default_dataset.csv  # Raw dataset
├── loan_default_preprocessed.csv  # Preprocessed dataset
├── requirements.txt  # Required Python libraries
├── README.md  # Project documentation
```

---

## 3. Instructions to Run the AI/ML Application

### 3.1 Running the Jupyter Notebooks
1. Clone the repository:
   ```sh
   git clone <repo-url>
   cd <repo-folder>
   ```
2. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Start Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
4. Open the notebooks in order (B1.ipynb → B6.ipynb) and run the cells sequentially.

---

## 4. Model Evaluation
- The model is trained using **XGBoost**.
- **Performance Metrics:**
  - Accuracy
  - Precision
  - Recall
  - F1 Score
- **Cross-Validation** is used to ensure model generalization.
- **Hyperparameter tuning** is performed using GridSearchCV.

---

## 5. Output Files
- `loan_default_preprocessed.csv`: Cleaned and preprocessed dataset.
- Evaluation metrics displayed in the final notebook.

---

## 6. Notes
- Ensure the dataset file (`Loan_default_dataset.csv`) is in the project directory.
- The execution order of notebooks is **important** to avoid missing dependencies.

---
