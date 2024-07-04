
# Movie Rating Prediction

![Movie Rating Prediction]("https://github.com/Soumyabk3/CODSOFT/blob/main/Task2%20Codsoft/Images/Movie%20Rating%20Prediction.png)

## Problem Statement

- Build a model that predicts the rating of a movie based on
features like genre, director, and actors. You can use regression
techniques to tackle this problem.

- The goal is to analyze historical movie data and develop a model
that accurately estimates the rating given to a movie by users or
critics.

- Movie Rating Prediction project enables you to explore data
analysis, preprocessing, feature engineering, and machine
learning modeling techniques. It provides insights into the factors
that influence movie ratings and allows you to build a model that
can estimate the ratings of movies accurately.

## Introduction

With this project, we hope to develop a model that uses past data to predict movie ratings. The goal is to create a model that can accurately forecast movie ratings by looking at factors such as actors, directors, and genre.

## Dependencies

To run this project, you need to install the following Python libraries:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn
- IPython
- Plotly
- Warnings



## Installation

To install the specified packages (numpy, pandas, matplotlib, seaborn, scikit-learn, and ipython) and generate a requirements.txt file, follow these steps:


1. *Installing Dependencies*:

```bash
   pip install numpy pandas matplotlib seaborn scikit-learn ipython plotly

```
 
2. *To look at the dependencies type the command on the cmd*:

```bash
pip list

```
or

```bash
   pip show numpy pandas matplotlib seaborn scikit-learn ipython plotly

```

3. * you can use the pip freeze command to get a list of all installed packages along with their versions*:

```bash
pip freeze

```

```bash
 txt
ipython==8.4.0
matplotlib==3.5.2
numpy==1.22.4
pandas==1.4.2
scikit-learn==1.1.1
seaborn==0.11.2
```

## Load the data set from Kaggle website:

```bash
https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies

```





## Summary
- Here we loaded Dependencies

- Data Collection: Data Loading the dataset from a CSV file

- Get the shape and basic information of the dataset:

- Check and handle missing and redundant values:

- Data Preprocessing

- Data Analysis

- Data Visualization
    Various visualizations provide insights into the data and model performance:

    Distribution plots for understanding the spread of ratings.
    Correlation matrix to see how features are interrelated.
    Histograms and line plots to explore temporal and categorical trends.

- Feature Endgineering

- Model Building:
    The predictive model is built using scikit-learn:

    Splitting the data into training and testing sets.
    Normalizing numerical features using StandardScaler.
    Implementing a LinearRegression model.

- Model Training:
    Train the logistic regression model

- Model Evaluation:
    The model's performance is evaluated using metrics such as:

    Mean Squared Error (MSE)
    Mean Absolute Error (MAE)
    R-squared (R²)

- Prediction

## Conclusion
The project successfully demonstrates the steps involved in building a machine learning model for predicting movie ratings. The thorough data cleaning, preprocessing, feature engineering, and visualization ensure a robust analysis, leading to more accurate predictions
## Authors

- [@Soumyabk3](https://github.com/Soumyabk3)

