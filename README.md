Federated Learning for Network Intrusion Detection System (IDS)
A comprehensive federated learning framework for network intrusion detection using the UNSW-NB15 dataset. This system implements FedAvg aggregation with trust-based weighting mechanisms and advanced data preprocessing capabilities.

🚀 Features

Federated Learning Framework: Built on NVIDIA FLARE with custom aggregation and training strategies
Trust-Based Weighting: Manual trust score configuration for client reliability assessment
Advanced Data Preprocessing: Feature selection, outlier handling, and standardization
Multi-Client Support: Scalable architecture supporting  any number of federated clients (3-12 in this system)
Comprehensive Evaluation: Detailed performance metrics and visualization
Real-time Monitoring: Round-by-round performance tracking and comparison

🚀 Running the System
bash
nvflare simulator -w /path/to/workspace -n 5 -t 5
