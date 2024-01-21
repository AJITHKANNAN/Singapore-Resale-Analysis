**Project Summary:** Resale Price Prediction for Singaporean Flats

**Objective**:
Develop a machine learning model and deploy a user-friendly web application to predict the resale prices of flats in Singapore. The model will be based on historical data of resale flat transactions and aims to assist both potential buyers and sellers in estimating the resale value of a flat.

**Motivation**:
The Singaporean resale flat market is highly competitive, making it challenging to accurately estimate resale values. This project addresses this issue by leveraging historical transaction data to create a predictive model that factors in location, flat type, floor area, and lease duration.

**Data Source** : https://beta.data.gov.sg/collections/189/view


**Scope**:

**Data Collection and Preprocessing:**

Collect and preprocess resale flat transaction data from the Singapore Housing and Development Board (HDB) spanning from 1990 to the present.
Clean and structure the data for machine learning, handling missing values, outliers, and ensuring data quality.

**Feature Engineering:**

Extract relevant features from the dataset, including town, flat type, storey range, floor area, flat model, and lease commence date.
Create additional features to enhance prediction accuracy, such as the age of the flat or proximity to amenities.

**Model Selection and Training:**

Choose an appropriate regression model (e.g., linear regression, decision trees, or random forests) based on the dataset's characteristics.
Split the dataset into training and testing sets and train the selected model using a portion of the data.

**Model Evaluation:**

Assess the model's predictive performance using regression metrics (MAE, MSE, RMSE, R2 Score).
Refine the model if necessary, considering feature importance and potential overfitting.

**Streamlit Web Application:**

Develop a Streamlit web application for users to input flat details (town, flat type, storey range, etc.).
Utilize the trained machine learning model to predict resale prices based on user inputs.
Deploy the application on the Render platform for internet accessibility.

**Testing and Validation:**

Thoroughly test the deployed application to ensure correct functionality and accurate predictions.
Validate model predictions against real-world resale prices to verify reliability.
Address identified issues and make necessary refinements.
