General health assessment is an important area in healthcare data analysis because health-related
information can contain patterns that may be useful for understanding an individual's overall health
condition. Machine learning provides methods for analyzing such information and building predictive
models from historical data.
This project presents a General Health Prediction System using Machine Learning based on a CVD
dataset. The dataset contains demographic, lifestyle and health-related attributes such as age category,
sex, height, weight, BMI, exercise, smoking history, alcohol consumption, fruit consumption, vegetable
consumption, diabetes, arthritis, depression and other health-related factors.
The project follows a complete machine learning workflow. The dataset is first inspected and
preprocessed. The target variable, General_Health, contains five health-status categories: Poor, Fair,
Good, Very Good and Excellent. The dataset is divided into 80% training data and 20% testing data.
Three machine learning algorithms are applied: Logistic Regression, Support Vector Machine (SVM),
and Random Forest. The trained models are evaluated on unseen test data using accuracy, classification
reports and confusion matrices. A bar chart is also used to compare model accuracies.
Randomized Grid Search is subsequently applied to tune the hyperparameters of the Random Forest
model. Finally, a single record from the test dataset is passed to the trained model to demonstrate an AIstyle
health prediction.
The project demonstrates the complete process of data preprocessing, model training, testing, evaluation,
hyperparameter tuning and prediction using machine learning.
INTRODUCTION :
Healthcare datasets contain a large amount of information related to people's demographic
characteristics, lifestyle habits and health conditions. Analyzing such data manually can be difficult when
the dataset contains a large number of records. Machine learning can be used to identify patterns in
historical data and build predictive classification models. In this project, machine learning techniques are
applied to predict the general health status of an individual using information available in the CVD dataset.
The target variable used in the project is General_Health, which contains five categories:
1. Poor
2. Fair
3. Good
4. Very Good
5. Excellent
The project uses three classification algorithms:
1. Logistic Regression
2. Support Vector Machine (SVM)
3. Random Forest
The models are trained using the training dataset and evaluated using previously unseen testing data.
The project also includes hyperparameter tuning using Randomized Grid Search and demonstrates
prediction for a single input record
