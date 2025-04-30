# Task Statement 1.1 Explain Basic AI Concepts and Terminologies

## Model Inference

- The output of a machine learning model is called an inference.
- Example: A model trained to recognize images of fish uses inference to identify fish in new images.

## Overfitting

- Occurs when a model performs well on training data but poorly on new, unseen data.
- The model fits the training data too closely, including unimportant features (noise).
- Overfitting can result from training the model for too long or with insufficiently diverse data.
- **Correction:** Train the model with more diverse data to improve generalization.

## Underfitting

- Happens when a model cannot capture the underlying relationship between input and output data.
- Underfit models perform poorly on both training and new data.
- Causes include insufficient training time or too small a dataset.
- **Solution:** Increase training time or dataset size, but avoid overfitting.

## Bias in Machine Learning Models

- Bias refers to disparities in model performance across different groups.
- Results may be skewed in favor of or against certain outcomes for specific classes.
- Example: A loan approval model trained on non-diverse data may unfairly reject applications from underrepresented groups.

### Example Scenario

- Features: income, job history, age, gender, location.
- If the training data lacks approved applications from a specific group (e.g., 25-year-old women in Wisconsin), the model may incorrectly learn to reject such applications.

## Data Quality and Fairness

- Model quality depends on the quality and quantity of training data.
- Data scientists can adjust feature weights to reduce noise and bias.
- Features introducing bias (e.g., gender) can be removed from consideration.
- Fairness constraints (e.g., avoiding age or sex discrimination) should be identified before model creation.
- Training data should be inspected for potential bias.
- Models must be continually evaluated for fairness by checking their results.