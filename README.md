📱 Mobile Addiction Detection and Analysis
Overview

This project studies mobile phone usage to predict if a person might be addicted. It uses machine learning to find patterns of excessive use and gives insights to encourage healthier habits.

Features

Clean and prepare mobile usage data

Explore and visualize usage patterns

Predict mobile addiction using machine learning models

Evaluate models with accuracy, precision, recall, and F1-score

Technologies

Python with pandas, numpy, matplotlib, seaborn, scikit-learn

Models: Logistic Regression, Random Forest, Gradient Boosting

Project Structure
mobile-addiction-project/
│
├── data/          # Dataset files
├── scripts/       # Python scripts
├── results/       # Model results
├── plots/         # Visualizations
├── notebooks/     # Optional Jupyter notebooks
├── README.md
├── requirements.txt
└── LICENSE

Installation
git clone <repository_link>
cd mobile-addiction-project
pip install -r requirements.txt

Usage
python scripts/data_preprocessing.py
python scripts/exploratory_analysis.py
python scripts/train_models.py
python scripts/evaluate_models.py
python scripts/predict_addiction.py

Results

Evaluation metrics: results/model_metrics.csv

Visualizations: plots/ folder

Future Work

Add more features for better predictions

Create a web or mobile app for real-time monitoring

Integrate wearable devices for activity tracking
