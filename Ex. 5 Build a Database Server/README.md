# Lab 5 – Build a Database Server (AWS)
## Author
* **Name**: DEEPIKA G
* **Register Number**:212224040060
* **Date of Submission**: 20-11-2026

---

## Objective

The objective of this experiment is to understand how to deploy and configure a database server in AWS. This lab focuses on launching an EC2 instance, installing a database management system (DBMS), configuring basic database settings, creating a sample database, and validating connectivity to the database server.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing VPC and EC2 knowledge (from previous labs)
* Basic knowledge of Linux commands and SQL

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Security Groups
* SSH Client (Terminal / PuTTY)
* MySQL / MariaDB / PostgreSQL (any one)

---

## Tasks Performed

### Task 1: Launch EC2 Instance for Database Server

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type and configure key pair and security group.

---

### Task 2: Configure Security Group for Database Access

Modify the security group to allow:

* SSH (Port 22) for remote access
* Database port (e.g., MySQL – 3306 or PostgreSQL – 5432)

---

### Task 3: Connect to EC2 Instance

Connect to the EC2 instance using SSH from your local machine.

---

### Task 4: Install Database Server

Install a database server software such as MySQL, MariaDB, or PostgreSQL on the EC2 instance using package manager commands.

---

### Task 5: Start and Configure Database Service

Start the database service and configure basic settings such as root password and user privileges.

---

### Task 6: Create a Sample Database

Create a sample database and a table inside it. Insert a few records into the table.

---

### Task 7: Test Database Connectivity

Test the database server by connecting to it locally or remotely and performing basic SQL queries.

---

## Workflow (Student Explanation)

(Write the steps you followed in your own words)
1. I launched an EC2 instance using Amazon Linux 2.
2. I configured the security group to allow SSH and database access.
3. I connected to the EC2 instance using SSH.
4. I installed and started the database server.
5. I created a sample database, inserted records, and tested the connection.

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

(Insert Screenshot Here)

<img width="941" height="1038" alt="Screenshot 2026-11-20 205003" src="https://github.com/user-attachments/assets/30767b88-428d-4e0f-876d-57d79c973555" />
---

### Screenshot 2: Database Service Running

(Insert Screenshot Here)
<img width="1906" height="1032" alt="image" src="https://github.com/user-attachments/assets/ccff4c6e-587d-47fb-a594-0d6053cbe71c" />

---

### Screenshot 3: Sample Database and Table

(Insert Screenshot Here)

<img width="1906" height="1032" alt="image" src="https://github.com/user-attachments/assets/ccff4c6e-587d-47fb-a594-0d6053cbe71c" />

---

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
