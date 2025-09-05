UNSW-NB15 Dataset link: https://research.unsw.edu.au/projects/unsw-nb15-dataset

Federated Learning for Network Intrusion Detection System (IDS)
A comprehensive federated learning framework for network intrusion detection using the UNSW-NB15 dataset. This system implements FedAvg aggregation with trust-based weighting mechanisms and advanced data preprocessing capabilities.

🚀 Features

Federated Learning Framework: Built on NVIDIA FLARE with custom aggregation and training strategies
Trust-Based Weighting: Manual trust score configuration for client reliability assessment
Advanced Data Preprocessing: Feature selection, outlier handling, and standardization
Multi-Client Support: Scalable architecture supporting  any number of federated clients (3-12 in this system)
Comprehensive Evaluation: Detailed performance metrics and visualization
Real-time Monitoring: Round-by-round performance tracking and comparison

📊 Data Preprocessing Pipeline

1. Feature Engineering

Original Features: 44 network traffic features
Target Features: Configurable (default: 25)
Feature Selection Methods:

Variance threshold filtering
Correlation-based redundancy removal
Statistical significance testing (F-test)
Random Forest importance ranking

2. Data Quality Improvements

Duplicate Removal: Configurable retention ratio
Outlier Handling: Multiple methods (robust clipping, IQR, Winsorization)
Standardization: Robust scaling for federated consistency
Class Balancing: Weighted loss functions and optional SMOTE

🚀 Running the System

bash

nvflare simulator -w /path/to/workspace -n 5 -t 5


