Task 4 – Classification with Logistic Regression

Objective
Build a binary classifier using logistic regression on the Breast Cancer Wisconsin dataset. Evaluate its performance and explore threshold tuning and the sigmoid function.

Tools Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Dataset Used
Breast Cancer Wisconsin Dataset (built-in from sklearn.datasets)

Target classes: 0 = malignant, 1 = benign

Number of features: 30

No missing values

Steps Performed

Data Loading

Loaded Breast Cancer dataset using load_breast_cancer() from scikit-learn.

Converted to DataFrame for easier exploration.

Preprocessing

Split the dataset using train_test_split() (80/20 ratio).

Standardized features using StandardScaler.

Model Training

Trained a logistic regression model using LogisticRegression(max_iter=1000).

Used scaled data for better convergence.

Evaluation

Generated a classification report (precision, recall, f1-score).

Plotted a confusion matrix using Seaborn.

Calculated and plotted the ROC Curve and ROC-AUC score.

Threshold Tuning and Sigmoid Explanation

Plotted Precision and Recall vs Threshold to analyze threshold impact.

Visualized the Sigmoid function to explain how logistic regression predicts probabilities.

Key Insights

Logistic Regression achieved high performance on the breast cancer dataset.

The ROC-AUC score confirmed good separability between classes.

Precision and recall trade-off can be adjusted using threshold tuning.

The sigmoid function helps explain the model's probabilistic decision-making.

Outputs

Classification report (printed to console)

Confusion matrix heatmap (Seaborn)

ROC Curve and AUC Score

Precision/Recall vs Threshold plot

Sigmoid function visualization

Conclusion
This task successfully demonstrated how to implement and evaluate a logistic regression classifier. The code also included visual and statistical techniques for understanding model confidence and decision boundaries.