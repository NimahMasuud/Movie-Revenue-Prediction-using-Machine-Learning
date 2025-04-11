# Movie-Revenue-Prediction-using-Machine-Learning
Predicting movie revenue categories based on attributes like genre, ratings, cast, user interactions, and more. Built to showcase end to end ML pipeline skills from data cleaning to deployment.

Project Highlights
Built from scratch: from data wrangling to deployment

Clean and interpretable code

Fully documented and reproducible

Shows real-world use of ML in media & entertainment

Project Overview
This project predicts the revenue category of a movie using various metadata features such as IMDb ratings, viewer interactions (likes, dislikes, comments), awards, runtime, genre, and more.

Whether you're a film studio or a data enthusiast, understanding what makes a movie successful at the box office can drive better decisions. This model brings data science into the entertainment industry.

📌 Problem Statement
Can we predict how much revenue a movie will generate based on its attributes?
The goal is to classify movies into predefined revenue categories (e.g., low, medium, high, blockbuster).

📊 Dataset Description
The dataset contains information on 2,400 movies, with features such as:

title, country, genres, language

ratings_imdb, ratings_tomatoes, ratings_metacritic

likes, dislikes, comments, overall_views

awards_win, awards_nomination, special_award

revenue_category (target variable)

🛠️ Tools & Technologies Used
Python, Pandas, NumPy, Matplotlib, Seaborn

Scikit learn for model building

Flask for API deployment

Render or Railway for hosting

Git & GitHub for version control

🔍 Exploratory Data Analysis (EDA)
The EDA phase revealed insights like:

Genres with higher average revenue

Relationship between user engagement (likes, comments) and revenue

Influence of awards and critic ratings on revenue categories

✅ Missing values were handled using imputation strategies.
✅ Categorical variables were encoded using One-Hot or Label Encoding.

🤖 Model Development
A classification model was trained to predict the revenue category using:

Random Forest Classifier (best performing)

Compared with Logistic Regression, Decision Trees, and XGBoost

🔧 Model Performance
Metric	Value
Accuracy	85%+
F1-Score	High for all classes
Feature Importance	Visualized to interpret key drivers
🧪 Evaluation
Confusion matrix and classification report were used to evaluate model performance. The model was found to generalize well to unseen data, making it suitable for real-world applications.

🧠 Key Learnings
Gained experience in cleaning dirty, multi-type real-world data

Learned to balance model accuracy with interpretability

Built an ML model pipeline from data prep to deployment

Strengthened skills in model evaluation and error analysis

