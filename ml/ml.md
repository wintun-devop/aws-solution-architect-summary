### Amazon Comprehend (powerful natural language processing (NLP) solutions)
```
https://docs.aws.amazon.com/comprehend/latest/dg/what-is.html
```
- Amazon Comprehend is a natural language processing (NLP) service from AWS that helps analyze and understand text using machine learning.Commonly usage as follow:
 - Sentiment Analysis – Identifying whether a text expresses positive, negative, neutral, or mixed sentiments.
 - Entity Recognition – Extracting key information like names, dates, locations, and organizations from text.
 - Key Phrase Extraction – Identifying the most important phrases in a piece of text.
 - Language Detection – Automatically determining the language of a given text.
 - Topic Modeling – Grouping documents by topics without requiring pre-labeled data.
 - Syntax Analysis – Breaking sentences into parts of speech to understand grammatical structure.
 - Custom Classification – Training models to classify text according to specific categories.

### Amazon Polly (Test to speech)
```
https://docs.aws.amazon.com/connect/latest/adminguide/text-to-speech.html
```
- Amazon Polly is a text-to-speech (TTS) service from AWS that converts written text into spoken words using deep learning technologies. It’s designed to create natural, human-like speech and is commonly used for:
 - Voice-Enabled Applications – Integrating speech capabilities into websites, mobile apps, and IoT devices.
 - Content Narration – Converting articles, blogs, or ebooks into spoken audio.
 - Assistive Technology – Providing accessibility for visually impaired users.
 - Call Center Automation – Improving customer interactions with automated voice responses.
 - Multilingual Speech – Generating speech in multiple languages and accents.
 - Real-Time Streaming – Delivering speech instantly for live applications.
 - Custom Voice – Using voice synthesis markup language (SSML) to personalize speech output.


### Amazon Connect (Cloud Base Contact Center)
```
https://docs.aws.amazon.com/connect/latest/adminguide/connect-feature-overview.html
```
- Amazon Connect is a cloud-based contact center service that helps businesses manage customer interactions seamlessly. It's designed for scalability, automation, and AI-driven insights, making it useful for various applications like:
 - Inbound & Outbound Calls – Handling customer service, sales, and support calls.
 - Chat & Messaging – Engaging customers via web chat or SMS.
 - Automatic Call Routing – Directing calls to the right agents based on skill and availability.
 - AI-Powered Assistants – Using Amazon Lex for chatbots and Amazon Comprehend for sentiment analysis.
 - Call Recording & Analytics – Monitoring conversations for compliance and performance insights.
 - Custom Integrations – Connecting to CRM systems and third-party applications.
 - Self-Service Options – Allowing customers to resolve inquiries using IVR (interactive voice response).


### Amazon Lex Developer Guide
- Amazon Lex (AI Chat Bot)
```
https://docs.aws.amazon.com/lex/
```

### Amazon QuickSight
 - Business intelligence (BI) tool that allows users to create interactive dashboards and visualizations. It helps businesses    
   analyze data and gain insights using machine learning-powered analytics.
```
https://docs.aws.amazon.com/quicksight/
```

### Amazon Rekognition (Cloud Base Image and Video Analysis)
```
https://aws.amazon.com/rekognition/
```
```
https://docs.aws.amazon.com/rekognition/
```
- Cloud-based image and video analysis service provided by AWS. It uses machine learning to perform a variety of tasks, including Facial 
  Recognition – Identifying people in images and videos.
  - Object and Scene Detection – Detecting objects, activities, and settings in an image.
  - Text Detection – Extracting words and characters from images.
  - Unsafe Content Detection – Identifying inappropriate or explicit content.
  - Celebrity Recognition – Recognizing famous individuals.
  - Face Analysis – Estimating attributes like age range, emotions, and gender.
  - Face Comparison – Determining similarity between faces in different images.
  - Custom Label Detection – Training models to detect specialized objects in images.

### Amazon Forecast(Fully Managed Deep Learning Service for Time-series Forecasting)
```
https://docs.aws.amazon.com/managedservices/latest/userguide/forecast.html
```
```
https://docs.aws.amazon.com/forecast/
```
- Amazon Forecast is a machine learning service from AWS that helps businesses make accurate predictions based on historical data.
  It’s commonly used for:
  - Demand Forecasting – Predicting future product demand to optimize inventory.
  - Financial Planning – Forecasting revenue, expenses, or other business metrics.
  - Workforce Management – Predicting staffing needs based on trends.
  - Supply Chain Optimization – Improving logistics and inventory decisions.
  - Energy Consumption Prediction – Estimating future power usage for efficient resource allocation.
  - Custom Forecasting Models – Creating specialized predictions tailored to unique datasets.
 
### Amazon Fraud Detector(Detect online fraud faster with machine learning)
```
https://docs.aws.amazon.com/frauddetector/latest/ug/what-is-frauddetector.html
```
```
https://v1.maturitymodel.security.aws.dev/en/4.-optimized/fraud-detector/
```
```
https://www.scaler.com/topics/aws/aws-detective/
```
- Amazon Fraud Detector is an AI-powered fraud detection service from AWS that helps businesses identify and prevent fraudulent activities in
  real time. It’s useful for:
  - Online Payment Fraud – Detecting fraudulent transactions before they are processed.
  - Account Takeover Prevention – Identifying suspicious login attempts or unauthorized access.
  - New Account Fraud – Assessing risk when users create new accounts to prevent fake registrations.
  - Loyalty & Rewards Fraud – Protecting against abuse of points, discounts, and promotions.
  - Custom Fraud Models – Training machine learning models using historical fraud patterns.
- It automates fraud detection without requiring deep expertise in machine learning, making it useful for e-commerce, banking, and digital
  services.

### Amazon Kendra(AI-powered enterprise search service)
```
https://aws.amazon.com/kendra/
```
```
https://docs.aws.amazon.com/kendra/
```
- Amazon Kendra is an AI-powered enterprise search service from AWS that helps organizations retrieve relevant information quickly from large
  amounts of unstructured data.
 - Intelligent Search – Finding accurate answers across documents, databases, and web pages.
 - Semantic Understanding – Recognizing context and intent in natural language queries.
 - Enterprise Knowledge Management – Organizing and retrieving information efficiently within a company.
 - Integration with Apps – Embedding search functionality into websites, chatbots, and applications.
 - Document Ranking – Prioritizing the most relevant content in search results.
- It’s valuable for industries that deal with extensive documentation, such as healthcare, legal, financial services, and customer support.


### Amazon Detective
```
https://aws.amazon.com/detective/
```
```
https://docs.aws.amazon.com/detective/latest/userguide/what-is-detective.html
```
### Reference
```
https://v1.maturitymodel.security.aws.dev/en/4.-optimized/detective/
```
- Automatically collects log data from AWS resources and uses machine learning, statistical analysis, and graph theory to generate 
  visualizations that assist in security investigations
- a security service that helps analyze, investigate, and quickly identify the root cause of security findings or suspicious 
  activities in AWS environments.
- Simplifies security investigations by consolidating data from multiple AWS services into an interactive visualization.
- Security teams to quickly analyze suspicious activities, detect anomalies, and understand the context of security findings.
- Usage
  - Security Investigation: Helps security teams analyze potential threats and determine the scope of security issues.
  - Data Aggregation: Automatically collects and processes logs from AWS services like CloudTrail, VPC Flow Logs, and GuardDuty 
    findings.
  - Graph-Based Analysis: Uses graph models to visualize relationships between users, IP addresses, and AWS resources, making 
    investigations more efficient.
  - Historical Data Access: Provides up to a year of historical event data for deeper analysis.Integration with AWS Security Services: 
    Works seamlessly with GuardDuty, AWS Security Hub, and other security tools.
