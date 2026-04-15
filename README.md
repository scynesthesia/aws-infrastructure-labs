# AWS Infrastructure & Security Labs

## Project 1: Multi-Tier High Availability Architecture
This project demonstrates a secure, resilient VPC design aligned with AWS Best Practices.

![Architecture Diagram](./Docs/aws-multi-tier-architecture.png)

### Key Features:
* **High Availability:** Resources deployed across two Availability Zones.
* **Network Isolation:** EC2 instances reside in private subnets with no direct internet access.
* **Secure Egress:** Private instances communicate with the internet via NAT Gateways in the public tier.
* **Load Balancing:** Traffic is distributed via an Application Load Balancer (ALB).

### Project 2: Cloud Security Hardening
* Focused on implementing IAM security standards and monitoring via CloudWatch.
