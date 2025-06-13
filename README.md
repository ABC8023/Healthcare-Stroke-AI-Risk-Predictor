# Stroke Risk Predictor

A Flask-based web application that predicts the likelihood of stroke in patients using a trained neural network model and healthcare data. Users input basic health-related information, and the app returns a prediction and probability of stroke risk.

## Features

- User-friendly web interface for entering patient data
- Predicts stroke likelihood based on health parameters
- Uses a pre-trained neural network model
- Real-time probability output
- Built with Flask, pandas, joblib, and scikit-learn

## Dataset

This project uses a healthcare dataset for stroke prediction which includes features like age, gender, hypertension, heart disease, glucose level, BMI, and smoking status.

## Getting Started

### Prerequisites

- Python 3.x
- Flask
- pandas
- scikit-learn
- joblib

You can install the dependencies using:

pip install flask pandas scikit-learn joblib

# Setup
## 1.Clone the repository:

git clone https://github.com/yourusername/stroke-predictor.git

cd stroke-predictor

## 2. Make sure the following files are in place:

app.py (Flask application)

Trained model file (trained_neural_network.joblib)

Preprocessor file (preprocessor.joblib)

HTML templates: index.html and result.html

## 3. Run the app:

python app.py

## 4. Open your browser and navigate to:

http://127.0.0.1:5000/

# Input Fields

Gender

Age

Hypertension (0 or 1)

Heart Disease (0 or 1)

Ever Married (Yes or No)

Work Type (e.g., Private, Self-employed)

Residence Type (Urban or Rural)

Average Glucose Level

BMI

Smoking Status

# Output

Prediction: Whether the user is at risk of stroke.

Probability: Likelihood (between 0 and 1) of stroke occurrence.

# License

This project is open-source and free to use under the MIT License.
