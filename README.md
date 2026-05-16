# Midas
Project repo for the JPMC Advanced Software Engineering Forage program

# About This Project
Midas Core is a backend financial transaction processing system built with **Spring Boot** and **Apache Kafka**. It simulates a real-world event-driven architecture where transactions are consumed from a Kafka topic, validated, processed, and persisted to a database.

# Tasks Completed

# Task 1 — Project Setup
- Set up the Spring Boot project structure
- Configured Maven dependencies and application properties

# Task 2 — Kafka Consumer
- Implemented a Kafka listener to consume transaction events
- Configured consumer group, deserializers, and topic bindings

# Task 3 — Transaction Processing
- Validated sender and recipient existence
- Enforced balance checks before processing
- Updated balances and persisted records to H2 database

# Task 4 — Incentive API Integration
- Integrated with an external Incentive REST API using RestTemplate
- Applied incentive amounts to recipient balances
- Stored incentive data in TransactionRecord
- **Final Answer: Wilbur's balance = 3089**

# Task 5 — REST API Controller
- Exposed a GET /balance endpoint on port 33400
- Accepts userId as a request parameter
- Returns a JSON-serialized Balance object
- Returns 0 if user does not exist

# Completion Certificate
<img width="1755" height="1240" alt="JP Morgan Virtual Internship _completion_certificate" src="https://github.com/user-attachments/assets/ce933adf-edf7-4777-b018-15548853a09a" />
