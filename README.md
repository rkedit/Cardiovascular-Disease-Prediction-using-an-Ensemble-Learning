# Cardiovascular-Disease-Prediction-using-an-Ensemble-Learning
Cardiovascular disease (CVDs) is the number one cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. training a machine learning model using Decision Tree, Random Forest and XGBoost models to assist with diagnosing this disease.

In this project, we set out to solve a problem using machine learning and neural networks. We began by gathering data and splitting it into training and testing sets. We explored various machine learning models, including Logistic Regression, Naive Bayes, SVM, K-Nearest Neighbors, Decision Trees, Random Forest, Gradient Boosting, and XGBoost. We evaluated their performance and found that Random Forest achieved the highest accuracy on our dataset.

We also delved into neural networks and implemented a simple feedforward neural network for binary classification.

Throughout the project, we emphasized the importance of data preprocessing, model selection, and evaluation using metrics like accuracy, precision, recall, F1-score, and ROC curves. These metrics helped us assess the performance of our models and make informed decisions.

Ultimately, this project serves as a practical guide for those venturing into the world of machine learning and neural networks. It highlights the importance of choosing the right model and evaluation metrics for the specific task at hand. We hope this project has been informative and helpful for your own machine learning endeavors. Thank you for joining us on this journey!


******************
Features: 


age:			age


sex:			1: male, 0: female


cp:			chest pain type, 1: typical angina, 2: atypical angina, 3: non-anginal pain, 4: asymptomatic


trestbps:			resting blood pressure


chol:			 serum cholestoral in mg/dl


fbs:			fasting blood sugar > 120 mg/dl


restecg:			resting electrocardiographic results (values 0,1,2)


thalach:			 maximum heart rate achieved


exang:			exercise induced angina


oldpeak:			oldpeak = ST depression induced by exercise relative to rest


slope:			the slope of the peak exercise ST segment


ca:			number of major vessels (0-3) colored by flourosopy


thal:			thal: 3 = normal; 6 = fixed defect; 7 = reversable defect


target:    Heart Disease	Target variable: 0 for No Heart Disease, 1 for Heart Disease

************************
Having correlations with targets:

target      1.000000

exang       0.436757

cp          0.433798

oldpeak     0.430696

thalach     0.421741

ca          0.391724

slope       0.345877

thal        0.344029

sex         0.280937

age         0.225439

trestbps    0.144931

restecg     0.137230

chol        0.085239

fbs         0.028046

*******************
Model: Logistic Regression

Cross-Validation Mean Accuracy: 0.8102891156462585

Test Accuracy: 0.8524590163934426
**********
Model: Naive Bayes

Cross-Validation Mean Accuracy: 0.8103741496598639

Test Accuracy: 0.8524590163934426
************
Model: SVM

Cross-Validation Mean Accuracy: 0.6285714285714284

Test Accuracy: 0.6885245901639344
************
Model: K-Nearest Neighbors

Cross-Validation Mean Accuracy: 0.619812925170068

Test Accuracy: 0.639344262295082
******************
Model: Decision Tree

Cross-Validation Mean Accuracy: 0.7562925170068027

Test Accuracy: 0.7868852459016393
****************
Model: Random Forest

Cross-Validation Mean Accuracy: 0.8225340136054422

Test Accuracy: 0.8688524590163934
****************
Model: Gradient Boosting

Cross-Validation Mean Accuracy: 0.8103741496598639

Test Accuracy: 0.8032786885245902
*******************
The accuracy score achieved using XGBoost is: 78.69 %
*********************************

The accuracy score achieved using neural network is: 85.00 %
********************************
Rahul Kumar, M.tech AI, NIT Silchar
