# Task Statement 5.2: Recognize Governance and Compliance Regulations for AI Systems

# Governance and Compliance Regulations for AI Systems

## Emerging Compliance Standards for AI

- **ISO 402001 and ISO 23894 (2023):**
  - Establish mechanisms for assessing and managing risk in AI systems.
  - Provide a framework for organizations to systematically address and control risks related to AI development and deployment.
  - Emphasize responsible AI practices and adoption of AI-specific controls.
  - Foster global interoperability and set a foundation for responsible AI.

- **Compliance Standards:**
  - Highly recommended but not legal requirements in most jurisdictions.

## Regulatory Frameworks

### EU AI Act

- **Overview:**
  - First comprehensive regulation on AI by a major regulator.
  - Assigns AI applications to three risk categories:
    1. **Unacceptable Risk:** Banned outright (e.g., social scoring, facial recognition databases scraping internet images, emotion inference in workplaces/education).
    2. **High Risk:** Subject to specific legal requirements (e.g., CV scanning tools ranking job applicants).
    3. **Low/Minimal Risk:** Largely unregulated.
  - Most AI systems fall under the high-risk category.

- **Requirements for High-Risk Applications:**
  - Establish a risk management system.
  - Conduct data governance.
  - Document compliance.

- **Global Impact:**
  - EU regulations often become global standards (e.g., GDPR).

### NIST AI Risk Management Framework (RMF)

- **Purpose:**
  - Provides guidance for trustworthy, responsible AI development and use.
  - Voluntary framework for organizations designing, developing, deploying, or using AI systems.

- **Framework Functions:**
  - **Govern**
  - **Map**
  - **Measure**
  - **Manage**

- **Risk Estimation:**
  - Risk = Likelihood of event × Severity of consequences.
  - Use a risk matrix to categorize risk levels.

- **Risk Management Process:**
  1. Identify AI use case and stakeholders.
  2. Identify potentially harmful events.
  3. Use risk matrix to determine risk for each event.
  4. Address inherent risk with security controls and monitoring.
  5. Calculate residual risk (risk remaining after mitigations).
  6. Summarize risk levels for an overall system risk rating.

### Algorithmic Accountability

- **Algorithmic Accountability Act (U.S.):**
  - Proposed legislation requiring companies to assess impacts of AI systems.
  - Aims to increase transparency and empower consumers.
  - Seeks to protect against unfair and unexplained AI outcomes.
  - Example: Consumers have the right to know why a loan application was rejected and whether bias was involved.

## Explainability and Transparency

- **Explainability:**
  - Understanding how an AI system arrives at an output.
  - Model-agnostic approaches observe input-output behavior to determine feature importance.
  - Interpretable algorithms (e.g., decision trees, rule-based systems) allow observation of model weights and inner workings.
  - Tradeoffs between interpretability and performance should be considered with regulatory requirements in mind.

- **Transparency:**
  - Disclose to users when they are interacting with generative AI rather than a human.
  - For some applications, deeper explanations of model inferences may be required.

## Bias and Fairness

- **Bias Removal:**
  - Ensure results are not influenced by improper use of personal attributes (e.g., race, sex, gender identity, religion, political affiliation, location).
  - Test and monitor for bias in model results and training data.

- **Tools for Bias Detection:**
  - Use tools to understand variable influence on model behavior and monitor for bias and feature attribution drift.