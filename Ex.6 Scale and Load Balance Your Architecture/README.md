# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture

Author : HEMIMA JASLIN V  
Reg no : 212224250006   
Date : 29.05.2026

---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

First, I reviewed the existing EC2 architecture created in the previous experiment.
Then, I created a Launch Template by specifying the AMI, instance type, security group, and user data.
After that, I created an Auto Scaling Group using the launch template and set the minimum, maximum, and desired number of instances.
Next, I created an Application Load Balancer and configured a target group to route traffic to the EC2 instances.
I attached the Auto Scaling Group to the target group so that the load balancer could distribute traffic to the instances.
Then, I configured scaling policies based on CPU utilization using Amazon CloudWatch alarms.
Finally, I tested the setup by generating traffic and observed load balancing and automatic scaling of instances.

## Output Screenshots 


OUTPUT1
<img width="1249" height="635" alt="image" src="https://github.com/user-attachments/assets/e515f5e4-06cb-4d9d-9e05-224bcc829967" />

OUTPUT2
<img width="1234" height="606" alt="image" src="https://github.com/user-attachments/assets/43518bc2-045e-4b0b-a9d2-9e24c206d886" />

OUTPUT3
<img width="1250" height="612" alt="image" src="https://github.com/user-attachments/assets/d1358f24-6879-4ca3-88f5-54bda0c97966" />



## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
