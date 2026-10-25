# 🏥 Insurance Cost Estimator

**Predict medical insurance costs using Machine Learning.**

An interactive web application that estimates annual medical insurance charges based on individual characteristics and lifestyle factors. Built using Python, Scikit-learn, and Streamlit.

## ✨ Features

- 👤 **Personalized Predictions** — Estimate insurance costs using age, sex, BMI, number of children, smoking status, and region.
- 🤖 **Machine Learning** — Uses a trained regression model to predict insurance charges.
- 📊 **Interactive Visualization** — Compare predicted charges with average costs for smokers and non-smokers.
- 💰 **INR-Based Estimates** — Displays estimated annual insurance costs in Indian Rupees.
- ⚡ **Real-Time Interaction** — Update input parameters and generate predictions through an interactive interface.

## 🛠️ Tech Stack

- **Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Web Application:** Streamlit
- **Visualization:** Plotly
- **Model Storage:** Pickle

## ⚙️ How It Works

1. Collects user information through interactive input controls.
2. Processes the inputs into the format expected by the trained model.
3. Generates a prediction using the saved machine learning model.
4. Converts the model's log-scale prediction back to the original cost scale.
5. Displays the estimated annual insurance cost in INR.
6. Visualizes the prediction against smoker and non-smoker average charges.

## 📂 Project Structure

```text
insurance-cost-estimator/
│
├── app.py                  # Streamlit application
├── insurance_model.pkl     # Trained ML model
├── model_features.pkl      # Model feature configuration
├── model_name.pkl          # Saved model information
├── medical_insurance.csv   # Dataset
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation
```

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/REYASHREE/insurance-cost-estimator.git
cd insurance-cost-estimator
```

### 2. Install Dependencies

```bash
pip install streamlit pandas numpy scikit-learn plotly
```

### 3. Run the Application

```bash
streamlit run app.py
```

Open the local URL displayed in your terminal to use the application.

## 📊 Input Parameters

| Parameter | Description |
|---|---|
| Age | Age of the individual |
| Sex | Male or female |
| BMI | Body Mass Index |
| Children | Number of dependent children |
| Smoker | Smoking status |
| Region | Geographic region |

## 🎯 Objective

To demonstrate how machine learning can be integrated into an interactive application to generate personalized insurance cost estimates and communicate predictions through data visualization.

## ⚠️ Disclaimer

This application is an educational machine learning project. Predictions are estimates based on the training data and should not be treated as actual insurance quotes or financial advice.

## 👩‍💻 Author

**REYASHREE**

Developed as a machine learning and data analytics portfolio project.
