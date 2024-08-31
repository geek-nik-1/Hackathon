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
<br>
<hr>

Features :
<br>
Data Analysis & Feature Engineering: Exploratory Data Analysis (EDA) and feature engineering steps to handle and preprocess sensor and usage data.
<br>
Model Selection: Tested with different models including Decision Tree Classifier, Random Forest, and XGBoost. XGBoost provided the best accuracy.
<br>
Real-time Monitoring: Flask web app with a user-friendly interface to predict system failure.
<br>
CI/CD Pipelines: Integrated pipelines for continuous integration and continuous delivery.
<br>
Model Deployment: The final model is saved as a pickle file and deployed using Flask.
<br>
Alert System: Provides alerts based on prediction results to notify about potential machine failures.
<br>
<br>
<hr>

Technology Stack :
<br>
Backend: Python, Flask
<br>
Machine Learning: Scikit-learn, XGBoost, Numpy, Pandas
<br>
Frontend: HTML, CSS
<br>
Model Deployment: Flask
<br>
<br>
<hr>

Project Structure :
<br>
├── src
<br>
│   ├── pipeline
<br>
│   │   ├── __init__.py
<br>
│   │   ├── predict_pipeline.py   # Prediction pipeline code
<br>
├── templates
│   ├── index.html                # Main page
<br>
│   ├── home.html                 # Prediction page
<br>
├── static
<br>
│   ├── css
<br>
│   │   └── styles.css            # Styling for the web pages
<br>
├── app.py                        # Flask application entry point
<br>
├── model.pkl                     # Trained machine learning model
<br>
└── README.md                     # This README file
<br>
<hr>

Prerequisites :
<br>
Python 3.7+
<br>
Flask
<br>
Numpy
<br>
Pandas
<br>
Scikit-learn
<br>
XGBoost

<br>
<br>
<hr>

Model Performance :
<br>
The model performance was evaluated using different machine learning techniques. XGBoost performed the best, providing the highest accuracy compared to Decision Tree and Random Forest.
<br>
<br>
XGBoost: Best accuracy
<br>
RandomForest: Moderate accuracy
<br>
DecisionTree: Baseline model
<br>
<br>
<hr>


Future Enhancements :
<br>
Integrate advanced analytics for more accurate predictions.
<br>
Implement a more sophisticated alerting system (e.g., email/SMS notifications).
<br>
Optimize the model for better real-time performance.
<br>
Add more data sources for improved prediction accuracy.
<br>
<br>
<hr>

Contributing:
<br>
Feel free to open issues or submit pull requests for improvements and features.
<br>
<br>
<hr>


Acknowledgments :
Thanks to the open-source community for the libraries and frameworks used in this project.

<br>
<br>
