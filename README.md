# Task 5: Decision Trees and Random Forests  

## Objective  
Explore tree-based models for classification using **Decision Tree** and **Random Forest**, evaluate their performance, and analyze feature importance.  

---

## Steps Implemented  
1. **Dataset Loading**  
   - Loaded the **Heart Disease dataset** (`heart.csv`).  
   - Split into features (X) and target (y).  

2. **Train-Test Split**  
   - 80% training, 20% testing.  

3. **Decision Tree Classifier**  
   - Trained a Decision Tree with `max_depth=3`.  
   - Visualized the tree using `plot_tree`.  
   - Evaluated accuracy on the test set.  

4. **Random Forest Classifier**  
   - Trained a Random Forest with 100 estimators.  
   - Compared accuracy with Decision Tree.  
   - Observed better generalization.  

5. **Cross-Validation**  
   - Applied 5-fold cross-validation on Random Forest.  
   - Reported mean CV accuracy.  

6. **Feature Importance**  
   - Extracted feature importances from Random Forest.  
   - Plotted top contributing features (thalach, ca, oldpeak, thal, cp).  

---

## Key Results  
- **Decision Tree Accuracy:** ~0.80  
- **Random Forest Accuracy:** ~0.88  
- **Cross-Validation Accuracy:** ~0.82 (mean)  
- Important features: **thalach, ca, oldpeak, thal, cp**  

---

## Learnings  
- Decision Trees are easy to interpret but prone to overfitting.  
- Random Forests reduce overfitting using bagging and multiple trees.  
- Feature importance helps identify key factors in predictions.  
