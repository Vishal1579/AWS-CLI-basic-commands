onfigure AWS CLI:
bash
Copy code
aws configure
This is the initial step to set up the AWS CLI on your machine. It prompts you to enter your AWS Access Key, Secret Key, default region, and output format.
List S3 Buckets:
bash
Copy code
aws s3 ls
Lists all the S3 buckets under your AWS account.
Upload a File to S3:
bash
Copy code
aws s3 cp myfile.txt s3://mybucket/myfile.txt
Uploads myfile.txt from your local system to the specified S3 bucket.
Download a File from S3:
bash
Copy code
aws s3 cp s3://mybucket/myfile.txt myfile.txt
Downloads myfile.txt from the specified S3 bucket to your local system.
List EC2 Instances:
bash
Copy code
aws ec2 describe-instances
Lists all EC2 instances for your account, providing details such as instance IDs, types, states, and more.
Start an EC2 Instance:
bash
Copy code
aws ec2 start-instances --instance-ids i-1234567890abcdef0
Starts an EC2 instance with the specified instance ID.
Stop an EC2 Instance:
bash
Copy code
aws ec2 stop-instances --instance-ids i-1234567890abcdef0
Stops the specified EC2 instance.
Create a Key Pair:
bash
Copy code
aws ec2 create-key-pair --key-name MyKeyPair
Creates an EC2 key pair with the specified name for SSH access to EC2 instances.
Describe Specific EC2 Instance:
bash
Copy code
aws ec2 describe-instances --instance-ids i-1234567890abcdef0
Shows detailed information about the specified EC2 instance.
List IAM Users:
bash
Copy code
aws iam list-users
Lists all IAM users for your AWS account.
