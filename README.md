# Breast_cancer-prediction
🩺 Breast Cancer Prediction
This project focuses on building predictive models to classify breast cancer tumors as malignant or benign using the well-known Breast Cancer Wisconsin dataset from sklearn.datasets.

📌 Dataset
The dataset is preloaded via load_breast_cancer() from scikit-learn. It includes features like mean radius, mean texture, and more, along with binary labels (0 = malignant, 1 = benign).

📊 Exploratory Data Analysis
Visualized distributions using histograms and box plots (e.g., Mean Radius, Mean Texture).

Heatmaps provided a high-level correlation view.

Checked for missing values and performed summary statistics.

🧪 Preprocessing
Split dataset into training and testing sets.

Applied Normalization and Standardization using Normalizer and StandardScaler from sklearn.

🧠 Models Used
1. Support Vector Classifier (SVC)
Kernel: 'rbf'

Trained and evaluated on:

Raw features

Standardized features

Normalized features

2. Decision Tree Classifier
Criterion: 'entropy'

Also evaluated on both standardized and normalized data.

📈 Model Performance
Accuracy scores were computed for both training and testing datasets.

SVC and Decision Tree models were both tested for robustness across different preprocessing methods.

🔍 Patient Prediction
Test cases included predictions for individual patients using preprocessed input features.

✅ Key Highlights
Clean data pipeline with no missing values.

Multiple preprocessing strategies tested.

High accuracy in predictions, especially after scaling.

Ready-to-use for model experimentation or further optimization.
