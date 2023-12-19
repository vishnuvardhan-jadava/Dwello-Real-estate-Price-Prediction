# Dwello-Real-estate-Price-Prediction

**Dwello** is the name of our project.

**Dataset**: The data is collected from the official website of Zillow, an American tech real-estate marketplace company.
The dataset contains features like:
* zipcode
* county
* City
* State
* columns with date in the format yyyy-mm-dd from the year 2000 to 2023 for every month. Column name examples: 2001-05-29, 2010-03-29. These columns contain the price of the zip code in the respective date of the column.
  
  The size of the dataset is (26368, 294).

**Objective**: The goal is to design a webpage that allows users to input a zip code and a specific year. The webpage will then provide a prediction of the real estate value for that zip code in the specified year. When the user enters a zip code, we extract the city, state, county of that zip code, and other features to predict the price. After predicting the price, we map and display the price for the given zip code on interactive maps. Machine Learning model used to predict the price is Linear Regression.

**Technologies used**: Python(pandas, numpy, matplotlib, scikit-learn, flask-ngrok, folium, pyngrok==4.1.1, geopy, pgeocode), HTML

Sample images of how the Project's front end looks like.

<img width="954" alt="image" src="https://github.com/vishnuvardhan-jadava/Dwello-Real-estate-Price-Prediction/assets/83878754/98e9712c-2599-41ba-92e0-62bd7d929183">


<img width="924" alt="image" src="https://github.com/vishnuvardhan-jadava/Dwello-Real-estate-Price-Prediction/assets/83878754/4c51dbc1-c42d-4ca6-9d52-c6cd539644dc">


<img width="827" alt="image" src="https://github.com/vishnuvardhan-jadava/Dwello-Real-estate-Price-Prediction/assets/83878754/7e6454d5-9587-4520-b4af-fdc72a5e3aee">


<img width="713" alt="image" src="https://github.com/vishnuvardhan-jadava/Dwello-Real-estate-Price-Prediction/assets/83878754/3e253a18-737e-4708-a62d-7682e879808d">


<img width="767" alt="image" src="https://github.com/vishnuvardhan-jadava/Dwello-Real-estate-Price-Prediction/assets/83878754/954b59dc-d49c-4ae2-9a92-9bfb3fe3c7ce">



