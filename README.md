# Laptop Price Prediction Using Machine Learning
Welcome to the Laptop Price Prediction repository! This project aims to predict the price of laptops based on various features using machine learning techniques and deploy the model using Streamlit for an interactive user interface.
<a href="https://laptop-price-prediction-stream-lit.streamlit.app/">Live Prediction Web-App Link</a>

### Overview
This project uses a machine learning model to predict the price of laptops. The prediction is based on several features, such as company, type, RAM, weight, touchscreen capability, IPS display, CPU brand, HDD, SSD, operating system, and GPU brand.

### Model
***The model is built using the following steps:***

- Data Preprocessing: Handling missing values, encoding categorical variables, and scaling numerical features.
- Feature Engineering: Creating new features or transforming existing features to improve model performance.
- Model Training: Using regression algorithms such as Linear Regression, Random Forest, or Gradient Boosting to train the model.
- Model Evaluation: Evaluating the model's performance using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

### Deployment
***The model is deployed using Streamlit to provide an interactive web interface for users. The app.py file contains the code for the Streamlit app, which includes:***

- User input forms for all the features.
- Data preprocessing steps applied to the user inputs.
- Model loading and prediction.
- Display of the predicted laptop price.
