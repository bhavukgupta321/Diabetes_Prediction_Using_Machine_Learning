# 🩺 Diabetes Prediction Using Machine Learning
## 📌 Project Objective
The objective of this project is to predict the likelihood of diabetes in patients based on diagnostic health measurements.
By applying various machine learning algorithms to the PIMA Indian Diabetes Dataset, the aim is to create a reliable tool that supports early detection and enables timely healthcare interventions.

Key steps in the workflow include:
- Cleaning the dataset and handling missing values.
- Treating outliers using statistical methods.
- Performing Exploratory Data Analysis (EDA) to discover patterns.
- Training and testing multiple ML models.
- Evaluating and comparing performance using accuracy scores and confusion matrices.

## 📊 Key Insights from EDA & Analysis
- Outcome Distribution – Around 65% of the cases are non-diabetic, while 35% are diabetic. This imbalance slightly impacts model predictions.
- Glucose Levels – A strong positive correlation exists between high glucose readings and diabetes likelihood.
- Age Impact – Older individuals show a significantly higher chance of having diabetes.
- BMI & Skin Thickness – Higher values are associated with an increased probability of diabetes.
- Pregnancies – A greater number of pregnancies correlates with higher diabetes risk in women.
- Genetic Influence – The Diabetes Pedigree Function (family history) plays a notable role in predicting diabetes.
- Feature Correlation – Glucose, Age, and Pregnancies have the highest correlation with the target outcome.
- Data Cleaning Effect – Replacing zero values with mean values and treating outliers improved data quality and model accuracy.
- Feature Importance – Random Forest feature importance revealed Glucose, BMI, and Age as top predictors.
- Visual Patterns – Histograms and KDE plots clearly show separation between diabetic and non-diabetic groups for key variables.

## 📈 Model Performance
- Ensemble Voting Classifier delivered the highest accuracy at 77.06%, outperforming all individual models.
- Random Forest Classifier achieved 75.32% accuracy, showing strong predictive power and robustness.
- Support Vector Machine (SVM) achieved 74.03% accuracy, performing well but slightly lower than ensemble methods.
- Decision Tree Classifier recorded 70.56% accuracy, making it the most interpretable but less accurate model.

## 🛠 Tech Stack
- Programming Language: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels
- Machine Learning Models: Decision Tree, SVM, Random Forest, Ensemble Voting Classifier

## 📌 Dataset Details
- Total Records: 768
- Features: 8 predictive attributes + 1 target variable
- Target Variable: Outcome (0 = Non-diabetic, 1 = Diabetic)
- Key Features: Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age.

## 💡 Business & Practical Impact
- Early Diagnosis Support: Helps medical professionals identify high-risk individuals quickly.
- Cost Reduction: Early detection can reduce healthcare costs by preventing severe complications.
- Data-Driven Decisions: Enables healthcare providers to prioritize patients based on risk scores.
- Scalability: Can be integrated into hospital systems for real-time prediction.
