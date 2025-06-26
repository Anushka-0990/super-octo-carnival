# super-octo-carnival
This project predicts average annual rainfall in India using historical weather data (1901–2015) and machine learning models like Linear Regression and Random Forest. It helps understand rainfall trends and provides insights for weather analysis and agricultural planning.

🌧️ Rainfall Prediction using Machine Learning

📌 Overview

This project predicts average annual rainfall in India using historical data from 1901 to 2015. It applies Machine Learning models such as Linear Regression and Random Forest Regressor to analyze and forecast rainfall trends.

This model can be helpful in agricultural planning, climate trend analysis, and early warning systems for drought or flood-prone areas.

📁 Dataset

- Dataset Name: Rainfall in India 1901–2015
- Source: https://www.kaggle.com/datasets/rajanand/rainfall-in-india
- File: rainfall in india 1901-2015.csv
- Description: Contains yearly rainfall data across multiple Indian regions

🧠 Machine Learning Models Used

1. Linear Regression – Baseline model for trend prediction
2. Random Forest Regressor – More accurate, handles non-linearity

📊 Features

- Clean and preprocess rainfall data
- Group and average rainfall values year-wise
- Visualize trends over time
- Train and compare ML models
- Evaluate using R² and Mean Squared Error

🛠️ Tech Stack

- Language: Python 3.x
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

📂 Folder Structure

rainfall-prediction/
├── data/
│   └── rainfall in india 1901-2015.csv
├── main_notebook.ipynb
├── requirements.txt
├── README.txt
└── data_info.txt

🚀 How to Run

1. Clone the project or download the ZIP
2. Install dependencies:
   pip install -r requirements.txt
3. Open `main_notebook.ipynb` in Jupyter or Google Colab
4. Run all cells to train and evaluate the models

🧯 Troubleshooting

❗ FileNotFoundError: CSV not found
✔️ Make sure the dataset file is inside the /data folder and the name is exactly correct.

❗ No module named 'pandas'
✔️ Install with: pip install pandas

❗ Poor accuracy or model performance
✔️ Try tuning Random Forest parameters or explore more data features

🧪 Testing in Google Colab

- Upload notebook + CSV
- If using Colab, you may need:
  from google.colab import files
  files.upload()

📌 Project Outcome

- Forecasted rainfall using real-world data
- Learned regression models and data cleaning
- Useful for academic projects, resume, and GitHub portfolio

✍️ Made with ❤️ by Tushar for Anushka’s Data Science portfolio

