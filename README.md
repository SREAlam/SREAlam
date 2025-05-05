# 👋 Alam Zaib Ahmed | Cloud & IaC Specialist ☁️⚡

> *"Terraforming AWS with Go-powered automation - one Monster Energy at a time."*

## 🛠️ Core Expertise

**Infrastructure as Code**  
[![Terraform](https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white)](https://www.terraform.io/)
[![AWS CDK](https://img.shields.io/badge/AWS_CDK-FF9900?logo=amazonaws&logoColor=white)](https://aws.amazon.com/cdk/)
[![Pulumi](https://img.shields.io/badge/Pulumi-8A3391?logo=pulumi&logoColor=white)](https://www.pulumi.com/)

**Cloud Platforms**  
[![AWS](https://img.shields.io/badge/AWS-FF9900?logo=amazonaws&logoColor=white)](https://aws.amazon.com)
[![AWS Certified](https://img.shields.io/badge/-AWS_Certified-FF9900?logo=amazonaws&logoColor=white)](https://www.credly.com)

**Programming**  
[![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)](https://golang.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://python.org/)

**DevOps Toolchain**  
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)](https://kubernetes.io/)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)](https://github.com/features/actions)

## 🚀 Recent IaC Projects

- **Multi-Cloud Terraform Modules** - Reusable modules for AWS/GCP deployments
- **AWS Landing Zone** - Automated account provisioning with SCPs and Guardrails
- **K8s Operator in Go** - Custom controller for managing cloud resources
- **Serverless Framework** - Lambda-based event processors with Python

## 📜 Certifications
[![AWS Certified](https://img.shields.io/badge/AWS-Certified-FF9900?logo=amazonaws&logoColor=white)](https://www.credly.com)
[![Terraform Certified](https://img.shields.io/badge/Hashicorp-Certified-7B42BC?logo=terraform&logoColor=white)](https://www.hashicorp.com/certification)
[![Kubernetes Certified](https://img.shields.io/badge/CNCF-Certified-326CE5?logo=kubernetes&logoColor=white)](https://www.cncf.io/certification/)

> *"Validating cloud expertise between energy drink sips"*

## 💻 Code & Contributions

```python
# Simple AWS S3 Terraform module in Python CDK
from aws_cdk import (
    aws_s3 as s3,
    core
)

class SecureBucketStack(core.Stack):
    def __init__(self, scope: core.Construct, id: str, **kwargs) -> None:
        super().__init__(scope, id, **kwargs)
        
        s3.Bucket(
            self, "SecureDataLake",
            encryption=s3.BucketEncryption.S3_MANAGED,
            block_public_access=s3.BlockPublicAccess.BLOCK_ALL
        )
