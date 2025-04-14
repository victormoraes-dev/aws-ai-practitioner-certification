# Multiple-Choice

The multiple-choice question type will be seen on your AWS Certification exam.

Multiple-choice questions have one correct response and three incorrect responses, also known as distractors.

When answering a multiple-choice question, remember the following information:

1. **Read the scenario and question carefully.**

2. **Look for the number of response options required to answer the question.**  
   Multiple-choice questions require you to select one option to answer the question.

3. **Identify keywords or information.**  
   Look for important details in the scenario such as information related to service requirements. Also, watch for keywords in the question like "LEAST", "MOST", "operational overhead", and "cost-effective".

4. **Eliminate incorrect answer choices.**  
   Review the keywords and information you identified to help eliminate incorrect answer choices and select the correct option.

**Multiple-choice question example:**

Which of the following is a responsability of AWS under the AWS shared responsability model?

A. Design a customer's application for disaster recovery

B. Update the guest operating systems on deployed Amazon EC2 instances.

C. Configure new resources within an AWS account.

D. Secure the physical infrastructure


# Multiple-Response

The multiple-response question type will be seen on your AWS Certification exam.

Multiple-response questions have two or more correct responses out of five or more response options. You must select all the correct responses to earn credit for the question. The question will state how many responses to select.

When answering a multiple-response question, remember the following information:

1. **Read the scenario and question carefully.**

2. **Look for the number of response options required.** The question will specify how many response options to select (for example, "Select TWO").

3. **Identify keywords or information.** Look for important details in the scenario, such as service requirements. Also, watch for keywords in the question like "LEAST", "MOST", "operational overhead", or "cost-effective".

4. **Eliminate incorrect answer choices.** Review the keywords and information you identified to help you select the correct options.

**Multiple-choice question example:**

Which of the following are benefits of the AWS Cloud? (Select TWO)

A. Companies need increased IT staff.

B. Capital expenses are replaced with variable expenses.

C. Customers receive the same monthly bill regardless of wich resources they use.

D. Companies gain increased agility.

E. AWS holds responsability for security in the cloud.


# Ordering Question

The ordering question type might be seen on your AWS Certification exam. To answer an ordering question, you will place a list of responses in the order specified in the question. Each question will include a list of 3–5 responses and state how to order the responses. 

### Key Points to Remember:
1. **Read the question carefully.** Look for the phrase “Select and order” in the question.
2. **Identify keywords or information.** Determine what type of responses you are ordering and how to order them. For example:
   - Ordering steps in a process.
   - Ranking information using qualifiers like MOST to LEAST or LEAST to MOST.
3. **Start with the first or last response.** Identify the first or last response in the ordered list and select those responses from the dropdown list initially.
4. **Build the sequence step by step.** Start by ordering the first two responses, then incorporate the next response into the sequence.
5. **Confirm the correct number of responses.** If the question states each response should be selected once, ensure each response is selected only once.

**Multiple-choice question example:**

**Question:** Select and order the AWS infrastructure layers from the following list from LARGEST scope to SMALLEST scope. Each infrastructure layer should be selected one time. (Select and order THREE.)

**Responses:**
- Availability Zone
- AWS Region
- Subnet

**Answer:**
1. AWS Region (LARGEST scope)
2. Availability Zone
3. Subnet (SMALLEST scope)

# Matching Question

The matching question type might be seen on your AWS Certification exam. To answer a matching question, you will match list responses to one or more prompts provided in the question. Each question will include a list of 3–7 responses. The directions in the question will state the number of responses to match and if each response should be selected from each dropdown list once or more than once. You must correctly match all prompts with a response to earn credit for the question.

---

**Matching question example:**

**Question:** Select the correct category of workload from the following list for each AWS service. Each category of workload should be selected one or more times. (Select SIX.)

**Prompts (AWS Services):**
1. Amazon EMR  
2. Amazon Forecast  
3. Amazon Kendra  
4. Amazon QuickSight  
5. AWS Glue  
6. AWS Panorama  

**Responses (Categories of Workload):**
- Analytics  
- Machine Learning  

---

### Example Answer:

| **AWS Service**       | **Category of Workload** |
|------------------------|--------------------------|
| Amazon EMR            | Analytics               |
| Amazon Forecast        | Machine Learning        |
| Amazon Kendra          | Machine Learning        |
| Amazon QuickSight      | Analytics               |
| AWS Glue               | Analytics               |
| AWS Panorama           | Machine Learning        |

---

# Case Study Question Type

The case study question type might be seen on your AWS Certification exam. A case study includes a main scenario and two or more questions. The main scenario remains the same for all questions in the case study. Each question is evaluated separately, meaning you will earn credit for each question you answer correctly.

---

### Example Case Study:

**Scenario:**
A company is building a machine learning application to predict customer churn. The application uses Amazon SageMaker for model training and deployment. The data is stored in Amazon S3, and the company uses AWS Glue for data preparation. The company wants to ensure the solution is secure, cost-effective, and scalable.

---

**Question 1 (Multiple Choice):**
Which AWS service should the company use to monitor the deployed model's performance in real-time?

A. Amazon CloudWatch  
B. Amazon SageMaker Model Monitor  
C. AWS Glue DataBrew  
D. Amazon Macie  

---

**Question 2 (Multiple Response):**
What are the best practices to secure the machine learning application? (Select TWO.)

A. Use IAM roles to grant least privilege access.  
B. Store sensitive data in Amazon S3 without encryption.  
C. Enable encryption at rest and in transit.  
D. Allow public access to the Amazon SageMaker endpoint.  
E. Use hardcoded credentials in the application code.  