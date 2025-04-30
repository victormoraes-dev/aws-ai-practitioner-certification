# Basic AI Concepts and Terminologies

## Model Artifacts and Deployment

- **Model Artifacts**: The output of the training process, typically including:
  - Trained parameters (weights)
  - Model definition (architecture for inference)
  - Metadata
- **Packaging and Deployment**:
  - Artifacts are stored and packaged with inference code (software that loads the model and performs predictions) to create a deployable model.

## Model Hosting Options

1. **Real-Time Inference**
   - An endpoint is always available to accept inference requests.
   - Suitable for online, low-latency, high-throughput requirements.
   - The model is deployed on a persistent endpoint to handle a continuous flow of requests.
   - Clients send input data and receive predictions quickly.

2. **Batch Inference**
   - Used for offline processing of large datasets.
   - No persistent endpoint; resources are provisioned only during batch processing.
   - Suitable when results can be delayed and cost efficiency is important.
   - Example: Processing historical sales data monthly to forecast inventory needs.

**Key Difference**:
- Real-time inference requires always-on compute resources.
- Batch inference provisions resources only when needed, then shuts them down.

## Machine Learning Styles

### 1. Supervised Learning

- **Definition**: Model is trained on labeled data (input-output pairs).
- **Example**: Image classification (e.g., identifying fish in images).
- **Process**:
  - Model learns to map inputs (images) to outputs (labels: fish/not fish).
  - Training adjusts internal parameters to improve prediction accuracy.
- **Output**: Model predicts the probability of a given input belonging to a class.
- **Challenge**: Requires large, labeled datasets (manual labeling effort).

### 2. Unsupervised Learning

- **Definition**: Model is trained on data without labels.
- **Capabilities**:
  - Finds patterns, clusters, or groups in the data.
  - Useful for pattern recognition, anomaly detection, and automatic categorization.
- **Example**: Clustering network traffic to identify security incidents.
- **Advantage**: No need for labeled data; setup is straightforward.
- **Use Case**: Detecting sensor anomalies (e.g., identifying a failing temperature sensor).

### 3. Reinforcement Learning

- **Definition**: Focuses on autonomous decision-making by an agent in an environment.
- **Process**:
  - Agent takes actions to achieve specific goals.
  - Learns through trial and error; actions are rewarded or penalized.
  - No labeled input required.
- **Exploration**: Agent must sometimes try new actions to learn effectively.
- **Example**: An autonomous agent navigating a track, where the agent is the car, the environment is the track, actions are movements, and the goal is to stay on track and finish efficiently.

## Comparison of Learning Styles

| Learning Style         | Labeled Data Required | Example Use Case                | Output Type         |
|-----------------------|----------------------|---------------------------------|---------------------|
| Supervised Learning   | Yes                  | Image classification            | Class probabilities |
| Unsupervised Learning | No                   | Clustering, anomaly detection   | Groups, patterns    |
| Reinforcement Learning| No                   | Autonomous control              | Policy/strategy     |

- Unsupervised and reinforcement learning both operate without labeled data, but reinforcement learning has a specific end goal and uses rewards to guide learning.