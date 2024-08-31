# Predictive Maintenance System
<br>
<br>
Project Overview :
<br>
This project aims to predict when industrial machinery is likely to fail or require maintenance using machine learning techniques. By analyzing sensor data, usage history, and environmental conditions, the solution can help companies schedule maintenance proactively and prevent costly downtimes.
<br>
The project includes a machine learning model that predicts equipment failure, a Flask-based web application for real-time monitoring, and CI/CD pipelines for continuous integration and deployment.
<br>
<br>

Features :
<br>
Data Analysis & Feature Engineering: Exploratory Data Analysis (EDA) and feature engineering steps to handle and preprocess sensor and usage data.
Model Selection: Tested with different models including Decision Tree Classifier, Random Forest, and XGBoost. XGBoost provided the best accuracy.
Real-time Monitoring: Flask web app with a user-friendly interface to predict system failure.
CI/CD Pipelines: Integrated pipelines for continuous integration and continuous delivery.
Model Deployment: The final model is saved as a pickle file and deployed using Flask.
Alert System: Provides alerts based on prediction results to notify about potential machine failures.
<br>
<br>

Technology Stack :
<br>
Backend: Python, Flask
Machine Learning: Scikit-learn, XGBoost, Numpy, Pandas
Frontend: HTML, CSS
CI/CD: GitHub Actions (or any other CI/CD tool you may have used)
Model Deployment: Flask
<br>
<br>

Project Structure :
<br>
├── src
│   ├── pipeline
│   │   ├── __init__.py
│   │   ├── predict_pipeline.py   # Prediction pipeline code
├── templates
│   ├── index.html                # Main page
│   ├── home.html                 # Prediction page
├── static
│   ├── css
│   │   └── styles.css            # Styling for the web pages
├── app.py                        # Flask application entry point
├── model.pkl                     # Trained machine learning model
└── README.md                     # This README file


<br>
<br>
<br>
Getting Started
<br>
Prerequisites :
<br>
Python 3.7+
Flask
Numpy
Pandas
Scikit-learn
XGBoost

<br>
<br>

Model Performance :
<br>
The model performance was evaluated using different machine learning techniques. XGBoost performed the best, providing the highest accuracy compared to Decision Tree and Random Forest.
<br>

XGBoost: Best accuracy
RandomForest: Moderate accuracy
DecisionTree: Baseline model
<br>
<br>

CI/CD Pipeline :
CI/CD pipelines are integrated for continuous integration and deployment. The codebase is automatically tested and deployed to ensure that any new changes do not break the functionality.
<br>
<br>

Future Enhancements :
Integrate advanced analytics for more accurate predictions.
Implement a more sophisticated alerting system (e.g., email/SMS notifications).
Optimize the model for better real-time performance.
Add more data sources for improved prediction accuracy.
<br>
<br>

Contributing:
Feel free to open issues or submit pull requests for improvements and features.


Acknowledgments :
Thanks to the open-source community for the libraries and frameworks used in this project.

<br>
<br>
