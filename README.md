# Machine Learning App with Streamlit

A web-based machine learning application built with Streamlit that implements Random Forest Regression with customizable hyperparameters.

## Features

- Upload your own CSV data or use the built-in California housing dataset
- Interactive parameter tuning via sidebar controls
- Real-time model performance metrics including:
  - R² score (coefficient of determination)
  - Mean squared error (MSE)
  - Training/test set evaluation
- Responsive wide layout for better viewing experience
- Model parameter inspection

## Getting Started

### Prerequisites

- Python 3.6+
- pip package manager

### Installation

1. Clone the repository:
   
   git clone https://github.com/Kiranwaqar/MachineLearningApp.git
   
2. Install the required packages:

   pip install -r requirements.txt
   
3. Running the App
   Launch the application with:

   streamlit run mlapp.py

   The app will automatically open in your default web browser at http://localhost:8501.

### Usage

1. Parameter Tuning:

   Adjust data split ratio between training and test sets

   Modify Random Forest hyperparameters including:

     Number of estimators

     Max features

     Minimum samples split/leaf

     Performance criterion

2. View Results:

    See dataset overview

    Examine model performance metrics

    View final model parameters


### Example Dataset
The app comes with the California housing dataset as a built-in example. This dataset contains features like:

MedInc - median income in block group

HouseAge - median house age in block group

AveRooms - average number of rooms per household

AveBedrms - average number of bedrooms per household

Population - block group population

AveOccup - average number of household members

Latitude - block group latitude

Longitude - block group longitude

The target variable is the median house value for California districts.
