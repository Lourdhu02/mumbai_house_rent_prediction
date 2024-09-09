# House Rent Prediction in Mumbai

This repository contains a Jupyter Notebook for predicting house rents in Mumbai, India using machine learning techniques. The dataset used includes various features such as house size, type, location, price, and more.

## Dataset

The dataset contains information on:

- **House Type**: Type of house (e.g., 2 BHK Apartment)
- **House Size**: Size of the house in square feet
- **Location**: Specific locality within Mumbai
- **Price**: Rent price of the house
- **Number of Bathrooms**: Count of bathrooms in the house
- **Number of Balconies**: Count of balconies
- **Is Negotiable**: Whether the rent is negotiable or not
- **Verification Date**: When the house listing was verified
- **Security Deposit**: Security deposit amount
- **Furnishing Status**: Whether the house is furnished, semi-furnished, or unfurnished

## Project Overview

This project utilizes machine learning to predict house rents based on the available features in the dataset.

### Steps involved:

1. **Data Preprocessing**:
   - Import and clean the dataset.
   - Handle missing values and format features.
   
2. **Exploratory Data Analysis**:
   - Analyze the dataset to understand relationships between features and rent prices.

3. **Modeling**:
   - Use machine learning models like Random Forest Regressor to predict house rents.
   - Split the data into training and testing sets.
   - Train the model and evaluate its performance using metrics like Mean Squared Error (MSE) and R-squared score.

4. **Results Visualization**:
   - Visualize the results of the predictions using plots to compare actual vs predicted rents.

## Requirements

- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`

To install the required libraries, run:
```bash
pip install -r requirements.txt
```

## How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/house-rent-prediction.git
    ```

2. Navigate to the project directory and open the Jupyter notebook:
    ```bash
    jupyter notebook House_Rent.ipynb
    ```

3. Follow the steps in the notebook to explore the data, preprocess it, and train the model.

## Future Improvements

- Expand the dataset to include other cities.
- Experiment with other machine learning models to improve prediction accuracy.
- Deploy the model using Flask or Streamlit for real-time rent predictions.

