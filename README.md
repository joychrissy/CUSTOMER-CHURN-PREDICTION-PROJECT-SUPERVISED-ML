# CUSTOMER-CHURN-PREDICTION-PROJECT-SUPERVISED-ML
This is a supervised machine learning project that aims at developing a robust customer churn predictive system to accurately forecast customer churn in order to  reduce customer attrition and enhance customer loyalty.
# PROCESSES
- Library Importation
- Load Dataset
- Data Exploration /Assessment
- Data Pre-processing
- Exploratory Data Analysis(EDA)
- Feature Engineering
- Machine Learning
# LIBRARY IMPORTATION
Python libraries for data analysis , visualizations, data preprocessing , machine learning classifier , metric evaluation was imported
# DATA IMPORTATION / EXPLORATION
- The CSV data set was uploaded using pandas
- Data was explored and assesed for data type features, duplicates and missing values 
# DATA PRE-PROCESSING
- Missing values in the dataset was filled with the median values.
- Some numerical values were grouped for easy and better exploration.
# EXPLORATORY DATA ANALYSIS(EDA)
Univariate ,Bivariate and Multivariate EDA was carried out in order to identify patterns ,relationship in respect to customer churn.
# FEATURE ENGINEERING
- Drop off columns that are not relevant to the analysis
- Encode categorical variable using one hot encoder
- Segment data into predictor and target variable
- Scaled numerical column using standard scaler
- Split dataset to training and testing set 
# MACHINE LEARNING
Total of eight (8) machine learning models was applied to the dataset to help predict customer churn , these models include;
- XGB Classifier             
- Random Forest Classifier
- KNeighbors Classifier
- SGD Classifier
- SVC
- Gaussian NB
- Decision Tree Classifier
- Logistic Regression
# Model evaluation was carried out using the following metrics;
- Accuracy score, precission, recall, f1_score, AUC-ROC score and confussion matrix.
- more priority was given to recall and AUC score in choosing the best fit.
