Titanic Dataset - Data Cleaning & Preprocessing
Objective
This project demonstrates data cleaning and preprocessing techniques on the Titanic dataset to prepare it for machine learning models.

 Steps Performed
Imported Dataset & Explored Data

Checked data types, shape, null values.

Generated descriptive statistics.

Handled Missing Values

Age → Filled with median.

Embarked → Filled with mode.

Dropped Cabin column (too many missing values).

Encoded Categorical Variables

Converted Sex using Label Encoding.

Applied One-Hot Encoding for Embarked.

Feature Scaling

Standardized numerical features (Age, Fare) using StandardScaler.

Outlier Detection & Removal

Used IQR method for Age and Fare.

Visualized with Boxplots.

Visualizations

Boxplots for outlier detection.

Correlation heatmap using Seaborn.

Saved Cleaned Dataset

Final cleaned data exported to titanic_cleaned.csv.

🛠 Tools & Libraries
Python 3

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

📂 Files in this Repository
titanic_preprocessing.ipynb → Main notebook with code & explanations.

titanic_cleaned.csv → Cleaned dataset.

README.md → Project overview and steps.

📊 Dataset
Titanic Dataset: Kaggle Link https://www.kaggle.com/datasets/yasserh/titanic-dataset

🚀 How to Run
bash
Copy
Edit

# Clone this repository
git clone https://github.com/your-username/titanic-preprocessing.git

# Navigate to folder
cd titanic-preprocessing

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook titanic_preprocessing.ipynb
