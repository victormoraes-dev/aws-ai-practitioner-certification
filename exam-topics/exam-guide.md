# AWS Certified AI Practitioner (AIF-C01) Exam Guide

## Introduction

The AWS Certified AI Practitioner (AIF-C01) exam is designed to assess knowledge of AI/ML, generative AI technologies, and related AWS services and tools. The exam validates the ability to:

- Understand AI, ML, and generative AI concepts, methods, and strategies in general and on AWS.
- Understand the appropriate use of AI/ML and generative AI technologies for organizational needs.
- Determine the correct types of AI/ML technologies for specific use cases.
- Use AI, ML, and generative AI technologies responsibly.

## Target Candidate Description

- Up to 6 months of exposure to AI/ML technologies on AWS.
- Uses, but does not necessarily build, AI/ML solutions on AWS.

### Recommended AWS Knowledge

- Familiarity with core AWS services (e.g., Amazon EC2, Amazon S3, AWS Lambda, Amazon SageMaker) and their use cases.
- Understanding of the AWS shared responsibility model for security and compliance.
- Familiarity with AWS Identity and Access Management (IAM) for securing and controlling access to AWS resources.
- Understanding of AWS global infrastructure (Regions, Availability Zones, edge locations).
- Familiarity with AWS service pricing models.

## Out-of-Scope Job Tasks

The following tasks are not expected for the exam:

- Developing or coding AI/ML models or algorithms.
- Implementing data engineering or feature engineering techniques.
- Performing hyperparameter tuning or model optimization.
- Building and deploying AI/ML pipelines or infrastructure.
- Conducting mathematical or statistical analysis of AI/ML models.
- Implementing security or compliance protocols for AI/ML systems.
- Developing and implementing governance frameworks and policies for AI/ML solutions.

## Exam Content

### Question Types

- **Multiple choice:** One correct response and three distractors.
- **Multiple response:** Two or more correct responses out of five or more options; all correct responses must be selected for credit.
- **Ordering:** Arrange 3–5 responses in the correct order to complete a task.
- **Matching:** Match responses to 3–7 prompts; all pairs must be correct for credit.
- **Case study:** One scenario with two or more questions; each question is evaluated separately.

Unanswered questions are scored as incorrect. The exam includes 50 scored questions and 15 unscored questions (not identified on the exam).

### Exam Results

- Pass or fail designation.
- Scaled score: 100–1,000 (minimum passing score: 700).
- Compensatory scoring model: passing the overall exam is required, not each section.
- Section-level feedback is provided for general strengths and weaknesses.

## Content Outline

| Domain                                                      | Weight (%) |
|-------------------------------------------------------------|------------|
| 1. Fundamentals of AI and ML                                | 20         |
| 2. Fundamentals of Generative AI                            | 24         |
| 3. Applications of Foundation Models                        | 28         |
| 4. Guidelines for Responsible AI                            | 14         |
| 5. Security, Compliance, and Governance for AI Solutions    | 14         |

---

### Domain 1: Fundamentals of AI and ML

#### Task Statement 1.1: Explain basic AI concepts and terminologies.

##### Objectives:

1.1.1 Define basic AI terms (for example, AI, ML, deep learning, neural networks, computer vision, natural language processing [NLP], model, algorithm, training and inferencing, bias, fairness, fit, large language model [LLM]).

1.1.2 Describe the similarities and differences between AI, ML, and deep learning.

1.1.3 Describe various types of inferencing (for example, batch, real-time).

1.1.4 Describe the different types of data in AI models (for example, labeled and unlabeled, tabular, time-series, image, text, structured and unstructured).

1.1.5 Describe supervised learning, unsupervised learning, and reinforcement learning.

#### Task Statement 1.2: Identify practical use cases for AI.

##### Objectives:

1.2.1 Recognize applications where AI/ML can provide value (for example, assist human decision making, solution scalability, automation).

1.2.2 Determine when AI/ML solutions are not appropriate (for example, cost-benefit analyses, situations when a specific outcome is needed instead of a prediction).

1.2.3 Select the appropriate ML techniques for specific use cases (for example, regression, classification, clustering).

1.2.4 Identify examples of real-world AI applications (for example, computer vision, NLP, speech recognition, recommendation systems, fraud detection, forecasting).

1.2.5 Explain the capabilities of AWS managed AI/ML services (for example, SageMaker, Amazon Transcribe, Amazon Translate, Amazon Comprehend, Amazon Lex, Amazon Polly).

#### Task Statement 1.3: Describe the ML development lifecycle.

##### Objectives:

1.3.1 Describe components of an ML pipeline (for example, data collection, exploratory data analysis [EDA], data pre-processing, feature engineering, model training, hyperparameter tuning, evaluation, deployment, monitoring).

1.3.2 Understand sources of ML models (for example, open source pre-trained models, training custom models).

1.3.3 Describe methods to use a model in production (for example, managed API service, self-hosted API).

1.3.4 Identify relevant AWS services and features for each stage of an ML pipeline (for example, SageMaker, Amazon SageMaker Data Wrangler, Amazon SageMaker Feature Store, Amazon SageMaker Model Monitor).

1.3.5 Understand fundamental concepts of ML operations (MLOps) (for example, experimentation, repeatable processes, scalable systems, managing technical debt, achieving production readiness, model monitoring, model re-training).

1.3.6 Understand model performance metrics (for example, accuracy, Area Under the ROC Curve [AUC], F1 score) and business metrics (for example, cost per user, development costs, customer feedback, return on investment [ROI]) to evaluate ML models.

### Domain 2: Fundamentals of Generative AI

#### Task Statement 2.1: Explain the basic concepts of generative AI.

##### Objectives:

2.1.1 Understand foundational generative AI concepts (for example, tokens, chunking, embeddings, vectors, prompt engineering, transformer-based LLMs, foundation models, multi-modal models, diffusion models).

2.1.2 Identify potential use cases for generative AI models (for example, image, video, and audio generation; summarization; chatbots; translation; code generation; customer service agents; search; recommendation engines).

2.1.3 Describe the foundation model lifecycle (for example, data selection, model selection, pre-training, fine-tuning, evaluation, deployment, feedback).

#### Task Statement 2.2: Understand the capabilities and limitations of generative AI for solving business problems.

##### Objectives:

2.2.1 Describe the advantages of generative AI (for example, adaptability, responsiveness, simplicity).

2.2.2 Identify disadvantages of generative AI solutions (for example, hallucinations, interpretability, inaccuracy, nondeterminism).

2.2.3 Understand various factors to select appropriate generative AI models (for example, model types, performance requirements, capabilities, constraints, compliance).

2.2.4 Determine business value and metrics for generative AI applications (for example, cross-domain performance, efficiency, conversion rate, average revenue per user, accuracy, customer lifetime value).

#### Task Statement 2.3: Describe AWS infrastructure and technologies for building generative AI applications.

##### Objectives:

2.3.1 Identify AWS services and features to develop generative AI applications (for example, Amazon SageMaker JumpStart; Amazon Bedrock; PartyRock, an Amazon Bedrock Playground; Amazon Q).

2.3.2 Describe the advantages of using AWS generative AI services to build applications (for example, accessibility, lower barrier to entry, efficiency, cost-effectiveness, speed to market, ability to meet business objectives).

2.3.3 Understand the benefits of AWS infrastructure for generative AI applications (for example, security, compliance, responsibility, safety).

2.3.4 Understand cost tradeoffs of AWS generative AI services (for example, responsiveness, availability, redundancy, performance, regional coverage, token-based pricing, provision throughput, custom models).

### Domain 3: Applications of Foundation Models

#### Task Statement 3.1: Describe design considerations for applications that use foundation models.

##### Objectives:

3.1.1 Identify selection criteria to choose pre-trained models (for example, cost, modality, latency, multi-lingual, model size, model complexity, customization, input/output length).

3.1.2 Understand the effect of inference parameters on model responses (for example, temperature, input/output length).

3.1.3 Define Retrieval Augmented Generation (RAG) and describe its business applications (for example, Amazon Bedrock, knowledge base).

3.1.4 Identify AWS services that help store embeddings within vector databases (for example, Amazon OpenSearch Service, Amazon Aurora, Amazon Neptune, Amazon DocumentDB [with MongoDB compatibility], Amazon RDS for PostgreSQL).

3.1.5 Explain the cost tradeoffs of various approaches to foundation model customization (for example, pre-training, fine-tuning, in-context learning, RAG).

3.1.6 Understand the role of agents in multi-step tasks (for example, Agents for Amazon Bedrock).

#### Task Statement 3.2: Choose effective prompt engineering techniques.

##### Objectives:

3.2.1 Describe the concepts and constructs of prompt engineering (for example, context, instruction, negative prompts, model latent space).

3.2.2 Understand techniques for prompt engineering (for example, chain-of-thought, zero-shot, single-shot, few-shot, prompt templates).

3.2.3 Understand the benefits and best practices for prompt engineering (for example, response quality improvement, experimentation, guardrails, discovery, specificity and concision, using multiple comments).

3.2.4 Define potential risks and limitations of prompt engineering (for example, exposure, poisoning, hijacking, jailbreaking).

#### Task Statement 3.3: Describe the training and fine-tuning process for foundation models.

##### Objectives:

3.3.1 Describe the key elements of training a foundation model (for example, pre-training, fine-tuning, continuous pre-training).

3.3.2 Define methods for fine-tuning a foundation model (for example, instruction tuning, adapting models for specific domains, transfer learning, continuous pre-training).

3.3.3 Describe how to prepare data to fine-tune a foundation model (for example, data curation, governance, size, labeling, representativeness, reinforcement learning from human feedback [RLHF]).

#### Task Statement 3.4: Describe methods to evaluate foundation model performance.

##### Objectives:

3.4.1 Understand approaches to evaluate foundation model performance (for example, human evaluation, benchmark datasets).

3.4.2 Identify relevant metrics to assess foundation model performance (for example, Recall-Oriented Understudy for Gisting Evaluation [ROUGE], Bilingual Evaluation Understudy [BLEU], BERTScore).

3.4.3 Determine whether a foundation model effectively meets business objectives (for example, productivity, user engagement, task engineering).

### Domain 4: Guidelines for Responsible AI

#### Task Statement 4.1: Explain the development of AI systems that are responsible.

##### Objectives:

4.1.1 Identify features of responsible AI (for example, bias, fairness, inclusivity, robustness, safety, veracity).

4.1.2 Understand how to use tools to identify features of responsible AI (for example, Guardrails for Amazon Bedrock).

4.1.3 Understand responsible practices to select a model (for example, environmental considerations, sustainability).

4.1.4 Identify legal risks of working with generative AI (for example, intellectual property infringement claims, biased model outputs, loss of customer trust, end user risk, hallucinations).

4.1.5 Identify characteristics of datasets (for example, inclusivity, diversity, curated data sources, balanced datasets).

4.1.6 Understand effects of bias and variance (for example, effects on demographic groups, inaccuracy, overfitting, underfitting).

4.1.7 Describe tools to detect and monitor bias, trustworthiness, and truthfulness (for example, analyzing label quality, human audits, subgroup analysis, Amazon SageMaker Clarify, SageMaker Model Monitor, Amazon Augmented AI [Amazon A2I]).

#### Task Statement 4.2: Recognize the importance of transparent and explainable models.

##### Objectives:

4.2.1 Understand the differences between models that are transparent and explainable and models that are not transparent and explainable.

4.2.2 Understand the tools to identify transparent and explainable models (for example, Amazon SageMaker Model Cards, open source models, data, licensing).

4.2.3 Identify tradeoffs between model safety and transparency (for example, measure interpretability and performance).

4.2.4 Understand principles of human-centered design for explainable AI.

### Domain 5: Security, Compliance, and Governance for AI Solutions

#### Task Statement 5.1: Explain methods to secure AI systems.

##### Objectives:

5.1.1 Identify AWS services and features to secure AI systems (for example, IAM roles, policies, and permissions; encryption; Amazon Macie; AWS PrivateLink; AWS shared responsibility model).

5.1.2 Understand the concept of source citation and documenting data origins (for example, data lineage, data cataloging, SageMaker Model Cards).

5.1.3 Describe best practices for secure data engineering (for example, assessing data quality, implementing privacy-enhancing technologies, data access control, data integrity).

5.1.4 Understand security and privacy considerations for AI systems (for example, application security, threat detection, vulnerability management, infrastructure protection, prompt injection, encryption at rest and in transit).

#### Task Statement 5.2: Recognize governance and compliance regulations for AI systems.

##### Objectives:

5.2.1 Identify regulatory compliance standards for AI systems (for example, International Organization for Standardization [ISO], System and Organization Controls [SOC], algorithm accountability laws).

5.2.2 Identify AWS services and features to assist with governance and regulation compliance (for example, AWS Config, Amazon Inspector, AWS Audit Manager, AWS Artifact, AWS CloudTrail, AWS Trusted Advisor).

5.2.3 Describe data governance strategies (for example, data lifecycles, logging, residency, monitoring, observation, retention).

5.2.4 Describe processes to follow governance protocols (for example, policies, review cadence, review strategies, governance frameworks such as the Generative AI Security Scoping Matrix, transparency standards, team training requirements).

---

## Appendix

### In-Scope AWS Services and Features

**Analytics**
- AWS Data Exchange
- Amazon EMR
- AWS Glue
- AWS Glue DataBrew
- AWS Lake Formation
- Amazon OpenSearch Service
- Amazon QuickSight
- Amazon Redshift

**Cloud Financial Management**
- AWS Budgets
- AWS Cost Explorer

**Compute**
- Amazon EC2

**Containers**
- Amazon ECS
- Amazon EKS

**Database**
- Amazon DocumentDB (MongoDB)
- Amazon DynamoDB
- Amazon ElastiCache
- Amazon MemoryDB
- Amazon Neptune
- Amazon RDS

**Machine Learning**
- Amazon Augmented AI (A2I)
- Amazon Bedrock
- Amazon Comprehend
- Amazon Fraud Detector
- Amazon Kendra
- Amazon Lex
- Amazon Personalize
- Amazon Polly
- Amazon Q
- Amazon Rekognition
- Amazon SageMaker
- Amazon Textract
- Amazon Transcribe
- Amazon Translate

**Management and Governance**
- AWS CloudTrail
- Amazon CloudWatch
- AWS Config
- AWS Trusted Advisor
- AWS Well-Architected Tool

**Networking and Content Delivery**
- Amazon CloudFront
- Amazon VPC

**Security, Identity, and Compliance**
- AWS Artifact
- AWS Audit Manager
- AWS IAM
- Amazon Inspector
- AWS KMS
- Amazon Macie
- AWS Secrets Manager

**Storage**
- Amazon S3
- Amazon S3 Glacier

---

### Out-of-Scope AWS Services and Features

**Analytics**
- AWS Clean Rooms
- Amazon CloudSearch
- Amazon FinSpace
- Amazon MSK

**Application Integration**
- Amazon AppFlow
- Amazon MQ
- Amazon SWF

**Business Applications**
- Amazon Chime
- Amazon Honeycode
- Amazon Pinpoint
- Amazon SES
- AWS Supply Chain
- AWS Wickr
- Amazon WorkDocs
- Amazon WorkMail

**Cloud Financial Management**
- AWS Application Cost Profiler
- AWS Billing Conductor
- AWS Marketplace

**Compute**
- AWS App Runner
- AWS Elastic Beanstalk
- EC2 Image Builder
- Amazon Lightsail

**Containers**
- Red Hat OpenShift Service on AWS (ROSA)

**Customer Enablement**
- AWS IQ
- AWS Managed Services (AMS)
- AWS re:Post Private
- AWS Support

**Database**
- Amazon Keyspaces (Cassandra)
- Amazon QLDB
- Amazon Timestream

**Developer Tools**
- AWS AppConfig
- AWS Application Composer
- AWS CloudShell
- Amazon CodeCatalyst
- AWS CodeStar
- AWS Fault Injection Service
- AWS X-Ray

**End User Computing**
- Amazon AppStream 2.0
- Amazon WorkSpaces
- Amazon WorkSpaces Thin Client
- Amazon WorkSpaces Web

**Frontend Web and Mobile**
- AWS Amplify
- AWS AppSync
- AWS Device Farm
- Amazon Location Service

**Internet of Things (IoT)**
- AWS IoT Analytics
- AWS IoT Core
- AWS IoT Device Defender
- AWS IoT Device Management
- AWS IoT Events
- AWS IoT FleetWise
- FreeRTOS
- AWS IoT Greengrass
- AWS IoT 1-Click
- AWS IoT RoboRunner
- AWS IoT SiteWise
- AWS IoT TwinMaker

**Machine Learning**
- AWS DeepComposer
- AWS HealthImaging
- AWS HealthOmics
- Amazon Monitron
- AWS Panorama

**Management and Governance**
- AWS Control Tower
- AWS Health Dashboard
- AWS Launch Wizard
- AWS License Manager
- Amazon Managed Grafana
- Amazon Managed Service for Prometheus
- AWS OpsWorks
- AWS Organizations
- AWS Proton
- AWS Resilience Hub
- AWS Resource Explorer
- AWS Resource Groups
- AWS Systems Manager Incident Manager
- AWS Service Catalog
- Service Quotas
- AWS Telco Network Builder
- AWS User Notifications

**Media**
- Amazon Elastic Transcoder
- AWS Elemental MediaConnect
- AWS Elemental MediaConvert
- AWS Elemental MediaLive
- AWS Elemental MediaPackage
- AWS Elemental MediaStore
- AWS Elemental MediaTailor
- Amazon Interactive Video Service (IVS)
- Amazon Nimble Studio

**Migration and Transfer**
- AWS Application Discovery Service
- AWS Application Migration Service
- AWS Database Migration Service (DMS)
- AWS DataSync
- AWS Mainframe Modernization
- AWS Migration Hub
- AWS Snow Family
- AWS Transfer Family

**Networking and Content Delivery**
- AWS App Mesh
- AWS Cloud Map
- AWS Direct Connect
- AWS Global Accelerator
- AWS Private 5G
- Amazon Route 53
- Amazon Route 53 Application Recovery Controller
- Amazon VPC IP Address Manager (IPAM)

**Security, Identity, and Compliance**
- AWS Certificate Manager (ACM)
- AWS CloudHSM
- Amazon Cognito
- Amazon Detective
- AWS Directory Service
- AWS Firewall Manager
- Amazon GuardDuty
- AWS IAM Identity Center
- AWS Payment Cryptography
- AWS Private Certificate Authority
- AWS Resource Access Manager (RAM)
- AWS Security Hub
- Amazon Security Lake
- AWS Shield
- AWS Signer
- Amazon Verified Permissions
- AWS WAF

**Storage**
- AWS Backup
- AWS Elastic Disaster Recovery