# FinCorp — Payment Fraud Monitoring & Risk Analytics System

### End-to-End Banking Transaction Fraud Detection and Risk Analytics

**Technologies:** MySQL | Python | Pandas | NumPy | Matplotlib | Seaborn | Power BI | DAX | GitHub

**Project Status:** In Development

## 1. Project Overview

FinCorp is a portfolio project focused on developing an end-to-end payment fraud monitoring and risk analytics system using synthetic banking transaction data.

The project simulates customer banking behaviour, payment transactions and fraudulent activities across interconnected database tables.

It aims to demonstrate how SQL, Python and business intelligence tools can support transaction monitoring, fraud risk identification, data quality management and analytical decision-making.

All customer and transaction data used in this project will be synthetic.

## 2. Business Problem

Financial institutions process large volumes of transactions across multiple payment channels.

Detecting suspicious transactions is challenging because fraudulent activities may resemble legitimate customer behaviour.

A fraud monitoring system must balance two competing objectives:

- Identify potentially fraudulent transactions.
- Minimize unnecessary alerts affecting genuine customers.

The project investigates how customer transaction history, behavioural deviations and explainable risk rules can help identify suspicious payment activity.

## 3. Project Objectives

1. Design a relational banking and payment transaction database.
2. Generate realistic synthetic customer and transaction behaviour.
3. Implement data quality and referential integrity checks.
4. Perform exploratory analysis using SQL and Python.
5. Develop behavioural fraud detection features.
6. Build an explainable rule-based risk scoring system.
7. Evaluate detection performance using time-based data partitions.
8. Develop interactive Power BI dashboards.
9. Document business findings, system limitations and recommendations.

## 4. Database Architecture

The planned database includes eight interconnected tables:

| Table | Description |
|---|---|
| customers | Customer profiles and demographic attributes |
| banks | Issuing and acquiring bank information |
| accounts | Customer bank accounts |
| cards | Debit and credit card details |
| devices | Customer-associated transaction devices |
| merchants | Merchant information and categories |
| beneficiaries | Payment beneficiary information |
| transactions | Payment activity across banking channels |

The database schema and relationships will be finalized and documented during implementation.

## 5. Project Methodology

**Phase 1 — Database Design and Data Quality**

Design database relationships, validate data integrity and establish data quality controls.

**Phase 2 — Synthetic Data Generation and Exploratory Analysis**

Simulate customer behaviour, generate legitimate transactions, introduce fraud scenarios and investigate transaction patterns.

**Phase 3 — Fraud Detection and Risk Scoring**

Calculate historical transaction features, implement fraud detection rules and assign explainable risk scores.

**Phase 4 — Detection Performance Evaluation**

Measure precision, recall, F1 score, false positives and false negatives using time-based development, validation and test datasets.

**Phase 5 — Power BI Reporting**

Develop interactive dashboards for executive monitoring, fraud pattern analysis and detection performance evaluation.

## 6. Planned Fraud Detection Signals

- High transaction amount relative to customer behaviour
- Repeated failed transactions
- High transaction velocity
- Unusual transaction hours
- New or unfamiliar devices
- New beneficiaries
- Unusual transaction locations
- Multiple suspicious signals within a transaction

Risk signals will be calculated from available transaction information without using confirmed fraud labels as detection inputs.

## 7. Power BI Dashboard Plan

**Page 1 — Executive Fraud Overview**

Transaction volumes, transaction values, confirmed fraud, alerts and trends.

**Page 2 — Fraud Patterns and Risk Analysis**

Behavioural anomalies, transaction channels, fraud scenarios and risk distribution.

**Page 3 — Detection Performance**

Confusion matrix, precision, recall, F1 score, missed fraud and false-positive analysis.

## 8. Repository Structure

```text
config/       Simulation and risk settings
data/         Synthetic datasets
docs/         Technical and business documentation
images/       Diagrams and dashboard screenshots
notebooks/    Exploratory analysis notebooks
powerbi/      Power BI reports and DAX documentation
sql/          Database and analytical SQL scripts
src/          Python source code
tests/        Automated quality and validation tests
```

## 9. Evaluation Approach

The project will use chronological data partitions to separate development, threshold tuning and final performance testing.

The evaluation will consider both fraud detection effectiveness and the operational cost of unnecessary alerts.

Actual performance results will be published after validation is completed.

## 10. Project Limitations

The system uses simulated financial transactions rather than production banking data.

Synthetic fraud patterns may not fully represent real-world fraud behaviour, adversarial adaptation or changing customer activity.

Detection metrics will therefore demonstrate performance within the simulated environment and should not be interpreted as production banking performance.

## 11. Project Deliverables

- Relational MySQL database and data dictionary
- Reproducible synthetic transaction generator
- SQL data quality and analytical queries
- Python fraud detection and risk scoring pipeline
- Detection validation and error analysis
- Three-page Power BI dashboard
- Technical documentation and business recommendations

---

**Project Type:** Data Analytics | Financial Risk Analytics | Fraud Monitoring

**Development Tools:** MySQL Workbench, Python, Jupyter Notebook, Power BI and GitHub

**Author:** Venkat Krishnan PV
