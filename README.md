# Description
A classification model built in python that can forecast the likelihood of specific crimes occurring in designated locations to individuals, providing residents with proactive insights to enhance their safety

# Methodology
The project methodology employs machine learning techniques to analyze patterns within the compiled crime and weather datasets, training a model to identify and classify potential crimes. This process involves cleaning the data, selecting features, and applying algorithms to predict the likelihood of different types of crimes occurring

# Data Collection
The project's data was gathered from two main sources using APIs. Crime data was obtained from the Los Angeles Police Department (LAPD), detailing incidents dating back to 2020. This dataset provides a comprehensive look at various crimes within the city. Weather data was sourced from Visual Crossing, offering insights into the potential impact of weather on crime occurrences. Together, these datasets form a rich basis for analyzing crime patterns in relation to weather conditions, aiming to predict crime types more effectively

Crime Data: https://catalog.data.gov/dataset/crime-data-from-2020-to-present

Weather Data: https://www.visualcrossing.com/weather/weather-data-services

# Objective
The objective of this project is to construct and evaluate various machine learning models capable of classifying and predicting the types of crimes occurring in Los Angeles, based on weather patterns and historical crime data. The classification models to be employed and evaluated for their predictive accuracy include the Decision Tree, Random Forest, ANN and XGBoost algorithms In pursuing this aim, the project entailed the following key steps:

*Conducting a thorough exploratory data analysis to uncover underlying patterns and insights within the crime and weather datasets
-Implementing data preprocessing techniques including data cleaning, categorical variable conversion, and handling missing values to refine the dataset for modeling
-Employing feature selection methods such as Lasso regression to pinpoint the most impactful predictors for the classification models.
-Adopting dimensionality reduction strategies like Principal Component Analysis (PCA) to concentrate on the most informative features and improve model efficiency
-Comparing the effectiveness of the chosen models, focusing on metrics such as accuracy, precision, and recall to identify the most accurate model for crime type prediction

# Steps taken to build the models
* Data Exploration
* Data Preparation
* Modelling
* Model Evaluation
* Model Selection
* Model Fine-Tuning

# Results
The Random Forest model outperformed other models with the highest accuracy, reaching 57%. This model exhibited robustness across various metrics, achieving strong precision, recall, and F1-Score. These high scores indicate that the model was effective in minimizing both false positives and negatives, crucial for reliable crime type classification




