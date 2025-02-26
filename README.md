# Credit Risk Classification

## 📌 Project Overview
This project focuses on **credit risk classification**, utilizing **machine learning models** to assess financial risk based on historical loan data. The analysis aims to predict the likelihood of loan default, helping financial institutions make informed lending decisions.

## 🛠️ Technologies Used
- **Python** 🐍
- **Pandas & NumPy** 📊
- **Scikit-Learn** 🤖
- **Matplotlib & Seaborn** 🎨
- **Jupyter Notebook** 📓

## 📂 Repository Structure
```
📦 credit_risk_classification
 ┣ 📂 data                 # Dataset(s) used for training and testing
 ┣ 📂 notebooks            # Jupyter Notebooks with analysis and modeling
 ┣ 📜 README.md            # Project documentation
 ┣ 📜 requirements.txt     # Dependencies
 ┗ 📜 model.pkl           # Trained machine learning model (if applicable)
```

## 🚀 Getting Started
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/BrendanD2/credit_risk_classification.git
cd credit_risk_classification
```
### 2️⃣ Install Dependencies
Ensure you have Python installed, then run:
```bash
pip install -r requirements.txt
```
### 3️⃣ Run the Analysis
Open Jupyter Notebook and execute the analysis:
```bash
jupyter notebook
```

## 📊 Key Features & Insights
✔ **Data Cleaning & Preprocessing** – Handling missing values, encoding categorical variables, and feature engineering.  
✔ **Exploratory Data Analysis (EDA)** – Visualizing credit risk trends and feature distributions.  
✔ **Machine Learning Modeling** – Training and evaluating classification models (Logistic Regression, Random Forest, XGBoost).  
✔ **Model Evaluation** – Assessing accuracy, precision, recall, and AUC-ROC for performance comparison.  

## 📌 Example Code Snippet
```python
from sklearn.ensemble import RandomForestClassifier
# Initialize model
model = RandomForestClassifier(n_estimators=100, random_state=42)
# Train model
model.fit(X_train, y_train)
# Make predictions
y_pred = model.predict(X_test)
```

## 📜 License
This project is licensed under the **MIT License** – feel free to use, modify, and distribute.

## 🤝 Contributing
Contributions are welcome! If you'd like to improve or extend this project, please fork the repository and submit a pull request.

## 📬 Contact
For any questions or collaborations, feel free to connect with me on **[LinkedIn](https://www.linkedin.com/in/brendan-doucette-0b33ab268/)**.

