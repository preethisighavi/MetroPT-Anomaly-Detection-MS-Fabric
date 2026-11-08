# MetroPT-Anomaly-Detection-MS-Fabric

## MetroPT Industrial Compressor Anomaly Detection

An end-to-end machine learning project for detecting abnormal behavior and potential failures in industrial air compressors.

## Project Overview

This project uses Microsoft Fabric to build an industrial predictive-maintenance workflow:

- Data preparation in a Fabric Lakehouse
- Failure-label creation from known failure periods
- Isolation Forest anomaly detection
- Model evaluation using ROC-AUC, Precision, Recall, and F1 Score
- Power BI dashboard for anomaly trends and maintenance insights

## Model Results

The model was evaluated on 200,000 records:

| Metric | Result |
|---|---:|
| ROC-AUC | 0.979 |
| Precision | 53.1% |
| Recall | 84.9% |
| F1 Score | 65.3% |

## Tools and Technologies

- Microsoft Fabric
- Fabric Lakehouse
- PySpark
- Python
- Scikit-learn
- Isolation Forest
- Power BI
- GitHub

## Dashboard Features

- Daily anomaly trends
- Anomalies by severity
- Model performance metrics
- Top anomalies requiring attention
- Interactive severity filtering

## Future Enhancement

Add a Generative AI assistant to summarize anomalies and recommend maintenance actions when a paid Fabric capacity is available.

## Project Status

Completed: ML pipeline, evaluation, and interactive Power BI dashboard.
