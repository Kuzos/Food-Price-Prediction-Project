# Food-Price-Prediction-Project
Objective: The goal of this project is to build a machine learning model capable of predicting food prices in a country experiencing a crisis.  

The file Final.ipynb includes the code and all necessary documentation, organized through an outline (table of contents) where each section is described. 

The dataset provided in the file wfp_food_prices_ukr.csv is the original dataset from the WFP Food Price Dataset.
The file Reindexed.csv contains the preprocessed dataset used for training the models.

Dataset:
The project utilizes data from the World Food Programme (WFP) Price Database, which provides comprehensive information on food prices at the country level. The dataset includes staple commodities such as maize, rice, beans, fish, and sugar, covering 98 countries and approximately 3,000 markets.
- Frequency: Reported primarily on a monthly basis as time series data.
- Historical Coverage: Some countries have data as far back as 1992, with broader availability starting from 2003 onwards.
- Source: WFP Food Price Dataset  
https://data.humdata.org/dataset/global-wfp-food-prices/resource/0f2ef8c4-353f-4af1-af97-9e48562ad5b1

Methodology: 
The notebook focuses on using machine learning regression models to predict food prices, specifically leveraging datasets for Ukraine. Analysis conducted using data for a common commodity (in my case was choosen rice). 
In this notebook, I study: 
1. Data Exploration and Preprocessing (Section 1)
    - Handling Missing data 

2. Implementing and performance comparison three models:
- Naive Forecasting (Section 2)
- Simple Feed-Forward Neural Network (FFNN) (Section 3)
- LSTM Model (Section 4)

3. Hyperparameter Optimization for LSTMs (Section 4)
- Conducting grid search experiments to fine-tune LSTM model parameters.
    - Experiment Breakdown:
    -   Evaluating different network structures.
    -   Exploring the impact of data scaling 
    -   Exploring the use of new indicators 

This structured approach aims to identify the most suitable machine learning model and configuration for accurate food price prediction under crisis conditions.
