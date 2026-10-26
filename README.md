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
- **Serverless Architecture**: AWS completely handles underlying server maintenance, operating system patching, and capacity provisioning.
- **Event-Driven Execution**: Functions execute strictly in response to specific triggers, such as an HTTP request via Amazon API Gateway, changes to an Amazon S3 bucket, or data streams from Amazon Kinesis.
- **Automatic Scaling**: The platform instantly scales from a single request to tens of thousands of concurrent executions based on incoming traffic volume.
- **Granular Billing Model**: You only pay for the exact compute time consumed, measured in millisecond increments. No costs are incurred when your code is idle.


## VPC - Virtual Private Cloud
It is a foundational AWS networking service that lets you launch AWS resources in a logically isolated virtual network. It gives you complete control over your virtual networking environment, mimicking a traditional data center but backed by the scalable infrastructure of AWS.

## AWS Step Functions
AWS Step Functions is a visual workflow service that helps developers use AWS services to build distributed applications, automate processes, orchestrate microservices, and create data and machine learning (ML) pipelines.

### Benefits and features
- **Built-in error handling**: AWS Step Functions tracks the state of each step, so you can automatically retry failed or timed-out tasks, catch specific errors, and recover gracefully, whether the task takes seconds or months to complete.
- **Automatic scaling**: AWS Step Functions automatically scales the operations and underlying compute to run the steps of your application for you in response to changing workloads. Step Functions scales automatically to help ensure the performance of your application workflow remains consistently high as the frequency of requests increases.
- **Pay per use**: With AWS Step Functions, you pay only for the transition from one step of your application workflow to the next, called a state transition. Billing is metered by state transition, regardless of how long each state persists (up to one year).
- **Execution event history**: AWS Step Functions creates a detailed event log for every execution, so when things do go wrong, you can quickly identify not only where, but why. All of the execution history is available visually and programmatically to quickly troubleshoot and remediate failures.
- **High availability**: AWS Step Functions has built-in fault tolerance. Step Functions maintains service capacity across multiple Availability Zones in each region to help protect application workflows against individual machine or data center facility failures. There are no maintenance windows or scheduled downtimes.
