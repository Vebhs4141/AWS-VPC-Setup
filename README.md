# AWS VPC Setup

This project demonstrates the creation of a Virtual Private Cloud (VPC) in AWS with the following configuration:
- A public subnet in `ap-south-1a` (10.0.0.0/24)
- A private subnet in `ap-south-1b` (10.0.1.0/24)
- An internet gateway for public subnet connectivity
- A NAT gateway for private subnet connectivity
- Custom route tables for subnet routing


## Features
- Secure networking using public and private subnets
- Efficient routing using custom route tables
- Connectivity to the internet for resources in the private subnet through a NAT gateway
