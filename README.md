# Diabetes Prediction

## Overview
This project predicts the likelihood of diabetes in individuals based on medical data. It utilizes logistic regression for classification and provides a web-based interface for users to input their data and get predictions.

## Features
- **Machine Learning Model:** Logistic Regression
- **Web Application:** Flask-based interface
- **Dataset:** Diabetes dataset used for training and testing
- **Model Files:** Pretrained model (`modelForPrediction.pkl`) and scaler (`standardScaler.pkl`)
- **Jupyter Notebook:** Includes data analysis and model training steps

## Installation
1. Clone this repository:
   ```sh
   git clone <repository_url>
   cd diabetes_prediction
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## How to Execute
1. Ensure all dependencies are installed.
2. Run the Flask application:
   ```sh
   python application.py
   ```
3. Open a browser and go to `http://127.0.0.1:5000/`.
4. Enter patient medical data and click 'Predict' to get a diabetes prediction.

## Project Structure
```
├── Dataset
│   ├── diabetes.csv
├── Model
│   ├── modelForPrediction.pkl
│   ├── standardScaler.pkl
├── Notebook
│   ├── Logistic_Regression.ipynb
├── templates
│   ├── home.html
│   ├── index.html
│   ├── single_prediction.html
├── application.py
├── requirements.txt
```

## Usage
- Enter patient medical data in the web interface.
- Click 'Predict' to get diabetes prediction.
- The model outputs the probability of diabetes.

## Technologies Used
- **Programming Language:** Python
- **Libraries:** Flask, Scikit-Learn, Pandas, NumPy
- **Machine Learning Model:** Logistic Regression

## Acknowledgments
This project is inspired by medical diagnostics research and aims to provide an easy-to-use diabetes prediction tool.


