# Task Statement 5.1: Explain Methods to Secure AI Systems

# Methods to Secure AI Systems

## AI System Vulnerabilities

- **Training Data Manipulation**: Attackers may inject malicious data into training datasets, altering model predictions (e.g., labeling fraudulent transactions as non-fraudulent).
- **Adversarial Inputs**: Subtle, crafted modifications to input data can cause models to misclassify (e.g., altering images to bypass facial recognition).
- **Model Inversion**: Attackers infer sensitive training data by repeatedly querying the model and analyzing outputs.
- **Model Extraction**: Attackers use input-output pairs to recreate or reverse-engineer the original model.
- **Prompt Injection (for LLMs)**: Malicious prompts are used to manipulate model behavior or extract sensitive information.

## Security Best Practices

- **Access Control**
  - Apply the principle of least privilege for all data and model access.
  - Configure strict permissions and block public access.
- **Data and Artifact Encryption**
  - Encrypt data and model artifacts to add a layer of protection.
- **Model Access Limitation**
  - Restrict and monitor access to deployed models to prevent reverse engineering.
- **Input Validation**
  - Inspect and validate all user input for unusual or malicious patterns.
  - Implement detection for known attack patterns (e.g., prompt injection).
- **Output Restriction**
  - Limit information provided in model outputs to prevent leakage of sensitive details.
- **Adversarial Training**
  - Train models with adversarial examples to improve robustness against attacks.
- **Frequent Retraining**
  - Regularly retrain models on new, clean data to mitigate the impact of corrupted training data.
- **Validation and Monitoring**
  - Maintain a separate validation dataset and validate models after each retraining.
  - Routinely scan and monitor data for quality and anomalies before training.
- **Anomaly Investigation**
  - Investigate significant changes in model predictions to determine if caused by data quality issues or attacks.

## Model and Data Quality Monitoring

- **Continuous Monitoring**
  - Monitor models in production for data drift, anomalies, and deviations from expected performance.
- **Automated Alerts**
  - Set up automated alert systems for deviations in model quality or data integrity.
- **Data Capture**
  - Enable data capture to store inference inputs and outputs for analysis.
- **Baseline Creation**
  - Use training datasets to establish baselines for data and model quality.
- **Scheduled Monitoring Jobs**
  - Schedule jobs to compare current data and model performance against baselines.
- **Performance Evaluation**
  - Use labeled data to evaluate model predictions and performance over time.
- **Result Visualization**
  - Visualize monitoring results and metrics to support proactive maintenance and improvement.

## Summary

- Secure AI systems by controlling access, encrypting data, validating inputs, restricting outputs, and monitoring for anomalies.
- Regularly retrain and validate models, and use automated tools to detect and respond to threats and data quality issues.