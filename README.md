# aws-proserve-network-foundations

AWS ProServe Network Foundations
Overview

This repository focuses on mastering AWS networking fundamentals from a Professional Services (ProServe) and Cloud Architect perspective. The goal is to design secure, scalable, and cost-efficient VPC architectures while documenting decisions as if delivering to an enterprise customer.

This project is part of a structured 12-week preparation plan targeting AWS ProServe and Technical Account Manager roles.

Objectives

Understand Amazon VPC core components and traffic flow

Design multi-AZ network architectures

Apply security best practices using Security Groups and NACLs

Implement internet access patterns using Internet Gateway and NAT Gateway

Evaluate cost implications of networking decisions

Document architecture and trade-offs like a consultant

Weekly Deliverables

VPC architecture diagram

Hands-on AWS lab completion

Spanish technical notes

Cost estimate and design rationale

Final checklist

Architecture Scope (Week 1)

One VPC (10.0.0.0/16)

Two Availability Zones

Public and private subnets per AZ

Internet Gateway attached to the VPC

NAT Gateway in a public subnet

Route tables for public and private traffic

EC2 instances for validation testing

Repository Structure
aws-proserve-network-foundations/
├── README.md
├── diagrams/
│   └── vpc-day1.png
├── notes-es/
│   └── day1.md
├── labs/
│   └── vpc-lab-notes.md
How to Use This Repository

Follow the daily tasks outlined in the training plan

Complete AWS console labs

Save diagrams under /diagrams

Write Spanish learning notes under /notes-es

Document lab results in /labs

Commit progress daily

Success Criteria

By the end of this phase, this repository should demonstrate:

Clear understanding of AWS networking fundamentals

Consultant-style documentation

Production-ready security considerations

Cost-aware architecture design

Ability to explain traffic flows to customers

Target Roles

AWS Professional Services Consultant / PCA (L5)

AWS Technical Account Manager (TAM)
