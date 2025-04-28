# DataScience-Project
Prediction and Optimization of Energy Usage in Smart Grids :
This project is about predicting how much energy will be used in the future by a smart grid (the system that delivers electricity). The idea is to predict when the grid will have high energy demand, so the energy companies can prepare in advance. This helps save energy, reduce waste, and make the grid work better.
I have used past data (how much energy was used before) to train a machine to predict how much energy will be used in the future. This helps us figure out when energy consumption will be high or low.

Optimized Energy Usage:
Once we know when the grid will be under high demand, we can make decisions to save energy:
For example, we can encourage people to use energy at different times, like early in the morning or at night, when the demand is lower.
We could also raise prices during peak times to make people use less electricity during those periods.

Evaluated the Model:
We checked how accurate the model was by comparing its predictions with the real energy consumption data. If the model's predictions were close to the actual usage, we can say the model works well.
Real-World Impact:
For energy companies: They can use this model to know when the demand will be high and plan accordingly (like storing extra energy or making sure enough energy is available during peak hours).

For consumers: They could save money by using energy during off-peak times (when the energy price is lower), and they might be encouraged to use less energy when it's most needed by the grid.

The main outcome of this project is that we built a machine learning model that predicts when the demand for electricity will be high.
This helps optimize energy usage by guiding people to use energy during low-demand times and helping energy companies balance the grid better, reducing waste and saving money.
In simple terms, we built a tool that helps predict when energy will be used the most, so everyone can use it more wisely!


This project uses machine learning to predict energy usage and optimize smart grid performance.
By forecasting household energy consumption, we aim to:

Reduce energy wastage
Improve grid efficiency
Help energy companies manage resources better

Dataset :
Source: UCI Machine Learning Repository
Period: December 2006 to November 2010 (47 months)
Measurements: Household energy consumption recorded every minute
Features:
Date, Time
Global active/reactive power
Voltage, Current
Energy usage in Kitchen, Laundry, Water-heater

Note: 1.25% of the data has missing values, which were handled during preprocessing.

Methodology : 
Data Cleaning:
Missing values filled with the median.
Combined 'Date' and 'Time' into a 'Datetime' column.
Feature Engineering:
Created lag features (previous values) to capture time-based patterns.
Scaled the data where necessary.

Model Training:
Trained and compared multiple machine learning models:
Linear Regression
Random Forest
Artificial Neural Network (ANN)
Gradient Boosting

Evaluation Metrics:
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)

Visualizations
Plotted Actual vs Predicted energy usage for all models.
Showed how energy consumption changes over time.

Ethical Considerations
The dataset used is public and does not contain private information.
Future real-time projects should ensure user privacy and data security.
