California Housing Price Prediction
Project Overview

This project aims to predict the median house values in various regions of California using the California Housing dataset. The predictions are based on features such as median income, house age, average number of rooms, and other relevant factors. The goal is to build and evaluate different regression models to determine which one performs best in predicting housing prices.
Dataset Description

The dataset used in this project includes the following features:

    MedInc: Median income in the region.
    HouseAge: Median house age in the region.
    AveRooms: Average number of rooms per dwelling.
    AveBedrms: Average number of bedrooms per dwelling.
    Population: Total population in the region.
    AveOccup: Average number of occupants per household.
    Latitude: Geographical latitude of the region.
    Longitude: Geographical longitude of the region.
    MedHouseVal: Median house value (Target variable).

Project Structure

    Data Exploration: Loaded the dataset, explored the basic statistics, and checked for missing values.
    Data Preprocessing: Dropped irrelevant columns and prepared the features and target variable for model training.
    Model Training: Trained several regression models including:
        RandomForestRegressor
        GradientBoostingRegressor
        DecisionTreeRegressor
        KNeighborsRegressor
    Model Evaluation: Evaluated models using metrics such as Mean Squared Error (MSE) and Mean Absolute Error (MAE).

Results

The performance of each model was evaluated, and the results were compared based on the chosen metrics. The notebook includes detailed results and analysis of each model.
Libraries Used

    numpy
    pandas
    scikit-learn

How to Run

    Clone this repository.
    Ensure you have the required libraries installed (numpy, pandas, scikit-learn).
    Open the Jupyter notebook and run all cells to see the results.

License

This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments

    The dataset was provided by Kaggle as part of the Playground Series competition.
    Thanks to the Kaggle community for providing an excellent platform for data science competitions.
