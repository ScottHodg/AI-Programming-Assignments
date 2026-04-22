# **Abalone Sex Classification Model**

This project aims to predict the sex of an abalone (Male, Female, or Infant) using physical measurements. It is part of the Winter 2026 AI Programming course at Ontario Tech University.

## **Project Overview**

The task involves using the UCI Abalone dataset to perform programmatic data analysis and deep learning. The project specifically addresses:

* **Data Splitting**: Partitioning the dataset into 50% training and 50% validation sets.

* **Baseline Model**: Training a "poor" Deep Neural Network (DNN) to establish a performance baseline.

* **Optimization**: Training an optimized Sequential DNN using Keras to achieve higher predictive accuracy for the 'Sex' attribute.

## **Dataset Features**

The model utilizes the following features from the abalone.data file:

* Length  
* Diameter  
* Height  
* Whole weight  
* Shucked weight  
* Viscera weight  
* Shell weight

## **Implementation Details**

The solution is implemented in Abalone Scott.ipynb and includes:

* **Preprocessing**: Categorical mapping of sex labels (M, F, I) and feature scaling using StandardScaler.

* **Visualization**: Architectural plots of the developed models.

* **Video Walkthrough**: A recorded explanation of the implementation is available.
