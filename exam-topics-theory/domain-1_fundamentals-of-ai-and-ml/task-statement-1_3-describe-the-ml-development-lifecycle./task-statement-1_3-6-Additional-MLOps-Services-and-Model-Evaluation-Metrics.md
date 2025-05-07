# Task Statement 1.3 Describe de ML Development Lifecycle

# ML Development Lifecycle: Additional MLOps Services and Model Evaluation Metrics

## MLOps Services and Repositories

- **Code and Model Repositories:**  
  - Store versions of code and trained models for reproducibility and traceability.
- **Feature Store:**  
  - Centralized repository for feature definitions used in training data.
- **Model Registry:**  
  - Centralized repository for trained models and their version history.

## Pipeline Orchestration Options

- **Pipelines:**  
  - Orchestrate machine learning workflows and automate steps in the ML lifecycle.
- **Step Functions:**  
  - Define serverless workflows with a visual interface, integrating various services and custom logic.
- **Apache Airflow:**  
  - Open source tool for programmatically authoring, scheduling, and monitoring workflows.
  - Managed service options are available for scalability, availability, and security.

## Model Evaluation Metrics

### Confusion Matrix

A confusion matrix summarizes the performance of a classification model by comparing actual and predicted values.

|                | Predicted Positive | Predicted Negative |
|----------------|-------------------|-------------------|
| Actual Positive| True Positive (TP) | False Negative (FN)|
| Actual Negative| False Positive (FP)| True Negative (TN) |

- **True Positive (TP):** Model correctly predicts positive class.
- **True Negative (TN):** Model correctly predicts negative class.
- **False Positive (FP):** Model incorrectly predicts positive class.
- **False Negative (FN):** Model incorrectly predicts negative class.

### Example

Suppose 100 labeled test images are evaluated:

- TP = 25
- TN = 40
- FP = 20
- FN = 15

### Accuracy

Measures the proportion of correct predictions.

\[
\text{Accuracy} = \frac{TP + TN}{TP + TN + FP + FN}
\]

Example calculation:

\[
\text{Accuracy} = \frac{25 + 40}{100} = 0.65 \text{ or } 65\%
\]

> Note: Accuracy is not a reliable metric for imbalanced datasets.

### Precision

Measures the proportion of true positives among all predicted positives.

\[
\text{Precision} = \frac{TP}{TP + FP}
\]

Example calculation:

\[
\text{Precision} = \frac{25}{25 + 20} = 0.55 \text{ or } 55\%
\]

- Useful when minimizing false positives is important.

### Recall (Sensitivity, True Positive Rate)

Measures the proportion of true positives among all actual positives.

\[
\text{Recall} = \frac{TP}{TP + FN}
\]

Example calculation:

\[
\text{Recall} = \frac{25}{25 + 15} = 0.625 \text{ or } 62.5\%
\]

- Useful when minimizing false negatives is important.

### F1 Score

Balances precision and recall.

\[
\text{F1 Score} = 2 \times \frac{\text{Precision} \times \text{Recall}}{\text{Precision} + \text{Recall}}
\]

- Useful when both precision and recall are important.

### Metric Selection

- **Precision:** Minimize false positives (e.g., spam detection).
- **Recall:** Minimize false negatives (e.g., disease diagnosis).
- **F1 Score:** Balance between precision and recall.

---