# 🎯 Diabetes Prediction

## 🌟 Overview
This project predicts the likelihood of diabetes in individuals based on medical data. It leverages **Logistic Regression** for classification and provides a **user-friendly web interface** for predictions.

🔗 **Project is live at:** [Diabetes Prediction Web App](https://diabetic-predict.onrender.com)

## 🚀 Features
- 🧠 **Machine Learning Model:** Logistic Regression
- 🌍 **Web Application:** Flask-based interface
- 📊 **Dataset:** Diabetes dataset for training and testing
- 📂 **Model Files:** Pretrained model (`modelForPrediction.pkl`) & scaler (`standardScaler.pkl`)
- 📜 **Jupyter Notebook:** Includes data analysis & model training steps

## 🛠 Installation
1. Clone the repository:
   ```sh
   git clone <repository_url>
   cd diabetes_prediction
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## ▶️ How to Run
1. Ensure all dependencies are installed.
2. Start the Flask application:
   ```sh
   python application.py
   ```
3. Open your browser and navigate to [`http://127.0.0.1:5000/`](http://127.0.0.1:5000/).
4. Enter patient medical data and click **'Predict'** to get a diabetes prediction.

## 📁 Project Structure
```
📦 diabetes_prediction
├── 📂 Dataset
│   ├── diabetes.csv
├── 📂 Model
│   ├── modelForPrediction.pkl
│   ├── standardScaler.pkl
├── 📂 Notebook
│   ├── Logistic_Regression.ipynb
├── 📂 templates
│   ├── home.html
│   ├── index.html
│   ├── single_prediction.html
├── 📝 application.py
├── 📄 requirements.txt
```

## 🎯 Usage
✅ Enter patient medical data in the web interface.  
✅ Click **'Predict'** to get a diabetes probability score.  
✅ Use the insights for early diagnosis and preventive care.  

## 🛠 Technologies Used
- **💻 Programming Language:** Python
- **📚 Libraries:** Flask, Scikit-Learn, Pandas, NumPy
- **🔬 Machine Learning Model:** Logistic Regression

## 🙌 Acknowledgments
This project is inspired by **medical diagnostics research** and aims to provide an accessible diabetes prediction tool.

📌 **Contributions & feedback are welcome!** 🚀

