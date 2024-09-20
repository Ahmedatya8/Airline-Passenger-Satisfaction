# Rental Bikes Count Prediction:
## Overview:
This project focuses on predicting bike rental counts (hourly or daily) based on various environmental and seasonal  settings.   Using a dataset of bike rentals, the project applies different machine learning models to forecast rental demand, considering   factors such as weather conditions, temperature, humidity, and time of year.
## Project Structure:
- Exploratory Data Analysis (EDA): Insights into the dataset using visualization and statistical summaries.
- Feature Engineering: Preprocessing and transforming the data to improve model performance.
- Modeling: Training various machine learning models to predict bike rental counts, including:
	- Linear Regression
	- Decision Tree Regressor
	- Random Forest Regressor
	- Support Vector Regressor (SVR)
	- Gradient Boosting Regressor
	- XGBoost Regressor
	- K-Nearest Neighbors Regressor (KNN)
- Model Evaluation: Assessing model performance using metrics like R² score and Mean Absolute Error (MAE).
- Hyperparameter Tuning: Optimizing model performance using GridSearchCV or RandomizedSearchCV to fine-tune the parameters of models such as Random Forest, Gradient Boosting, and XGBoost.
## Installation:
To install the required libraries for this project, run the following commands:
``` python
!pip install numpy
!pip install pandas
!pip install matplotlib
!pip install seaborn
!pip install datasist
!pip install scikit-learn
!pip install xgboost
```
## Usage:
1. Clone the repository:</br>
	``` python
	git clone https://github.com/ahmedatya8/rental-bikes-prediction.git
 
3. Navigate to the project directory:
    ``` python
	cd rental-bikes-prediction
5. Install the required libraries (see the installation section).
6. Run the notebook or Python scripts to explore and train models.

## Data:
The dataset contains historical records of bike rentals, with features such as:
- Date and time of rental.
- Temperature, humidity, windspeed, etc.
- Seasonal and weather information.


## Models:
The following machine learning models were used:
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **K-Nearest Neighbors Regressor**
- **Support Vector Regressor**
- **Gradient Boosting Regressor**
- **XGBoost Regressor**
## Evaluation:
The models are evaluated using several metrics, including:
- R² Score: Measures how well the model predicts the variance in the target.
- Mean Absolute Error (MAE): Provides an average of the errors in predictions.
## Results:
The best-performing model in this project was XGBoost Regressor, which achieved an R² score of 0.9509 and an MAE of 19.6358.
## Contributing:
Contributions are welcome! Feel free to submit a pull request or raise an issue if you have suggestions.
