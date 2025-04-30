# Basic AI Concepts and Terminologies: Focus on Machine Learning

---

## What is Machine Learning (ML)?
- **Definition:** Machine learning is the science of developing algorithms and statistical models that enable computer systems to perform complex tasks without explicit instructions.
- **How it Works:** ML algorithms process large quantities of historical data to identify patterns. The process starts with a mathematical algorithm that takes data as input and generates an output.

---

## Key Concepts in Machine Learning

### 1. Features
- **Definition:** Features are the individual measurable properties or characteristics of the data. 
- **Examples:** Columns in a table, pixels in an image, or key-value pairs in a JSON document.

### 2. Model Training
- **Process:**
  - The algorithm is trained using known data (with features and expected outputs).
  - The model adjusts its internal parameters to find correlations between input features and expected outputs.
  - Training continues until the model reliably produces the expected output.

### 3. Inference
- **Definition:** Inference is the process where a trained model makes predictions or produces output from new, unseen data.

---

## Types of Data Used in Machine Learning

### 1. Structured Data
- **Description:** Data stored in rows and columns (tabular format).
- **Examples:** CSV files, relational databases (e.g., Amazon RDS, Amazon Redshift).
- **Storage for ML:** Often exported to Amazon S3 for model training.

### 2. Semi-Structured Data
- **Description:** Data that does not fully conform to tabular structure but has some organizational properties.
- **Examples:** JSON files, key-value pairs.
- **Databases:** Amazon DynamoDB, Amazon DocumentDB (with MongoDB compatibility).
- **Storage for ML:** Exported to Amazon S3.

### 3. Unstructured Data
- **Description:** Data that does not conform to any specific model or structure.
- **Examples:** Images, videos, text files, social media posts.
- **Storage:** Typically stored as objects in Amazon S3.
- **Feature Extraction:** Techniques like tokenization are used to derive features from unstructured data.

### 4. Time Series Data
- **Description:** Sequential data labeled with timestamps, used for predicting trends.
- **Examples:** Performance metrics (memory usage, CPU percentage, transactions per second).
- **Storage:** Often stored in Amazon S3 due to large size.

---

## Example: Linear Regression in Machine Learning

- **Objective:** Find the best fit line to match input data (e.g., predicting height from weight).
- **Equation:** y = mx + b (or h = mw + b)
  - **h:** Dependent variable (height)
  - **w:** Independent variable (weight)
  - **m:** Slope (model parameter)
  - **b:** Intercept (model parameter)
- **Training:** The model iteratively adjusts m and b to minimize the error (distance between data points and the line).
- **Inference:** Once trained, the model can predict height from a new weight value.

---

## Summary
- Machine learning enables systems to learn from data and make predictions without explicit programming.
- ML models are trained on various data types: structured, semi-structured, unstructured, and time series.
- Data is often stored and processed using AWS services such as Amazon S3, Amazon RDS, Amazon Redshift, Amazon DynamoDB, and Amazon DocumentDB.
- Linear regression is a foundational ML technique for modeling relationships between variables.