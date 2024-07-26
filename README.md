This project is dedicated to forecasting the Natural Rubber (NR) industry using advanced machine learning techniques. Here’s a detailed summary based on the notebooks and content found in the repository:

Data Cleaning and Preprocessing:

HS_code_Cleaning.ipynb and NR_Cleaning.ipynb: These notebooks focus on cleaning the datasets related to HS codes and Natural Rubber. They handle missing values, standardize data formats, and prepare the data for further analysis.
Dataset Exploration:

NR_Dataset Explore.ipynb and NR_Dataset.ipynb: These notebooks are used for exploring the datasets. They provide visualizations and statistical summaries to understand the distribution and relationships within the data, which are crucial for building accurate forecasting models.
Model Training:

RNN_NRNet.ipynb: Implements a Recurrent Neural Network (RNN) for forecasting NR exports. RNNs are well-suited for time series data due to their ability to maintain temporal dependencies.
Transformer_NRNet.ipynb: Utilizes Transformer models, which have shown superior performance in various time series forecasting tasks due to their attention mechanism that captures long-term dependencies more effectively.
Attention_NRNet.ipynb: This notebook focuses on models with attention mechanisms, which help improve the prediction accuracy by focusing on the most relevant parts of the input sequence.
Analysis of Results:

NR_result_analysis.ipynb: This notebook is dedicated to analyzing the performance of the models. It compares the predictions against actual values and uses metrics like MAE (Mean Absolute Error) and RMSE (Root Mean Square Error) to evaluate model accuracy.
The project comprehensively covers the entire pipeline from data cleaning to model evaluation, showcasing the use of various state-of-the-art techniques in time series forecasting. 
