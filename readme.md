### **Serverless Product Search API with Event-Driven Processing**  
**Objective:** Develop a serverless product search API using AWS Lambda, API Gateway, DynamoDB, Kinesis, SQS, and SNS. The system should allow users to search for products efficiently and process product additions asynchronously.  

**Project Requirements:**  
- **Product Search:** Enable users to search for products stored in DynamoDB using Global Secondary Indexes (GSI) for optimized queries.  
- **Asynchronous Processing:** Handle product additions through Kinesis and SQS, ensuring real-time analytics or logging.  
- **Admin Notifications:** Notify the admin team via SNS whenever a new product is added.  

---

### **Real-Time Fraud Detection System Using AWS Serverless**  
**Objective:** Build a fully serverless fraud detection system for an e-commerce platform that processes transactions in real-time and detects fraudulent activities.  

**Project Requirements:**  
- **Transaction Ingestion:** Accept transactions via API Gateway, where customers submit purchases through a REST API.  
- **Real-Time Processing:** Stream transactions using Kinesis for immediate fraud analysis.  
- **Fraud Analysis:** Evaluate transactions in AWS Lambda against predefined fraud detection rules.  
- **Flagging Mechanism:** Send suspected fraudulent transactions to an SQS queue for further review.  
- **Data Storage:** Store all transactions (normal and flagged) in DynamoDB for record-keeping.  
- **Alert System:** Send SNS notifications to the fraud investigation team when a transaction is flagged as fraudulent.  

---

### **Serverless Subscription Management System**  
**Objective:** Design a fully serverless subscription management system using AWS Lambda, API Gateway, DynamoDB, Kinesis, SQS, and SNS to handle recurring payments, subscriber tracking, and lifecycle events.  

**Project Requirements:**  
- **Subscription Management:** Allow users to subscribe, upgrade, or cancel their plans.  
- **Recurring Payments:** Automate subscription renewals and manage failed payments.  
- **Lifecycle Tracking:** Monitor activation, renewal, expiration, and cancellation events.  
- **Event-Driven Processing:** Use AWS services to handle asynchronous workflows efficiently.  
- **Notification System:** Notify users via SNS about payment failures, renewals, and cancellations.  
