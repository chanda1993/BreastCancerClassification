# Breast Cancer Classification Project With Supervised Machine Learning Classification

![imageblack](https://github.com/chanda1993/BreastCancerClassification/assets/46183754/acc145a2-79e2-4405-b08a-c3a6f2c96b14)


The Breast Cancer Classification Project is aimed at developing a supervised machine learning model to classify breast cancer tumors as either benign or malignant based on various features. The project involves the following steps:

1. Dataset acquisition: Obtain a dataset that contains information about breast cancer tumors, such as tumor size, shape, texture, and other relevant attributes. The dataset should also include the corresponding labels indicating whether each tumor is benign or malignant.

2. Data preprocessing: Perform necessary preprocessing steps on the dataset, including handling missing values, dealing with outliers, and encoding categorical variables if any.

3. Feature selection/extraction: Analyze the dataset to identify the most relevant features for classification. Select or extract the features that provide the most discriminatory power in distinguishing between benign and malignant tumors.

4. Splitting the dataset: Divide the dataset into training and testing sets. The training set will be used to train the machine learning model, while the testing set will be used to evaluate its performance.

5. Model selection: Choose an appropriate supervised machine learning algorithm for classification, such as logistic regression, support vector machines (SVM), random forests, or gradient boosting.

6. Model training: Train the selected model using the training dataset. Adjust hyperparameters if necessary to optimize the model's performance.

7. Model evaluation: Evaluate the trained model's performance on the testing dataset. Calculate metrics such as accuracy, precision, recall, and F1 score to assess the model's effectiveness in classifying benign and malignant tumors.

8. Model optimization: Fine-tune the model by trying different approaches, such as adjusting hyperparameters, using different feature sets, or employing ensemble methods, to improve its performance.

9. Final model deployment: Once satisfied with the model's performance, deploy it to classify new, unseen breast cancer tumors in real-world scenarios.

The primary goal of this project is to develop a reliable and accurate classification model that can aid in diagnosing breast cancer tumors and assist medical professionals in making informed decisions about patient care.

Dataset Attribute Information:

1) ID number
2) Diagnosis (M = malignant, B = benign)
3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)
b) texture (standard deviation of gray-scale values)
c) perimeter
d) area
e) smoothness (local variation in radius lengths)
f) compactness (perimeter^2 / area - 1.0)
g) concavity (severity of concave portions of the contour)
h) concave points (number of concave portions of the contour)
i) symmetry
j) fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three
largest values) of these features were computed for each image,
resulting in 30 features. For instance, field 3 is Mean Radius, field
13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant
