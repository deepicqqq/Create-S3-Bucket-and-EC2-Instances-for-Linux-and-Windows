### CREATE S3 BUCKET AND EC2 INSTANCES FOR LINUX AND WINDOWS
### REG NUMBER : 212223240024
### NAME : DEEPIKA P
#### AIM :
To create an S3 bucket and EC2 instances for both Linux and Windows operating systems on AWS.

#### PROBLEM STATEMENT :
This experiment demonstrates the process of setting up cloud infrastructure on AWS by creating an S3 bucket for storage and EC2 instances to host Linux and Windows environments. The goal is to provide an overview of how to configure and interact with these resources effectively, along with commands and screenshots to document the process.

### ALGORITHM :
#### Step 1:
Log in to AWS Console

#### Step 2: Create an S3 Bucket
Navigate to the S3 service.
Click on Create bucket.
Enter a Bucket name and select a Region.
Configure Bucket settings as required (e.g., versioning, public access).
Click on Create bucket to finalize.

#### Step 3: Create an EC2 Instance (Linux)
Go to the EC2 service.
Click on Launch Instance.
Select an Amazon Machine Image (AMI) for Linux (e.g., Amazon Linux 2).
Choose an Instance Type (e.g., t2.micro for free tier).
Configure Instance Details, Storage, and Security Group.
Review and click Launch with a key pair (or create one if needed).

#### Step 4: Create an EC2 Instance (Windows)
Return to the EC2 service and click Launch Instance.
Select a Windows AMI (e.g., Windows Server 2019).
Choose the Instance Type.
Configure Instance Details, Storage, and Security Group.
Review and launch with a key pair (for future login).

#### Step 5: Verify and Connect to Instances
Verify the status of both instances in the EC2 dashboard.
Connect to the Linux instance using SSH.
Connect to the Windows instance using RDP.

## OUTPUT
![Screenshot 2024-11-20 130236](https://github.com/user-attachments/assets/790ea23e-3956-4e99-bb95-b10de855b1ed)
![Screenshot 2024-11-20 130241](https://github.com/user-attachments/assets/68b43b4f-9edc-44a8-a632-06cbf4ee7469)
![Screenshot 2024-11-20 130247](https://github.com/user-attachments/assets/f5d24e33-dbae-436d-8952-4a016ccc0d57)
![Screenshot 2024-11-20 130253](https://github.com/user-attachments/assets/f5f46f87-f4a4-4e92-a97e-c813e8f0fbef)
![Screenshot 2024-11-20 130258](https://github.com/user-attachments/assets/40555f86-47ed-4e58-8283-da03531d5d41)
![Screenshot 2024-11-20 130311](https://github.com/user-attachments/assets/f2279677-a156-419b-bc81-177c580cbd4e)
![Screenshot 2024-11-20 130316](https://github.com/user-attachments/assets/445a4adf-611e-4141-87f0-056d16207beb)

## RESULT
Successfully created an S3 bucket and EC2 instances for both Linux and Windows, demonstrating cloud resource management on AWS.
  


