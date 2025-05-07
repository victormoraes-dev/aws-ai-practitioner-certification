# Task Statement 1.3 Describe de ML Development Lifecycle

# ML Development Lifecycle: Model Evaluation and Business Metrics

## Model Evaluation Metrics

### Confusion Matrix Derived Metrics

- **False Positive Rate (FPR):**
  - Formula:  
    \[
    \text{FPR} = \frac{\text{False Positives (FP)}}{\text{False Positives (FP)} + \text{True Negatives (TN)}}
    \]
  - Measures the proportion of non-target instances incorrectly classified as positive.

- **True Negative Rate (TNR):**
  - Formula:  
    \[
    \text{TNR} = \frac{\text{True Negatives (TN)}}{\text{False Positives (FP)} + \text{True Negatives (TN)}}
    \]
  - Measures the proportion of non-target instances correctly classified as negative.

### Area Under the Curve (AUC) and ROC

- **AUC (Area Under the Curve):**
  - Used for evaluating binary classifiers that output probabilities.
  - The **Receiver Operating Characteristic (ROC) curve** plots the true positive rate against the false positive rate at various threshold settings.
  - **Threshold:** The probability value used to convert model output into a binary decision.
    - Example: A threshold of 0.6 means the model classifies as positive if the probability is 60% or higher.
  - **AUC Score:**
    - Ranges from 0 to 1.
    - 1 indicates perfect classification.
    - 0.5 indicates performance equivalent to random guessing.

### Regression Metrics

- **Mean Squared Error (MSE):**
  - Formula:  
    \[
    \text{MSE} = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2
    \]
  - Measures the average squared difference between predicted and actual values.
  - Always positive; lower values indicate better model performance.

- **Root Mean Squared Error (RMSE):**
  - Formula:  
    \[
    \text{RMSE} = \sqrt{\text{MSE}}
    \]
  - Expressed in the same units as the target variable, making interpretation easier.

- **Mean Absolute Error (MAE):**
  - Formula:  
    \[
    \text{MAE} = \frac{1}{n} \sum_{i=1}^{n} |y_i - \hat{y}_i|
    \]
  - Averages the absolute differences between predicted and actual values.
  - Less sensitive to outliers compared to MSE and RMSE.

## Business Metrics

- **Definition:** Quantitative measures that reflect the value delivered by a machine learning model to the business.
- **Examples:**
  - Cost reduction
  - Percentage increase in users or sales
  - Improvement in customer feedback scores
  - Any measurable metric aligned with business objectives

- **Risk and Cost Considerations:**
  - Estimate potential risks and costs associated with model errors (e.g., loss of sales or customers).
  - Track actual costs of building and operating the model.
  - Compare actual results and costs with initial business goals and cost-benefit analysis to determine return on investment (ROI).

- **Resource Cost Tracking:**
  - Assign cost allocation tags to resources used in the ML pipeline.
  - Use cost reporting tools to filter and analyze project-specific expenses.

---