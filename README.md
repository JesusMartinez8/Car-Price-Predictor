Car Price Predictor

This is a machine learning project which takes data of electric cars and manipulates it in order to accurately predict the price of a car with different elements.
Utilizing Jupyter Notebook along with Python, the 

The dataset used in this project contains the following columns:

Name: Name of the electric car model
Drive: Type of drive (Front Wheel Drive, Rear Wheel Drive, All Wheel Drive)
Number of Seats: Number of seats in the car
Acceleration (sec): Acceleration time from 0 to 100 km/h (in seconds)
Top Speed (km/h): Maximum speed of the car in kilometers per hour
Range (km): Range of the car in kilometers on a full charge
Efficiency (Wh/km): Efficiency of the car in watt-hours per kilometer
Fast Charge Speed (km/h): Fast charging speed of the car in kilometers per hour
Price (UK): Price of the car in the UK market (target variable)

Preprocessing
Removed missing values from the dataset.
Converted categorical variables into numerical format.
Removed outliers from the target variable.

Models Used
Linear Regression
Random Forest Regressor
Gradient Boosting Regressor
XGBoost Regressor

Evaluation
Evaluated the models using R-squared score.
Random Forest Regressor achieved the highest R-squared score among the models.
GUI Application
Implemented a Tkinter GUI application for predicting car prices based on user input.
The user can input various attributes of the electric car, and the application predicts the price using the trained Random Forest Regressor model.

Files
electricCars.csv: Dataset containing information about electric cars.
electricCar_price_predictor: Trained Random Forest Regressor model saved using joblib.
electric_car_price_prediction.py: Python script containing the code for preprocessing, training, evaluating models, and creating the Tkinter GUI application.
Usage
Clone the repository to your local machine.
Install the required dependencies using pip install -r requirements.txt.
Run the electric_car_price_prediction.py script to preprocess the data, train the models, and create the GUI application.

Requirements
Python 3.x
Pandas
NumPy
Scikit-learn
XGBoost
Tkinter (for GUI application) OR pip install ipywidgets
