## Consumer Data Classification with SVM and Logistic Regression

This repository features a comprehensive analysis of customer segmentation using two popular machine learning models: Support Vector Machines (SVM) and Logistic Regression. The analysis is performed on a dataset, `CustomersData.csv`, which includes attributes such as age, spending score, and segmentation labels.

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
- Detailed accuracy metrics and classification reports for both models.
- Visualizations of decision boundaries and performance metrics.

Feel free to explore the notebooks for in-depth analysis and adapt the code for different datasets or model configurations. For questions or contributions, please open an issue or submit a pull request!


*Usage**: Ensure `CustomersData.csv` is in the working directory and execute the notebooks to view the results.
