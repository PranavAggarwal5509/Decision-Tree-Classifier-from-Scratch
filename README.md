Decision Tree Classifier from Scratch

This project implements a Decision Tree Classifier from scratch in Python using only NumPy and core libraries. It demonstrates how decision trees work internally, without relying on scikit-learn’s implementation. The model is tested on multiple real-world datasets and custom CSV inputs.

🚀 Features

Custom Algorithm: Implemented entropy, information gain, and recursive tree construction.

Stopping Criteria: Supports max_depth and min_samples_split to control overfitting.

Dataset Compatibility: Works on built-in scikit-learn datasets (Iris, Breast Cancer, Wine, Digits, Diabetes, Forest Cover, KDDCup99) and synthetic datasets.

CSV Support: Can be tested on custom datasets with CSV files.

Evaluation: Reports accuracy, dataset details, and sample predictions.

📂 Project Structure
├── decision_tree.py   # Core implementation of DecisionTreeClassifier
├── datasets_test.py   # Functions to test on built-in datasets
├── custom_csv_test.py # Function to test on custom CSV file
├── README.md          # Project documentation

⚙️ How It Works

Entropy Calculation: Measures dataset impurity.

Information Gain: Finds the best split based on entropy reduction.

Tree Construction: Recursively splits data into left and right child nodes.

Prediction: Traverses the tree until a leaf node (class label) is reached.

📊 Datasets Used

Iris

Breast Cancer

Wine

Digits

Diabetes (converted to classification)

Forest Cover (subset of 10,000 samples)

KDDCup99 (simplified to binary classification)

Synthetic classification dataset

📈 Sample Output
==================================================
Testing on iris dataset

Training Decision Tree (max_depth=3)...

Results:
- Accuracy: 0.9333
- Tree depth used: 3
- Dataset shape: (150, 4)
- Features: 4
- Classes: 3

Sample predictions (True -> Predicted):
0 -> 0
1 -> 1
2 -> 2

🔮 Future Improvements

Add support for Gini Index as a split criterion.

Implement pruning methods to reduce overfitting.

Extend to handle regression tasks.

Visualize decision tree structure.

✨ Key Learnings

Gained deeper understanding of how decision trees split data.

Learned about entropy, information gain, and recursive algorithms.

Practiced handling diverse datasets and preprocessing steps.
