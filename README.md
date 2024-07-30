# Iris-Flower-classification

Phases of the project:
1)Hypothesis generation & understand the problem
2)load the dataset
3)quick dataset summary
4)explore data with visualisation
5)data modelling
6)Results

Problem statement : The aim of this project is to predict the class of the flower based on available attributes.

Business Context:

Background Information
The Iris flower classification project focuses on identifying different species of Iris flowers based on their physical characteristics. The Iris dataset, a classic dataset in machine learning and statistics, includes measurements of various features such as sepal length, sepal width, petal length, and petal width. The three species of Iris flowers in the dataset are Iris-setosa, Iris-versicolor, and Iris-virginica.

Industry Relevance
Botanical Research and Horticulture:
In the field of botany and horticulture, accurate classification of plant species is essential for research, conservation, and cultivation purposes. Identifying and categorizing plant species helps researchers understand biodiversity, track plant health, and study ecological relationships.

Agriculture and Floriculture:
For agricultural and floricultural businesses, such as nurseries and garden centers, knowing the specific species of plants is crucial for effective breeding, pest management, and customer service. Accurate classification of Iris flowers can help these businesses provide better recommendations to customers, ensure proper plant care, and optimize inventory management.

Educational and Research Institutions:
Educational institutions and research organizations use datasets like the Iris dataset to teach and learn about machine learning algorithms and statistical analysis. By solving classification problems with well-known datasets, students and researchers can gain insights into model performance and data handling techniques.

Business Value
Enhanced Decision-Making:
In a commercial setting, accurate classification of plant species can lead to better decision-making regarding plant care and cultivation. For example, understanding the specific needs and characteristics of different Iris species allows businesses to tailor their horticultural practices, improve plant health, and increase yield.


Language: Python
Modules: Numpy, seaborn,matplotlib,pandas

Algorithm utilized:
Liner Models:
Logistic Regression
Linear Discriminant Analysis(LDA)

Non-Linear models:
Decision Tree Classifier
KNN-Knearest neighbour
SVC-Support Vector Classifier
GaussianNB


Results:
----------
Testing KNN
Accuracy: 0.9
Confusion_matrix: [[ 7  0  0]
 [ 0 11  1]
 [ 0  2  9]]
classification_report:                  precision    recall  f1-score   support

    Iris-setosa       1.00      1.00      1.00         7
Iris-versicolor       0.85      0.92      0.88        12
 Iris-virginica       0.90      0.82      0.86        11

       accuracy                           0.90        30
      macro avg       0.92      0.91      0.91        30
   weighted avg       0.90      0.90      0.90        30

----------
Testing GNB
Accuracy: 0.8333333333333334
Confusion_matrix: [[7 0 0]
 [0 9 3]
 [0 2 9]]
classification_report:                  precision    recall  f1-score   support

    Iris-setosa       1.00      1.00      1.00         7
Iris-versicolor       0.82      0.75      0.78        12
 Iris-virginica       0.75      0.82      0.78        11

       accuracy                           0.83        30
      macro avg       0.86      0.86      0.86        30
   weighted avg       0.84      0.83      0.83        30

----------
Testing SVC
Accuracy: 0.9333333333333333
Confusion_matrix: [[ 7  0  0]
 [ 0 10  2]
 [ 0  0 11]]
classification_report:                  precision    recall  f1-score   support

    Iris-setosa       1.00      1.00      1.00         7
Iris-versicolor       1.00      0.83      0.91        12
 Iris-virginica       0.85      1.00      0.92        11

       accuracy                           0.93        30
      macro avg       0.95      0.94      0.94        30
   weighted avg       0.94      0.93      0.93        30
