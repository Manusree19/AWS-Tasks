# Task 02 – Connect to EC2 Instance (MyFirstEC2)

## 🎯 Objective
Connect to the launched Amazon EC2 instance using **EC2 Instance Connect** from the AWS Management Console and access the Linux terminal.

---

## 📝 Steps

### Navigate to AWS Console
- Sign in to the **AWS Management Console**
- Search for **EC2** in the search bar
- Click **EC2** to open the EC2 Dashboard

### Open Instances
- In the left navigation panel, click **Instances**
- Select the instance **MyFirstEC2**

### Connect to the Instance
- Click the **Connect** button
- Select **EC2 Instance Connect**
- Ensure the following settings:

| Setting | Value |
|-------|-------|
| Connection Type | Connect using a Public IP |
| Username | ec2-user |

- Click **Connect**

### Access the Terminal
A browser-based terminal will open, allowing you to run commands on the EC2 instance.

---

## ✅ Verification

- The terminal opens successfully
- The prompt displays the EC2 user

