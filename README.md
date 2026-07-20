# 🚢 Titanic Survival Prediction

Welcome to my Machine Learning project! 👋

This project is part of the **Neurofive ML Track**, where I learned how to use Machine Learning to predict whether a passenger on the Titanic survived or not.

---

## 📌 Project Goal

The goal of this project is to build a Machine Learning model that can predict passenger survival based on information such as:

* 👤 Gender
* 🎂 Age
* 🎟️ Passenger Class
* 💰 Ticket Fare
* 👨‍👩‍👧 Family Information
* 🚢 Boarding Port

---

## 🛠️ What I Did

* 📂 Loaded the Titanic dataset
* 🧹 Cleaned missing values
* 🔄 Converted text data into numbers
* ✂️ Split the data into training and testing sets
* 🤖 Trained a Logistic Regression model
* 📊 Evaluated the model using Accuracy Score
* 📋 Analyzed the results with a Confusion Matrix

---

## 📈 Model Performance

| Model | Accuracy |
|--------|----------|
| Original Logistic Regression | 78.06% |
| Tuned Logistic Regression | 81.29% |

### Hyperparameter Tuning

I used **GridSearchCV** to find the best values for:

- C
- Solver

This slightly improved the model performance and helped find better model settings automatically.

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📚 Technologies Used

* 🐍 Python
* 🐼 Pandas
* 🔢 NumPy
* 🤖 Scikit-learn
* 📊 Matplotlib
* 🎨 Seaborn
* 📓 Google Notebook

---

## 📁 Project Files

* 📘 `titanic.ipynb` — Complete notebook
* 📄 `README.md` — Project overview
* 📦 `requirements.txt` — Required Python libraries

---
## Histogram
![image alt](https://github.com/Sankesh12/neurofive-ml-track/blob/main/histogram.png)

## Bar Chart
![image alt](https://github.com/Sankesh12/neurofive-ml-track/blob/main/bar_chart.png)

## Performance: Before vs After Tuning
![image alt](https://github.com/Sankesh12/neurofive-ml-track/blob/main/accuracy.png)

---

## 🎯 What I Learned

Through this project, I learned how to:

* Explore and clean real-world data
* Prepare data for Machine Learning
* Evaluate model performance
* Understand the importance of data preprocessing

---

## 🚀 Future Improvements

* Try other Machine Learning algorithms
* Improve model accuracy with feature engineering
* Deploy the model as a simple web application on streamlit

---

## 👨‍💻 Author

**Sankesh Lal**

⭐ If you found this project interesting, feel free to explore the repository and share your feedback!
