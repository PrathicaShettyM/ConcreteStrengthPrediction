# Concrete Strength Prediction

![Concrete](https://img.icons8.com/ios-filled/50/000000/concrete.png)

## Project Overview
This project leverages machine learning to predict the compressive strength of concrete based on its mix ingredients and age. The model is deployed using a Flask server and a Streamlit client for user interaction. Users can input the mix proportions and get the predicted concrete strength.

## Features
- 🔧 **Machine Learning Model**: Utilizes XGBoost for accurate strength predictions.
- 🌐 **Flask Server**: Handles backend processes and model inference.
- 📊 **Streamlit Client**: Provides a user-friendly interface for input and prediction visualization.
- 🔍 **Feature Engineering & EDA**: Comprehensive Exploratory Data Analysis and feature engineering for improved model performance.

## Table of Contents
1. [Installation](#installation)
2. [Running the Application](#running-the-application)
3. [Input Fields](#input-fields)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)

## Installation

### Create Virtual Environment (Windows)
1. Install virtual environment using bash:
    ```sh
    py -m venv myvenv
    ```
2. Activate virtual environment:
    ```sh
    myvenv\Scripts\activate
    ```
3. Install pip:
    ```sh
    py -m ensurepip --upgrade
    ```
4. Install `ipykernel` for Jupyter Notebook:
    ```sh
    pip install ipykernel
    ```

## Running the Application
1. Install all the packages in the terminal after activating the virtual environment:
    ```sh
    pip install flask streamlit requests scikit-learn xgboost joblib
    ```
2. Run the Flask server:
    ```sh
    python flask_app.py
    ```
3. Run the Streamlit frontend:
    ```sh
    streamlit run streamlit_app.py
    ```

## Input Fields

The application takes the following input fields for user data:

![Input](https://img.icons8.com/ios-filled/50/000000/submit-for-approval.png)
- **Cement** (kg/m³)

- **Blast Furnace Slag**  (kg/m³)

- **Fly Ash**  (kg/m³)

- **Water**  (kg/m³)

- **Superplasticizer**  (kg/m³)

- **Coarse Aggregate**  (kg/m³)

- **Fine Aggregate**  (kg/m³)

- **Age**  (kg/m³)

## Usage
1. Enter the mix proportions and age of the concrete.
2. Click on the "Predict" button.
3. The model will predict and display the compressive strength of the concrete.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or additions.

## License
This project is licensed under the MIT License.

---