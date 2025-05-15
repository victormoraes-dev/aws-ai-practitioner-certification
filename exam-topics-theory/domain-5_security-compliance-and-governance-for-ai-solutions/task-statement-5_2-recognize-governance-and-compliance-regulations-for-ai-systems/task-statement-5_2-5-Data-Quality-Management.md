# Task Statement 5.2: Recognize Governance and Compliance Regulations for AI Systems

# Governance and Compliance Regulations for AI Systems

## Data Quality Management

- **Data quality management** addresses issues found during data profiling or other means.
- Root cause analysis requires both business and technical knowledge of the data and its role in targeted initiatives.
- If issues originate from the data source, they should be reported to data stewards and business users for correction.

## Data Integration

- Involves collecting and merging data from various sources.
- Ensures coherent linking of data from different sources for comprehensive analysis.

## Metadata Management

- **AWS Glue Data Catalog** stores metadata about data sources, including locations, schemas, data types, and table definitions.
- Metadata can be populated manually or automatically using AWS Glue crawlers.

## Data Quality Evaluation

- **AWS Glue Data Quality** evaluates objects in the AWS Glue Data Catalog.
- Allows non-coders to set up data quality rules, recommends rules, and uses machine learning to detect anomalies.
- After defining rule sets, jobs can be run to review which rules pass or fail.

## Data Security and Access Control

- Data security defines who can access data and when.
- Role-based and temporary access is typically enabled by data stewards, guided by policies from data owners.

## Compliance

- Compliance involves understanding and adhering to government regulations.
- Data owners collaborate with security and legal teams to make policy decisions for sensitive data domains.
- Rules require interpretation, judgment, and business knowledge.

## Data Lifecycle Management

- Intentional storage of data for easy access and optimized cost.
- Balances control and access to prevent data silos and reduce business risk.

## Fine-Grained Access Control

- **AWS Lake Formation** manages fine-grained access control for data lakes in Amazon S3, cataloged with AWS Glue Data Catalog.
- Permissions can be enforced at column, row, and cell levels across analytics and machine learning services.
- Supports breaking down data silos and centralizing structured and unstructured data.

### Access Workflow Example

1. Identify existing data stores (Amazon S3, relational, NoSQL databases).
2. Move data into the data lake.
3. Catalog the data and set permissions.
4. When a user requests access via an analytical engine (e.g., Athena, AWS Glue, Amazon EMR, Amazon Redshift), the AWS Glue Data Catalog checks permissions with Lake Formation before granting access.

## Data Storage Classes and Lifecycle Rules

- **Amazon S3** offers multiple storage classes optimized for different access patterns:
  - **S3 Standard**: Frequently accessed data.
  - **S3 Standard-IA / S3 One Zone-IA**: Infrequently accessed, but quickly retrievable data.
  - **S3 Intelligent-Tiering**: Automatically moves data to lower-cost tiers based on access patterns.
  - **S3 Glacier**: Rarely accessed data, used for long-term archiving and compliance.

### Lifecycle Rules

- Define rules to transition data between storage classes based on age or access patterns.
- Example lifecycle rule:
  - Transition from S3 Standard to S3 Standard-IA after 5 days.
  - Move to S3 Glacier Deep Archive after 120 days.
  - Delete data after 5 years.

## Summary

- Data governance ensures data is available to the right people and applications while maintaining security and compliance.
- Proper management of data quality, integration, metadata, access control, compliance, and lifecycle is essential for effective governance and compliance in AI systems.