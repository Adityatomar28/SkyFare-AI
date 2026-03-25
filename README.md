✈️ SkyFare AI — Flight Fare Prediction System

A Machine Learning web application that predicts airline ticket prices based on travel details such as source, destination, airline, and number of stops.
The system uses historical flight data, performs preprocessing and analysis, and applies a Random Forest Regressor model to generate accurate fare predictions.

🌐 Live Demo
https://skyfare-ai.onrender.com
🧠 Model Performance
Model	Accuracy
Linear Regression	72.00%
XGBoost	82.00%
Extra Trees Regressor	93.70%
Random Forest Regressor	93.80%

Selected Model: Random Forest
R² Score: 0.90

🎯 Features
Predict flight prices instantly
User-friendly web interface
Real-time ML predictions
Multiple model comparison
Responsive modern UI
End-to-end deployment
🛠️ Technologies Used
Programming
Python
HTML
CSS
JavaScript
Machine Learning
Scikit-learn
Random Forest
XGBoost
Pandas
NumPy
Web & Deployment
Flask
Gunicorn
Render
GitHub
Data Processing
BeautifulSoup
Data Cleaning
Feature Engineering
Exploratory Data Analysis (EDA)
📂 Project Structure
SkyFare-AI
│
├── app.py
├── flight.pkl
├── requirements.txt
├── Procfile
├── runtime.txt
│
├── templates/
│   ├── index.html
│   └── predict.html
│
├── static/
└── README.md
⚙️ Run Locally
git clone https://github.com/Adityatomar28/SkyFare-AI.git

cd SkyFare-AI

pip install -r requirements.txt

python app.py

Open in browser:

http://127.0.0.1:5000
📌 Example Prediction
Input
Source: Mumbai
Destination: Delhi
Stops: Non-stop
Airline: IndiGo
Output
Predicted Price: ₹5239
🚀 Skills Demonstrated
Machine Learning
Regression Modeling
Data Preprocessing
Feature Engineering
Flask Web Development
Model Deployment
Git & GitHub
End-to-End ML Project
👨‍💻 Author

Aditya Singh Tomar

GitHub:
https://github.com/Adityatomar28

LinkedIn:
https://linkedin.com/in/aditya-singh-tomar-1683a3279
