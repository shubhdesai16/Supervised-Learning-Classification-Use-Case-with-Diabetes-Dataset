**Business Understanding:**

**Problem Statement:** Predict diabetes in patients based on medical attributes.
**Importance:** Early detection of diabetes is crucial for better management, improving patient outcomes, and reducing healthcare costs.
**Dataset:** Sourced from the National Institute of Diabetes and Digestive and Kidney Diseases, containing predictors like age, BMI, blood pressure, etc.

**Data Collection:**
Dataset obtained from Kaggle named "diabetes.csv" with columns including Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age, and Outcome.
Data Understanding:

**Exploratory Data Analysis (EDA):**
Identified missing values and zero entries in several columns.

**Data Preparation:**
Handled missing values by replacing zeros with mean values.
Split data into training (80%) and testing (20%) sets.

**Methodology:**

**Model Selection:** Used Extra Trees Classifier, Quadratic Discriminant Analysis, and Random Forest Classifier.

**Model Training:** Trained each model on the training dataset.

**Model Evaluation:** Evaluated models using accuracy, precision, recall, F1 score, and Jaccard score.

**Results:**
Extra Trees Classifier performed the best with the highest accuracy (75.97%).
Presented performance metrics and visualizations like ROC curves and confusion matrices.

**Conclusions:**
Suggested improvements by including more relevant features and applying advanced techniques like ensemble learning.
Discussed real-life applications, potential client value, and key learnings from the project.

**Iteration 2:**
Improved data balance by under-sampling, leading to increased accuracy (88%) and ROC (88).
