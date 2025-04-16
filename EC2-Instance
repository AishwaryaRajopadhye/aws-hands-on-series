# Prerequisites
- AWS account ([Create one here](https://portal.aws.amazon.com/billing/signup))
- IAM user with EC2 access
- Billing enabled for free tier usage
# Step 1: Log into AWS Console
- Go to: https://aws.amazon.com/console
- Sign in using your IAM or root credentials.

![login](https://github.com/user-attachments/assets/aa6232ab-4b80-43b3-8d4a-db40f8b9c78a)
#  Step 2: Navigate to EC2 Dashboard
- On the AWS homepage, search for EC2 in the “Find Services” search bar.
- Click on EC2 to open the EC2 Dashboard.

![ec2-dashboard1](https://github.com/user-attachments/assets/931444b2-dc75-430c-88ea-d8422d3752b1)

![ec2-dashboard2](https://github.com/user-attachments/assets/7372d7eb-4d45-40d0-b710-a0dcde4194a3)

# Step 3: Launch a New Instance
- Click on "Launch Instance".
- Give your instance a name (e.g., MyFirstEC2).

![launch-instance](https://github.com/user-attachments/assets/87b96404-79fd-454b-a7af-b31118a10cd9)

![launch-instance2](https://github.com/user-attachments/assets/5d0c7b9a-17c8-432f-85d9-087f3e04aa4b)


# Step 4: Choose an Amazon Machine Image (AMI)
- Select an Amazon Linux 2 AMI (Free tier eligible) or Ubuntu.
- This is the OS that will run on your instance.

![select-ami](https://github.com/user-attachments/assets/5b0871fc-f2c8-4a85-993d-7ba3ee22958e)

# Step 5: Choose an Instance Type
- Select t2.micro (Free tier eligible).
- You can upgrade later as needed.

![select-instance-type](https://github.com/user-attachments/assets/94923905-4861-4641-98ce-1e138a638b9e)

# Step 6: Configure Key Pair (Login Method)
- Select "Create new key pair".
- Give it a name like test-key, choose .pem, and download it.
- Keep this file safe – it’s your only way to SSH into the instance.

![create-key-pair](https://github.com/user-attachments/assets/f2718cc1-9903-499a-9bfc-fbade64bad8f)

# Step 7: Configure Network Settings
- Create or select a security group.
- Allow SSH (port 22), and optionally HTTP (port 80) if you plan to host a web app.

![security-group](https://github.com/user-attachments/assets/ca909a29-a451-4eed-8844-63503c4fd801)

# Step 8: Review and Launch
- Double-check all settings.
- Click Launch Instance.

![review-launch](https://github.com/user-attachments/assets/9b1d9f07-8112-4ba4-b7f6-31c458c929a4)

# Step 9: View Instance Status
- Go back to the EC2 Dashboard.
- You’ll see your instance initializing under Instances.

![instance-running](https://github.com/user-attachments/assets/d213c275-d51a-4206-8e29-a3d074bfdfc4)

# Step 10: Connect to Your Instance
- Select the instance → Click "Connect".
- Choose SSH client, copy the SSH command.
- In your terminal, run:
   ssh -i "test-key.pem" ec2-user@<your-public-ip>

![ssh-connect](https://github.com/user-attachments/assets/b10110f6-1be8-46e7-833b-2d665a2a67ee)


You now have a running EC2 instance. You can install software, host a website, or even deploy backend applications.!!







  









