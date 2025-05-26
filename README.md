# Ex.2: Cloud Storage Creation (S3) And Launching An (Ec2) Instance In Aws
 Name: SHAHIN J
 
 Register Number: 212223040190
# Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS.

# Procedure:
# a) Steps to Create a first S3 Bucket:
```
Step 1: Sign in to the AWS Management Console
        Go to https://console.aws.amazon.com/s3.
Step 2: Open the S3 Service. In the console, type S3 in the search bar and select S3 to open the service dashboard.
Step 3: Create Bucket. Click the Create bucket button.
Step 4: Configure Bucket Settings
• Bucket name: Choose a globally unique name.
• AWS Region: Select the region where you want to store your data.
Step 5: Object Ownership
Choose between:
▪ ACLs disabled (recommended) – Bucket owner has full control.
▪ ACLs enabled – Control access via access control lists.
Step 6: Block Public Access Settings. By default, all public access is blocked. Leave it as-is unless you need public access.
Step 7: Bucket Versioning (optional). Choose whether to enable versioning for objects in the bucket.
Step 8: Encryption (optional). Select encryption options (SSE-S3, SSE-KMS, or none).
Step 9: Advanced Settings (optional). Add tags, configure logging, etc.
Step 10: Create the Bucket. Click Create bucket at the bottom of the page.
```
# b) i. Steps to launch an EC2 Instance
```
1. Go to the EC2 Dashboard in AWS Console.
2. Click on “Launch Instance”.
3. Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).
4. Select an instance type (e.g., t2.micro for Free Tier).
5. Create or choose a key pair for SSH access.
6. Configure network settings (use default VPC/subnet).
7. Configure storage (default root volume is fine).
8. Review the settings and click “Launch Instance”.
9. Wait for the instance to enter the running state.
```
# c) Step 3: Connect to Your Instance

• Linux: Use SSH command with your .pem key.
• Windows: Use RDP with decrypted admin password.

# d) Steps to Clean Up (Terminate the Instance)

1. Go to EC2 Instances.
2. Select your instance → Instance State → Terminate.

# Output:
![image](https://github.com/user-attachments/assets/c8ab4002-b6d2-4ae1-b87f-a46c980d16f6)
![image](https://github.com/user-attachments/assets/bab92364-0a88-4b5a-987b-044741c9eb3f)
![image](https://github.com/user-attachments/assets/406a24e4-b233-4f60-8050-64f4f0c40b7e)
![image](https://github.com/user-attachments/assets/b9fe4112-7cb7-41e3-bd46-b000cf473ebf)
![image](https://github.com/user-attachments/assets/462df3e8-6c3b-4de9-a2c5-72b026c390cf)
![image](https://github.com/user-attachments/assets/a195157b-c4b4-44dc-b05b-575f983daa2e)

# Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS.
