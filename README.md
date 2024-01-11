# AWS Three-Tier Web App Deployment

Deployed a highly scalable and available three-tier web application on AWS, focusing on secure and efficient architecture.

## Architecture Overview

![Screenshot 2024-01-11 210047](https://github.com/Its-Lord-Stark/AWS-Three-tier-webApp/assets/126385754/3fe5aa34-9713-4427-b521-ad52ab1a7a01)

## Implementation 
Private VPC:
![VPC](https://github.com/Its-Lord-Stark/AWS-Three-tier-webApp/assets/126385754/cfa118d1-0212-4bf6-9d51-a7eb80f202d4)
Public and Private Instannces:
![Instances](https://github.com/Its-Lord-Stark/AWS-Three-tier-webApp/assets/126385754/7d297fcc-8159-4af1-9c9c-f188d31322a3)
S3 Bucket:
![S3](https://github.com/Its-Lord-Stark/AWS-Three-tier-webApp/assets/126385754/e96bd218-9b0f-4cfe-a5ac-75d3acd54fad)
NAT Gateways:
![NAT](https://github.com/Its-Lord-Stark/AWS-Three-tier-webApp/assets/126385754/e8672620-c5b6-40a3-8751-94cdecd95e2b)
Subnets:
![Subnets](https://github.com/Its-Lord-Stark/AWS-Three-tier-webApp/assets/126385754/762c12bf-3f7c-4893-b262-14970fb5223b)
Preview:
![WebApp](https://github.com/Its-Lord-Stark/AWS-Three-tier-webApp/assets/126385754/c0f45911-edf6-4d4f-9c9f-08f4e426422f)



## Features

- **High Scalability:** Utilized internal and external load balancers for efficient traffic distribution, ensuring the application can scale horizontally.
- **High Availability:** Deployed across two availability zones to ensure continuous service availability.
- **Secure Networking:** Employed a private VPC with 4 private and 2 public subnets, along with Internet and NAT gateways for robust network security.
- **Database Operations:** Web application performs transactional database operations using AWS Aurora.

## Getting Started

1. Clone the repository.
2. Follow this worlshop : https://catalog.us-east-1.prod.workshops.aws/workshops/85cd2bb2-7f79-4e96-bdee-8078e469752a/en-US

## Prerequisites

- Idea about AWS EC2, RDS, S3 ,VPC, Security.
