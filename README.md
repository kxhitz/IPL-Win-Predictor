# IPL-Win-Predictor
IPL Win Predictor
Overview
The IPL Win Predictor is a web-based application designed to predict the winning probability of a cricket team during an IPL match. By inputting match-related data such as the batting and bowling teams, host city, target score, current score, overs completed, and wickets lost, the app provides a percentage prediction of the likelihood of each team's victory.

Features
Predicts win probabilities based on real-time match input.
Supports all IPL teams and a variety of host cities.
User-friendly interface developed with Streamlit.
Powered by machine learning models trained on IPL data.
Files in the Repository
1. app2.py

This is the main Streamlit application script. It includes:

The user interface with dropdowns, input fields, and buttons.
Real-time probability calculations based on match data.
Integration with a pre-trained machine learning model (pipe.pkl) for predictions.
2. File.ipynb

Contains the exploratory data analysis (EDA) and preprocessing steps that were performed to prepare the dataset for model training.

3. WinPredictor.ipynb
Details the machine learning model development, training, and evaluation process. The notebook documents:

The model architecture and hyperparameters.
Performance metrics and validation.
Serialization of the trained model using pickle.
Requirements
To run the application, ensure the following dependencies are installed:

bash

streamlit
pandas
pickle
How to Run
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/ipl-win-predictor.git
cd ipl-win-predictor
Install the required libraries:

bash
Copy code
pip install -r requirements.txt
Ensure the serialized model file (pipe.pkl) is in the same directory.

Run the Streamlit app:

bash
Copy code
streamlit run app2.py
Open the app in your browser (usually http://localhost:8501).

