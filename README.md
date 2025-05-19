# 🍄 Mushroom Classification Using Machine Learning

This project focuses on building a machine learning model to classify mushrooms as **edible** or **poisonous** based on their physical characteristics. Leveraging the **UCI Mushroom Dataset**, the project applies various classification algorithms to achieve high accuracy and reliable predictions.

---

## 📌 Project Objective

To develop a predictive model that classifies mushrooms using features such as:

- Cap shape & surface
- Cap color
- Gill attachment & spacing
- Stalk shape & size
- Odor
- Habitat
- Spore print color

By applying multiple classification algorithms, the model learns to distinguish between edible and poisonous mushrooms effectively.

---

## ⚙️ Machine Learning Models and Accuracy

| Model                         | Accuracy     |
|------------------------------|--------------|
| Logistic Regression          | 64%          |
| Support Vector Machine (SVM) | 91%          |
| K-Nearest Neighbors (KNN)    | 99% ✅        |
| Naive Bayes Classifier       | 64%          |
| Decision Tree                | 98% ✅        |
| Random Forest                | 99% ✅        |

✅ **KNN** and **Random Forest** achieved the highest accuracy.

---

## 📁 Dataset

- **Source**: UCI Machine Learning Repository
- **Data**: 8124 instances and 22 categorical attributes
- **Target**: Mushroom class – `edible` (`e`) or `poisonous` (`p`)

---

## 🧠 Technologies Used

- Python 3
- Pandas
- NumPy
- Scikit-learn (SVM, KNN, Decision Tree, Random Forest, Logistic Regression, Naive Bayes)
- Jupyter Notebook

---

## 🚨 Disclaimer

> ⚠️ **This project is for educational purposes only.**
>
> Do **not** use this model for real-world mushroom identification or consumption decisions.
> Always consult a qualified **mycologist** or expert before consuming wild mushrooms.
> Misclassification can lead to **serious health risks or death**.
