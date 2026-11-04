# Cloud-Storage-creation-S3-and-Launching-an-EC2-Instance-in-AWS
## NAME : HALIMA HARISHA A 
## REG NO:212224040094
Ex.2 Cloud storage creation (S3) and launching an (Ec2) instance in AWS
Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS. 
Procedure
a)	Steps to Create a first S3 Bucket:
Step 1: Sign in to the AWS Management Console
Go to https://console.aws.amazon.com/s3.
Step 2: Open the S3 Service
In the console, type S3 in the search bar and select S3 to open the service dashboard.
Step 3: Create Bucket
Click the Create bucket button.
Step 4: Configure Bucket Settings
•	Bucket name: Choose a globally unique name.
•	AWS Region: Select the region where you want to store your data.
Step 5: Object Ownership
Choose between:
	ACLs disabled (recommended) – Bucket owner has full control.
	ACLs enabled – Control access via access control lists.
Step 6: Block Public Access Settings
By default, all public access is blocked. Leave it as-is unless you need public access.
Step 7: Bucket Versioning (optional)
Choose whether to enable versioning for objects in the bucket.
Step 8: Encryption (optional)
Select encryption options (SSE-S3, SSE-KMS, or none).
Step 9: Advanced Settings (optional)
Add tags, configure logging, etc.
Step 10: Create the Bucket
Click Create bucket at the bottom of the page.
b)	i. Steps to launch an EC2 Instance
1.	Go to the EC2 Dashboard in AWS Console.
2.	Click on “Launch Instance”.
3.	Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).
4.	Select an instance type (e.g., t2.micro for Free Tier).

5.	Create or choose a key pair for SSH access.
6.	Configure network settings (use default VPC/subnet).
7.	Configure storage (default root volume is fine).
8.	Review the settings and click “Launch Instance”.
9.	Wait for the instance to enter the running state.

c)	Step 3: Connect to Your Instance
•	Linux: Use SSH command with your .pem key.
•	Windows: Use RDP with decrypted admin password.

d)	Steps to Clean Up (Terminate the Instance)
1.	Go to EC2 Instances.
2.	Select your instance → Instance State → Terminate.


## Snap Shots:

 <img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/26450cb9-255a-4341-a759-d44411bf5466" />

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/4ab9390a-8e2f-4322-bf2d-43fe26665296" />

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/b768ba0b-ed30-4bda-8e5c-a42bb254252d" />

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/02e90d0a-8274-4b3d-ab56-ad6fcfd8052d" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/7f09516c-b4c9-41e5-8911-0f241f30b461" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/03309af9-6681-4719-ae59-7f4b6e0280a9" />

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/7f517554-730e-4926-8722-1f3e19a33ede" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/c3079e55-e5ff-4809-bc89-7c84ee6d952d" />

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/9e2ba393-436b-4736-9465-426c04f87d6e" />

## Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
