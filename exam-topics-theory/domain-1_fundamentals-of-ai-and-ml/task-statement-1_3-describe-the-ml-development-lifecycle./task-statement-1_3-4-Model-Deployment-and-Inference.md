# Task Statement 1.3 Describe de ML Development Lifecycle

# ML Development Lifecycle: Model Deployment and Inference

## Model Deployment Overview

After training, tuning, and evaluating a machine learning model, the next step is to deploy the model for inference. Deployment makes the model available for use, allowing it to generate predictions based on new input data.

## Inference Types

- **Batch Inference**
  - Suitable for processing large volumes of data where immediate results are not required.
  - Typically used for scheduled jobs, such as overnight processing of daily sales data.
  - Cost-effective, as compute resources are only used during batch runs.

- **Real-Time Inference**
  - Provides immediate responses to prediction requests.
  - Commonly used in applications requiring instant feedback, such as generative AI or interactive web applications.
  - Clients interact with the model via a REST API over HTTP.

## Inference Workflow Example

1. **Client Request**
   - A client application sends a POST request with input data to an API endpoint.
2. **API Gateway**
   - The request is received by an API gateway, which forwards it to a compute resource running the model.
3. **Model Execution**
   - The compute resource processes the input using the deployed model and generates a prediction.
4. **Response**
   - The prediction result is returned to the client in the API response.

## Containerized Model Deployment

- Model inference code and artifacts are typically packaged as Docker containers.
- Containers can be deployed on various compute resources with a container runtime, including:
  - AWS Batch
  - Amazon Elastic Container Service (ECS)
  - Amazon Elastic Kubernetes Service (EKS)
  - AWS Lambda
  - Amazon Elastic Compute Cloud (EC2)

## Managed Model Hosting

- Managed services can reduce operational overhead by handling endpoint management, scaling, updates, and security.
- Example: A managed service can deploy model artifacts from object storage and a container image from a container registry, then create and manage inference endpoints.

## Inference Options

| Inference Option      | Description                                                                                  | Use Case                                      |
|----------------------|----------------------------------------------------------------------------------------------|-----------------------------------------------|
| Batch Transform      | Offline inference for large datasets. No persistent endpoint required.                       | Large-scale, non-interactive batch processing |
| Asynchronous         | Queues requests and handles large payloads or long processing times. Scales to zero when idle.| High-latency, bursty, or large-payload jobs   |
| Serverless Inference | Real-time inference without provisioning compute instances. Uses event-driven compute.        | Variable or unpredictable traffic patterns    |
| Real-Time Inference  | Persistent, fully managed endpoint for interactive, low-latency responses.                   | Interactive applications, sustained traffic   |

## Inference Endpoint Configuration

- When creating an endpoint, select the appropriate inference option based on workload requirements.
- Managed endpoints support auto scaling and can be configured for different instance types and counts.
- Serverless options use event-driven compute, charging only for active usage.

## Key Considerations

- **Batch Inference:** Best for large, non-urgent jobs.
- **Asynchronous Inference:** Suitable for large or slow requests, with automatic scaling to zero.
- **Serverless Inference:** Ideal for workloads with variable or infrequent traffic.
- **Real-Time Inference:** Required for applications needing immediate, interactive responses.