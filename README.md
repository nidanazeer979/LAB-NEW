# Model Evaluation Metrics - Updated Lecture Package

## Files Included
- Model_Evaluation_Lecture_Updated.docx
- Model_Evaluation_Lab_Updated.ipynb

## How to Run in Google Colab
1. Open Google Colab
2. Click Upload Notebook
3. Upload Model_Evaluation_Lab_Updated.ipynb
4. Run the cells from top to bottom

## Recommended Repo Name
week5-model-evaluation-ml

---

## 📘 Lab Coverage
This lab includes:
- step-by-step cells
- comments in code
- model comparison
- confusion matrix
- ROC curve
- easy tasks
- practice code

---

## 🧪 Student Practice Tasks (Important)

After completing the lab, students must perform the following tasks:

### 🔹 Task 1: KNN Experiment
- Change `n_neighbors` value:
  - Try K = 3, 7, 9
- Observe:
  - Accuracy
  - F1 Score
- Write your observation:
  > Which value of K gives better performance?

---

### 🔹 Task 2: Random Forest Tuning
- Change number of trees:
  - `n_estimators = 50`
  - `n_estimators = 300`
- Compare results with default (200)
- Write your observation:
  > Does increasing trees always improve performance?

---

### 🔹 Task 3: Metric Understanding
Answer the following:

1. Why is **accuracy not reliable** for imbalanced datasets?
2. When should we prefer **recall over precision**?
3. Give one real-life example where **precision is more important**.

---

### 🔹 Task 4: Model Comparison
- Compare all models:
  - Logistic Regression
  - KNN
  - Random Forest
- Decide:
  > Which model is best and why?

(Hint: Don't only look at accuracy — consider F1-score and ROC-AUC)

---

### 🔹 Task 5: Real-Life Thinking (Very Important)
Choose one scenario and explain:

- Spam Detection → Which metric?
- Disease Prediction → Which metric?
- Fraud Detection → Which metric?

Explain your answer clearly.

---

### 🔹 Task 6: Bonus Challenge 🚀
- Create your own model using:
  - Logistic Regression OR KNN
- Change parameters
- Evaluate using all metrics
- Compare with previous results

---

## 🎯 Learning Outcome

After completing this lab, students will be able to:
- evaluate machine learning models properly
- understand difference between metrics
- choose correct metric based on problem
- compare multiple models
- think like a Data Scientist

---

## 👨‍🏫 Instructor Note

Encourage students to:
- not rely only on accuracy
- explain their answers in words
- relate metrics to real-world problems