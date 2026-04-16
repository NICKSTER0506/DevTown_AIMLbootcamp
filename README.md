# Titanic Survival Prediction using Machine Learning

1. Introduction	
In this project, we worked on the famous Titanic dataset to analyze passenger data and predict whether a passenger survived or not. The goal was to understand how different factors like gender, class, and fare influenced survival, and then build a machine learning model to make predictions.

________________________________________
2. Objective
The main objective of this project was to:
•	Explore and understand the dataset
•	Clean and preprocess the data
•	Visualize important patterns
•	Build a machine learning model to predict survival
________________________________________
3. Dataset Description
The dataset contains information about passengers such as:
•	Age
•	Gender (Sex)
•	Passenger Class (Pclass)
•	Fare
•	Number of family members (SibSp, Parch)
•	Embarked location
These features help in analyzing survival patterns.
________________________________________
4. Data Preprocessing
Before building the model, the data needed to be cleaned and prepared:
•	Missing values in Age were filled using median values
•	Missing values in Embarked were filled using mode
•	Missing values in Deck were handled using a placeholder ("Unknown")
•	Unnecessary columns such as who, alive, deck, etc., were removed
•	Categorical values like Sex, Embarked, and Alone were converted into numerical form
This step ensured the dataset was ready for machine learning.
________________________________________
5. Data Visualization & Insights
Several graphs were plotted to understand the data better:
•	Survival Distribution: Showed how many passengers survived vs not survived
•	Survival by Gender: Females had a significantly higher survival rate than males
•	Fare vs Class (Box Plot): First-class passengers paid higher fares
Key Insights:
•	Female passengers had a much higher chance of survival
•	Passengers in higher classes (especially first class) survived more
•	Higher fare was associated with better survival chances
These insights helped us understand patterns before building the model.
________________________________________
6. Model Building
We used Logistic Regression, a classification algorithm, since the output (survived or not) is binary.
Steps followed:
•	Selected input features (X) and output (y = survived)
•	Split the dataset into training (80%) and testing (20%)
•	Trained the model on training data
•	Predicted results on test data
________________________________________
7. Model Evaluation
Accuracy
The model achieved an accuracy of:
82.5%
This means the model correctly predicted survival for about 82 out of 100 passengers.
________________________________________
Confusion Matrix Interpretation
•	69 passengers were correctly predicted as not survived
•	49 passengers were correctly predicted as survived
•	13 passengers were incorrectly predicted as survived
•	12 passengers were incorrectly predicted as not survived
Overall, most predictions were correct, with relatively few errors.
________________________________________
8. Conclusion
This project shows that:
•	Gender and passenger class are strong factors affecting survival
•	Data visualization helps in understanding patterns clearly
•	Logistic Regression performs well for this classification problem
Even though the model is not perfect, it gives good accuracy and meaningful insights.
________________________________________
9. Learning Outcomes
Through this project, we learned:
•	Data cleaning and preprocessing techniques
•	Data visualization using Seaborn and Matplotlib
•	Converting categorical data into numerical form
•	Building and evaluating a machine learning model
•	Interpreting results using accuracy and confusion matrix

