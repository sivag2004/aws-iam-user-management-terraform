#  AWS IAM User Management using Terraform

##  Overview

This project automates **IAM user and group management** in AWS using Terraform.

It demonstrates how to implement **role-based access control (RBAC)** and follow **least privilege principles**.

---

##  Features

* Create multiple IAM users dynamically
* Create IAM groups (Education, Engineering, Managers)
* Assign users to groups based on tags
* Attach policies to groups
* Fully automated using Terraform

---

##  Key Concepts

* IAM Users, Groups, Policies
* Role-Based Access Control (RBAC)
* Least Privilege Principle
* Infrastructure as Code (Terraform)

---

##  Tech Stack

* AWS IAM
* Terraform

---

##  Highlights

* Used `for_each` to dynamically create users
* Implemented logic-based group assignment
* Handled real-world IAM permission errors (AccessDenied)
* Built reusable and scalable Terraform code

---

## 🛠️ Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/your-username/aws-iam-user-management-terraform.git
cd aws-iam-user-management-terraform
```

### 2. Initialize Terraform

```bash
terraform init
```

### 3. Apply configuration

```bash
terraform apply
```

---

##  Important Note

Ensure your IAM user has required permissions:

* `iam:CreateUser`
* `iam:CreateGroup`
* `iam:AddUserToGroup`

---

##  Output

* IAM users created successfully
* Users grouped based on department
* Policies attached to groups

---

##  Future Improvements

* Add IAM Roles for EC2
* Implement MFA enforcement
* Use Terraform modules for better structure

---

## 👨‍💻 Author

Sivaganesh T
