

This repository contains a **cloud-based transaction monitoring service** built to demonstrate backend engineering practices used in financial systems. The application exposes a REST API that receives transaction data, evaluates it against fraud detection rules, and returns a decision indicating whether the transaction should be **approved automatically or flagged for manual review**. The system is designed using a **serverless architecture**, allowing the application to process requests without maintaining traditional infrastructure while still providing scalable and reliable transaction processing.

The project emphasizes clean backend design, modular Python development, and cloud service integration. It reflects common patterns used in modern fintech platforms where incoming events are processed by lightweight compute services and stored in managed databases. This implementation focuses on demonstrating practical skills relevant to software engineering roles, including API development, cloud deployment, rule-based data processing, and automated testin

* Python Backend Logic – Implements transaction evaluation and fraud detection rules
* AWS Lambda** – Handles incoming requests and executes fraud analysis logic
* Amazon API Gateway – Provides REST endpoints for submitting and retrieving transactions
* Amazon DynamoDB – Stores processed transaction records for retrieval and auditing
* Fraud Detection Rules – Evaluates transaction amount, geographic risk, velocity patterns, and account activity
* Automated Unit Testing – Uses pytest to validate fraud detection behavior across multiple scenarios
* Modular Code Structure – Separates configuration, rule evaluation, utilities, and API logic
* Sample Transaction Dataset – Provides multiple realistic transaction scenarios for testing and demonstration
