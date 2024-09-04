# Predicting Oil Reservoirs with CNN - Upstream Use Case

## How to Use This Repository



This repository contains all the components necessary for predicting potential oil reservoirs using seismic data with a **Convolutional Neural Network (CNN)**. The structure of the repository is as follows:

-   **Data**: This folder contains the **seismic_with_calculated_features.csv** file. This dataset includes seismic features such as amplitude, wave velocity, reflection strength, and several calculated features like seismic impedance. These features are crucial inputs for the CNN model to make predictions about the presence of oil reservoirs.
    
-   **Notebook**: This folder contains the Jupyter notebook that walks you through the entire process, from loading the data to transforming it and training a CNN to predict the likelihood of oil presence.
    
-   **Dashboard**: This folder includes the Power BI Dashboards.
    

## Business Use Case

 Accurate identification of potential oil reservoirs is critical for optimizing upstream oil exploration, reducing exploration costs, and increasing drilling success rates. This project leverages seismic data and advanced deep learning techniques to:

-   Predict the likelihood of oil reservoirs based on seismic data, allowing for more targeted and efficient drilling operations.
-   Reduce financial risks associated with unnecessary drilling by improving the accuracy of predictions.
-   Provide valuable insights into subsurface conditions through feature engineering and data visualization.

## Project Structure



### Step 1: Loading and Analyzing Seismic Data


The first step involves loading seismic data into a pandas DataFrame. This dataset forms the foundation for the analysis and prediction model. Instructions for loading the dataset are provided in the notebook, including a detailed view of the raw seismic data.

### Step 2: Enhancing the Data with Calculated Features

Once the data is loaded, the next step is creating calculated features such as **Seismic Impedance**, **Amplitude-to-Reflection Strength Ratio**, and **Fault Influence**. These features add valuable insights to the dataset, enabling the CNN to make more accurate predictions.

### Step 3: Exploring the Data and Visualizing Patterns

This step guides you through visualizing relationships between seismic features using heatmaps and distribution plots. Understanding these relationships helps to identify patterns that could indicate oil presence, providing crucial insights for decision-making.

### Step 4: Building and Training the CNN Model

In this step, the notebook walks you through building the CNN model. You'll learn how to structure the data for CNN input, construct convolutional and pooling layers, and use a **Dense Layer** for classification. This model is key for analyzing seismic data and predicting the presence of oil reservoirs.

### Step 5: Evaluating and Visualizing Predictions

After training the CNN, you will evaluate the model's performance using accuracy metrics. The notebook helps you visualize the training process, the performance of the model on test data, and the predicted likelihood of oil presence compared to actual results. This step ensures the model is robust and reliable.

## Dashboard



## Conclusion

This project demonstrates how seismic data, combined with feature engineering and deep learning using CNNs, can significantly improve oil reservoir predictions. By integrating data analysis, feature transformations, and predictive modeling, this approach enables more informed upstream exploration decisions, ultimately saving time, resources, and costs for the oil industry.
