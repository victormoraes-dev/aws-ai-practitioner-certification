# Task Statement 5.1: Explain Methods to Secure AI Systems

# Methods to Secure AI Systems

## Identity Federation

- Identity federation enables users to authenticate with an external identity provider (e.g., Active Directory).
- After authentication, users receive temporary AWS credentials.
- AWS IAM Identity Center allows the use of external identity providers or a directory created within IAM Identity Center for authentication.
- Authenticated users (workforce users) can access an AWS portal to choose AWS consoles or obtain temporary access keys for permitted AWS accounts.
- Centralized management of users and permissions across multiple AWS accounts is possible through IAM Identity Center.
- Users can be grouped, and permission sets can be assigned at the group level.
- IAM Identity Center uses roles to grant temporary permissions, reducing the risk associated with long-lived credentials.
- AWS recommends using IAM Identity Center for user management.

## Auditing and Logging

- Logging and reviewing user actions is essential for auditing and validating security configurations.
- AWS CloudTrail captures API calls and related events made by or on behalf of an AWS account.
- CloudTrail delivers log files to a specified Amazon S3 bucket.
- Amazon SageMaker is integrated with CloudTrail, logging all API calls except endpoint invocations.
- CloudTrail logs include details such as the request, IP address, requester, timestamp, and additional metadata.

## Data Access and Privacy

- Customers are responsible for managing access to their data, ensuring training data and artifacts remain private and secure.
- Amazon S3 Block Public Access can be used to block public access to all objects at the bucket or account level.
    - Bucket-level: Some buckets may remain public if not configured.
    - Account-level: No buckets, existing or new, can grant public access.
- S3 Block Public Access overrides any public permissions granted by bucket policies or access control lists.

## Role Management for Machine Learning

- Amazon SageMaker Role Manager simplifies the creation of IAM roles for machine learning activities.
- Provides three pre-configured role personas:
    - **Data Scientist Persona:** For general ML development and experimentation.
    - **MLOps Persona:** For managing models, pipelines, experiments, and endpoints without S3 data access.
    - **SageMaker Compute Persona:** For SageMaker compute resources to perform training and inference.
- Predefined permissions for 12 ML activities, including access to Amazon S3, AWS Glue, Amazon Athena, and Amazon CloudWatch.
- Roles can be customized by selecting or deselecting activities.
- Additional IAM policies can be attached as needed.