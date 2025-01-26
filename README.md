# Terraform AWS Project: Scalable WordPress Deployment on AWS with EFS Integration

## Getting Started

Follow these instructions to initialize and deploy the infrastructure.

### Prerequisites

Ensure you have the following installed and configured on your local machine:

1. **Terraform** (Version 1.5 or higher)

2. **AWS CLI** (Configured with a user or role with sufficient permissions)

3. **Git** (To clone the repository)

4. **Text Editor/IDE** (e.g., VS Code)

5. An **AWS Account**

### Clone the Repository

Clone the project repository to your local machine:

git clone https://github.com/Akacybersec/Terraform_aws_project.git

cd Terraform_aws_project

### Set Up Environment Variables

### Export the required environment variables for Terraform:

#### Alternatively, configure your AWS credentials using the aws configure command:

### Terraform Initialization

#### Run the following command to initialize Terraform and download necessary providers:


```
terraform init  
```

###Run Terraform Plan


```
terraform plan
```
### Deploy your code

```
terraform apply -auto-approve
```

### Access the Deployed Application

Please remember to destroy the resources to avoid incuring costs when your resources are not in use.


``` 
terraform  destroy  -auto-approve
```

### SERVICES USED
AWS Identity and Access Management (IAM)

Securely manage user identities and control access to AWS services and resources.
Amazon Virtual Private Cloud (VPC)

Create and manage a logically isolated virtual network for launching AWS resources.
Amazon Elastic Compute Cloud (EC2)

Provides scalable and customizable virtual servers to meet your computing needs.
Amazon Relational Database Service (RDS)

A fully managed cloud database service for easy operation and scaling of relational databases.
Amazon Simple Storage Service (S3)

Highly scalable object storage with robust data availability, security, and performance.
Amazon Elastic File System (EFS)

Serverless, elastic file storage that automatically scales to meet demand.
AWS Systems Manager (SSM)

A centralized operations hub for managing AWS applications and resources securely.
AWS Secrets Manager

Simplifies the management, retrieval, and rotation of secrets like database credentials, API keys, and tokens.
AWS Certificate Manager (ACM)

Easily provision and manage SSL/TLS certificates for your AWS resources.
Amazon CloudFront

A high-performance content delivery network (CDN) that enhances security and speeds up content delivery.
