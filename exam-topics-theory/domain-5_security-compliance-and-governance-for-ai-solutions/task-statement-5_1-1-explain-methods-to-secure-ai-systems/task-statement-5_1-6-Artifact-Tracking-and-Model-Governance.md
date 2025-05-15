# Task Statement 5.1: Explain Methods to Secure AI Systems

# Methods to Secure AI Systems: Artifact Tracking and Model Governance

## Artifact Versioning and Tracking

- **Version Control for Code**  
  - Use code repositories to automatically retain versions of source code, including:
    - Training code
    - Inference code
    - Experiments
    - Notebooks

- **Dataset Management**  
  - Store datasets in object storage and partition them with unique prefixes to identify each training dataset.

- **Container Image Tracking**  
  - Store container images in a container registry.
  - Assign unique IDs and tags to each image for identification.

- **Training Job Metadata**  
  - Automatically assign unique identifiers to each training job.
  - Store metadata such as:
    - Hyperparameters
    - Container image IDs
    - Dataset identifiers
    - Model output locations

## Model Versioning and Cataloging

- **Model Registry**  
  - Catalog models in model groups containing different versions.
  - Each model package corresponds to a trained model.
  - Associate and view model metadata, including training metrics.
  - Deploy models directly from the registry.
  - Maintain model status (e.g., pending, approved, rejected).

- **Endpoint Tracking**  
  - Assign unique identifiers and metadata to each model endpoint.
  - Track the model used as part of the endpoint configuration.

## Model Documentation and Governance

- **Model Cards**  
  - Document, retrieve, and share essential model information from conception to deployment.
  - Record intended model uses, risk ratings, training details, and evaluation results.
  - Export model cards for sharing with stakeholders.

- **Lineage Tracking**  
  - Automatically create a graphical representation of all elements in the machine learning workflow.
  - Establish model governance, reproduce workflows, and maintain work history.
  - Track entities for trial components, trials, and experiments.
  - Query lineage data to discover relationships between entities (e.g., which models use a specific dataset).

## Feature Management

- **Feature Store**  
  - Centralized store for features and associated metadata.
  - Simplifies creation, sharing, and management of features for machine learning development.
  - Supports workflow pipelines to convert raw data into features and add them to feature groups.
  - View feature group lineage, including:
    - Execution code of feature processing workflows
    - Data sources and ingestion methods
  - Supports point-in-time queries to retrieve the historical state of features.

## Model Monitoring and Dashboard

- **Model Dashboard**  
  - Centralized portal to view, search, and explore all models.
  - Aggregates information from monitoring and documentation features.
  - Visualize workflow lineage and track endpoint performance.
  - Track deployed models for inference, batch jobs, or hosted endpoints.
  - Monitor real-time prediction performance and compliance with data quality, model quality, bias, and explainability thresholds.
  - Identify models lacking configured monitoring metrics.