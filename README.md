# Financial Fraud Detection using Spark
## Overview
This project aims to develop a system for detecting financial fraud in payment services using Apache Spark. Financial fraud is a significant issue in the banking and financial industry, leading to substantial financial losses and damages to both businesses and customers. Detecting fraudulent activities promptly is crucial for minimizing these losses and maintaining trust in financial systems.

## Features
- Data Preprocessing: The project involves preprocessing large volumes of transaction data to extract relevant features and prepare the data for model training.
- Model Development: Various machine learning algorithms, such as logistic regression, random forest, or gradient boosting, are implemented using Spark's MLlib library to build predictive models for fraud detection.
- Model Evaluation: The trained models are evaluated using appropriate metrics such as accuracy, precision, recall, and F1-score to assess their performance in detecting fraudulent transactions.
- Scalability: Leveraging the distributed computing capabilities of Apache Spark, the system can handle large volumes of transaction data with high scalability and performance.
## Requirements
- Apache Spark: The project requires Apache Spark for distributed data processing and machine learning.
- Python (or Scala): Programming language for implementing Spark jobs and data analysis.
- Data: High-quality transaction data containing both legitimate and fraudulent transactions for model training and testing.
## Usage
- Data Preprocessing: Use the provided scripts to preprocess the transaction data, including feature extraction and data transformation.
- Model Training: Train the machine learning models using Spark's MLlib library with the preprocessed data.
- Model Evaluation: Evaluate the trained models using relevant metrics to assess their performance.
## Contributors
- Nguyen Truong Duy (22DAI): Team Leader
- Pham Hoang Long (22DAI): Team Member
- Do Quoc Dat (22DAI): Team Member
## License
This project is licensed under the MIT License - see the http://www.apache.org/licenses/ file for details.
