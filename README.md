# Cloud-Native Web Application
A scalable, production-ready web application built with modern cloud architecture and DevOps best practices. This full-stack application demonstrates enterprise-level development with automated deployments, infrastructure as code, and comprehensive testing.
Overview
This project showcases a complete cloud-native application lifecycle from development to production deployment on AWS. Features include user authentication, health monitoring, automated CI/CD pipelines, and scalable infrastructure management.

## Architecture

- Application Layer: RESTful API built with Node.js and Express
- Data Layer: PostgreSQL database with optimized queries and migrations
- Cloud Infrastructure: AWS (EC2, RDS, S3, Lambda, CloudWatch)
- Deployment: Automated CI/CD with GitHub Actions
- Infrastructure: Managed through Terraform (IaC)

## Key Features

- User registration and authentication with secure password hashing
- Health check endpoints with database connectivity verification
- File upload and management with AWS S3 integration
- Email notifications via AWS SNS/Lambda
- Automated database backups and disaster recovery
- Comprehensive logging and monitoring with CloudWatch
- Auto-scaling based on traffic patterns
- Zero-downtime deployments

## Technical Highlights

- Integration testing with Jest and SuperTest (80%+ coverage)
- Custom AMI builds with Packer
- Blue-green deployment strategy
- Database connection pooling and optimization
- SSL/TLS encryption and security groups
- Environment-based configuration management

## Getting Started
```
npm install
npm test
npm start
```
## Infrastructure Deployment
Infrastructure is fully automated using Terraform. Includes VPC configuration, load balancers, auto-scaling groups, RDS instances, and S3 buckets.
```
terraform init
terraform plan
terraform apply
```

Author - Sonal Sunil Takaikar
