# ✅ Task 4: IAM Policy for S3 Read-Only Access

## 🎯 Objective:
To implement secure and restricted access to an S3 bucket by creating a dedicated IAM user with **read-only permissions**.

This task demonstrates Identity and Access Management (IAM) practices in AWS by granting **minimal access** needed for users to safely interact with storage resources.

---

## 🛠 Tools & Services Used:
- **AWS IAM**
- **Amazon S3**
- **IAM Policy Attachments**

---

## 🔐 What I Did:
- Created an IAM user without AWS Console access
- Attached the managed policy: `AmazonS3ReadOnlyAccess`
- Verified read-only permissions using credentials

---

## 📄 Policy Used:
### ✅ Attached IAM Policy:
AmazonS3ReadOnlyAccess  
(ARN: `arn:aws:iam::aws:policy/AmazonS3ReadOnlyAccess`)

---

## 📷 Screenshot:
![IAM Access Screenshot](Screenshot%202025-07-18%20083034.png)

---

## 🏢 Internship:
This project was developed as part of my Cloud Internship at **Cyberoid Technology Pvt. Ltd.**, mentored by **Elite Techno Groups**.

---

## 🔖 Tags:
#AWS #IAM #S3 #ReadOnlyAccess #BucketPolicy #CloudSecurity #CloudInternship #EliteTechnoGroups #KrishJain


