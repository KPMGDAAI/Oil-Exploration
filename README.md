# Oil Exploration Probability Using Regression Modeling

## How to Use This Repository

This repository contains everything needed to predict the probability of oil exploration success using seismic data and machine learning. The repository is structured as follows:

### DATA

This folder contains the CSV files with seismic data that include geological features and location information. These files are essential for training and testing the machine learning model.

### NOTEBOOK

This folder includes the notebook, which walks through the process of loading data, feature engineering, training the regression model, and evaluating the predicted probabilities of oil exploration success.

### DASHBOARD

This folder contains scripts and visualizations that help analyze the exploration probabilities, providing insights through an interactive dashboard.

----------

## Business Use Case

![enter image description here](https://i.pinimg.com/736x/60/60/f2/6060f272a12cc311bc7dfe6d13a19caa.jpg)

Accurate prediction of oil exploration success is crucial for optimizing resources and improving the efficiency of exploration efforts. This project helps:

-   **Predict the probability of discovering hydrocarbons** at different locations using seismic data.
-   **Make data-driven decisions** for oil exploration, reducing time and cost by focusing on high-probability areas.
-   **Provide visual insights** through interactive dashboards that highlight promising exploration sites.

----------

## Project Structure
![enter image description here](https://i.pinimg.com/736x/44/da/14/44da1474bff6159da1fe39c7b4eba7ca.jpg)
### Step 1: Loading and Analyzing Seismic Data

The first step is to load the seismic data into a pandas DataFrame. This data includes features such as amplitude, wave velocity, and fault presence, which are critical to predicting the probability of hydrocarbon presence.

### Step 2: Engineering Features

In this step, additional features are created to improve the model's predictive power. The notebook explains how to engineer features like `Amplitude_to_Reflection_Ratio`, `Normalized_Travel_Time`, and `Fault_Influence` to capture more meaningful patterns in the data.

### Step 3: Training the Regression Model

This step involves training a regression model to predict the probability of hydrocarbon presence at different locations based on the seismic features. The notebook provides details on splitting the data, training the model, and evaluating its performance.

### Step 4: Visualizing Results

Once the model has been trained, the results are visualized. The notebook guides you through creating a table of locations with predicted probabilities and their categories (e.g., High Probability, Low Probability).

----------

## Dashboard
![enter image description here](https://i.pinimg.com/736x/e1/60/b4/e160b4b384d41defb5b635cb1aea80e1.jpg)


The dashboard section provides visual insights into the model's predictions. You can interact with the exploration data, view high-probability sites, and filter locations based on probability categories.

----------

## Conclusion

This project demonstrates how machine learning, coupled with seismic data analysis, can enhance decision-making in oil exploration. The model helps ADNOC prioritize exploration sites based on predicted hydrocarbon presence, ensuring more efficient exploration and resource allocation.
