# Car-Price-Prediction
Car Price Prediction is a machine learning project that estimates the market value of a car using features such as brand, model, manufacturing year, fuel type, transmission, mileage, and engine capacity. The system is trained on historical car datasets to learn price patterns and generate accurate predictions.

In this project, a dataset containing various car features such as brand, model, manufacturing year, fuel type, transmission type, engine capacity, mileage, and number of previous owners is used. The dataset is first preprocessed by cleaning missing values, removing duplicates, and converting categorical data into numerical form using encoding techniques. After preprocessing, exploratory data analysis is performed to understand the relationship between different features and the car price. Visualization tools are used to identify trends and correlations that influence pricing.

Once the data is prepared, machine learning algorithms such as Linear Regression, Random Forest Regressor, or Decision Tree Regressor are applied to train the prediction model. The dataset is divided into training and testing sets to evaluate the model’s performance and accuracy. Different evaluation metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score are used to measure the effectiveness of the model.

The project also includes a simple and interactive user interface where users can input car details and instantly get an estimated price. This interface is developed using Streamlit, which allows the machine learning model to be deployed as a web application.

**Key Features**

* Predicts car prices based on multiple car attributes
* Data preprocessing and feature engineering for improved accuracy
* Exploratory Data Analysis (EDA) with visualizations
* Implementation of machine learning regression algorithms
* Real-time price prediction through a web interface
* Model evaluation using standard performance metrics

**Tools and Technologies Used**

* **Python** – Main programming language
* **Pandas & NumPy** – Data cleaning and manipulation
* **Scikit-learn** – Machine learning model development
* **Matplotlib & Seaborn** – Data visualization
* **Streamlit** – Web-based user interface
* **Jupyter Notebook** – Model training and experimentation
