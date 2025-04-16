# Multi-Agent System for AML Fraud Detection

![GitHub License](https://img.shields.io/badge/license-MIT-blue) ![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen)

## Overview

This project demonstrates a **multi-agent system** for detecting fraudulent transactions and uncovering potential money laundering activities. It integrates four key functionalities into a single Python script:

1. **SQL Agent**: Filters transactions exceeding $10,000.
2. **Rule-Based Agent**: Flags suspicious transactions based on predefined AML rules (e.g., high-risk countries, unusual amounts).
3. **Machine Learning Agent**: Detects anomalies using DBSCAN clustering.
4. **Visualization Agent**: Creates an interactive network graph to visualize flagged transactions.

This project is designed as a **practice exercise** to simulate how AML systems work in real-world banking scenarios.

---

## Table of Contents

1. [Project Objectives](#project-objectives)
2. [Features](#features)
3. [Dataset](#dataset)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)

---

## Project Objectives

The goal of this project is to:
- Automate the detection of suspicious transactions using SQL-like filtering.
- Apply predefined AML rules to flag red flags.
- Use machine learning algorithms to detect hidden patterns and anomalies.
- Provide clear visualizations of transaction networks for deeper investigation.

---

## Features

- **SQL Agent**: Filters transactions exceeding $10,000.
- **Rule-Based Agent**: Flags transactions involving high-risk countries or unusually large amounts.
- **Machine Learning Agent**: Detects anomalies using DBSCAN clustering.
- **Visualization Agent**: Generates a directed graph to visualize flagged transactions and relationships.

---

## Dataset

The dataset used in this project simulates real-world banking transactions. Here’s a sample of the input data:

| customer_id | transaction_id | transaction_date | amount | transaction_type | country         |
|-------------|----------------|------------------|--------|------------------|-----------------|
| 1           | T001           | 2023-01-01       | 12000  | wire             | US              |
| 2           | T002           | 2023-01-02       | 15000  | cash             | US              |
| 1           | T003           | 2023-01-03       | 25000  | wire             | Cayman Islands  |
| 3           | T004           | 2023-01-04       | 8000   | cash             | US              |
| 2           | T005           | 2023-01-05       | 17000  | wire             | Cayman Islands  |

Key Fields:
- `customer_id`: Unique identifier for each customer.
- `transaction_id`: Unique identifier for each transaction.
- `transaction_date`: Date when the transaction occurred.
- `amount`: The dollar value of the transaction.
- `transaction_type`: Type of transaction (e.g., wire transfer, cash).
- `country`: The country where the transaction originated or terminated.

You can download the dataset (`transactions.csv`) from the repository.

---

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/priyakashyap/aml-fraud-detection.git
   cd aml-fraud-detection
   
2.Install the required dependencies:
pip install pandas scikit-learn networkx matplotlib

3.Run the python script:
aml_fraud_detection.py

## Expected Output:

Filtered Transactions : Transactions exceeding $10,000.
Flagged Transactions : Transactions flagged based on AML rules.
Anomalies Detected : Transactions identified as anomalies by DBSCAN clustering.
Visualization : A directed graph showing flagged transactions and their connections.

## Contributors

We would like to thank the following individual for their valuable contributions to this project:

- **Deepak** ([@deepakusername](https://github.com/deepakusername)) for their insights, guidance, and support.

## License

This project is licensed under the MIT License . See the LICENSE file for details.

## Contact

Have questions or want to collaborate? Feel free to reach out:

Email: priyakashyapp007@gmail.com  

GitHub: ([@priyakashyap](https://github.com/PriyaKashyapp))

LinkedIn: https://www.linkedin.com/in/priyaa-kashyapp/
 
















