# AWS Cloud Foundations Notes
Formação AWS Cloud Foundations

## EC2 - Virtual Machine - Elastic Compute Cloud
It is an Amazon Web Services (AWS) service that provides virtual servers (called instances) in the cloud on demand.

## EBS - Block Storage
Is a high-performance, persistent block storage service designed for use with Amazon Elastic Compute Cloud (EC2) instances.\
It works like a virtual hard drive in the cloud.

## S3 - Simple Storage Service
Amazon S3 (Simple Storage Service) is a fully managed, high-performance object storage service provided by Amazon Web Services (AWS).
- S3 Standard: Frequently accessed, general-purpose data.
- S3 Glacier: Low-cost data archiving and backups with retrieval in hours.

### Buckets 
Fundamental containers used to store objects. Every bucket must have a globally unique name across all of AWS and is tied to a specific geographic region.

### Objects
The basic entities stored in S3. An object consists of the file data itself (ranging from 0 bytes up to 5 TB), a unique identifier called a Key, and metadata describing the file.

## Lambda
AWS Lambda is an event-driven, serverless computing platform provided by Amazon Web Services (AWS). It allows developers to run code for applications or backend services without provisioning, managing, or scaling physical or virtual servers.
Core concepts:
- Serverless Architecture: AWS completely handles underlying server maintenance, operating system patching, and capacity provisioning.
- Event-Driven Execution: Functions execute strictly in response to specific triggers, such as an HTTP request via Amazon API Gateway, changes to an Amazon S3 bucket, or data streams from Amazon Kinesis.
- Automatic Scaling: The platform instantly scales from a single request to tens of thousands of concurrent executions based on incoming traffic volume.
- Granular Billing Model: You only pay for the exact compute time consumed, measured in millisecond increments. No costs are incurred when your code is idle.
