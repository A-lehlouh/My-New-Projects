#  Car Price Prediction Web App

This is an interactive web application built using **Streamlit** that predicts the price of a used car based on user inputs like manufacturer, production year, fuel type, engine volume, mileage, and more. The prediction is made using a **Random Forest Regressor** model trained on historical car pricing data.

---

##  Features

-  Predict used car prices using machine learning
-  User-friendly interface built with **Streamlit**
-  Categorical data is handled automatically using one-hot encoding
-  Real-time data visualizations using **Matplotlib**
-  Three key visualizations included:
  - **Bar chart** of car counts by manufacturer
  - **Line chart** of average price by production year
  - **Scatter plot** showing price vs. mileage

---

##  Technologies Used

- Python
- Streamlit
- Pandas
- Scikit-learn
- Matplotlib

---

### Project Structure

car-price-prediction/
├── app.py                      
├── car_price_prediction.csv   
├── requirements.txt            
├── encoded_data.xlsx          
├── README.md                  
└── models/
    └── rf_model.pkl           
