# Logistic Regression Binary Classifier

This project builds a binary classifier using **Logistic Regression** on the Breast Cancer Wisconsin (Diagnostic) dataset. It demonstrates core machine learning concepts like feature scaling, model evaluation, threshold tuning, and the sigmoid function.

## 🔍 Objective

- Build a logistic regression model to classify breast cancer tumors as **malignant** or **benign**.
- Evaluate model performance using multiple metrics.
- Explore the impact of threshold tuning and understand the role of the sigmoid function.

## 📁 Dataset

- **Source**: Breast Cancer Wisconsin (Diagnostic) Data Set
- **Target Variable**: `diagnosis` (`M` = Malignant, `B` = Benign)

## 🧰 Tools Used

- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn

## 🧪 Steps

1. **Load and preprocess data**
2. **Train/test split and feature scaling**
3. **Train Logistic Regression model**
4. **Evaluate performance**
   - Confusion Matrix
   - Precision & Recall
   - ROC Curve and AUC
5. **Tune decision threshold**
6. **Visualize sigmoid function**

## 📊 Evaluation Metrics

- **Precision**: Measures accuracy of positive predictions.
- **Recall**: Measures completeness of positive class.
- **ROC-AUC**: Measures ability to distinguish between classes.
- **Confusion Matrix**: Summary of prediction results.

## 📈 Threshold Tuning

Threshold tuning helps adjust the trade-off between precision and recall, especially important in imbalanced datasets or sensitive domains (e.g., healthcare).

## 📚 Interview Preparation

### What You'll Learn:
- Binary classification
- Sigmoid function
- Evaluation metrics: precision, recall, ROC-AUC
- Threshold tuning

### Common Interview Questions:
1. How does logistic regression differ from linear regression?
2. What is the sigmoid function?
3. What is precision vs recall?
4. What is the ROC-AUC curve?
5. What is the confusion matrix?
6. What happens if classes are imbalanced?
7. How do you choose the threshold?
8. Can logistic regression be used for multi-class problems?

📄 See the included `Logistic_Regression_Interview_QA` for detailed answers.

## 🚀 Run the Project

```bash
pip install pandas scikit-learn matplotlib seaborn
python Elevate_Labs_Task_4.ipy
