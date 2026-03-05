# AWS IAM Security Demo

This project demonstrates AWS IAM best practices, least privilege enforcement, and secure S3 access control. It serves as a hands‑on showcase of cloud security fundamentals, complete with documentation and screenshots.

---

## Project Objectives
- Demonstrate IAM best practices in AWS
- Show least privilege enforcement with custom policies
- Document secure S3 bucket creation and access control
- Provide recruiter‑ready evidence of hands‑on AWS security skills

---

## Key Learnings
- How to create and manage IAM users and groups
- Writing and testing custom JSON policies
- Enforcing least privilege with access denied scenarios
- Configuring S3 buckets for secure uploads and downloads
- Documenting cloud security projects for professional review

---

## Step‑by‑Step Walkthrough

1. **Created IAM Admin User**
   - Configured MFA and strong password policy
   - Captured screenshot of admin user setup

2. **Created Restricted IAM User**
   - Attached least privilege policy
   - Tested access denial for EC2 and S3

3. **Built Custom Policies**
   - Wrote JSON policy for S3 bucket access
   - Fixed misconfigured permissions and retested

4. **Configured S3 Bucket**
   - Created bucket and uploaded objects
   - Verified upload success and download restrictions

5. **Documented Results**
   - Captured screenshots of access denied scenarios
   - Organized evidence in `screenshots/` folder

---

## Screenshots

### Admin & Restricted Users
![Admin user creation](screenshots/admin-user.png)  
![Restricted user creation](screenshots/restricted-user.png)

### Policies
![Policy fix](screenshots/policy-fix.png)  
![Policy creation](screenshots/policy-creation.png)

### S3 Bucket & Uploads
![Bucket creation](screenshots/bucket-creation.png)  
![S3 account created](screenshots/s3-account-created.png)  
![Upload success](screenshots/s3-upload-success.png)

### Access Control
![Access denied](screenshots/access-denied.png)  
![Access denied EC2](screenshots/access-denied-ec2.png)  
![Object download](screenshots/object-download.png)

### Groups & Overview
![S3 Website Group](screenshots/s3websitegroup.png)  
![IAM Security Demo overview](screenshots/iam-security-demo.png)

---

## Conclusion
This demo highlights practical AWS security skills: enforcing least privilege, managing IAM users and groups, and securing S3 buckets. The screenshots provide recruiter‑ready evidence of hands‑on cloud security implementation.
