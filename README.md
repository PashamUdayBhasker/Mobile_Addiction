📱 Mobile Addiction Detection and Analysis

📝 Project Overview

This project analyzes mobile usage patterns to predict mobile addiction tendencies. Using machine learning, it identifies behaviors indicating excessive mobile use and provides actionable insights for healthier digital habits.

⚡ Features

Data preprocessing and cleaning

Exploratory Data Analysis (EDA) with visualizations

Machine learning models for mobile addiction prediction

Model evaluation with metrics: accuracy, precision, recall, F1-score

🛠️ Technologies Used

Language: Python

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Models: Logistic Regression, Random Forest, Gradient Boosting

Visualization: Matplotlib, Seaborn

📂 Project Structure
mobile-addiction-project/
│
├── README.md                 # Project documentation
├── requirements.txt          # Python dependencies
├── LICENSE                   # MIT License
│
├── data/                     # Dataset folder
│   └── mobile_usage.csv
│
├── scripts/                  # Python scripts
│   ├── data_preprocessing.py
│   ├── exploratory_analysis.py
│   ├── train_models.py
│   ├── evaluate_models.py
│   └── predict_addiction.py
│
├── results/                  # Model evaluation results
│   └── model_metrics.csv
│
├── plots/                    # Data visualizations
│   ├── correlation_heatmap.png
│   └── screen_time_distribution.png
│
└── notebooks/                # Optional Jupyter notebooks
    └── analysis.ipynb

📥 Installation

Clone the repository:

git clone <repository_link>


Navigate to the project folder:

cd mobile-addiction-project


Install dependencies:

pip install -r requirements.txt

🖥️ Usage

Preprocess data:

python scripts/data_preprocessing.py


Visualize data (EDA):

python scripts/exploratory_analysis.py


Train machine learning models:

python scripts/train_models.py


Evaluate models:

python scripts/evaluate_models.py


Predict addiction level for new users:

python scripts/predict_addiction.py

📊 Results

Evaluation metrics: results/model_metrics.csv

Visualizations: plots/ folder

🌟 Future Work

Add more behavioral and demographic features for improved predictions

Deploy as a web or mobile application for real-time monitoring

Integrate wearable devices for combined activity and screen time tracking
