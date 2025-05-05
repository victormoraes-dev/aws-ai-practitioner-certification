# Task Statement 1.2 Identify Practical Use Cases for AI

# Practical Use Cases for AI

## Utilizing Pre-Trained AI Services

For many common use cases, building and training a custom model is not necessary. Pre-trained AI services, accessible through APIs, can address a wide range of needs efficiently. It is recommended to investigate existing services before investing in custom model development.

---

## Computer Vision

### Amazon Rekognition

- **Type:** Pre-trained deep learning service for computer vision.
- **Capabilities:**
  - Works with images and videos, including streaming video.
  - Face recognition: Verifies identity by comparing images (e.g., employee badge, driver's license).
  - Detects and labels objects for searchable image/video libraries.
  - Real-time object detection in security systems with alerting.
  - Custom object recognition using labeled images.
  - Text detection in images (e.g., street signs).
  - Content moderation: Detects and filters explicit, inappropriate, and violent content; flags content for human review.
- **Example:** Given a reference image, the service can identify the same person in other images or videos and provide a confidence score for matches.

---

## Document and Text Analysis

### Amazon Textract

- **Type:** Optical character recognition and more.
- **Capabilities:**
  - Extracts text, handwriting, forms, and tabular data from scanned documents.

### Amazon Comprehend

- **Type:** Natural language processing service.
- **Capabilities:**
  - Discovers insights and relationships in text.
  - Sentiment analysis (e.g., classifying customer feedback).
  - Detects personal identifiable information (PII) such as names, addresses, emails, phone numbers, and credit card numbers.
  - Returns confidence scores for detected entities.
- **Integration Example:** Content extracted by Amazon Textract can be analyzed by Amazon Comprehend for sentiment or PII detection.
- **Use Case:** Setting a confidence threshold to automatically remove PII from datasets.

---

## Conversational Interfaces

### Amazon Lex

- **Type:** Service for building voice and text interfaces.
- **Capabilities:**
  - Powers chatbots and interactive voice response (IVR) systems.
  - Used in customer service applications to route calls or engage users via chat.

---

## Speech Recognition

### Amazon Transcribe

- **Type:** Automatic speech recognition service.
- **Capabilities:**
  - Supports over 100 languages.
  - Processes live and recorded audio or video.
  - Provides high-quality transcriptions for search and analysis.
  - Real-time captioning for streaming audio.

---