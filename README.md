# Taiwanese Bankruptcy Prediction System

An AI-powered financial risk assessment system that predicts the likelihood of company bankruptcy using machine learning and financial indicators. The application utilizes an Artificial Neural Network (ANN) model and provides probability-based predictions through an interactive Streamlit interface.

## Features

* Bankruptcy risk prediction
* Probability-based risk assessment
* Interactive Streamlit web application
* Financial ratio analysis
* ANN-based classification model
* Data preprocessing and feature scaling
* Real-time prediction results
* User-friendly financial input interface

## Technologies Used

* Python
* TensorFlow / Keras
* Streamlit
* Pandas
* Scikit-learn
* Joblib

## Financial Features

The model uses the following financial indicators:

* Debt Ratio (%)
* Current Ratio
* Quick Ratio
* Operating Profit Rate
* After-tax Net Interest Rate
* Net Income to Total Assets
* Net Income to Stockholder's Equity

## Machine Learning Pipeline

1. Data preprocessing
2. Feature normalization
3. Feature scaling
4. ANN model training
5. Model evaluation
6. Bankruptcy prediction

## Model Performance

* Accuracy: 91.3%
* ROC-AUC Score: 0.92
* Precision (Non-Bankrupt): 99.3%
* Recall (Bankrupt): 80.3%

## Project Structure

```text
Taiwanese-Bankruptcy-Prediction/
│
├── app.py
├── DATA SCIENCE.ipynb
├── Prototype.ipynb
├── data.csv
├── ann_model.h5
├── ann_model_simplified.h5
├── scaler.pkl
├── scaler_simplified.pkl
├── metrics.json
├── requirements.txt
└── README.md
```

## How to Run

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Application

```bash
streamlit run app.py
```

### Access Application

Open your browser and navigate to:

```text
http://localhost:8501
```

## Prediction Output

The system provides:

* Probability of Bankruptcy
* Probability of Not Being Bankrupt
* Bankruptcy Risk Classification
* Financial Risk Assessment

## Learning Outcomes

* Artificial Neural Networks (ANN)
* Financial Risk Analytics
* Binary Classification
* Data Preprocessing
* Feature Scaling
* Model Evaluation
* Streamlit Application Development
* Predictive Analytics

## Author

Ngoh Jia Ying


