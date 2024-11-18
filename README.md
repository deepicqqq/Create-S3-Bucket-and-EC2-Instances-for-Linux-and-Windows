### CREATE S3 BUCKET AND EC2 INSTANCES FOR LINUX AND WINDOWS
### REG NUMBER : 212223240024
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
![Screenshot 2024-11-18 181406](https://github.com/user-attachments/assets/121a83e1-367b-4c2c-a369-910285b5696b)
![Screenshot 2024-11-18 181451](https://github.com/user-attachments/assets/52d81ebe-574e-487e-90cc-3c80582c43b1)
![Screenshot 2024-11-18 181500](https://github.com/user-attachments/assets/9d422dfd-1eb6-4fbe-b7a2-8a1e8683371d)
![Screenshot 2024-11-18 181517](https://github.com/user-attachments/assets/1eb0167c-f827-470e-8c80-dca447c095d4)
![Screenshot 2024-11-18 181530](https://github.com/user-attachments/assets/5c76be70-492c-4b06-b4d5-36b656dce71f)
![Screenshot 2024-11-18 181545](https://github.com/user-attachments/assets/2c080d37-8847-4227-bcc6-568b02fb1b57)


##RESULT
Successfully created an S3 bucket and EC2 instances for both Linux and Windows, demonstrating cloud resource management on AWS.
  


