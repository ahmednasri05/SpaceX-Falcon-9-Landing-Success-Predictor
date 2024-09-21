# Falcon 9 First Stage Landing Prediction Capstone

This project aims to predict the successful landing of the Falcon 9 rocket's first stage, a key factor in reducing launch costs. SpaceX significantly lowers launch expenses by reusing the first stage, making their rockets more competitive compared to other providers. By predicting the success of first-stage landings, we can estimate launch costs and use this information to assist other companies in bidding against SpaceX for rocket launches.

## Project Overview

The cost of a Falcon 9 rocket launch is approximately $62 million, significantly lower than the $165 million charged by other providers. This cost advantage is largely due to the reusable nature of the first stage of the rocket. This project develops a machine learning model to predict whether the first stage will successfully land, based on various factors. The prediction can assist other companies in evaluating their bid strategy when competing with SpaceX.

The project is divided into seven Jupyter notebooks:

1. **Data Collection via RESTful APIs**  
   Collect launch data from public APIs, including details such as rocket specifications, launch site, and mission success.
   
2. **Web Scraping for Additional Data**  
   Use web scraping techniques to gather additional data points that may not be available via APIs, further enriching the dataset.

3. **Data Wrangling**  
   Perform essential data preprocessing tasks, including:
   - One-hot encoding for categorical variables
   - Replacing missing values
   - Normalization and standardization of numerical data to ensure uniform scaling.

4. **Exploratory Data Analysis (EDA) with SQLite**  
   Analyze the dataset using SQL queries for structured data exploration. Investigate relationships between variables to gain initial insights.

5. **EDA with Seaborn and Visualization Tools**  
   Utilize data visualization libraries (Seaborn, Matplotlib) to:
   - Explore variable correlations
   - Apply feature engineering techniques to identify important predictors of first-stage landing success.

6. **Geospatial Analysis with Folium**  
   Leverage Folium for interactive mapping and geospatial analysis, examining how demographic factors and safety measures influence landing success.

7. **Model Development and Evaluation**  
   Build and evaluate machine learning classification models to predict first-stage landing success. This notebook covers:
   - Model training
   - Hyperparameter tuning
   - Selecting the best-performing model based on evaluation metrics like accuracy, precision, recall, F1-score, and AUC.
     

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ahmednasri05/SpaceX-Falcon-9-Landing-Success-Predictor.git
