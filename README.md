# Linear-Regression-Housing-

Overview

This project implements a Linear Regression Model to predict house prices based on square footage, number of bedrooms, and number of bathrooms. The model is trained and evaluated using scikit-learn and visualized with Matplotlib & Seaborn.

Dataset

The dataset used for this project contains information about houses, including:

square_footage: Total area of the house.
bedrooms: Number of bedrooms.
bathrooms: Number of bathrooms.
price: The actual price of the house (target variable).

Dependencies

Ensure you have the following Python libraries installed:
pip install pandas numpy matplotlib seaborn scikit-learn

Project Structure

House-Price-Prediction/
│-- Housing.csv         
│-- house_price_model.py  
│-- README.md             



Model Performance

After training, the model is evaluated using:
-Mean Absolute Error (MAE)
-Mean Squared Error (MSE)
-Root Mean Squared Error (RMSE)
-R² Score (Coefficient of Determination)

Results Visualization

A scatter plot with a regression trendline is used to compare actual vs. predicted house prices.

How to Run the Project

1)Clone this repository:
  git clone https://github.com/YOUR_USERNAME/House-Price-Prediction.git

2)Navigate to the project folder:
  cd House-Price-Prediction

3)Run the script:
  python house_price_model.py

Contributing
Feel free to fork this repository and improve the model or visualization!

License
This project is open-source and available under the MIT License.
