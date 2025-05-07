# Task Statement 1.3 Describe de ML Development Lifecycle

# ML Development Lifecycle: Data Collection and Preparation

## Data Collection

- **Identify Required Data**
  - Determine the type and source of data needed for model development.
  - Assess whether data is generated as a stream or can be loaded in batches.

- **Data Ingestion Process**
  - Configure an Extract, Transform, and Load (ETL) process to collect data from multiple sources.
  - Store collected data in a centralized repository.
  - Ensure the process is repeatable for frequent model retraining.

- **Data Labeling**
  - Identify if the data is labeled or requires labeling.
  - Plan for data labeling, which can be time-consuming if labeled data does not already exist.

## Data Preparation

- **Pre-processing and Feature Engineering**
  - Perform exploratory data analysis (EDA) using visualization tools to understand the data.
  - Use data wrangling tools for interactive analysis and preparation.

- **Data Cleaning**
  - Filter out or repair missing and anomalous values.
  - Mask or remove personally identifiable information (PII).

- **Data Splitting**
  - Split data into three sets:
    - Training set (~80%)
    - Evaluation set (~10%)
    - Test set (~10%)

- **Feature Selection**
  - Select relevant features that contribute to minimizing model error.
  - Reduce features to those necessary for inference.
  - Combine features to further reduce dimensionality, optimizing memory and compute requirements.

## Data Ingestion and Preparation Tools

- **ETL Services**
  - Fully managed ETL services can automate data extraction, transformation, and loading.
  - Metadata, such as table definitions and schemas, are cataloged for easy access and management.

- **Data Catalog**
  - Centralized catalog stores references to data sources and targets.
  - Contains indexes for location, schema, and runtime metrics.
  - Supports automated schema discovery via crawlers and manual entry.

- **Visual Data Preparation**
  - Visual tools enable interactive data cleaning and transformation without code.
  - Built-in transformations assist with removing nulls, fixing schema inconsistencies, and more.
  - Transformation steps can be saved as reusable recipes.
  - Data quality can be evaluated using rule sets and profiling jobs.

- **Data Labeling**
  - Tools support building high-quality labeled datasets using active learning.
  - Automatic labeling is performed where possible; remaining data is labeled by human workforce.

- **Feature Engineering and Management**
  - Visual interfaces simplify feature engineering and data analysis.
  - Built-in transformations allow for quick normalization and combination of features.
  - Centralized feature stores manage features and associated metadata for easy discovery and reuse.
  - Workflow pipelines automate the conversion of raw data into features and their addition to feature groups.

## Key Considerations

- Ensure data collection and preparation processes are repeatable and scalable.
- Focus on data quality, completeness, and relevance for effective model training.
- Optimize feature selection to balance model performance and resource efficiency.