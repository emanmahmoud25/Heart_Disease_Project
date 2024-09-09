
# Heart Disease Risk Prediction

## Project Overview
This project aims to develop a predictive model to estimate the risk of coronary heart disease (CHD) based on various health-related factors. Using a dataset that includes demographic, lifestyle, and clinical variables, we applied machine learning techniques to create a model that predicts CHD risk.

## Dataset
The dataset contains the following features:
- **sex**: Gender of the individual
- **age**: Age of the individual
- **education**: Education level
- **smokingStatus**: Current smoking status
- **cigsPerDay**: Cigarettes smoked per day
- **BPMeds**: Whether the individual is on blood pressure medication
- **prevalentStroke**: History of stroke
- **prevalentHyp**: History of hypertension
- **diabetes**: Diabetes status
- **totChol**: Total cholesterol level
- **sysBP**: Systolic blood pressure
- **diaBP**: Diastolic blood pressure
- **BMI**: Body Mass Index
- **heartRate**: Heart rate
- **glucose**: Glucose level
- **CHDRisk**: Risk score for coronary heart disease (target variable)

## Data Processing
The dataset required preprocessing steps before it could be used for modeling:
1. **Handling missing values**: Missing data was imputed or removed as needed.
2. **Feature Scaling**: Variables were normalized or standardized to improve model performance.
3. **Feature Engineering**: New features were created to capture relationships in the data better.

## Methodology
The project followed these steps:
1. **Exploratory Data Analysis (EDA)**: Visualizations were created to understand the distribution of variables and their correlations with CHD risk.
2. **Model Selection**: Various machine learning models were tested, including:
   - Logistic Regression
   - Random Forest Regressor
   - Gradient Boosting Machines (GBM)
   - K-Nearest Neighbors (KNN)
   - Support Vector Machines (SVM)
3. **Hyperparameter Tuning**: Hyperparameters were tuned to improve accuracy.
4. **Model Evaluation**: Models were evaluated using metrics like accuracy, precision, recall, and F1-score.

## Results

### Logistic Regression
- **Accuracy**: 0.853
- **Precision**: 
  - Class 0: 0.86
  - Class 1: 0.64
- **Recall**: 
  - Class 0: 0.99
  - Class 1: 0.08
- **F1-Score**: 
  - Class 0: 0.92
  - Class 1: 0.14

### Random Forest Regressor
- **Accuracy**: 0.848
- **Precision**: 
  - Class 0: 0.86
  - Class 1: 0.50
- **Recall**: 
  - Class 0: 0.97
  - Class 1: 0.15
- **F1-Score**: 
  - Class 0: 0.92
  - Class 1: 0.23

### Gradient Boosting Machines (GBM)
- **Accuracy**: 0.850
- **Precision**: 
  - Class 0: 0.86
  - Class 1: 0.56
- **Recall**: 
  - Class 0: 0.99
  - Class 1: 0.08
- **F1-Score**: 
  - Class 0: 0.92
  - Class 1: 0.14

### K-Nearest Neighbors (KNN)
- **Accuracy**: 0.854
- **Precision**: 
  - Class 0: 0.87
  - Class 1: 0.57
- **Recall**: 
  - Class 0: 0.98
  - Class 1: 0.18
- **F1-Score**: 
  - Class 0: 0.92
  - Class 1: 0.27

### Support Vector Machines (SVM)
- **Accuracy**: 0.852
- **Precision**: 
  - Class 0: 0.85
  - Class 1: 1.00
- **Recall**: 
  - Class 0: 1.00
  - Class 1: 0.03
- **F1-Score**: 
  - Class 0: 0.92
  - Class 1: 0.05

### Model Comparison
- **Best Accuracy**: K-Nearest Neighbors (0.854)
- **Highest Precision for Class 1**: Support Vector Machines (1.00)
- **Highest Recall for Class 0**: Support Vector Machines (1.00)
- **Highest F1-Score for Class 0**: All models have similar scores around 0.92

## Conclusion
This project demonstrated the potential of using machine learning techniques to predict coronary heart disease risk based on readily available health metrics. While all models showed similar accuracy, each had strengths and weaknesses in different performance metrics. The K-Nearest Neighbors model achieved the highest accuracy, while the Support Vector Machines model excelled in precision for Class 1 and recall for Class 0.

