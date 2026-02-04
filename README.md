# Titanic-survival-project-using-Decision-tree-algorithm

# Project Overview

This project predicts whether a passenger survived the Titanic disaster based on features such as age, gender, ticket class, and fare.
A Decision Tree Classifier is used to model the relationship between these features and survival probability.

🧠 Objective

To analyze the Titanic dataset and build a machine learning model that can predict survival outcomes of passengers with good accuracy.

📂 Dataset

Source: Titanic Dataset – DataScienceDojo (Kaggle Version)

Key Features Used:

Pclass → Passenger Class (1 = Upper, 2 = Middle, 3 = Lower)
Sex → Gender (0 = Male, 1 = Female)
Age → Passenger’s Age
SibSp → Number of siblings/spouses aboard
Parch → Number of parents/children aboard
Fare → Ticket fare
Survived → Target variable (1 = Survived, 0 = Did not survive)

🧩 Steps Performed

- Data Loading – Read dataset using Pandas.
- Data Cleaning – Filled missing Age values with median.
- Feature Encoding – Converted categorical columns (Sex) into numeric.
- Train-Test Split – Divided data into 80% training and 20% testing.
- Model Training – Trained DecisionTreeClassifier with entropy criterion.
- Model Evaluation – Calculated accuracy, confusion matrix & classification report.
- Visualization – Plotted decision tree & feature importance chart.
- Prediction – Tested model on new sample passenger data.

🧾 Model Used

- Algorithm: Decision Tree Classifier
- Criterion: Entropy
- Max Depth: 4
- Accuracy: ~80–85%

📊 Visualizations

- Confusion Matrix (Seaborn Heatmap)
- Feature Importance Bar Chart
- Decision Tree Plot (Graphical representation of model decisions)

🧠 Insights

Female passengers had higher survival chances.
Passengers in 1st class were more likely to survive.
Younger passengers had slightly better chances.

🧪 Sample Predictions

Passenger	Pclass	Sex	Age	SibSp	Parch	Fare	Prediction
1	3	Male	25	0	0	7.25	❌ Did Not Survive
2	1	Female	38	1	0	71.83	✅ Survived
3	2	Male	45	0	2	13.0	❌ Did Not Survive

⚙️ Technologies Used

Python 
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

💡 Future Improvements

- Use Random Forest for better accuracy.
- Try Hyperparameter Tuning (GridSearchCV).
- Add more features (Embarked, Cabin, etc.) for richer predictions.

👨‍💻 Author

Ankit Kashyap
Data Science & Machine Learning Enthusiast
----------------------------------------------------------------------------------------------
