# Human-Activity-Recognition-with-Smartphone-Data

## Description
This project utilizes data from a study where 30 participants performed daily activities while carrying a smartphone equipped with inertial sensors. The goal is to classify activities into six categories using machine learning techniques.

## Dataset
The **Human Activity Recognition (HAR) dataset** consists of sensor data collected from a **Samsung Galaxy S II** smartphone placed at the participant's waist. The dataset contains:
- **30 volunteers** (ages 19-48) performing six activities.
- **Six activity labels:**
  - WALKING
  - WALKING UPSTAIRS
  - WALKING DOWNSTAIRS
  - SITTING
  - STANDING
  - LAYING
- Data recorded at **50Hz** using an accelerometer and gyroscope.
- Pre-processed signals divided into training (70%) and testing (30%) sets.

## Workflow
1. **Data Preprocessing**
   - Load the dataset.
   - Handle missing values and normalize sensor readings.
   - Extract relevant features for classification.
2. **Exploratory Data Analysis (EDA)**
   - Visualize sensor readings for different activities.
   - Identify patterns in acceleration and angular velocity.
3. **Model Training & Evaluation**
   - Train various machine learning models (e.g., Decision Trees, Random Forest, SVM, Neural Networks).
   - Evaluate model performance using accuracy, precision, recall, and F1-score.
4. **Predictions & Insights**
   - Use the trained model to classify new activity data.
   
## Installation & Requirements
Ensure you have the following dependencies installed:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Running the Project
Execute the Jupyter Notebook to:
- Load and preprocess data.
- Train and evaluate models.
- Generate predictions on test data.

## Results
- Achieved **high accuracy** in classifying activities.
- Identified distinct sensor patterns for each movement category.

## Future Work
- Extend the dataset with more diverse activities.
- Implement deep learning approaches (LSTMs, CNNs) for time-series classification.

## References
- [UCI Machine Learning Repository - HAR Dataset](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)

