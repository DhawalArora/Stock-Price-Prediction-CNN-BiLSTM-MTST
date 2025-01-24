# Stock Price Prediction using CNN-BiLSTM and MTST Models

## Project Overview
This project aims to predict stock price trends for Tesla, GE, Apple, and Nvidia using **CNN-BiLSTM** and **MTST** models. The models are trained on historical stock data and evaluated using metrics like **MAPE**, **RMSE**, and **Cumulative Returns**.

## Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/DhawalArora/Stock-Price-Prediction-CNN-BiLSTM-MTST.git

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt

4. Run the scripts:

  - data_preprocessing.py: Preprocess the stock data.
     ```bash
     python data_preprocessing.py

  - model_training.py: Train the CNN-BiLSTM and MTST models.
     ```bash
     python model_training.py

  - evaluation.py: Evaluate the models and generate results.
     ```bash
     python evaluation.py

## Results
Figure 1: Predicted vs. Actual Stock Prices.

Table 1: Performance Metrics (MAPE, RMSE, Cumulative Returns)


---

## Repository Structure
- data_preprocessing.py: Downloads, cleans, and preprocesses stock data.
- model_training.py: Builds and trains the CNN-BiLSTM and MTST models.
- evaluation.py: Evaluates the models and generates visualizations.
- requirements.txt: Lists the required Python libraries.
- README.md: Explains the project and how to run the code.


README.md: Explains the project and how to run the code.
---

## Contributors
- Dhawal Arora
- Pang Chern Hong
