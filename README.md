# 🚢 Titanic Dataset – Data Cleaning & Visualization










# 📌 Project Overview

This project explores the Titanic dataset through data cleaning and visualization using Python libraries.
The main goal was to practice data preprocessing techniques and generate insights about passenger survival patterns — without applying machine learning models.

# 🛠 Tech Stack

Python

Pandas → Data cleaning, handling missing values, feature engineering

Matplotlib & Seaborn → Visualization of survival rates, distributions, and correlations

Jupyter Notebook for analysis

# 🔑 Key Steps
🔹 Data Cleaning

Handled missing values in Age, Embarked, and Cabin.

Converted categorical variables (Sex, Embarked) into usable formats.

Created new features like FamilySize and IsAlone.

🔹 Exploratory Data Analysis (EDA)

Analyzed distributions of Age, Fare, and Passenger Class.

Compared survival rates across gender, passenger class, and embarkation port.

Visualized correlations between features using heatmaps.

# 🔹 Visualization Highlights

📊 Bar plots of survival by gender & class.

🎂 Pie charts of embarkation distribution.

📈 Age vs. Fare scatter plots.

🔥 Correlation heatmap of numerical features.

# 📊 Sample Insights

👩 Women had higher survival rates compared to men.

🎓 First-class passengers were more likely to survive than third-class passengers.

🛳 Passengers who embarked from Cherbourg (C) had higher survival chances.

👨‍👩‍👧 Family size influenced survival — those traveling in small groups fared better.

# 🚀 How to Run

Clone the repository:

git clone https://github.com/yourusername/titanic-eda.git
cd titanic-eda


Install dependencies:

pip install -r requirements.txt


Open the notebook:

jupyter notebook Titanic_EDA.ipynb

# 📂 Project Structure
📦 Titanic-EDA
 ┣ 📊 data/                 # Titanic dataset (train.csv, test.csv)
 ┣ 📄 Titanic_EDA.ipynb     # Main notebook (cleaning + visualization)
 ┣ 📄 requirements.txt      # Python dependencies
 ┣ 📄 README.md             # Project documentation

# 📌 Future Improvements

Add more advanced visualizations (pair plots, violin plots).

Automate the cleaning pipeline for reproducibility.

Build an optional interactive Streamlit dashboard.

# 👤 Author

Emmanuel Anowai
💼 Data Analyst | 📊 Python & Visualization Enthusiast | 🌐 Nigeria


✨ If this project helped you, don’t forget to ⭐ star the repo!
