# Credit Loan Classification (KNN & Decision Tree)

This project applies **K-Nearest Neighbors** and **Decision Tree** classifiers to predict loan outcomes using customer financial data. It includes preprocessing, model training, evaluation, and visualization.


## Dataset

Includes customer features such as:
- Income, Credit Score, Monthly Debt
- Job History, Credit Problems, Open Accounts
- Target: `Loan_Dummy` (0 = Not Paid, 1 = Paid)

## Workflow

- **Preprocessing**: Encoding categorical variables, dropping missing values.
- **EDA**: Summary stats and visualizations (scatter plots, histograms).
- **Modeling**:
  - `KNeighborsClassifier`
  - `DecisionTreeClassifier` (with plot)
- **Evaluation**: Accuracy, confusion matrix, classification report.

## Tools

- Python, Pandas, NumPy
- Scikit-learn, Matplotlib, Seaborn

## Outcome

The models classify loan status with good accuracy. The decision tree offers easy interpretability, while KNN provides a non-parametric baseline.
