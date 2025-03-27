# Logistic Regression Projects

This repository contains two beginner-friendly projects demonstrating how **Logistic Regression** is used for binary and multi-class classification problems. These were implemented using Python and `scikit-learn`, and aim to provide a hands-on understanding of how logistic regression works in different contexts.

---

## 📁 Project 1: Employee Attrition Prediction (Binary Classification)

### 📌 Dataset
- **Dataset Used**: `HR_comma_sep.csv`
- **Target**: `left` – Whether an employee has left the company (1) or not (0)

### ✅ What I Did
- Loaded and explored the HR dataset
- Selected three key features: `satisfaction_level`, `average_montly_hours`, and `promotion_last_5years`
- Preprocessed the data and trained a **Logistic Regression** model
- Evaluated performance using:
  - Train/Test accuracy
  - Classification report
  - Confusion matrix
- Visualized data distribution and predictions with `matplotlib`

### 🎯 Outcome
- Successfully predicted employee attrition using logistic regression
- Gained insights into how employee satisfaction and promotions affect retention

---

## 📁 Project 2: Iris Flower Classification (Multi-class Classification)

### 📌 Dataset
- **Dataset Used**: `sklearn.datasets.load_iris()`
- **Target**: Type of Iris flower (`setosa`, `versicolor`, `virginica`)

### ✅ What I Did
- Loaded and inspected the classic Iris dataset
- Focused on two features: `sepal length` and `sepal width`
- Trained a logistic regression model for multi-class prediction
- Visualized decision boundaries for each class
- Used `matplotlib` for 2D plotting

### 🎯 Outcome
- Built a working classifier to differentiate among three flower species
- Learned how logistic regression handles multi-class problems via the "One-vs-Rest" (OvR) strategy

---

## 🛠️ Tools & Libraries
- Python 3
- `pandas`, `numpy`
- `scikit-learn`
- `matplotlib`

---

## 📌 Key Takeaways
- Logistic Regression is great for both binary and multi-class classification
- Feature selection and data visualization play a big role in performance and interpretability
- OvR strategy helps extend logistic regression for multiple classes

---

## 🚀 Next Steps
- Try adding more features to the models
- Experiment with regularization parameters (like `C`) in logistic regression
- Visualize model coefficients to interpret feature importance

---

## 🤝 Connect with Me
**Rohit Gomes**  
📧 gomesrohit92@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/rohit-gomes-12209620a)

---

> "Every small project takes you one step closer to mastering machine learning."

