# Infrastructure as Code using AWS CDK

![AWS CDK](https://img.shields.io/badge/AWS-CDK-orange)
![TypeScript](https://img.shields.io/badge/TypeScript-blue)
![Node.js](https://img.shields.io/badge/Node.js-green)
![CloudFormation](https://img.shields.io/badge/AWS-CloudFormation-orange)

## Project Overview

This project demonstrates Infrastructure as Code (IaC) using the AWS Cloud Development Kit (AWS CDK) with TypeScript.

Instead of manually creating AWS resources through the AWS Management Console, the infrastructure is defined as code and synthesized into an AWS CloudFormation template.

The project provisions a deployment-ready cloud architecture containing an Amazon VPC, EC2 instance, S3 bucket, and Security Group.

## Architecture

The infrastructure consists of:

- Amazon VPC
- Public and isolated subnets
- Internet Gateway
- Amazon EC2 instance
- Amazon S3 bucket
- EC2 Security Group
- AWS CloudFormation resources generated through CDK

![Architecture Diagram](architecture.png)

## Features

- Infrastructure as Code using AWS CDK
- TypeScript-based infrastructure definition
- Amazon VPC with multiple Availability Zones
- Public and isolated subnet configuration
- Amazon EC2 instance
- Amazon S3 bucket with versioning
- S3 server-side encryption
- S3 public access blocking
- EC2 Security Group
- CloudFormation template generation
- CloudFormation outputs for deployed resource IDs

## Technologies Used

- AWS CDK v2
- TypeScript
- Node.js
- AWS CloudFormation
- Amazon VPC
- Amazon EC2
- Amazon S3
- AWS IAM

## Project Structure

```text
aws-cdk-infrastructure/
│
├── bin/
│   └── aws-cdk-infrastructure.ts
│
├── lib/
│   └── aws-cdk-infrastructure-stack.ts
│
├── test/
│   └── aws-cdk-infrastructure.test.ts
│
├── screenshots/
│   ├── build.png
│   └── synth.png
│
├── architecture.png
├── README.md
├── LICENSE
├── package.json
├── package-lock.json
├── cdk.json
├── tsconfig.json
└── jest.config.js
