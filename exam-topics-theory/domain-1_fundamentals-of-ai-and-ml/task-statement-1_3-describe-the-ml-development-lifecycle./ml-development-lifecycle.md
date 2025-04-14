# ML Development Lifecycle and AWS AI Practitioner Exam Topics

The ML development lifecycle is a structured process that involves several stages to build, deploy, and maintain machine learning models. Below is an overview of the lifecycle, aligned with the AWS AI Practitioner exam topics:

---

## 1. Components of an ML Pipeline

### **Data Collection**
- **Description**: Gather data from various sources (e.g., databases, APIs, IoT devices).
- **AWS Services**: Amazon S3, AWS Glue.

### **Exploratory Data Analysis (EDA)**
- **Description**: Analyze the data to understand its structure, patterns, and anomalies.
- **AWS Services**: Amazon SageMaker Data Wrangler.

### **Data Pre-processing**
- **Description**: Clean and prepare the data (e.g., handling missing values, normalization).
- **AWS Services**: Amazon SageMaker Processing.

### **Feature Engineering**
- **Description**: Extract and create meaningful features from raw data to improve model performance.
- **AWS Services**: Amazon SageMaker Feature Store.

### **Model Training**
- **Description**: Train the model using labeled data (supervised learning) or unlabeled data (unsupervised learning).
- **AWS Services**: Amazon SageMaker Training.

### **Hyperparameter Tuning**
- **Description**: Optimize model parameters to improve performance.
- **AWS Services**: Amazon SageMaker Automatic Model Tuning.

### **Model Evaluation**
- **Description**: Assess the model's performance using metrics like accuracy, F1 score, and AUC.
- **AWS Services**: Amazon SageMaker Clarify (for bias detection and explainability).

### **Model Deployment**
- **Description**: Deploy the model to production for real-time or batch inferencing.
- **AWS Services**: Amazon SageMaker Endpoints, Amazon SageMaker Batch Transform.

### **Model Monitoring**
- **Description**: Continuously monitor the model's performance and retrain if necessary.
- **AWS Services**: Amazon SageMaker Model Monitor.

---

## 2. Sources of ML Models

### **Open-source Pre-trained Models**
- **Description**: Models available from libraries like TensorFlow, PyTorch, or Hugging Face.
- **AWS Services**: Amazon SageMaker JumpStart.

### **Training Custom Models**
- **Description**: Build models tailored to specific use cases using custom datasets.
- **AWS Services**: Amazon SageMaker Studio.

---

## 3. Methods to Use a Model in Production

### **Managed API Service**
- **Description**: Deploy models as managed endpoints for real-time inferencing.
- **AWS Services**: Amazon SageMaker Endpoints.

### **Self-hosted API**
- **Description**: Host the model on custom infrastructure (e.g., Amazon EC2).

---

## 4. Relevant AWS Services for Each Stage

- **Data Collection**: Amazon S3, AWS Glue.
- **EDA and Pre-processing**: Amazon SageMaker Data Wrangler, AWS Glue DataBrew.
- **Feature Engineering**: Amazon SageMaker Feature Store.
- **Model Training and Tuning**: Amazon SageMaker Training, SageMaker Automatic Model Tuning.
- **Evaluation**: Amazon SageMaker Clarify.
- **Deployment**: Amazon SageMaker Endpoints, Batch Transform.
- **Monitoring**: Amazon SageMaker Model Monitor.

---

## 5. MLOps Concepts

### **Experimentation**
- **Description**: Test different models and configurations.
- **AWS Services**: Amazon SageMaker Experiments.

### **Repeatable Processes**
- **Description**: Automate workflows for consistency.
- **AWS Services**: Amazon SageMaker Pipelines.

### **Scalable Systems**
- **Description**: Use scalable infrastructure for training and deployment.
- **AWS Services**: Amazon SageMaker, Amazon EC2.

### **Managing Technical Debt**
- **Description**: Ensure models are maintainable and upgradable.

### **Achieving Production Readiness**
- **Description**: Validate models for deployment.

### **Model Monitoring and Re-training**
- **Description**: Continuously monitor and retrain models to maintain performance.

---

## 6. Model Performance Metrics

### **Technical Metrics**
- Accuracy, F1 Score, AUC (Area Under the Curve).

### **Business Metrics**
- Cost per user, development costs, customer feedback, ROI.

---

By understanding these stages and the corresponding AWS services, you can effectively manage the ML development lifecycle and align with the AWS AI Practitioner exam requirements.