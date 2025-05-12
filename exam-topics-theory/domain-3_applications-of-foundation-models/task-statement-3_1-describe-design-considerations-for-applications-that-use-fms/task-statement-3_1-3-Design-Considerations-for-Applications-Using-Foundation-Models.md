# Task Statement 3.1: Describe Design Considerations for Applications thet Use Foundation Models

# Design Considerations for Applications That Use Foundation Models

## Retrieval Augmented Generation (RAG)

- **RAG Components**:
  - **Retriever**: Searches through a knowledge base to find relevant information.
  - **Generator**: Produces outputs based on the retrieved information.

- **Purpose**: Enables models to access up-to-date and domain-specific knowledge beyond their original training data.

- **Workflow Example**:
  1. The prompt is passed into a query encoder, which embeds the data.
  2. The embedding is sent to a vector database to search for similar embeddings.
  3. The vector database returns similar data, which is mapped back to its original context.
  4. The retriever fetches the relevant data.
  5. The LLM augments the prompt with the retrieved data and generates a completion.

- **Benefits**:
  - Reduces hallucinations by supplementing generative LLMs with factual, external knowledge.
  - Provides accurate and contextually relevant responses.

- **Applications**:
  - Question-answering systems
  - Dialogue systems
  - Content generation using external knowledge

## Vector Databases and Embeddings

- **Vector Databases**: Store embeddings (vector-coded representations) of knowledge articles or data.
- **Real-World Usage**: When querying, the input is embedded and compared to stored embeddings to find relevant information.
- **Common AWS Services for Embedding Storage**:
  - Amazon OpenSearch Service
  - Amazon Aurora
  - Redis
  - Amazon Neptune
  - Amazon DocumentDB (MongoDB compatibility)
  - Amazon RDS with PostgreSQL (supports `pgvector` extension)

- **OpenSearch Capabilities**:
  - Low-latency search and aggregations
  - Visualization and dashboarding tools
  - Advanced plugins for alerting, access control, observability, security monitoring, and vector storage/processing
  - Supports semantic search and RAG with LLMs
  - Vector engine for storage and search, enabling ML-augmented search and generative AI applications

- **Semantic Search**: Improves search results using language-based embeddings (e.g., BERT) for document retrieval.

- **Amazon Bedrock**: Offers fully managed RAG and knowledge base integration, allowing secure connection of foundation models to company data stored as embeddings for more relevant and accurate responses.

## Model Size and Capabilities

- Larger models generally demonstrate higher capability and performance.
- Larger models may require less additional in-context learning or further training to perform tasks effectively.

## Agents in Multi-Step Tasks

- **Foundation Models**: Can understand and respond to queries based on pre-trained knowledge but cannot execute real-world tasks requiring organization-specific data and workflows.
- **Agents**:
  - Software components that orchestrate prompt completion workflows and interactions between user requests, foundation models, and external data sources or applications.
  - Can automatically break down tasks, generate orchestration logic, write custom code, and securely connect to databases via APIs.
  - Ingest and structure data for machine consumption, augmenting it with contextual details for more accurate responses.
  - Can call APIs to take actions and invoke knowledge bases to supplement information.

- **Example Use Case**: An agent that processes customer reservations by interacting with external systems and databases.

---