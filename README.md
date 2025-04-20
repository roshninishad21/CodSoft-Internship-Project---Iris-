🌸 Iris Flower Classification

This project is part of my CodSoft Data Science Internship, where I built a machine learning model to classify iris flowers into three species using Logistic Regression and Random Forest Classifier.

📌 Objective

To classify iris flowers into the correct species — Setosa, Versicolor, or Virginica — based on their sepal and petal measurements.

📁 Dataset

Source: UCI Machine Learning Repository – Iris Dataset

The dataset contains 150 samples with the following features:

SepalLengthCm

SepalWidthCm

PetalLengthCm

PetalWidthCm

Species (Target variable)

⚙️ Workflow

. Exploratory Data Analysis (EDA)

. Visualized the distribution of features

. Explored feature relationships using pair plots and correlation heatmaps

. Data Preprocessing

. Checked for missing values (none in this dataset)

. Label encoding for the target variable

. Model Building

Logistic Regression: 

Simple linear classifier

Random Forest Classifier: 

Ensemble learning method

Model Evaluation

Train-test split (typically 80-20)

Evaluated using:

Accuracy Score

Confusion Matrix

Classification Report

🧪 Results

Model	Accuracy
Logistic Regression	~96%
Random Forest	~98%
Both models performed well, with Random Forest achieving slightly better accuracy due to its ability to capture complex patterns.

🧰 Technologies & Libraries

. Python

. Pandas, NumPy – Data handling

. Matplotlib, Seaborn – Visualizations

. Scikit-learn (sklearn) – ML models and evaluation tools

🧠 Key Learnings

. Basics of multiclass classification

. Comparison between linear and ensemble models

. Importance of feature visualization for understanding data patterns

. Practical experience with model evaluation techniques

📌 Conclusion

The Iris Flower Classification project is a classic beginner-friendly machine learning task that demonstrates how different algorithms can be used to achieve high accuracy on clean, well-structured data. It served as a great way to practice model comparison and understand the core concepts of classification.
