# AML Transaction Risk Scoring & Customer Alert Prioritisation

## Project Overview
A Python-based Anti-Money Laundering (AML) portfolio project that demonstrates transaction risk scoring, customer risk profiling, and alert prioritisation using synthetic financial transaction data.

The analysis covers 5,000 transactions across 989 unique customers and applies rule-based indicators to identify transactions that may require further review.

## Objectives
- Identify potentially higher-risk transactions using rule-based indicators.
- Calculate transaction risk scores using weighted risk factors.
- Categorise transactions and customers by risk level.
- Generate a prioritised transaction alert queue.
- Summarise customer-level risk indicators for analyst review.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- GitHub

## Risk Indicators
- High transaction amount
- Simulated high transaction frequency
- Politically Exposed Person (PEP) indicator
- Synthetic high-risk-country flag
- Previous alert indicator

## Key Results
- **5,000** transactions analysed
- **989** unique customers
- **16** High-risk transactions identified by the rules
- **16** High-risk customers identified by the rules
- **85** transactions associated with High-risk customers

These results reflect the project's illustrative scoring rules. They do not establish that any transaction or customer is involved in money laundering.

## Project Files
- `AML_Transaction_Risk_Scoring_System.ipynb` — Python analysis and risk-scoring workflow.
- `aml_transactions_v2.csv` — transaction data with derived risk scores and indicators.
- `aml_customer_risk_summary_v2.csv` — customer-level risk summary.
- `aml_transaction_alert_queue_v2.csv` — prioritised transaction alert queue.

## Limitations
- The dataset is synthetic and intended for educational use.
- The high-risk-country flag is randomly simulated and does not represent an actual country-risk assessment.
- Transaction frequency is simulated, not calculated from real transaction timestamps.
- Risk weights and thresholds are illustrative and are not institution-specific standards.
- The model has not been validated against confirmed suspicious-activity outcomes.

## Disclaimer
This project demonstrates a basic, rule-based AML monitoring approach for learning and portfolio purposes. In a real financial institution, alert investigation and any
