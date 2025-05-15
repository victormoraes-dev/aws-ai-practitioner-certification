# Task Statement 5.2: Recognize Governance and Compliance Regulations for AI Systems

# Governance and Compliance Regulations for AI Systems

## AWS Services for Compliance

### AWS Audit Manager
- Maps compliance requirements to AWS usage data.
- Collects evidence of compliance or noncompliance.
- Produces assessment reports for auditors.
- Supports built-in frameworks (e.g., generative AI best practices, SOC 2) and custom frameworks.
- Automatically assesses resources based on defined controls and attaches evidence to assessments.
- Generates auditor-friendly reports to demonstrate control effectiveness.

### Guardrails for Amazon Bedrock
- Implements application-specific safeguards based on use cases and responsible AI policies.
- Provides content filters with configurable thresholds for categories such as hate, insults, sexual content, and violence.
- Allows definition of restricted topics using natural language descriptions and example phrases.
- Detects and blocks user inputs and model responses that fall into restricted topics.
- Detects personally identifiable information (PII) in user inputs and model responses.
- Supports selective rejection or redaction of PII based on use case.
- Enables configuration of custom messages for blocked prompts and responses.

### AWS Config
- Maintains a detailed inventory of current AWS resource configurations.
- Captures and records configuration changes in history snapshots.
- Evaluates changes against configuration rules for compliance.
- Supports automatic remediation of noncompliant changes using AWS Systems Manager automation documents.
- Offers prebuilt and custom rules (via Lambda functions).
- Conformance packs bundle rules and remediation actions for streamlined deployment.
  - Examples: Operational best practices for AI/ML, security best practices for Amazon SageMaker.

### Amazon Inspector
- Performs security assessments at the application and container level.
- Checks for security vulnerabilities and deviations from best practices (e.g., open access, vulnerable software).
- Provides prioritized security findings with detailed descriptions and remediation recommendations.

### AWS Trusted Advisor
- Continuously evaluates AWS environments using best practice checks.
- Categories: Cost optimization, performance, resilience, security, operational excellence, service limits.
- Recommends actions to remediate deviations from best practices.

## Summary
AWS provides a suite of services and features to support governance and compliance for AI systems. These tools enable auditing, monitoring, control, and reporting on security controls, helping organizations maintain compliance and improve the security and reliability of their AI workloads.