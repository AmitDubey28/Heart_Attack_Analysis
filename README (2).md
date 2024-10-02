
# Heart Attack Analysis

About 610,000 people die of heart disease in the India every year–that’s 1 in every 4 deaths.
Heart disease is the leading cause of death for both men and women. More than half of the deaths due to heart disease in 2019 were in men.1
Coronary Heart Disease(CHD) is the most common type of heart disease, killing over 370,000 people annually.
Every year about 735,000 Americans have a heart attack. Of these, 525,000 are a first heart attack and 210,000 happen in people who have already had a heart attack.

This project focuses on analyzing the risk factors contributing to heart attacks using machine learning techniques. By leveraging clinical data, we aim to build predictive models that can help in identifying individuals at risk of heart disease.
## Dataset

The dataset used for this project comes from the Kaggle. It contains medical data of patients, including the following attributes:

- Age : Age of the patient
- Sex : Sex of the patient
- CP : Chest Pain type chest pain type
    - Value 1: typical angina
    - Value 2: atypical angina
    - Value 3: non-anginal pain
    - Value 4: asymptomatic
- trtbps : resting blood pressure (in mm Hg)
- chol : cholestoral in mg/dl fetched via BMI sensor
- fbs : (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
- restecg : resting electrocardiographic result
    - Value 0: normal
    - Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
    - Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
- thalach : maximum heart rate achieved
- exang: exercise induced angina (1 = yes; 0 = no)
- oldpeak : STdpression invluded by exercise relative to rest ('ST' relates to positions on the ECCG plot)
- slp(slope) : the slope of the peak exercise ST segment
    - 0 : downslopping;
    - 1 : flat;
    - 2 : upslopping;
- caa: number of major vessels (0-3)
- thall : Displays the thalassemia : 1,3 = normal  ,6 = fixed defect, 7 = reversible defect: no proper blood movement when excercising
- output : 0 = NO , he is not in danger of heart attack ,1 = YES , he is  in the danger of heart attack
## Objective

The main objective is to predict the likelihood of a heart attack based on medical records and to analyze which factors contribute most significantly to heart attacks.
## Key Tasks include

- Data cleaning and preprocessing.
- Exploratory Data Analysis (EDA).
- Building various machine learning models (Logistic Regression, Random Forest, SVM, etc.)
- Evaluating model performance using metrics like accuracy, precision, recall, and F1-score.
## Results

The results of the analysis include:
- Correlation Analysis: Identified significant factors like cholesterol levels, age, and exercise-induced angina.
- Model Performance: The Random Forest model achieved an accuracy of 85% with an F1 score above 0.82, outperforming other models.
- Feature Importance: Cholesterol, maximum heart rate, and age were found to be key predictors of heart attacks.
## Future Enhancements

- Incorporate Additional Datasets: Expand the model by integrating more datasets for broader demographic coverage.
- Feature Engineering: Introduce new features like BMI, lifestyle factors, and time-series data to improve predictions.
- Hyperparameter Tuning: Implement advanced techniques like Grid Search or Bayesian Optimization for better model performance.
- Deep Learning Models: Explore neural networks to capture more complex patterns in the data.
- Deployment: Build a web or mobile app for real-time predictions and integrate cloud services for scalability.
- Model Interpretability: Use explainability techniques (SHAP, LIME) to make predictions more understandable.
- Early Warning System: Develop a system for real-time health monitoring using wearable devices.
- Validation: Validate the model with real-world clinical data to ensure accuracy.
- User Feedback: Incorporate feedback from medical professionals to improve the model.
- Visualization: Create interactive visualizations for better data insights.
## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and make changes as needed. You can also raise issues if you find bugs or have feature requests.