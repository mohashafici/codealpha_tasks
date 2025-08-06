# 🌸 Iris Flower Classification - Machine Learning Project

## 📌 Project Overview

This project is a machine learning classification task that predicts the species of Iris flowers based on their physical measurements. It uses a clean and widely known dataset — the **Iris dataset**, which contains 150 flower samples from three species:
- **Iris-setosa**
- **Iris-versicolor**
- **Iris-virginica**

Each sample includes four features:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

---

## 🎯 Objectives

- Understand the basic concepts of classification in machine learning.
- Load and explore the Iris dataset using Python and Pandas.
- Visualize the data to find patterns and relationships.
- Train a machine learning model to classify the Iris species.
- Evaluate the model using test data to measure its accuracy and performance.

---

## 🛠️ Tools and Libraries Used

- **Python 3.8+**
- **Pandas** — for data manipulation
- **NumPy** — for numerical operations
- **Matplotlib & Seaborn** — for data visualization
- **Scikit-learn** — for model building, training, and evaluation

---

## 📊 Exploratory Data Analysis (EDA)

- Checked for missing values (none found).
- Used `pairplot` to visualize the relationships between features and species.
- Plotted a heatmap to understand feature correlation.
- Found strong correlation between petal length and petal width — useful for classification.

---

## 🧠 Model Training

- Features and labels were separated.
- Label encoding was applied to convert species names to numeric classes.
- Dataset was split into training (80%) and testing (20%) sets.
- Trained using **Random Forest Classifier** from Scikit-learn.

---

## ✅ Model Evaluation

- The model achieved **100% accuracy** on the test data.
- Classification report showed perfect precision, recall, and F1-score for all three species.
- Confusion matrix confirmed all predictions were correct.

---

## 🗂️ Dataset

- File Name: `Iris.csv`
- Source: [https://www.kaggle.com/datasets/saurabh00007/iriscsv?resource=download) (or similar dataset)
- Columns:
  - `SepalLengthCm`
  - `SepalWidthCm`
  - `PetalLengthCm`
  - `PetalWidthCm`
  - `Species`

---

## 📁 Project Structure

├── Iris.csv # Dataset file
├── Untitled14.ipynb # Jupyter Notebook with all code and analysis
├── README.md # Project documentation (you are reading this!)

yaml
Copy
Edit

---

## 🚀 How to Run the Project

1. Clone this repository:
git clone https://github.com/mohashafici/codealpha_tasks.git

sql
Copy
Edit
2. Navigate into the project directory and open the notebook:
cd iris-flower-classification
jupyter notebook Untitled14.ipynb

yaml
Copy
Edit
3. Run the cells step by step to see the full analysis and model output.

---

## 📌 Learnings & Concepts Applied

- Supervised learning & classification
- Train/test data splitting
- Label encoding
- Random Forest algorithm
- Performance metrics: accuracy, precision, recall, F1-score
- Data visualization & feature correlation analysis

---

## ✨ Future Improvements (Optional)

- Try different models (e.g., SVM, KNN, Logistic Regression)
- Use cross-validation for better evaluation
- Save the trained model using `joblib` or `pickle`
- Build a simple web app using `Streamlit` or `Flask` to deploy the model

---

## 📬 Contact

If you have any questions or suggestions, feel free to contact me:

**Name:** Moha shafici 
**Email:** [mohashafici44@gmail.com]  
**GitHub:** [github.com/mohashafici](https://github.com/mohashafici)

---

## 📌 License

This project is available under the [MIT License](LICENSE).
