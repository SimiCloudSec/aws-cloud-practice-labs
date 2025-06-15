# Deliverable 001 – AWS S3 Bucket Creation via CLI

**Date Completed:** June 15, 2025  
**Environment:** Kali Linux VM  
**AWS Profile:** practice  
**Region:** us-east-1  

---

## 🎯 Objective
Create a secure S3 bucket using the AWS CLI and upload a test file. Verify it via CLI and AWS Console, proving hands-on AWS cloud skills.

---

## 🧠 Commands Used

```bash
aws s3 mb s3://s3-practice-simi-001 --region us-east-1 --profile practice
echo "Hello from AWS" > test.txt
aws s3 cp test.txt s3://s3-practice-simi-001 --profile practice
aws s3 ls s3://s3-practice-simi-001 --profile practice
