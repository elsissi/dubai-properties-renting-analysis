<h1> Predicting House Rental Prices in Dubai: A Machine Learning Approach </h1>

Dubai's real estate market is renowned for its dynamic nature and diverse range of properties. With rapid urbanization and a growing expatriate population, the demand for rental properties has surged. This project aims to leverage machine learning techniques to predict rental prices for houses in Dubai, using a comprehensive dataset that includes various property attributes.

<h2>Project Overview</h2>
<h3>Objectives</h3>
The primary objective of this project is to build a predictive model that can accurately estimate the rental prices of houses in Dubai based on a set of features. These features include the address, number of bedrooms, number of bathrooms, type of property, area in square feet, and other relevant attributes.

<h3>Data Collection</h3>
The dataset used in this project contains detailed information about properties available for rent in Dubai.<p> The key features include:</p>

<p><b>Address</b>: The location of the property.</p>
<p><b>Rent</b>: The rental price of the property.</p>
<p><b>Beds</b>: Number of bedrooms.</p>
<p><b>Baths</b>: Number of bathrooms.</p>
<p><b>Type</b>: Type of property (e.g., Villa, Apartment).</p>
<p><b>Area_in_sqft</b>: Area of the property in square feet.</p>
<p><b>Rent_per_sqft</b>: Rent per square foot.</p>
<p><b>Rent_category</b>: Category of rent.</p>
<p><b>Frequency</b>: Frequency of rent payment.</p>
<p><b>Furnishing</b>: Furnishing status of the property.</p>
<p><b>Purpose</b>: Purpose of the property.</p>
<p><b>Posted_date</b>: Date the property was posted.</p>
<p><b>Age_of_listing_in_days</b>: Age of the listing in days.</p>
<p><b>Location</b>: Location of the property.</p>
<p><b>City</b>: City of the property.</p>
<p><b>Latitude</b>: Latitude coordinate of the property.</p>
<p><b>Longitude</b>: Longitude coordinate of the property.</p>
<h2>Data Exploration and Visualization</h2>
<h3>Data Cleaning</h3>
The initial step involved cleaning the dataset to handle missing values, outliers, and inconsistencies. Properties with missing essential information were either imputed or removed to ensure data integrity.

<h3>Exploratory Data Analysis (EDA)</h3>
Exploratory Data Analysis (EDA) was conducted to understand the distribution of rental prices and other features.
<p>Key insights include:</p>

<p><b>Distribution of Rental Prices</b>: Rental prices exhibited a skewed distribution with a few high-value outliers.</p>
<p><b>Correlation Analysis</b>*: Strong correlations were observed between rental prices and features such as the number of bedrooms, number of bathrooms, and area in square feet.</p>
<h3>Visualization</h3>
Data visualization techniques were employed to highlight patterns and trends within the dataset.
<p>Some notable visualizations include:</p>

<p><b>Heatmaps</b>: Illustrated correlations between different features.</p>
<p><b>Boxplots</b>: Showcased the distribution of rental prices across different property types and locations.</p>
<p><b>Scatter Plots</b>: Displayed the relationship between area in square feet and rental prices.</p>
<h2>Model Building</h2>
<h3>Feature Engineering</h3>
Feature engineering was performed to create new variables that could improve the model's predictive power.
<p>For example, the Age_of_listing_in_days feature was derived from the Posted_date.</p>

<h3>Model Selection</h3>
Several machine learning models were evaluated to determine the best-performing algorithm for predicting rental prices.
<p>The models tested include:</p>

<p><b>Linear Regression</b></p>
<p><b>Random Forest Regressor</b></p>
<p><b>Gradient Boosting Regressor</b></p>
<p><b>XGBoost</b></p>

<h2>Model Evaluation</h2>
The models were evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
<p>Cross-validation techniques were employed to ensure the robustness of the models.</p>

<h2>Results</h2>
The Random Forest Regressor emerged as the best-performing model with the lowest RMSE.
<p> Key findings from the model include:</p>

<p><b>Feature Importance</b>: The most significant features impacting rental prices were the number of bedrooms, area in square feet, and location of the property.</p>
<p><b>Model Accuracy</b>: The model achieved an RMSE of approximately [insert RMSE value], indicating a good predictive accuracy.</p>
<h2>Conclusion</h2>
This project successfully developed a machine learning model to predict house rental prices in Dubai. 
<p>The model provides valuable insights into the factors influencing rental prices and can serve as a useful tool for real estate professionals and potential renters.</p>
