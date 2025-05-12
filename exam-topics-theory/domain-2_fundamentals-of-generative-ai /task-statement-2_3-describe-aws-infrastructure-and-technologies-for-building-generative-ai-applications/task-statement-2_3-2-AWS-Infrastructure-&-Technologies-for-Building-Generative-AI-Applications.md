# Task Statement 2.3: Describe AWS Infrastructure & Technologies for Building Generative AI Applications

# AWS Infrastructure & Technologies for Building Generative AI Applications

## Cost Tradeoffs for AWS Generative AI Services

### Pricing Models for Large Language Models (LLMs)
- **Self-Hosted LLMs**:
  - Pay for computing resources required to run the models.
  - May require a license fee for the LLM.
  - Infrastructure investment and ongoing maintenance are necessary.
- **Token-Based Pricing**:
  - Charges are based on the number of tokens processed.
  - A token can represent a character, word, pixel, or other discrete unit of information.
  - Used by vendors to price API calls.
  - Adds scalability and flexibility.

## AWS Global Infrastructure

- **Architectural Components**:
  - **Regions**: Geographically isolated areas for deploying resources.
  - **Edge Locations**: Used for content delivery and low-latency access.
  - **Availability Zones**: Isolated locations within regions for high availability.
- **Resilience**:
  - Services are designed for global, regional, and availability zone resilience.
  - High availability and fault tolerance are built into many managed services.

## AWS Machine Learning and AI Services Stack

- **Infrastructure Layer**: Provides the foundational compute, storage, and networking.
- **Machine Learning Services Layer**: Includes services such as Amazon SageMaker for building, training, and deploying models.
- **AI Services Layer**: Prebuilt services, algorithms, and models accessible via APIs and SDKs.

## AWS Services for Building Generative AI Applications

### Amazon SageMaker JumpStart
- Model hub for quickly deploying foundation models.
- Supports fine-tuning and deployment of models.
- Enables rapid production and scaling.
- Requires GPUs for fine-tuning and deployment.
- Cost optimization practices:
  - Refer to SageMaker pricing before selecting compute resources.
  - Delete unused model endpoints.
  - Monitor and optimize costs.

### Amazon Bedrock
- Managed service for accessing a variety of foundation models (FMs) via APIs.
- Supports both AWS-curated and third-party models (e.g., Cohere, Stability AI).
- Enables development of generative AI applications at scale.
- Allows importing custom weights for supported model architectures.
- On-demand serving with pay-as-you-go pricing.
- No time-based term commitment.
- Includes Amazon Titan, a general-purpose foundation model for text generation.
- Features:
  - Playgrounds for experimenting with different models and inference parameters.
  - Model evaluations to align use cases with the most suitable foundation model.

### PartyRock
- Playground built on Amazon Bedrock.
- Used for building generative AI applications and learning prompt engineering.
- Example applications: playlist creation, trivia games, recipe generation.

## Considerations for Using Generative AI on AWS

- Training LLMs requires significant investment in research, data collection, and hardware.
- Hosting models independently incurs hardware and storage expenses.
- Generative AI applications can utilize vector databases for storing data as embeddings.
  - Embeddings are vectors that can be compressed, stored, and indexed for advanced search capabilities.

## Advantages of AWS Generative AI Services

- Ability to build and scale generative AI applications for new customer and employee experiences.
- Customization of data and use cases.
- Access to a wide range of industry-leading FMs and LLMs.
- Enterprise-grade security and privacy for generative AI-powered solutions.