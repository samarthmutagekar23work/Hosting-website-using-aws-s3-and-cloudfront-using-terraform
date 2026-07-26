# 🌐 Hosting a Static Website using AWS S3 & CloudFront with Terraform

This project demonstrates how to deploy a **secure static website** on AWS using **Terraform**. The infrastructure is fully automated using Infrastructure as Code (IaC), making deployment simple, repeatable, and efficient.

---

## 🚀 Features

- Infrastructure as Code using Terraform
- Amazon S3 Private Bucket
- CloudFront Distribution
- Origin Access Control (OAC)
- Automatic Website File Upload
- Secure Bucket Policy
- HTTPS Support
- Global Content Delivery

---

## 🛠️ AWS Services Used

- Amazon S3
- Amazon CloudFront
- Origin Access Control (OAC)
- IAM Bucket Policy
- Terraform

---

## 📁 Project Structure

```
.
├── main.tf
├── variables.tf
├── local.tf
├── .gitignore
├── README.md
└── www/
    ├── index.html
    ├── style.css
    └── script.js
```

---

## ⚙️ Prerequisites

- AWS Account
- AWS CLI
- Terraform
- Git

---

## 🚀 Deployment Steps

### 1. Clone the repository

```bash
git clone https://github.com/samarthmutagekar23work/Hosting-website-using-aws-s3-and-cloudfront-using-terraform.git

cd Hosting-website-using-aws-s3-and-cloudfront-using-terraform
```

### 2. Configure AWS Credentials

```bash
aws configure
```

### 3. Initialize Terraform

```bash
terraform init
```

### 4. Preview Changes

```bash
terraform plan
```

### 5. Deploy Infrastructure

```bash
terraform apply
```

Type **yes** when prompted.

---

## 🌍 Website Access

After deployment, Terraform will create a CloudFront Distribution.

Open the CloudFront URL in your browser to access the website.

---

## 🧹 Destroy Resources

To delete all AWS resources:

```bash
terraform destroy
```

---

## 📚 What I Learned

- Infrastructure as Code (Terraform)
- Amazon S3
- CloudFront CDN
- Origin Access Control (OAC)
- AWS Bucket Policies
- Secure Static Website Hosting

---

## 👨‍💻 Author

**Samarth Mutagekar**

- GitHub: https://github.com/samarthmutagekar23work

---

⭐ If you found this project helpful, don't forget to **Star** the repository!
