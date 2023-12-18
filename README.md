# Dwello-Real-estate-Price-Prediction

**Dwello** is the name of our project.

**Dataset**: The data is collected from the official website of Zillow, an American tech real-estate marketplace company.
The dataset contains features like:
* zipcode
* county
* City
* State
* columns with date in the format yyyy-mm-dd from the year 2000 to 2023 for every month. Column name examples: 2001-05-29, 2010-03-29. These columns contain the price of the zip code in the respective date of the column.

**Objective**: The goal is to design a webpage that allows users to input a zip code and a specific year. The webpage will then provide a prediction of the real estate value for that zip code in the specified year. When the user enters a zip code, we extract the city, state, county of that zip code, and other features to predict the price. After predicting the price, we map and display the price for the given zip code on interactive maps. Machine Learning model used to predict the price is Linear Regression.

**Technologies used**: Python(pandas, numpy, matplotlib, scikit-learn, flask-ngrok, folium, pyngrok==4.1.1, geopy, pgeocode), HTML
