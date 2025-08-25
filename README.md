



# 🏡 House Price Prediction Using XGBoost















A machine learning project to predict house prices using the Boston Housing Dataset and XGBoost Regressor.
The model is trained, evaluated, and visualized with multiple performance metrics.






---















## 🚀 Features



















📊 Exploratory Data Analysis (EDA): Dataset shape, summary statistics, correlation heatmap

🧮 Preprocessing: Feature/target separation, renaming columns, handling missing values

🤖 Model Training: XGBoost Regressor for predicting house prices

📈 Evaluation Metrics: R² Score, Mean Squared Error (MSE), Cross-validation

🔎 Visualization: Heatmap, Actual vs Predicted scatter plot, Residual plot










---















## 🧠 Machine Learning















- **Machine Learning Workflow:**  



Import Libraries: NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, XGBoost


Load Dataset: Boston Housing dataset (CSV)


Explore Data: .head(), .describe(), .shape(), correlation matrix

Preprocessing: Rename medv → price, train-test split (80/20)

Train Model: Fit XGBoost Regressor

Evaluate Model: R² score, Mean Squared Error (MSE), 5-fold cross-validation

Visualizations:

Heatmap of correlations

Actual vs Predicted plot

Residual analysis







---















## 🛠️ Tech Stack















| Layer       | Technology       |







|-------------|------------------|







| Language    | Python 3.12 |







| Framework   | Scikit-learn, XGBoost |







| Dataset     | Boston Housing Dataset |







| Tools       | NumPy, Pandas, Matplotlib, Seaborn |















---















## 📁 Project Structure















```text



├── BostonHousing.csv                ← Dataset
├── House Price Prediction.ipynb     ← Jupyter Notebook (main workflow)
├── outputs/                         ← Graphs & plots (optional)
└── README.md                        ← Project documentation


```

---



## 📊 Visualizations
📌 Correlation Heatmap → Shows relationship between features & house price

🎯 Actual vs Predicted → Scatter plot of model predictions

📉 Residual Plot → Analysis of prediction errors




