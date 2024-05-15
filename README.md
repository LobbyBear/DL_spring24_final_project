# Deep Learning Final Project: Stock Price Prediction

This repository contains the code and report for a deep learning final project focused on predicting stock prices using transformer-based models. The project leverages historical stock price data obtained from Yahoo Finance and implements a custom transformer model for time series prediction.

## Project Structure

- **dl_final_project.ipynb**: Jupyter Notebook containing the complete code for data processing, model implementation, training, and evaluation.
- **report.pdf**: PDF document providing a detailed analysis and discussion of the project, including methodology, results, and conclusions.
- **README.md**: This file, providing an overview of the project and instructions for usage.

## Getting Started

To run the code in `dl_final_project.ipynb` and reproduce the results, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your_username/deep-learning-final-project.git

2. **Open and Run the Notebook:**

Open dl_final_project.ipynb in Jupyter Notebook or JupyterLab. Execute the cells sequentially to load data, preprocess it, build the model, train the model, and generate predictions.

3. **View the Report:**

Refer to report.pdf for a detailed report on the project, including methodology, experimental setup, results, and insights.

## Project Overview

The project involves the following key components:

- **Data Retrieval and Preprocessing**: Historical stock price data is fetched from Yahoo Finance, preprocessed, and normalized for training the model.
- **Transformer-based Model**: A custom transformer model is implemented using TensorFlow/Keras to predict future stock prices based on historical data.
- **Training and Evaluation**: The model is trained on a portion of the data and evaluated using a held-out test set. Metrics such as Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) are computed for evaluation.
- **Report and Analysis**: The findings and insights from the project are summarized in the report.pdf document.

## Results and Discussion

The trained model achieves competitive performance in predicting stock prices, as demonstrated in the evaluation section of the notebook. Further details and analysis can be found in the accompanying report.

## Acknowledgements

- **Project Authors:** Runqi Chen and Luyi Ge
- **Yahoo Finance API**: Data for this project was obtained using the YahooFinance library.
