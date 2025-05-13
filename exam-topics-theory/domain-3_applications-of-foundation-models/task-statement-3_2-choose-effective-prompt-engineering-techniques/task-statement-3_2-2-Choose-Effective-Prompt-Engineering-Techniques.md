# Task Statement 3.2: Choose Effective Prompt Engineering Techniques

# Choose Effective Prompt Engineering Techniques

## Latent Space and Prompting

- **Latent Space**: The internal representation of knowledge within a language model, built from large text datasets such as RefinedWeb, Common Crawl, StarCoder data, BookCorpus, Wikipedia, and C4.
- **Prompt Interaction**: When a prompt is provided, the model references its latent space to generate a response based on statistical patterns.
- **Limitations**: If the latent space lacks sufficient information on a topic, the model may generate hallucinations—responses that are statistically plausible but factually incorrect.

## Model Behavior and Limitations

- Language models generate responses one word at a time, selecting each word based on conditional probability and context.
- Models do not reason; they assemble responses from statistical patterns in their training data.
- Understanding the limitations of a model's latent space is crucial for effective prompt engineering.

## Principles of Prompt Engineering

- **Specificity**: Provide clear instructions, including desired format, examples, style, tone, output length, and context.
- **Examples**: Include sample texts, data formats, templates, code, graphs, or charts to guide the model.
- **Iteration**: Experiment and refine prompts to observe how changes affect responses.
- **Model Awareness**: Understand the strengths and weaknesses of the chosen model.
- **Balance**: Avoid overly vague or complex prompts to reduce unrelated or unexpected answers.
- **Contextual Comments**: Use multiple comments to add context without cluttering tahe prompt.
- **Guardrails**: Implement safety and privacy controls to manage model interactions.

## Risks and Limitations of Prompt Engineering

- **Prompt Injection**: Manipulation of prompts by attackers to produce malicious or undesired responses.
- **Jailbreaking**: Attempts to bypass established safety measures or guardrails.
- **Hijacking**: Changing or manipulating the original prompt with new instructions.
- **Poisoning**: Embedding harmful instructions in messages, emails, or web pages to influence model behavior.

## Guardrails and Safety Controls

- Define undesirable topics within the application context.
- Block specific words or configure thresholds to filter harmful content.
- Filter inputs containing sensitive data.
- Monitor and analyze outputs to detect and mitigate prompt attacks.

## Application of Prompt Engineering

- Use prompt engineering to customize and control pre-trained language models for tasks such as content creation, summarization, question answering, and chatbots.
- Employ APIs and tools to construct, refine, and monitor prompts for high-quality output.

---