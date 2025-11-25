### Bank-Credit-Card-Risk
Aim of the Project
The aim of this project is to develop a reliable data analytics strategy to assist a bank in making informed loan approval decisions. By leveraging machine learning techniques, specifically Decision Tree and Naive Bayes classifiers, the project aims to predict the credit risk of potential customers based on historical data. This predictive modeling will help the bank minimize the risk of default by accurately identifying customers with good and bad credit risks. Another words, this dataset addresses the challenge of a bank in deciding on loan approval to customers. A bank needs to make the right decision in determining who should get the approval and who should not.

Summary of Dataset
The dataset used in this project is the German Credit Data dataset, which consists of 1000 entries and 21 attributes. The attributes include various financial and personal characteristics of customers, such as account balance, credit amount, duration of credit, payment status of previous credit, purpose of the loan, and more. The class attribute, 'Creditability', is a binary variable indicating whether the customer's credit rating is good (1) or bad (0). The dataset provides a comprehensive set of features that can be utilized to build effective predictive models for credit risk assessment.

Tools and Machine Learning Methods in Python:
To achieve the aim of this project, the following tools and machine learning methods were employed using Python:

Pandas: Used for data manipulation and analysis. It provides data structures like DataFrames to handle tabular data effectively.
NumPy: Utilized for numerical operations and array manipulations, which are fundamental for data preprocessing.
Scikit-learn: A machine learning library in Python that offers various tools for data mining and data analysis. The specific methods used include:
DecisionTreeClassifier: For building and training the Decision Tree model.
GaussianNB: For building and training the Naive Bayes model.
Train_test_split: To split the dataset into training and test sets.
StandardScaler: To standardize the features by removing the mean and scaling to unit variance.
Accuracy_score, classification_report, confusion_matrix: For evaluating the performance of the models.
Roc_curve, auc: For computing and plotting the Receiver Operating Characteristic (ROC) curve and the Area Under the Curve (AUC) metric.
Matplotlib and Seaborn: Libraries for creating visualizations to better
understand the data distributions, model performance metrics, and comparison of results.

These tools and methods collectively enable the development, training, evaluation, and visualization of the predictive models, thereby facilitating a comprehensive analysis of the credit risk prediction problem.
