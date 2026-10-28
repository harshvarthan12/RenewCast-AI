# RenewCast AI – Renewable Energy Generation Forecasting

## Project Information

- **Student Name:** HARSHAVARTHAN S
- **Register Number:** RA2411047050063
- **Department:** B.Tech Artificial Intelligence
- **Project Topic:** Dynamic Microgrid Renewable Energy Generation Forecasting
- **Project Type:** Deep Learning Mini Project

## 1. Project Overview

RenewCast AI is a simple deep learning project that forecasts solar power generation using historical energy generation data. It uses a Long Short-Term Memory (LSTM) neural network to learn patterns in past solar power readings and predict future power generation.

The project is implemented using Python and Google Colab.

## 2. Objectives

- To understand renewable energy generation forecasting.
- To analyze historical solar power generation data.
- To build a simple LSTM-based forecasting model.
- To compare actual and predicted solar power generation.
- To evaluate the model using error metrics.

## 3. Technologies Used

- Python
- Google Colab
- TensorFlow / Keras
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## 4. Dataset

The project uses a publicly available photovoltaic (PV) generation dataset.

**Dataset source:** [PV Generation Dataset on GitHub](https://github.com/upb-nlp/PV-Generation-Dataset)

The notebook uses the `active_power_kw` column to forecast solar power generation from historical readings.

## 5. Methodology

1. Load the solar power generation dataset.
2. Select and preprocess the power generation readings.
3. Normalize the data using Min-Max scaling.
4. Create input sequences using the previous 24 hours of readings.
5. Train an LSTM neural network.
6. Predict solar power generation for unseen time steps.
7. Evaluate predictions using MAE and RMSE.
8. Plot actual versus predicted values.

## 6. How to Run the Project

1. Open [Google Colab](https://colab.research.google.com/).
2. Select **File → Upload notebook**.
3. Upload `RenewCast_AI.ipynb`.
4. Run the code cell.
5. Wait for the dataset to load and the model to train.
6. View the evaluation metrics and prediction graphs.

An internet connection is required to load the dataset from GitHub.

## 7. Model Evaluation

The model is evaluated using:

- **MAE (Mean Absolute Error):** Measures the average absolute difference between actual and predicted values.
- **RMSE (Root Mean Squared Error):** Measures prediction error while giving larger errors more weight.

The notebook displays the calculated metric values after training.

## 8. Expected Output

- Model training and validation loss graph.
- Actual versus predicted solar power generation graph.
- MAE and RMSE evaluation results.
- CSV file containing prediction results.
- Saved trained LSTM model.

## 9. Applications

- Solar power generation forecasting.
- Renewable energy planning.
- Microgrid energy management research.
- Understanding time-series forecasting with deep learning.

## 10. Limitations

This is a basic educational prototype. It uses historical power generation readings and does not include a complete microgrid simulation, battery optimization, or real-time weather forecasting. Prediction accuracy depends on the dataset and model training.

## 11. Future Scope

- Include weather information such as temperature and solar irradiance.
- Compare LSTM with Transformer-based models.
- Extend forecasting to wind power generation.
- Integrate predictions into a microgrid energy management system.

## 12. Conclusion

RenewCast AI demonstrates how deep learning can be applied to renewable energy forecasting. The LSTM model learns patterns from historical solar power generation readings and produces predictions that can be evaluated against actual values.

This project provides a beginner-friendly introduction to time-series forecasting and its potential applications in renewable energy systems.
