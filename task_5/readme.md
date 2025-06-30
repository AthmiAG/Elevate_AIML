Task 5 – Decision Trees and Random Forests

Objective  
Learn tree-based models for classification and regression using Decision Tree and Random Forest algorithms.

Tools Used  
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

Steps Performed  

1. Train a Decision Tree Classifier and Visualize the Tree  
   - Used DecisionTreeClassifier from scikit-learn.  
   - Plotted the tree structure using plot_tree with feature names and class names.  
   - Displayed node labels with colors to enhance understanding.

2. Analyze Overfitting and Control Tree Depth  
   - Trained decision trees with increasing max_depth values.  
   - Plotted accuracy scores vs tree depth to observe overfitting behavior.  

3. Train a Random Forest and Compare Accuracy  
   - Used RandomForestClassifier with multiple estimators.  
   - Compared test accuracy of random forest to single decision tree.  
   - Visualized accuracy comparison using a bar chart.

4. Interpret Feature Importances  
   - Retrieved feature importance scores from the trained random forest.  
   - Plotted feature importances in descending order.  
   - Highlighted which features most influenced model decisions.

5. Evaluate Using Cross-Validation  
   - Used cross_val_score to evaluate both decision tree and random forest models.  
   - Printed mean accuracy and standard deviation from 5-fold CV.

Key Insights  
- Decision Trees can easily overfit, especially with deep trees.  
- Random Forests reduce overfitting and increase stability and accuracy.  
- Feature importance scores help explain model behavior.  
- Cross-validation gives a more reliable picture of model performance.

Outputs  
- Tree plot of decision tree structure  
- Accuracy vs depth line chart  
- Feature importance bar chart  
- Confusion matrix and accuracy comparison  
- Cross-validation scores

Conclusion  
This task successfully demonstrated the use of Decision Trees and Random Forests for classification tasks. Visual and statistical evaluations were used to understand model performance, overfitting control, and feature influence.
