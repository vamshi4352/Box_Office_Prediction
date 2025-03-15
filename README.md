# Box_Office_Prediction
 
## Project Overview

This project focuses on predicting the box office revenue of movies using a combination of data cleaning, exploratory data analysis (EDA), and advanced feature engineering techniques. The goal was to build a robust predictive model that could accurately estimate a movie's box office performance.

## Data Cleaning

The data underwent extensive cleaning to ensure accuracy and consistency. This process included:

- Handling missing values
- Removing duplicates
- Correcting data types
- Standardizing text data (e.g., movie titles, names)

## Exploratory Data Analysis (EDA)

A thorough EDA was performed to understand the underlying patterns and relationships in the data. This included:

- Visualizing the distribution of box office revenue
- Analyzing correlations between features
- Identifying outliers and their impact on the predictions
- Exploring relationships between categorical variables (e.g., genre, production company) and box office performance

## Feature Engineering

To improve the predictive power of the model, several new features were engineered, including:

- **Company Success:** A metric based on the historical box office performance of the production company.
- **Director Success:** A measure of the director's past success in terms of box office revenue.
- **Lead Actor Success:** A feature capturing the lead actor's previous box office performance.
- **Producer Success:** A metric indicating the producer's historical success.
- **Binary Encoding for Popular Genres:** Genres that are popular were encoded using binary values, which helped improve the model's accuracy.

## Machine Learning used:

- **SVM**
- **Random Forest**
- **XG Boost**
- **Cat Boost**
  

## Feature Ranking

Feature ranking was performed to identify and eliminate unimportant features, enhancing the model's efficiency and accuracy. This step helped in focusing on the most impactful features while discarding those that contributed little to the prediction performance.

### Best Performing Model

The feature engineering, binary encoding of genres and Feature Ranking contributed significantly to improving the model's accuracy. The **Random Forest** model was identified as the best-performing model.

## Conclusion

This project highlights the importance of data cleaning, feature engineering, and EDA in building accurate predictive models. The combination of new features and advanced encoding techniques led to a significant improvement in the model's predictive performance.


