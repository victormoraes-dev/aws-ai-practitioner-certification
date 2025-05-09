# Task Statement 2.2: Understand the Capabilities and Limitations of Generative AI for Solving Business Problems

## Fine-Tuning and Human-Like Responses

- **Fine-tuning with instructions**: Further training of models to better understand prompts and generate more human-like, natural-sounding responses.
- **Benefits**: Improves model performance and sustainability over the original pre-trained version.
- **Challenges**: Generating natural-sounding language can be difficult. Models may produce toxic, combative, or aggressive language, or provide detailed information on dangerous topics due to exposure to vast internet data.

## Risks and Hallucinations

- **Hallucinations**: Occur when a model provides confident but incorrect or misleading answers.
  - Example: Providing disproven health advice as fact.
- **Mitigation**: Always verify model outputs with authoritative sources before relying on them.
- **Harmful Outputs**: Models should not generate offensive, discriminatory, or illicit content.

## Principles for Responsible AI

- **Human Values**: Helpfulness, honesty, and harmlessness are key principles for responsible AI use.
- **Alignment**: Fine-tuning with human feedback can better align models with these values, reducing toxicity and incorrect information.

## Model Interpretability

- **Interpretability**: The ease of understanding a model's predictions.
- **Tradeoff**: Higher interpretability often means lower performance, as simpler models may not capture complex relationships.
- **Methods**:
  - **Intrinsic Analysis**: Suitable for models with low complexity and simple input-output relationships.
  - **Post Hoc Analysis**: Can be applied to both simple and complex models (e.g., neural networks). These methods are often model-agnostic and interpret a trained model based on inputs and outputs.
    - **Local Level**: Focuses on individual data points.
    - **Global Level**: Examines overall model behavior.

## Model Evaluation Metrics

- **Traditional Machine Learning**: Uses metrics like accuracy on deterministic outputs.
- **Large Language Models**: Outputs are non-deterministic and language-based, making evaluation more challenging.
- **Common Metrics**:
  - **ROUGE (Recall-Oriented Understudy for Gisting Evaluation)**: Assesses the quality of automatically-generated summaries by comparing them to human-generated reference summaries.
  - **BLEU (Bilingual Evaluation Understudy)**: Evaluates the quality of machine-translated texts by comparing them to human-generated translations.

---