# Student Score Prediction

This project demonstrates how to use linear regression to predict student scores based on the number of hours studied. The dataset consists of two columns: the number of hours studied and the corresponding percentage score achieved. This project follows the standard machine learning workflow, including data inspection, visualization, modeling, and evaluation.

## Table of Contents

- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Project Steps](#project-steps)
  - [1. Import Libraries](#1-import-libraries)
  - [2. Load and Inspect Data](#2-load-and-inspect-data)
  - [3. Visualize Data](#3-visualize-data)
  - [4. Prepare Data for Modeling](#4-prepare-data-for-modeling)
  - [5. Train the Model](#5-train-the-model)
  - [6. Make Predictions](#6-make-predictions)
  - [7. Evaluate the Model](#7-evaluate-the-model)
  - [8. Visualize Predictions](#8-visualize-predictions)
- [How to Run ?](#how-to-run-?)
- [Contribution](#contribution)

## Project Overview

This project uses linear regression to model and predict student scores based on their study hours. We follow a step-by-step approach, including data loading, exploration, visualization, model training, and evaluation.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook (for running the notebook)
- Libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`

### Installation

1. **Clone the Repository**:
   ```
   git clone https://github.com/your-username/Student-Score-Prediction.git
   cd Student-Score-Prediction
   ```
2. **Set Up the Environment**:
   Create and activate a virtual environment
   ```
   python -m venv myenv
   source myenv/bin/activate  # On Windows use: myenv\Scripts\activate
   ```
4. **Install Dependencies**:
   Install the required libraries:
   ```
   pip install -r requirements.txt
   ```

## Project Steps

1. **Import Libraries**
   We begin by importing the necessary libraries for data manipulation, visualization, and machine learning.
   
2. **Load and Inspect Data**
   The dataset is loaded from a remote URL, and basic information is displayed. This includes checking the first few rows, descriptive statistics, and missing values.
   
3. **Visualize Data**
   We create a scatter plot to visualize the relationship between the number of hours studied and the percentage score. This helps us understand the distribution and trend in the data.
   
4. **Prepare Data for Modeling**
   The data is prepared for modeling by separating features (`X`) and the target variable (`y`). We then split the data into training and test sets.
   
5. **Train the Model**
    We train a linear regression model using the training data and print the model's coefficients and intercept.
   
6. **Make Predictions**
    Using the trained model, we make predictions on the test set and compare them to the actual values.
    
7. **Evaluate the Model**
    We evaluate the performance of the model using metrics such as Mean Absolute Error (`MAE`), Mean Squared Error (`MSE`), Root Mean Squared Error (`RMSE`), and R-squared (`R²`) score.
    
8. **Visualize Predictions**
    We visualize the model's predictions by plotting the regression line along with the actual data points. This helps in understanding how well the model's predictions align with the actual values.

## How to Run ?

1. **Clone the Repository**
   ```
   git clone https://github.com/your-username/Student-Score-Prediction.git
   cd Student-Score-Prediction
   ```
   
2. **Set Up the Environment**
   Create and activate a virtual environment:
   ```
   python -m venv myenv
   source myenv/bin/activate  # On Windows use: myenv\Scripts\activate
   ```
   
3. **Install Dependencies**
   Install the required libraries:
   ```
   pip install -r requirements.txt
   ```
   
4. **Run the NoteBook**
   Open the Jupyter notebook and execute the cells in sequence:
   ```
   jupyter notebook
   ```

## Contribution

If you find this project helpful or interesting, please give it a star! ⭐️

Your support is greatly appreciated and helps to keep the project going.
