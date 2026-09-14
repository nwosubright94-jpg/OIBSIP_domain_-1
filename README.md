# Iris Flower Classification

## Objective
The main goal of this project is to build a machine learning model that can accurately identify and classify iris flower species (setosa, versicolor, and virginica) based on four physical characteristics: sepal length, sepal width, petal length, and petal width.

## Tools Used
 Python (Programming language)
  Jupyter Notebook (Development environment)
  Pandas (Data manipulation and cleaning)
  Seaborn & Matplotlib (Data visualization)
   Scikit-Learn (Machine learning algorithms and evaluation metrics)

## Steps Performed
1. Data Loading: Loaded the built-in Iris dataset using sklearn.datasets.load_iris and converted it into a Pandas DataFrame.
2. Exploratory Data Analysis (EDA): Analyzed feature distributions, species counts, and correlations using scatter plots and pair plots to understand feature relationships.
3. Data Preprocessing: Checked for missing values and prepared the target labels by mapping species class numbers to their names.
4. Model Training & Evaluation: Split the dataset into 80% training and 20% testing sets. Trained and evaluated two classification algorithms:
    Logistic Regression
    Random Forest Classifier
5. Model Comparison: Evaluated model performance on the test set using Accuracy Score, Confusion Matrix, and Classification Report.

## Key Outcomes & Results
Logistic Regression: Achieved an accuracy of 96.67% (29 out of 30 test samples correctly classified, misclassifying only one versicolor as virginica).
Random Forest Classifier: Achieved an accuracy of 90.00% (27 out of 30 test samples correctly classified, misclassifying three samples).
Conclusion: Logistic Regression outperformed Random Forest on this dataset. Because the Iris dataset is small and features like petal length and width are linearly separable, Logistic Regression provided a stronger fit without overfitting.
