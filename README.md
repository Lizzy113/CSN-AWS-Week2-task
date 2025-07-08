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
<img width="957" alt="IAM instance" src="https://github.com/user-attachments/assets/2fcd9ccd-91bc-48e3-a5cb-6cf138b3ebd5" />
*The screenshot shows instance name 'CSN-TASK2' , identity source, region and orgnizational ID*

### 2. Created group and User List
[Screenshot 2025-07-08 114248(https://github.com/user-attachments/assets/36f8175d-1642-4941-904e-0bf1eabd624b)
*shows the name of the group 'csn-assignment2' the user is in clearly*

### 3. Permission Set Assignment Confirmation
<img width="740" alt="group showing the assign permission" src="https://github.com/user-attachments/assets/41407d19-7c40-4bbe-b043-227e5c80b1dd" />
*The screenshot confirm the group created which user'Tommy' is in, was assigned the 'SecurityAudit' for the AWS account.![Screenshot 2025-07-08 114248](https://github.com/user-attachments/assets/8c939ec3-3219-465d-878c-37243b534203)



<img width="957" alt="IAM instance" src="https://github.com/user-attachments/assets/33402a97-a8fe-408d-af95-2e3921067ce8" />




