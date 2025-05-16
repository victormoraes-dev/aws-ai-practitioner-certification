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

#### Task Statement 1.1: Explain Basic AI Concepts and Terminologies

- 1.1.1 Define terms: AI, ML, deep learning, neural networks, computer vision, NLP, model, algorithm, training, inferencing, bias, fairness, fit, LLM.
- 1.1.2 Describe similarities and differences between AI, ML, and deep learning.
- 1.1.3 Describe types of inferencing (batch, real-time).
- 1.1.4 Describe types of data in AI models (labeled, unlabeled, tabular, time-series, image, text, structured, unstructured).
- 1.1.5 Describe supervised, unsupervised, and reinforcement learning.

#### Task Statement 1.2: Identify Practical Use Cases for AI

- 1.2.1 Recognize applications where AI/ML provides value (decision support, scalability, automation).
- 1.2.2 Determine when AI/ML is not appropriate (cost-benefit, need for specific outcomes).
- 1.2.3 Select appropriate ML techniques (regression, classification, clustering).
- 1.2.4 Identify real-world AI applications (computer vision, NLP, speech recognition, recommendation, fraud detection, forecasting).
- 1.2.5 Explain capabilities of AWS managed AI/ML services (SageMaker, Amazon Transcribe, Amazon Translate, Amazon Comprehend, Amazon Lex, Amazon Polly).

#### Task Statement 1.3: Describe the ML Development Lifecycle

- 1.3.1 Describe ML pipeline components: data collection, EDA, data pre-processing, feature engineering, model training, hyperparameter tuning, evaluation, deployment, monitoring.
- 1.3.2 Understand sources of ML models (open source pre-trained, custom training).
- 1.3.3 Describe production model usage (managed API, self-hosted API).
- 1.3.4 Identify AWS services for each pipeline stage (SageMaker, Data Wrangler, Feature Store, Model Monitor).
- 1.3.5 Understand MLOps concepts (experimentation, repeatability, scalability, technical debt, production readiness, monitoring, re-training).
- 1.3.6 Understand model and business performance metrics (accuracy, AUC, F1, cost per user, development costs, customer feedback, ROI).

---

### Domain 2: Fundamentals of Generative AI

#### Task Statement 2.1: Explain Basic Concepts of Generative AI

- 2.1.1 Understand concepts: tokens, chunking, embeddings, vectors, prompt engineering, transformer-based LLMs, foundation models, multi-modal models, diffusion models.
- 2.1.2 Identify use cases: image, video, audio generation; summarization; chatbots; translation; code generation; customer service; search; recommendation.
- 2.1.3 Describe foundation model lifecycle: data selection, model selection, pre-training, fine-tuning, evaluation, deployment, feedback.

#### Task Statement 2.2: Understand Capabilities and Limitations of Generative AI

- 2.2.1 Describe advantages: adaptability, responsiveness, simplicity.
- 2.2.2 Identify disadvantages: hallucinations, interpretability, inaccuracy, nondeterminism.
- 2.2.3 Understand factors for model selection: types, performance, capabilities, constraints, compliance.
- 2.2.4 Determine business value and metrics: cross-domain performance, efficiency, conversion rate, average revenue per user, accuracy, customer lifetime value.

#### Task Statement 2.3: Describe AWS Infrastructure and Technologies for Generative AI

- 2.3.1 Identify AWS services for generative AI: SageMaker JumpStart, Bedrock, PartyRock, Amazon Q.
- 2.3.2 Describe advantages of AWS generative AI services: accessibility, lower barrier to entry, efficiency, cost-effectiveness, speed to market, business objectives.
- 2.3.3 Understand AWS infrastructure benefits: security, compliance, responsibility, safety.
- 2.3.4 Understand cost tradeoffs: responsiveness, availability, redundancy, performance, regional coverage, token-based pricing, provision throughput, custom models.

---

### Domain 3: Applications of Foundation Models

#### Task Statement 3.1: Describe Design Considerations for Applications Using Foundation Models

- 3.1.1 Identify selection criteria for pre-trained models: cost, modality, latency, multi-lingual, model size, complexity, customization, input/output length.
- 3.1.2 Understand effect of inference parameters: temperature, input/output length.
- 3.1.3 Define Retrieval Augmented Generation (RAG) and business applications.
- 3.1.4 Identify AWS services for storing embeddings in vector databases: OpenSearch Service, Aurora, Neptune, DocumentDB (MongoDB), RDS for PostgreSQL.
- 3.1.4 Explain cost tradeoffs for customization: pre-training, fine-tuning, in-context learning, RAG.
- 3.1.5 Understand the role of agents in multi-step tasks (e.g., Agents for Amazon Bedrock).

#### Task Statement 3.2: Choose Effective Prompt Engineering Techniques

- 3.2.1 Describe prompt engineering concepts: context, instruction, negative prompts, model latent space.
- 3.2.2 Understand techniques: chain-of-thought, zero-shot, single-shot, few-shot, prompt templates.
- 3.2.3 Understand benefits and best practices: response quality, experimentation, guardrails, discovery, specificity, concision, multiple comments.
- 3.2.4 Define risks and limitations: exposure, poisoning, hijacking, jailbreaking.

#### Task Statement 3.3: Describe Training and Fine-Tuning Process for Foundation Models

- 3.3.1 Describe key elements: pre-training, fine-tuning, continuous pre-training.
- 3.3.2 Define fine-tuning methods: instruction tuning, domain adaptation, transfer learning, continuous pre-training.
- 3.3.3 Describe data preparation: curation, governance, size, labeling, representativeness, RLHF.

#### Task Statement 3.4: Describe Methods to Evaluate Foundation Model Performance

- 3.4.1 Understand evaluation approaches: human evaluation, benchmark datasets.
- 3.4.2 Identify relevant metrics: ROUGE, BLEU, BERTScore.
- 3.4.3 Determine if a model meets business objectives: productivity, user engagement, task engineering.

---

### Domain 4: Guidelines for Responsible AI

#### Task Statement 4.1: Explain Development of Responsible AI Systems

- 4.1.1 Identify features: bias, fairness, inclusivity, robustness, safety, veracity.
- 4.1.2 Use tools to identify responsible AI features (e.g., Guardrails for Amazon Bedrock).
- 4.1.3 Understand responsible model selection practices: environmental considerations, sustainability.
- 4.1.4 Identify legal risks: intellectual property, bias, customer trust, end user risk, hallucinations.
- 4.1.5 Identify dataset characteristics: inclusivity, diversity, curated sources, balanced datasets.
- 4.1.6 Understand effects of bias and variance: demographic impact, inaccuracy, overfitting, underfitting.
- 4.1.7 Describe tools for bias, trustworthiness, and truthfulness: label quality analysis, human audits, subgroup analysis, SageMaker Clarify, Model Monitor, Augmented AI (A2I).

#### Task Statement 4.2: Recognize Importance of Transparent and Explainable Models

- 4.2.1 Understand differences between transparent/explainable and non-transparent/non-explainable models.
- 4.2.2 Use tools to identify transparent/explainable models: SageMaker Model Cards, open source models, data, licensing.
- 4.2.3 Identify tradeoffs: model safety vs. transparency (interpretability, performance).
- 4.2.4 Understand human-centered design principles for explainable AI.

---

### Domain 5: Security, Compliance, and Governance for AI Solutions

#### Task Statement 5.1: Explain Methods to Secure AI Systems

- 5.1.1 Identify AWS services/features for security: IAM roles, policies, permissions; encryption; Amazon Macie; AWS PrivateLink; shared responsibility model.
- 5.1.2 Understand source citation and data origin documentation: data lineage, cataloging, SageMaker Model Cards.
- 5.1.3 Describe secure data engineering best practices: data quality assessment, privacy-enhancing technologies, access control, data integrity.
- 5.1.4 Understand security and privacy considerations: application security, threat detection, vulnerability management, infrastructure protection, prompt injection, encryption at rest/in transit.

#### Task Statement 5.2: Recognize Governance and Compliance Regulations for AI Systems

- 5.2.1 Identify regulatory compliance standards: ISO, SOC, algorithm accountability laws.
- 5.2.2 Identify AWS services/features for governance and compliance: AWS Config, Amazon Inspector, AWS Audit Manager, AWS Artifact, AWS CloudTrail, AWS Trusted Advisor.
- 5.2.3 Describe data governance strategies: data lifecycles, logging, residency, monitoring, observation, retention.
- 5.2.4 Describe governance protocol processes: policies, review cadence, review strategies, governance frameworks (e.g., Generative AI Security Scoping Matrix), transparency standards, team training requirements.

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