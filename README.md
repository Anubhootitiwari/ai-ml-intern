# Titanic Dataset - Data Cleaning & Preprocessing

### 📌 Objective
This project demonstrates how to clean and preprocess raw data for machine learning models using the Titanic dataset.

---

### ✅ Steps Performed
1. **Data Loading & Exploration**
   - Loaded Titanic dataset from Kaggle.
   - Checked data types, null values, and statistics.

2. **Handling Missing Values**
   - Filled `Age` with **median**.
   - Filled `Embarked` with **mode**.
   - Dropped `Cabin` due to too many missing values.

3. **Encoding Categorical Variables**
   - Converted `Sex` using **Label Encoding**.
   - Applied **One-Hot Encoding** for `Embarked`.

4. **Feature Scaling**
   - Standardized `Age` and `Fare` using **StandardScaler**.

5. **Outlier Detection & Removal**
   - Used **IQR method** for `Age` and `Fare`.
   - Visualized using boxplots.

6. **Visualization**
   - Correlation heatmap and boxplots using Seaborn.

7. **Saved Cleaned Dataset**
   - Exported final dataset as `titanic_cleaned.csv`.

---

### 🛠 Tools & Libraries
- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

### 📊 Dataset
- [Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

### 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/your-username/titanic-preprocessing.git

# Navigate to the folder
cd titanic-preprocessing

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook titanic_preprocessing.ipynb
```

---

### 📂 Files
- `titanic_preprocessing.ipynb` → Notebook with code and explanations.
- `titanic_cleaned.csv` → Cleaned dataset (generated after running notebook).
- `requirements.txt` → Required Python libraries.
- `README.md` → Project overview.
