# credit-card-fraud-detection 
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. It includes data preprocessing, exploratory data analysis (EDA), and model training with a Random Forest classifier. The goal is to identify patterns in the data that distinguish legitimate transactions from fraudulent ones.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [File Structure](#file-structure)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
Credit card fraud detection is a critical task in financial systems to prevent unauthorized transactions. This project uses a dataset of credit card transactions to train a machine learning model (Random Forest) to classify transactions as fraudulent or legitimate. The project includes:
- Data preprocessing and visualization.
- Feature engineering and correlation analysis.
- Model training and evaluation.
- Saving the trained model for future use.

- ## file structure
- credit-card-fraud-detection/
│
├── data/
│   └── creditcard.csv           # Dataset for training and testing
│
├── src/
│   ├── preprocess.py            # Script for data preprocessing
│   └── train_model.py           # Script for training the Random Forest model
│
├── saved_models/
│   ├── logistic_model.pkl       # Saved Logistic Regression model (if applicable)
│   └── random_forest_model.pkl  # Saved Random Forest model
│
├── README.md                    # Project documentation
├── requirements.txt             # List of dependencies
├── class_distribution.png       # Visualization of class distribution
├── correlation_heatmap.png      # Correlation heatmap of features
└── pca_visualization.png        # PCA visualization of the data
