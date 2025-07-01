Task 6 – K-Nearest Neighbors (KNN) Classification

Objective  
Understand and implement KNN for classification problems using Scikit-learn and visualize performance.

Tools Used  
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

Steps Performed  

1. Data Selection and Normalization  
   - Used the Iris dataset from sklearn.  
   - Standardized the feature values using StandardScaler to bring all features to the same scale.

2. Model Training  
   - Used KNeighborsClassifier from sklearn.neighbors.  
   - Trained the model with different values of K to compare performance.

3. Evaluation  
   - Evaluated model using accuracy score and confusion matrix.  
   - Plotted confusion matrix as a heatmap for visual clarity.

4. Visualization  
   - Visualized decision boundaries for KNN using only two selected features (for 2D plotting).  
   - Compared how the decision boundary changes with different K values.

Key Insights  
- KNN is a lazy learner that works based on the distance to neighbors.  
- Performance depends on the choice of K and the scale of data.  
- Small K values may lead to overfitting; large K values may oversmooth the decision boundary.  

Outputs  
- Accuracy scores for different K values  
- Confusion matrix heatmap  
- Decision boundary plots  

Conclusion  
KNN is simple and effective for classification problems when data is properly scaled. Best results depend on fine-tuning K and using distance-based evaluation.
