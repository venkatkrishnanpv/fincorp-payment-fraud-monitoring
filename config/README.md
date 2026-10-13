# Project Configuration

This folder contains configuration files for the
FinCorp Payment Fraud Monitoring & Risk Analytics System.

## Planned Configuration

- Random seed for reproducible data generation
- Customer, account, card and transaction volumes
- Simulation start and end dates
- Customer spending behaviour parameters
- Fraud scenario generation parameters
- Risk signal definitions and scoring weights
- Risk classifications and alert thresholds
- Development, validation and test periods

## Standards

- Configuration settings must be reproducible.
- Fraud generation and detection must remain independent.
- Final test data must not be used for threshold tuning.
- Passwords and database credentials must never be committed.

Actual configuration values will be defined
during project development.
