# Task Statement 4.1: Explain the Development of AI Systems That Are Responsible

# Development of Responsible AI Systems

## Measuring and Monitoring Model Bias, Trustworthiness, and Truthfulness

### Bias in AI Systems

- **Biases** are imbalances in data or disparities in model performance across different groups.
- It is important to detect and mitigate bias to ensure fairness and accuracy in AI systems.

### AWS Services for Responsible AI

#### SageMaker Clarify

- **SageMaker Clarify** is a tool that helps detect and mitigate bias during data preparation, after model training, and in deployed models.
- It examines specific attributes to identify potential bias and improve model explainability.

#### Explainability

- Explainability ensures that model decisions are unbiased and transparent.
- SageMaker Clarify analyzes model inputs and outputs, treating the model as a black box.
- It determines the relative importance of each feature in the model's predictions.
- Example: For a loan application, it can identify that income and outstanding debt were key factors in a rejection.

#### Support for Various Model Types

- SageMaker Clarify can explain predictions for deep learning models, including those used in computer vision and natural language processing, even when working with unstructured data.

### SageMaker Clarify Processing Workflow

1. **Processing Jobs**: SageMaker Clarify uses processing jobs to analyze datasets and models.
2. **Data Interaction**: The processing container interacts with an Amazon S3 bucket containing input datasets and a deployed model.
3. **Feature Analysis**: The processing container sends requests to the model container and retrieves predictions.
4. **Result Computation**: Analysis results are computed and saved to the S3 bucket, including:
    - JSON files with bias metrics and global feature attributions
    - Visual reports
    - Files for local feature attributions

### Metrics for Bias Detection

#### Dataset Metrics

- **Balanced Dataset**: Important to avoid errors for specific classes.
- **Demographic Disparity**: Indicates if a class has a larger proportion of negative outcomes.
    - Example: If women comprise 46% of rejected applicants but only 32% of accepted applicants in college admissions, this shows demographic disparity.

#### Model Metrics

- **Difference in Positive Proportions in Predictions**: Indicates if the model predicts positive outcomes differently for each class.
- **Specificity**: Measures how often the model correctly predicts a negative outcome.
    - Lower specificity for a group indicates bias against other groups.
- **Recall Difference**: Difference in recall (true positive rate) between two classes.
    - High recall for one class and low for another indicates potential bias.
- **Accuracy Difference**: Difference in prediction accuracies for different classes, often due to class imbalance.
- **Treatment Equality**: Difference in the ratio of false negatives to false positives between classes.
    - Even with equal accuracy, differences in error types can indicate bias.

#### Example: Loan Approval

- More incorrect loan denials for one class and more incorrect approvals for another demonstrate bias between classes.

## Summary

- Responsible AI development involves measuring and mitigating bias, ensuring explainability, and monitoring model performance across different groups.
- Tools like SageMaker Clarify provide metrics and analysis to support the development of fair and trustworthy AI systems.