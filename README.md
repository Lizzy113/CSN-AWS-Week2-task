# CSN-AWS-Week2-task
## Identity and Access Management for secured user and policy management

## Project Overview
This project demonstrates the setup and configuration of AWS IAM Identity Center. The core task involved creating a new user and assigning them a predefined "SecurityAudit" permission set to grant specific, limited access to an AWS account. This showcases fundamental skills in cloud identity and access management.

## Technologies Used
* **AWS IAM Identity Center:** For centralized user and access management.
* **AWS Identity and Access Management (IAM):** (Underlying service for permissions).
* **AWS Management Console:** For performing configurations.

## Key Concepts Demonstrated
* Enabling and configuring AWS IAM Identity Center.
* Creating new users within Identity Center.
* Creating and understanding Permission Sets.
* Assigning users to specific AWS accounts with defined permission sets.
* Utilizing predefined AWS job function policies.

## Steps Taken (Summary)
1.  Enabled AWS IAM Identity Center in the AWS account.
2.  Created a new group with title 'CSN-TASK-2'and also created a new  user named "Tommy" which i added to the group. 
3.  Created a new permission set based on the `SecurityAudit` predefined AWS managed policy, named 'SecurityAudit' Permission.
4.  Assigned the group 'CSN-TASK-2' which user tommy is part of directly to the primary AWS account with the 'SecurityAudit' set.
5.  Verified the successful assignment within the IAM Identity Center console.

## Deliverables (Screenshots)
Here are the screenshots demonstrating the successful completion of the task:

### 1. IAM Identity Center Instance Overview
<img width="957" alt="IAM instance" src="https://github.com/user-attachments/assets/33402a97-a8fe-408d-af95-2e3921067ce8" />
*The screenshot shows instance name 'CSN-TASK2' , identity source, region and orgnizational ID*

### 2. Created group and User List
![Screenshot 2025-07-08 114248](https://github.com/user-attachments/assets/b098979b-2056-4d25-8e58-4241deb434d2)
*shows the name of the group 'csn-assignment2' the user is in clearly*

### 3. Permission Set Assignment Confirmation
*The screenshot confirm the group created which user'Tommy' is in, was assigned the 'SecurityAudit' for the AWS account.
<img width="740" alt="group showing the assign permission" src="https://github.com/user-attachments/assets/9e7ea2a5-2143-4395-a17e-40a6cc0076d9" />






![Screenshot 2025-07-08 114248](https://github.com/user-attachments/assets/b098979b-2056-4d25-8e58-4241deb434d2)
<img width="957" alt="IAM instance" src="https://github.com/user-attachments/assets/33402a97-a8fe-408d-af95-2e3921067ce8" />
<img width="740" alt="group showing the assign permission" src="https://github.com/user-attachments/assets/9e7ea2a5-2143-4395-a17e-40a6cc0076d9" />




