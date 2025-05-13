# 09_Customer-Support-Case-Type-Classification
Support Cases Classification Classify customer support cases (Billing, General, Technical) using a Random Forest classifier with message length and response time.  Steps: Load and explore the dataset.  Train and evaluate the model.  Libraries Used: Pandas, Numpy, Matplotlib, Seaborn, scikit-learn
# Support Cases Classification

This project classifies customer support cases into three categories: Billing, General, and Technical, using a Random Forest classifier based on features like message length and response time.

## Steps

1. **Data Loading & Exploration**  
   The dataset `support_cases.csv` is loaded and explored to understand its structure and check for missing values.

2. **Data Visualization**  
   Visualizations are created to explore the distribution of case types and relationships between message length and response time.

3. **Data Preparation**  
   - The target variable `case_type` is encoded.
   - Features are scaled for normalization.

4. **Model Training & Evaluation**  
   A Random Forest classifier is trained and evaluated using classification metrics like accuracy and confusion matrix.

5. **Feature Importance**  
   The importance of features in the classification task is displayed.

## Libraries Used

- Pandas
- Numpy
- Matplotlib
- Seaborn
- scikit-learn
- mlxtend

## How to Run

1. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn mlxtend
