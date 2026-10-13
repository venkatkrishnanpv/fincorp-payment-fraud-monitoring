# FinCorp Datasets

This folder contains synthetic banking and payment
transaction datasets used for fraud monitoring and
risk analytics.

## Database Tables
1. customers
2. banks
3. accounts
4. cards
5. devices
6. merchants
7. beneficiaries
8. transactions

## Data Organization
- raw/ — Original synthetic datasets before cleaning
- processed/ — Cleaned and validated datasets for analysis

## Data Standards
- All records are synthetic; no real customer
  information is used.
- Foreign-key relationships must be validated.
- Data-quality issues are documented before correction.
- Fraud ground-truth labels are maintained separately
  from detection features.
- Large datasets and sensitive configuration files
  must not be committed unnecessarily.
