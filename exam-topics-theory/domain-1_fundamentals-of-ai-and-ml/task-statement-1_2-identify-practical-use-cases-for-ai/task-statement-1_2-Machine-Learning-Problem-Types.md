# Task Statement 1.2 Identify Practical Use Cases for AI

# Machine Learning Problem Types

## Supervised Learning

- **Definition**: Uses datasets with input features and labeled target values.
- **Goal**: Train models with known inputs and outputs.

### Classification

- **Target Values**: Categorical (discrete values).
- **Types**:
  - **Binary Classification**: Assigns input to one of two mutually exclusive classes.
    - *Example*: Medical diagnosis (disease or no disease).
  - **Multiclass Classification**: Assigns input to one of several classes.
    - *Example*: Document topic classification (religion, politics, finance).
    - *Example*: Identifying multiple categories of sea creatures.

### Regression

- **Target Values**: Continuous (mathematically continuous values).
- **Goal**: Estimate the value of a dependent variable based on one or more correlated variables.
- **Types**:
  - **Simple Linear Regression**: Uses a single independent variable.
    - *Example*: Predicting height from weight.
  - **Multiple Linear Regression**: Uses multiple independent variables.
    - *Example*: Predicting house prices using features like number of bathrooms, bedrooms, square footage.
  - **Logistic Regression**: Measures the probability of an event occurring (output between 0 and 1).
    - *Example*: Predicting heart disease based on BMI, smoking status, genetic predisposition.
    - *Example*: Predicting financial transaction fraud.

- **Note**: Both logistic and linear regression require significant amounts of labeled data for accuracy.

---

## Unsupervised Learning

- **Definition**: Uses datasets with input features but no labeled target values.
- **Goal**: Discover patterns or groupings within the data.

### Clustering

- **Goal**: Separate data into discrete groups (clusters).
- **Process**:
  - Define features for similarity.
  - Select a distance function to measure similarity.
  - Specify the number of clusters.
- **Example**: Segmenting customers by purchase history or clickstream activity.

### Anomaly Detection

- **Goal**: Identify rare items, events, or observations that differ significantly from the rest of the data.
- **Example**: Detecting failed sensors or medical errors.

---

## Summary Table

| Problem Type      | Input Data         | Target/Output           | Example Use Cases                              |
|-------------------|-------------------|-------------------------|-----------------------------------------------|
| Classification    | Features + Labels | Categorical             | Disease diagnosis, document classification    |
| Regression        | Features + Labels | Continuous              | House price prediction, height estimation      |
| Clustering        | Features          | Group Assignments       | Customer segmentation                         |
| Anomaly Detection | Features          | Outlier Identification  | Sensor failure detection, medical errors       |