1.Summary: This project's goal was to develop a ML model to predict daily energy consumption in buildings based on features like square footage, number of occupants and building type.

2.Results: The final model (final_model.pkl) is a linear regression model fit on the target variable (energy_concumption), transformed by means of a Boxcox transformation, and the features building type, encoded by the one hot encoding technique, square footage, number of occupants and appliances used. All predictor variables were sccaled down to z-scores. The final r-squared was close to 100%, and the normalized RMSE (RMSE/standard deviation of y) was around 0.01.

3.Approach:

3.1-DW: Data Wrangling

  3.1.1-Input: energy_data.csv (raw data)
  
  3.1.2-Output: wrangled_data.csv
  
3.2-EDA: Exploratory Data Analysis and Visualization

  3.2.1-Input: wrangled_data.csv
  
  3.2.2-Output: analyzed_data.csv
 
3.3-MDE: Model Development and Evaluation

  3.3.1-Input: analyzed_data.csv
  
  3.3.2-Output: final_model.pkl

3.4-Deliverable: A function to generate predictions based on the developed model.
