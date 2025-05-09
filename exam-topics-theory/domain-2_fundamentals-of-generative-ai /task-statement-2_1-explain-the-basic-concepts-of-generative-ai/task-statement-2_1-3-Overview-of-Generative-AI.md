# Task Statement 2.1: Explain the Basic Concepts of Generative AI

## Data Selection and Tokenization

- Generative AI models often utilize pre-trained foundation models.
- Every language-based generative AI model uses a **tokenizer** to convert human text into a sequence of token IDs.
- Each token ID corresponds to a token in the model's vocabulary.

## Vectors and Embeddings

- A **vector** is an ordered list of numbers representing features or attributes of an entity or concept.
- In generative AI, vectors can represent words, phrases, sentences, or other units.
- Vectors encode relationships, associations, analogies, and hierarchies between items.
- **Embeddings** are numerical, vectorized representations of entities (text, image, video, audio).
- Embeddings capture the semantic meaning of tokens.
- Tokens that are close in vector space have similar semantic meanings.
- Embeddings enable the model to statistically represent and understand human language.

## Transformer Networks

- The core element of generative AI is the **transformer network**.
- Transformers use a **self-attention mechanism** to weigh the importance of different parts of the input when generating each output token.
- Self-attention allows the model to capture long-range dependencies and contextual relationships.
- Previous architectures, such as recurrent neural networks (RNNs), struggled with long-range dependencies.

### Self-Attention Mechanism

- For each input token, the model computes a set of **query**, **key**, and **value** vectors.
- The dot products between these vectors determine the attention weights.
- The output for each token is a weighted sum of the value vectors, with weights from the attention scores.
- This process is repeated in multiple layers to build complex representations.

### Position Embeddings

- **Position embeddings** encode the relative position of each token in the sequence.
- They help the model distinguish between identical tokens in different positions, which is important for understanding sentence structure and word order.

## Model Inference and Training

- During inference, the transformer model uses self-attention to compute representations of input sequences, capturing long-term dependencies and enabling parallel computation.
- The transformer architecture consists of an **encoder** and a **decoder**, each with multiple layers and sublayers.
- **Residual connections** and **layer normalization** are used to facilitate training and prevent overfitting.
- **Positional encoding** helps the model capture the order of the sequence without recurrent or convolutional operations.
- During pre-training and fine-tuning, the transformer enables the model to gain contextual understanding from the input data.

## Key Concepts

- **Tokenizer**: Converts text into token IDs.
- **Vector**: Ordered list of numbers representing features.
- **Embedding**: Vectorized representation capturing semantic meaning.
- **Self-Attention**: Mechanism to weigh input parts for each output token.
- **Position Embedding**: Encodes token positions in a sequence.
- **Encoder/Decoder**: Components of the transformer architecture.
- **Residual Connection**: Helps with training deep networks.
- **Layer Normalization**: Stabilizes and accelerates training.
- **Positional Encoding**: Encodes order of tokens in a sequence.

---