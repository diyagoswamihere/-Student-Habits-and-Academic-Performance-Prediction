# 🎓 Student Habits and Academic Performance Prediction
This project analyzes and predicts student academic performance based on behavioral, psychological, and lifestyle factors. Using a synthetic dataset of 80,000 students, the goal is to build high-performing regression models to predict exam scores and GPA, while leveraging visualizations to explore feature relationships.

📁 Dataset
Source: Kaggle - Student Habits and Academic Performance Dataset
Structure:
The dataset is downloaded via kagglehub and located in a nested folder inside a zip:
enhanced_student_habits_performance_dataset/enhanced_student_habits_performance_dataset.csv

Key Features:
Demographics: age, gender, major
Habits: study_hours_per_day, social_media_hours, screen_time, netflix_hours
Lifestyle: sleep_hours, diet_quality, exercise_frequency
Psychological Factors: stress_level, mental_health_rating, exam_anxiety_score, motivation_level
Support Systems: parental_support_level, access_to_tutoring, extracurricular_participation
Targets: previous_gpa, exam_score

🔍 Exploratory Data Analysis
The notebook performs thorough EDA including:
-Distributions of target variables (GPA and Exam Score)
-Correlation Heatmap to analyze numeric relationships
-Box plots and pair plots to compare study habits, stress levels, mental health, and sleep hours with GPA and exam scores
-Handling of missing values, datatype casting, and encoding for categorical variables

🧠 Machine Learning Models
The following regression models were trained and evaluated:

Model	Description
Linear Regression	Baseline linear model
Decision Tree Regressor	Tree-based model capturing non-linearity
Random Forest Regressor	Ensemble model using bagging
Gradient Boosting Regressor	Boosted tree model for better performance
XGBoost Regressor	Efficient and optimized gradient boosting

✅ Metrics Used:
R² Score
Mean Absolute Error 
Mean Squared Error 
Root Mean Squared Error 

📊 Visualizations
Feature Importance plots from ensemble models
Scatter plots comparing predictions vs. actuals
Pairplots for multivariate visual comparison

🏆 Best Model
After experimentation, XGBoost Regressor achieved the best performance on both targets (exam_score, previous_gpa), due to its ability to handle non-linearity, feature interactions, and missing data.

🛠️ Tech Stack
Python 3.11+
Pandas, NumPy
Scikit-learn
Seaborn, Matplotlib
XGBoost
KaggleHub 


