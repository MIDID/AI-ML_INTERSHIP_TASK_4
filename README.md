# 🚀 Task 4: Binary Classification with Logistic Regression

This project is part of the AI & ML Internship and involves building a binary classifier using **Logistic Regression** with a provided dataset (`data.csv`).

---

## 🧠 Objective

To understand and implement logistic regression for binary classification. This includes:
- Training and testing a model.
- Evaluating performance with metrics.
- Understanding threshold tuning and sigmoid behavior.

---

## 📂 Dataset

The dataset used is `data.csv`, which contains features for classification and a binary target label.

**Assumptions:**
- The last column in the dataset is the target variable.
- No missing or non-numeric values are present after cleaning.

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 📈 Model Pipeline

1. **Data Loading** using `pandas`.
2. **Missing Value Handling** (`dropna()`).
3. **Feature-Target Split** (`X`, `y`).
4. **Train-Test Split** using `train_test_split()`.
5. **Standardization** with `StandardScaler`.
6. **Model Training** using `LogisticRegression`.
7. **Model Evaluation** with:
   - Confusion Matrix
   - Classification Report
   - Precision and Recall
   - ROC-AUC Curve
8. **Threshold Tuning**
9. **Sigmoid Function Plot**

---

## 📊 Outputs & Results

- ✅ Confusion matrix heatmap
- ✅ Classification report with accuracy, precision, recall, F1-score
- ✅ ROC Curve with AUC score
- ✅ Custom threshold confusion matrix
- ✅ Sigmoid function graph

---

## 🧪 Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **ROC-AUC**

---

## 📎 How to Run

1. Open the [Google Colab Notebook](https://colab.research.google.com).
2. Upload `data.csv` when prompted.
3. Run all cells to execute the complete classification pipeline.

---

## 📌 Interview Questions Covered

- What is logistic regression and how does it differ from linear regression?
- What is a sigmoid function?
- What are precision and recall?
- What is the ROC-AUC curve?
- What is a confusion matrix?
- How to handle class imbalance?
- How to choose a threshold?
- Can logistic regression be used for multi-class problems?

---

## 📎 Submission

Submitted as part of the internship task via [submission link](https://forms.gle/8Gm83s53KbyXs3Ne9).

---

## 📧 Contact

For queries or clarifications, please contact via GitHub or the internship coordinator.
