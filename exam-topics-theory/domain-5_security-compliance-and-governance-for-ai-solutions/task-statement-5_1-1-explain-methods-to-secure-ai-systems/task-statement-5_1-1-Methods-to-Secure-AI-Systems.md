# Task Statement 5.1: Explain Methods to Secure AI Systems

# Methods to Secure AI Systems

## Shared Responsibility Model

- **Security and compliance** in cloud environments is a shared responsibility between the cloud provider and the customer.
- **Cloud provider responsibilities** (Security of the Cloud):
  - Securing the global infrastructure, including regions, availability zones, and data centers.
  - Managing hardware, software, networking, and physical security.
- **Customer responsibilities** (Security in the Cloud):
  - Configuring services and applications securely.
  - Limiting access, using encryption, and following best practices.

## Service Responsibility Levels

- The level of customer responsibility varies by service type:
  - **Infrastructure as a Service (IaaS)** (e.g., Amazon EC2): Customers manage the operating system, security patches, scaling, and application security.
  - **Managed Services** (e.g., SageMaker Serverless Inferencing): The provider manages the underlying infrastructure, reducing customer management overhead.

## Identity and Access Management (IAM)

- **IAM** is used to manage and secure access to cloud accounts and resources.
- **Capabilities:**
  - Create and manage users and permissions.
  - Assign permission policies to control actions on resources.
  - Restrict user permissions to specific regions if needed.
  - Integrate with other services for unified access control.
- **Benefits:**
  - Grant permissions without sharing passwords or access keys.
  - Supports multifactor authentication (MFA) for enhanced security.
  - Supports identity federation for temporary access via external identity providers.
  - IAM is a global resource and incurs no additional charge.

## Root User Security

- The root user has unrestricted access to all services and resources.
- **Best Practices:**
  - Use a strong password and enable MFA for the root user.
  - Never share root user credentials.
  - Disable or delete root user access keys after creating other users.
  - Use the root user only for tasks that require it (e.g., billing management).
  - Create an IAM user with administrative permissions for daily tasks.

## Authentication Methods

- **Single-factor authentication:** Uses only a username and password.
  - Vulnerable to attacks if credentials are compromised.
- **Multifactor authentication (MFA):** Requires an additional authentication factor (e.g., a code from a physical or virtual device).
  - Provides enhanced protection even if the password is compromised.
  - Recommended to enable MFA immediately after account creation.

## IAM User Management

- **IAM user:** An identity created in the cloud environment representing a person or application.
  - Consists of a name and credentials.
- **Best Practices:**
  - Create individual IAM users for each person requiring access.
  - Assign unique security credentials to each user.
  - Do not share credentials among users to maintain visibility and accountability.
  - By default, new IAM users have no permissions; grant only necessary permissions for required actions.