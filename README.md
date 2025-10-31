# Classification Algorithms

A collection of machine learning classification algorithms implemented in Python using scikit-learn.

## Algorithms Included


- **Logistic Regression**: Linear model for binary classification using the logistic function
- **K-Nearest Neighbors (K-NN)**: Instance-based learning using k=5 nearest neighbors
- **Support Vector Machine (SVM)**: Linear SVM finding optimal separating hyperplane
- **Kernel SVM**: Non-linear SVM using RBF (Radial Basis Function) kernel
- **Naive Bayes**: Probabilistic classifier based on Bayes' theorem with Gaussian distribution
- **Decision Tree**: Tree-based model using entropy criterion for splits
- **Random Forest**: Ensemble method combining 10 decision trees for robust predictions

## Dataset

All algorithms use the `Social_Network_Ads.csv` dataset for demonstration purposes.

## Installation

```bash
pip install -r requirements.txt
```

## Usage

Run any classification algorithm:

```bash
python logistic_regression.py
python decision_tree_classification.py
python k_nearest_neighbors.py
```

Each script will:
1. Load and split the dataset
2. Train the classifier
3. Display accuracy metrics
4. Visualize the decision boundaries
