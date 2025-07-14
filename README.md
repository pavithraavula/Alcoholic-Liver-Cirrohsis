## Alcoholic-Liver-Cirrohsis


This project aims to predict liver cirrhosis using machine learning algorithms. The dataset contains various features related to liver disease, and several machine learning classifiers are compared for their prediction accuracy.

## Technologies Used

- **Python 3**
- **Pandas**: For data manipulation
- **Scikit-learn**: For building and evaluating machine learning models
- **XGBoost**: For advanced gradient boosting
- **Matplotlib / Seaborn**: For visualizing results (e.g., confusion matrices)

## Dataset

- The dataset used in this project is `pavithra_embc.csv`, which includes data from the UK Biobank.
- The target variable (`K703`) represents the presence or absence of liver cirrhosis.

## Requirements

Install the required libraries using the following command:

```bash
pip install pandas scikit-learn xgboost
```

## How to Use

1. **Download the dataset**: Ensure that the `pavithra_embc.csv` dataset is available in your project directory.

2. **Run the notebook**: Execute the Jupyter notebook (`LiverCirrohsis_figures_and_code.ipynb`) to:
   - Load and preprocess the data
   - Split the data into training and testing sets
   - Standardize the features
   - Train multiple models and evaluate their performance using accuracy, AUC, classification reports, and confusion matrices

3. **Model Comparison**: The following models are trained and evaluated:
   - Logistic Regression
   - Random Forest
   - Decision Tree
   - Support Vector Machine (SVM)
   - Gradient Boosting

## Results

For each model, the notebook will display:
- **Accuracy**
- **AUC** (Area Under the ROC Curve)
- **Classification Report** (Precision, Recall, F1-Score)
- **Confusion Matrix**

## Output

The confusion matrix for each model will be displayed graphically, and a summary of model performance (accuracy, AUC, classification report) will be printed.
