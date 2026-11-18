# Lab 3 – Introduction to Amazon Elastic Compute Cloud (EC2)
## Author

* **Name**: __DEEPIKA G__
* **Register Number**: _212224040060_
* **Date of Submission**: _18-11-2026_

---

## Objective

The objective of this experiment is to understand the fundamentals of Amazon Elastic Compute Cloud (EC2). This lab focuses on launching and managing a virtual server, understanding instance types and AMIs, connecting to an EC2 instance, monitoring its status, and performing basic instance operations such as start, stop, and terminate.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* Web browser with internet connectivity
* Basic knowledge of Linux commands (optional)

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Key Pair
* Security Group
* SSH Client (PuTTY / Terminal)

---

## Tasks Performed

### Task 1: Explore Amazon EC2 Dashboard

Explore the EC2 service dashboard in the AWS Management Console. Observe the different sections such as Instances, AMIs, Instance Types, Key Pairs, Security Groups, and Elastic IPs.

---

### Task 2: Launch an EC2 Instance

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type (t2.micro) under the free tier. Configure basic settings such as instance name, key pair, and security group.

---

### Task 3: Configure Security Group

Configure a security group to allow inbound access:

* SSH (Port 22) from your IP address
* HTTP (Port 80) from anywhere (0.0.0.0/0)

This security group acts as a firewall for the instance.

---

### Task 4: Connect to EC2 Instance

Connect to the running EC2 instance using SSH. Use the downloaded key pair and connect via terminal or PuTTY.

For Amazon Linux:

```
ssh -i "keyname.pem" ec2-user@<Public-IP>
```

---

### Task 5: Perform Basic Instance Operations

Perform the following operations from the EC2 console:

* Stop the instance
* Start the instance
* Reboot the instance

Observe the state changes of the instance.

---

### Task 6: Monitor EC2 Instance

Monitor the EC2 instance using the Monitoring tab. Observe metrics such as CPU utilization, network in/out, and instance status checks.

---

### Task 7: Terminate EC2 Instance

Terminate the EC2 instance after completing the experiment to avoid unnecessary AWS charges.

---

## Workflow (Student Explanation)

(Write the steps you followed in your own words)

Logged into AWS Console and opened the EC2 service.
Launched an EC2 instance using Amazon Linux 2 and t2.micro.
Created a key pair and configured the security group.
Connected to the instance and performed start, stop, and reboot operations.
Monitored the instance and terminated it after completing the lab.

---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Dashboard / Instance List

(Insert Screenshot Here)
<img width="1901" height="1028" alt="Screenshot 2026-11-05 140818" src="https://github.com/user-attachments/assets/a91e50eb-cc58-4029-9cd4-d70047276fb1" />

---

### Screenshot 2: SSH Connection to Instance

(Insert Screenshot Here)
<img width="1918" height="983" alt="Screenshot 2026-11-05 142038" src="https://github.com/user-attachments/assets/4e284b33-54b6-4eed-9253-096bd8b7e18a" />

---

### Screenshot 3: Instance Monitoring / Status

(Insert Screenshot Here)
<img width="1900" height="1031" alt="Screenshot 2026-11-05 142738" src="https://github.com/user-attachments/assets/bf157785-20f7-45a1-ac6f-c56339557b88" />

---

## Result
Thus, the Amazon EC2 instance was successfully launched, configured, connected through SSH, monitored, and managed using basic instance operations such as start, stop, reboot, and terminate.
This experiment provided hands-on experience with Amazon EC2 by demonstrating how to launch, connect, manage, and monitor a virtual server in AWS. It helped in understanding the concept of Infrastructure as a Service (IaaS) and how compute resources can be provisioned and controlled on demand in the cloud.
