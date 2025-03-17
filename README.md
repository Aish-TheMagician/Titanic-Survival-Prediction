# README: Binary Classification Model Performance

## Project Overview
This project focuses on binary classification using multiple machine learning models. The models have been trained on a dataset to predict a binary target variable (0 or 1). The performance metrics indicate exceptionally high accuracy.

## Dataset Details
- **Total Samples**: 84
- **Class Distribution**:
  - Class 0: 50 samples
  - Class 1: 34 samples
- **Features**: Multiple numerical/categorical features (detailed in the dataset)
- **Preprocessing Steps**:
  - Missing value handling
  - Feature scaling/normalization
  - Train-test split

## Models Used & Performance Metrics
All models achieved **100% accuracy**, which suggests either:
1. A highly separable dataset with strong features.
2. Overfitting due to a small dataset.
3. Possible data leakage.

### 1. Logistic Regression
**Accuracy**: 1.0  
Confusion Matrix:
```
[[50,  0],
 [ 0, 34]]
```

### 2. Random Forest
**Accuracy**: 1.0  
Confusion Matrix:
```
[[50,  0],
 [ 0, 34]]
```

### 3. Gradient Boosting
**Accuracy**: 1.0  
Confusion Matrix:
```
[[50,  0],
 [ 0, 34]]
```

### 4. Support Vector Machine (SVM)
**Accuracy**: 1.0  
Confusion Matrix:
```
[[50,  0],
 [ 0, 34]]
```

### 5. K-Nearest Neighbors (KNN)
**Accuracy**: 1.0  
Confusion Matrix:
```
[[50,  0],
 [ 0, 34]]
```

### 6. Decision Tree
**Accuracy**: 1.0  
Confusion Matrix:
```
[[50,  0],
 [ 0, 34]]
```

## Key Observations
- **100% accuracy across all models** is highly unusual in real-world datasets.
- This could indicate **overfitting** or **data leakage**.
- The dataset might be **too small** or **too easy** for classification.

## Next Steps
- Verify that no **data leakage** has occurred (e.g., target variable influencing features).
- Increase dataset size if possible.
- Perform **cross-validation** to ensure generalization.
- Introduce **feature engineering** to check if models are relying on a dominant feature.
