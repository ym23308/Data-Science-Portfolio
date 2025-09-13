# 📚 Student Exam Score Prediction

## 🎯 Objective
The goal of this project is to build a simple **Linear Regression model** that can predict a student's **math score** based on their **reading and writing scores**.  
By doing this, I practiced:
- Data loading and exploration
- Feature selection (choosing which columns to use)
- Model training and testing
- Evaluating model performance with R² score
- Visualizing results with scatter plots

---

## 📊 Dataset
- **Source:** [Students Performance in Exams (Kaggle)](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **Columns Used:** 
  - `reading score`
  - `writing score`
  - `math score` (target)

---

## 🛠️ Tools & Libraries
- **Python **
- **Pandas & NumPy** – Data handling
- **Matplotlib & Seaborn** – Visualization
- **Scikit-learn** – Model training & evaluation

---

## 🔧 Process
1. Loaded dataset using **KaggleHub**
2. Checked dataset shape & missing values
3. Selected features → `reading score`, `writing score`
4. Split data into **training (80%)** and **testing (20%)**
5. Trained a **Linear Regression** model
6. Predicted math scores on test data
7. Calculated **R² Score**
8. Created a **scatter plot** to visualize predictions vs actual results

---

## 📈 Model Performance
- **R² Score:** `0.68` 
- ✅ Indicates that the model explains ~68% of the variation in math scores

---

## 🖼️ Visualization
<img width="531" height="392" alt="Screenshot 2025-09-13 at 7 18 45 PM" src="https://github.com/user-attachments/assets/1e517c6b-b69d-4db1-91b6-cf8698126152" />

---

## 💡 Key Insights
- Students with higher reading & writing scores tend to also have higher math scores
- Linear Regression provides a good first approach for predicting math performance

---

## 🔗 Notebook
[
](https://colab.research.google.com/drive/1_MC3bPJKrinHdmf_T_xyj5iA4mqcVNpo?usp=sharing)
---

