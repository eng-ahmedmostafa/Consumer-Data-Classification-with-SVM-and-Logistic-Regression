## Consumer Data Classification with SVM and Logistic Regression

This repository features a comprehensive analysis of customer segmentation using Support Vector Machines (SVM) and Logistic Regression to compare their performance in classification. The analysis uses `CustomersData.csv`, covering attributes like age, spending score, and segmentation labels.

### Features:
- **Data Preprocessing**: 
  - Encoding categorical variables with `LabelEncoder`.
  - Handling missing values using `SimpleImputer`.
  - Feature scaling with `MinMaxScaler` and `StandardScaler`.
- **Feature Selection**: 
  - Using `SelectKBest` with ANOVA F-value for feature selection.
- **Modeling**:
  - **Logistic Regression**: Train and evaluate using accuracy score and confusion matrix.
  - **Support Vector Machines (SVM)**: Implement with linear, polynomial, and RBF kernels; perform hyperparameter tuning with `GridSearchCV`.
- **Visualization**:
  - Distribution plots and pair plots for exploratory data analysis.
  - Confusion matrix heatmap for model evaluation.
  - Decision boundary visualization for SVM with linear kernel.

### Results:
- Comparison of accuracy metrics and classification reports for both models.
- Visualizations of decision boundaries and performance metrics.

Explore the notebooks to see how SVM and Logistic Regression differ in classification tasks. For questions or contributions, please open an issue or submit a pull request!

---

**Usage**: Ensure `CustomersData.csv` is in the working directory and execute the notebooks to view the results.
