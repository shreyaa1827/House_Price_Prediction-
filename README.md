# House Price Prediction

A machine learning project that predicts house prices based on property features such as location, area, number of bedrooms, bathrooms, and other relevant attributes.

## 📌 Project Overview

The **House Price Prediction** project uses machine learning techniques to estimate the price of a house from its characteristics.

The project includes data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and prediction.

## 🚀 Features

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Feature selection and engineering
* Machine learning model training
* Model evaluation
* House price prediction
* Streamlit web application for interactive predictions

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation
* **NumPy** – Numerical computations
* **Matplotlib / Seaborn** – Data visualization
* **Scikit-learn** – Machine learning
* **Streamlit** – Web application

## 📂 Project Structure

```text
House-Price-Prediction/
│
├── data/
│   └── house_data.csv
│
├── app.py
├── model.py
├── train.py
├── requirements.txt
├── README.md
└── model.pkl
```

> The exact files may differ depending on your project structure.

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

If you don't have a `requirements.txt` file yet:

```bash
python -m pip install pandas numpy matplotlib seaborn scikit-learn streamlit
```

## ▶️ Running the Application

Start the Streamlit application using:

```bash
python -m streamlit run app.py
```

After starting the application, Streamlit will provide a local URL, usually:

```text
http://localhost:8501
```

Open that URL in your web browser.

## 🧠 Machine Learning Workflow

The project follows these steps:

1. Load the house-price dataset.
2. Clean missing and incorrect values.
3. Perform exploratory data analysis.
4. Select relevant features.
5. Split the data into training and testing sets.
6. Train a machine learning regression model.
7. Evaluate the model using appropriate regression metrics.
8. Save the trained model.
9. Use the model to predict house prices through the Streamlit application.

## 📊 Model Evaluation

The model can be evaluated using metrics such as:

* **Mean Absolute Error (MAE)**
* **Mean Squared Error (MSE)**
* **Root Mean Squared Error (RMSE)**
* **R² Score**

The best model is selected based on its performance on the test dataset.

## 🖥️ Streamlit Application

The Streamlit interface allows users to enter property details and receive an estimated house price.

Example inputs may include:

* Location
* Property area
* Number of bedrooms
* Number of bathrooms
* Number of floors
* Parking availability
* Property type
* Other relevant features

After entering the required information, the application displays the predicted house price.

## 📈 Future Improvements

* Improve model accuracy through hyperparameter tuning
* Add more property-related features
* Compare multiple regression algorithms
* Add interactive data visualizations
* Deploy the Streamlit application online
* Continuously update the model with new housing data


## 👨‍💻 Author
Varhadi Shreya 
