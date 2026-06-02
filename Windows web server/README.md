
# AWS EC2 Windows Instance with IIS Web Server

## 📌 Project Overview

This project demonstrates how to launch a Windows EC2 instance and configure an IIS (Internet Information Services) Web Server on Amazon Web Services (AWS). The project provides hands-on experience in cloud infrastructure deployment, Windows Server administration, and web hosting using AWS.

---

## 🚀 Project Objectives

* Launch an Amazon EC2 Windows Server instance
* Configure Security Groups for secure access
* Connect remotely using Remote Desktop Protocol (RDP)
* Install and configure IIS Web Server
* Host a sample web page on Windows Server
* Understand AWS networking concepts such as VPC and Availability Zones

---

## 🛠️ Technologies Used

* Amazon Web Services (AWS)
* Amazon EC2
* Windows Server 2022
* IIS (Internet Information Services)
* Remote Desktop Protocol (RDP)
* Virtual Private Cloud (VPC)
* Security Groups

---

## 📋 Prerequisites

Before starting, ensure you have:

* An AWS Account
* Basic understanding of Windows Server
* Remote Desktop Connection (RDP) Client
* EC2 Key Pair

---

## 🏗️ Architecture

```text
User
  │
  ▼
Internet
  │
  ▼
AWS Cloud
  │
  ▼
VPC
  │
  ▼
Security Group
  │
  ▼
Windows EC2 Instance
  │
  ▼
IIS Web Server
```

## 🔧 Implementation Steps

### Step 1: Launch a Windows EC2 Instance

1. Sign in to the AWS Management Console.
2. Navigate to the EC2 Dashboard.
3. Click Launch Instance.
4. Select Windows Server 2022 AMI.
5. Choose the desired instance type.
6. Configure Security Groups:

   * RDP (Port 3389)
   * HTTP (Port 80)
7. Launch the instance.

### Step 2: Connect Using RDP

1. Select the running EC2 instance.
2. Download the Remote Desktop File.
3. Retrieve the Administrator Password.
4. Connect to the instance using Remote Desktop Connection.

### Step 3: Install IIS Web Server

1. Open Server Manager.
2. Select Add Roles and Features.
3. Choose Web Server (IIS).
4. Complete the installation wizard.
5. Verify that IIS is installed successfully.

### Step 4: Create a Sample Web Page

1. Navigate to:

```text
C:\inetpub\wwwroot
```

2. Create or edit the index.html file.

Example:

```html
<!DOCTYPE html>
<html>
<head>
    <title>AWS IIS Web Server</title>
</head>
<body>
    <h1>Welcome to IIS Web Server on AWS EC2</h1>
</body>
</html>
```

### Step 5: Access the Website

Open a browser and enter:

```text
http://<Public-IP-Address>
```

You should see the hosted web page.

---

## 📸 Project Highlights

* Created and configured a Windows Server 2022 EC2 instance
* Installed and configured IIS Web Server
* Configured Security Groups for RDP and HTTP traffic
* Hosted a sample website successfully
* Learned AWS networking and cloud security fundamentals

---

## 🎯 Learning Outcomes

* AWS EC2 Instance Management
* Windows Server Administration
* IIS Web Server Configuration
* Security Group Management
* Cloud Networking Fundamentals
* Website Hosting on AWS

---

## 👨‍💻 Author

**Selvakumar C**
ECE – Electronics and Communication Engineering
Kongu Engineering College, Perundurai

---

## 🙏 Acknowledgement

Special thanks to **Aravindraj Gunasekaran** (CEO & Founder, Nminds Academy) and the entire **Nminds Academy** team for their valuable guidance and support throughout this project.

---

## 📜 License

This project is created for educational and learning purposes.
