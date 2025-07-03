# Task 7: Support Vector Machines with Breast Cancer Dataset

## Objective
Use SVMs (Linear and RBF) for classifying breast cancer data into benign or malignant.

## Exploratory Data Analysis
- Class balance check
- Feature correlation
- Boxplots for important metrics

## Models Used
- SVM with Linear Kernel
- SVM with RBF Kernel
- Hyperparameter tuning with GridSearchCV
- Cross-validation performance evaluation

## Results
- Linear Kernel Accuracy: ~96%
- RBF Kernel Accuracy: ~98%
- Best Hyperparameters: `C=10`, `gamma=0.01`, `kernel='rbf'`

## Visuals
- Decision boundary plotted using PCA-reduced 2D data

## Files
- `Task 7 Support Vector Machines (SVM).ipynb`: Complete code
- `breast-cancer.csv`: Dataset
- `README.md`: Summary
