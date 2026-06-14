# -AWS-EC2-Portfolio-Website-Deployment

## Overview
This project demonstrates the deployment of a static portfolio website using Amazon EC2.

## Technologies Used
- Amazon Web Services (AWS)
- EC2
- Ubuntu 22.04 LTS
- SSH
- SCP
- Python HTTP Server
- HTML

## Features
- Launch EC2 instance
- Configure Security Groups
- Connect via SSH
- Transfer files using SCP
- Host a portfolio website
- Public accessibility through EC2 Public IP
- Proper instance shutdown for cost optimization

## Deployment Steps

### Launch EC2 Instance
- Ubuntu 22.04 LTS
- t3.micro (Free Tier)

### Configure Security Groups
- Port 22 (SSH)
- Port 80 (HTTP)

### Connect to EC2

```bash
ssh -i Portfolio.pem ubuntu@<PUBLIC-IP>
