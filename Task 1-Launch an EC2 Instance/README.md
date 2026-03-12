# Task 01 – Launch EC2 Instance (MyFirstEC2)

## 🎯 Objective
Create and launch an Amazon EC2 instance to provide a virtual server in the AWS cloud using the Free Tier.

---

## 📝 Steps

### Navigate to AWS Management Console
1. Sign in to the AWS Management Console.
2. Search for **EC2** in the search bar.
3. Click **EC2** to open the EC2 Dashboard.

### Launch Instance
1. Click **Launch Instance**.
2. Instance Name: **MyFirstEC2**

### Choose Amazon Machine Image (AMI)
- Select **Amazon Linux AMI (Free Tier eligible)**.

### Choose Instance Type
- Select **t3.micro (Free Tier eligible)**.

### Create Key Pair
1. Click **Create Key Pair**.
2. Key Pair Name: **mykeypair**
3. Download the **.pem file**.

### Configure Network Settings
Allow the following inbound rules:

| Type | Protocol | Port | Source |
|-----|-----|-----|-----|
| SSH | TCP | 22 | Anywhere |
| HTTP | TCP | 80 | Anywhere |

### Configure Storage
- Keep the default storage **8 GB (Free Tier)**.

### Launch Instance
1. Click **Launch Instance**.
2. Wait for the instance to be created.

---

## ✅ Verification

1. Go to **EC2 Dashboard**.
2. Click **Instances**.
3. Confirm the instance **MyFirstEC2** is listed.
4. Verify the **Instance State** shows **Running**.
5. Check the **Public IPv4 address** and instance details.

---

