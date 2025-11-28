# 🧠 Purchase Prediction using Gaussian Naive Bayes

This project uses **Gaussian Naive Bayes Classifier** to predict whether a person will purchase a product based on **Age** and **Estimated Salary**.

---

## 📌 **Objective**
To classify purchase behavior using only two features:
- `Age`
- `EstimatedSalary`

The target variable is:
- `Purchased` (0 = No, 1 = Yes)

---

## 🛠️ **Tech Stack**
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🔄 **Workflow**
✔ Load and preprocess dataset  
✔ Feature selection  
✔ Train-test split  
✔ Gaussian Naive Bayes classifier  
✔ Find **best random_state** for highest accuracy  
✔ Generate **confusion matrix** & **classification report**  
✔ Visualize results  

---

## 📊 **Random State Optimization**
To improve accuracy, random_state was tested from 0 to 200.  
BEST ACCURACY : 0.92
BEST RANDOM STATE : 200

📄 Dataset
Filename: purchase_logistic.csv
Make sure the file is placed in the project directory.

🚀 How to Run
pip install pandas numpy scikit-learn matplotlib seaborn
python naive_bayes_purchase.py

📎 Output
✔ Maximum Accuracy
✔ Best Random State
✔ Confusion Matrix Plot
✔ Classification Report

🤝 Contributions
Pull requests and suggestions are welcome!

📬 Contact
Author: Manmeet Kaur
Let’s connect on LinkedIn[https://www.linkedin.com/in/manmeet-kaur-245a372ba/]

