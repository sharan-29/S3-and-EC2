# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-
```
Name:Sharan Kumar G
Register No:212224230260
```

## AIM :
To create an AWS account, set up a root user, and create an IAM user with specified permissions.

## PROBLEM STATEMENT :
This experiment involves creating an AWS account, configuring security settings for the root user, and setting up an IAM user. IAM users allow for secure, managed access to AWS resources without exposing the main account's root credentials.

## Procedure:
a) Steps to Create a first S3 Bucket:

Step 1: Sign in to the AWS Management Console

Go to https://console.aws.amazon.com/s3.

Step 2: Open the S3 Service

In the console, type S3 in the search bar and select S3 to open the service dashboard.

Step 3: Create Bucket

Click the Create bucket button.

Step 4: Configure Bucket Settings

• Bucket name: Choose a globally unique name.

• AWS Region: Select the region where you want to store your data.

Step 5: Object Ownership

Choose between:

• ACLs disabled (recommended) – Bucket owner has full control.

• ACLs enabled – Control access via access control lists.

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

b) Steps to launch an EC2 Instance

Go to the EC2 Dashboard in AWS Console.

Click on “Launch Instance”.

Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).

Select an instance type (e.g., t2.micro for Free Tier).

Create or choose a key pair for SSH access.

Configure network settings (use default VPC/subnet).

Configure storage (default root volume is fine).

Review the settings and click “Launch Instance”.

Wait for the instance to enter the running state.

c) Connect to Your Instance

• Linux: Use SSH command with your .pem key.

• Windows: Use RDP with decrypted admin password.

Steps to Clean Up (Terminate the Instance)

Go to EC2 Instances.

Select your instance → Instance State → Terminate.

## Output

<img width="1142" height="604" alt="image" src="https://github.com/user-attachments/assets/82feb290-8177-477a-b774-7b67ca6925dc" />

<img width="1438" height="745" alt="image" src="https://github.com/user-attachments/assets/1f95518a-9102-492b-9a84-4f1459a90144" />


<img width="1152" height="593" alt="image" src="https://github.com/user-attachments/assets/ea8a6143-87ba-4f98-8ed7-85736620e3e3" />


<img width="1432" height="740" alt="image" src="https://github.com/user-attachments/assets/7497f562-7732-4a46-993b-90200cedb3d2" />




## RESULT
The AWS account was successfully created, with set up for the root user . Additionally, an IAM user was created with specified permissions, allowing for secure, controlled access to AWS resources without the use of the root account.
