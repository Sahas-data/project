Forecasting Air Pollution Levels in Major Cities Using Deep Learning
Project Overview
This project explores deep learning methods for forecasting PM2.5 air pollution in urban environments. It focuses on LSTM and GRU architectures and evaluates how effectively they capture temporal behaviour in long term hourly air quality records. The analysis is based on publicly available environmental data collected over multiple years.
Dataset
The dataset provides hourly PM2.5 readings along with meteorological variables including temperature, dew point, pressure, wind direction and wind speed. It spans several consecutive years, making it suitable for sequence based forecasting. The data is ethically sourced and publicly accessible.
Methodology
The workflow includes data loading, cleaning and preparation. Missing values are handled to maintain continuity. Features are scaled and encoded. Time based sequences are created to model dependencies. LSTM and GRU models are developed with a consistent architecture to allow direct comparison. Training is carried out using a supervised learning approach with clearly defined input and output sequences.
Evaluation
Performance is assessed using RMSE, MAE and R2. Prediction plots show how well the models capture pollution peaks, seasonal changes and overall trends. Both models demonstrate strong forecasting ability and produce similar patterns with comparable error metrics.
Results Summary
The LSTM model performs well in identifying both short term fluctuations and long term behaviours in PM2.5. The GRU model shows similar accuracy and captures the same general structure in the predictions. The findings indicate that both architectures are effective for time series forecasting in environmental applications.
How to Run
Install required libraries including TensorFlow, NumPy, Pandas, Matplotlib and Scikit-learn. Load the dataset in the notebook environment, run all cells in sequence and review the generated output. The notebook provides complete preprocessing, modelling, evaluation and comparison steps.
Conclusion
Deep learning models such as LSTM and GRU provide reliable performance for air pollution forecasting. They capture meaningful temporal patterns and offer valuable insight for environmental monitoring and planning.
