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
Model Selection: Tested with different models including Decision Tree Classifier, Random Forest, and GradientBoost. GradientBoost provided the best accuracy.
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
Machine Learning: Scikit-learn, GradientBoostingClassifier, Numpy, Pandas, RandomForestClassifier, KNeighboursClassifier
<br>
Frontend: HTML, CSS
<br>
Model Deployment: Flask
<br>
<br>
<hr>

Project Structure :
Hackathon/<br>
├── data/<br>
│   └── predictive_maintainance.csv<br>
├── artifacts/<br>
│   ├── df.csv<br>
│   ├── model.pkl<br>
│   ├── processor.pkl<br>
│   ├── test.csv<br>
│   └── train.csv<br>
├── src/<br>
│   ├── components/<br>
│   │   ├── data_ingestion.py<br>
│   │   ├── data_transformation.py<br>
│   │   └── model_trainer.py<br>
│   ├── pipeline/<br>
│   │   ├── __init__.py<br>
│   │   └── predict_pipeline.py<br>
├── static/<br>
│   └── css/<br>
│       └── style.css<br>
├── templates/<br>
│   ├── home.html<br>
│   └── index.html<br>
├── app.py<br>
├── requirements.txt<br>
├── setup.py<br>
└── README.md<br>

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
<hr>

Model Performance :
<br>
The model performance was evaluated using different machine learning techniques. GradientBoosting performed the best, providing the highest accuracy compared to LogisticRegression and Random Forest.
<br>
<br>
GradientBoosting: Best accuracy
<br>
RandomForest: Moderate accuracy
<br>
LogisticRegression: Baseline model
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

<h2>Setup Instructions</h2>

<hr>

<h3>Local Setup</h3>

<pre>
1. <b>Clone the repository:</b><br>
   <code>git clone https://github.com/geek-nik-1/Hackathon.git</code><br>
   <code>cd Hackathon</code><br><br>

2. <b>Create and activate a virtual environment:</b><br>
   <code>python3 -m venv venv</code><br>
   <code>source venv/bin/activate  # On Windows use `venv\Scripts\activate`</code><br><br>

3. <b>Install dependencies:</b><br>
   <code>pip install -r requirements.txt</code><br><br>

4. <b>Install the project:</b><br>
   <code>pip install .</code><br><br>

5. <b>Run the application:</b><br>
   <code>python app.py</code><br><br>
   The web application will be accessible at <a href="http://127.0.0.1:8080/">http://127.0.0.1:8080/</a>.<br>
</pre>


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
