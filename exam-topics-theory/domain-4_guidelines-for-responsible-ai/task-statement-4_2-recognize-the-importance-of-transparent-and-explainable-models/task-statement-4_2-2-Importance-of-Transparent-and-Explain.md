# Task Statement 4.2: Recognize The Importance Of Transparent And Explainable Models

# Importance of Transparent and Explainable Models

## Tools for Achieving Transparency and Explainability

### Open Source AI Models
- **Open source software** is developed collaboratively and publicly, allowing users to understand the model's construction and inner workings.
- **Transparency** is maximized, instilling confidence in fairness and reducing bias due to diverse contributions.
- **Community involvement** increases the likelihood of identifying and correcting issues with bias or coding.
- **Model safety concerns** may lead some organizations to restrict the use of open source code, preferring proprietary development to limit transparency for safety reasons.

### Proprietary and Hosted Models
- When using fully trained, hosted models, users interact only through APIs without direct access to the model.
- **Transparency** is provided through documentation about responsible AI practices.

### Responsible AI Documentation
- **AI Service Cards**: Provide information on intended use cases, limitations, responsible AI design choices, and best practices for deployment and performance optimization.
    - Examples of services with AI service cards include:
        - Face matching
        - ID analysis
        - PII detection
        - Foundation models for text generation

- **Model Cards**: Document the lifecycle of a model, including design, training, evaluation, datasets, and containers used.

## Explainability Tools

### SageMaker Clarify
- Reports on both bias and explainability.
- **Feature attributions** are provided using Shapley values, indicating the contribution of each feature to model predictions.
- **Partial dependence plots** show how predictions change with different values of a feature.

## Human-Centered AI

### Principles
- **Human-centered AI** prioritizes human needs and values.
- Involves interdisciplinary collaboration (psychologists, ethicists, domain experts).
- Users are engaged in the development process to ensure AI is beneficial and user-friendly.
- Aims to enhance human abilities, not replace them.
- Ensures AI is transparent, explainable, fair, unbiased, and maintains privacy.

### Human Review in AI Systems

#### Amazon Augmented AI (A2I)
- Incorporates human review for samples of AI inferences.
- Configurable to send low-confidence inferences to human reviewers before client delivery.
- Human feedback can be used to retrain models.
- Supports random audits of predictions.
- Reviewers can be internal or sourced via platforms like Mechanical Turk.
- Configurable number of reviewers per prediction.

#### Example Use Case
- Detecting explicit or offensive content in images.
- Human reviewers validate low-confidence predictions to prevent inappropriate content from passing through.

## Reinforcement Learning from Human Feedback (RLHF)

- **RLHF** is used to ensure large language models produce truthful, harmless, and helpful content.
- Reinforcement learning techniques train models to maximize rewards, improving output accuracy.
- Human feedback is incorporated into the reward function.
- A separate reward model is trained using human preferences for model responses.
- The large language model refines its responses based on the reward model's predictions.

### Collecting Human Preferences

- **SageMaker Ground Truth** can be used to collect human rankings of model responses.
- Human workers are presented with multiple responses and asked to rank them for clarity and quality.

## Summary

- Transparent and explainable models are essential for trust, fairness, and responsible AI.
- Tools and documentation, such as open source models, AI service cards, model cards, and explainability reports, support transparency.
- Human-centered AI and human feedback mechanisms further enhance the reliability and alignment of AI systems with human values.