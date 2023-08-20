# Supervised classification - Iris Flower Dataset

## Iris Flower Dataset:

The Iris Flower Dataset holds a pivotal role in the realm of machine learning. It revolves around three distinct iris flower species: Setosa, Versicolor, and Virginica. Each entry comprises four essential attributes – sepal length, sepal width, petal length, and petal width – meticulously measured from these flowers. The dataset presents a classic classification challenge: utilizing these attributes to accurately categorize iris flowers into their respective species. This dataset serves as an essential starting point for both budding data enthusiasts and machine learning practitioners, offering valuable insights into pattern recognition and classification methodologies.

## Objective:
The project centers around practical application of diverse classification algorithms on Iris Flower dataset, utilizing the sklearn.datasets library. This dataset consists of 150 samples, each featuring significant attributes like Sepal Length, Sepal Width, Petal Length, and Petal Width. These attributes play a pivotal role in categorizing the flowers into three distinct classes: Setosa, Versicolour, and Virginica.

Steps involved in the Iris Flower classification Task are:

- Analyzing dataset characteristics, including shape, details, and potential missing values.
- Employing Cross-Validation Grid Search (GridSearchCV) to optimize hyperparameters for various classification models, thus refining the model's performance.
- Assessing the accuracy of different classification models, namely Logistic Regression, Decision Tree, Random Forest, Support Vector Machine (SVM), Naive Bayes, and 
  K-Nearest Neighbors (KNN).
  
Grid Search cross validation implies:
- 'SVM,' 'Random Forest', 'Logistic Regression,' and 'KNN' models demonstrate a slightly superior accuracy of around 96%.
- 'Naive Bayes,' and 'Decision Tree' models achieve an accuracy level of approximately 94%.

Based on the findings, the Logistic Regression model was chosen to predict outcomes on the test dataset. 
