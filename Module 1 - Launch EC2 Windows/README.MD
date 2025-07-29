📝 Project Introduction: Launching a Windows EC2 Instance on AWS
This project demonstrates the complete process of launching a Windows-based EC2 (Elastic Compute Cloud) instance using Amazon Web Services (AWS). 
The aim is to provide a step-by-step walkthrough—from logging into the AWS Console to successfully connecting with the Windows server using Remote Desktop Protocol (RDP).
EC2 Instance (Windows):
EC2 allows users to run virtual servers in the cloud with flexible compute capacity (Virtual Storage, CPU), making it ideal for hosting applications, websites, and remote environments. 
In this project, we specifically focus on creating and configuring a Windows Server EC2 instance, which can later be used for a wide range of purposes like software testing, application hosting, file sharing, and more.
EC2 Instance (Windows):
Once your Windows EC2 instance is launched and connected, you can use it for many real-world tasks, such as:
💼 1. Host a Website or Web Application
Deploy ASP.NET, PHP, or HTML-based websites using IIS (Internet Information Services).
🧪 2. Test and Develop Software
Use the server as a development or testing environment for .NET, Python, Java, etc.
📂 3. File Server / Remote File Access
Store and share files securely via Remote Desktop or file-sharing services.
🖥️ 4. Use as a Remote Desktop Workstation
Access a Windows desktop environment with GUI from anywhere via RDP.
🔐 5. Install and Run Windows-Based Software
Install any software like SQL Server, Visual Studio, or other enterprise tools.
🗃️ 6. Database Server
Host Microsoft SQL Server or MySQL for database management.
📡 7. Run Scheduled Tasks and Scripts
Use Task Scheduler or PowerShell to automate backups, jobs, or maintenance.
🔄 8. Join Domain / Use Active Directory
Integrate your instance into a Windows domain or test Active Directory setups.
Step-by-step process for EC2 Instance Launch (Windows):
Step 1: Open AWS Management Console
📝 Login to the AWS Management Console using your credentials.
Step 2: Navigate to EC2 Dashboard
📝 From the Services menu, click on EC2 to open the EC2 Dashboard.
Step 3: Launch Instance
📝 Click on the “Launch Instance” button to start the setup process for a new EC2 instance. 
 
Step 4: Name Your Instance
📝 Enter a name for your instance (e.g., "Windows-Test-Instance") for easy identification. 
 

Step 5: Choose an Amazon Machine Image (AMI)
📝 Select a Windows-based AMI, such as Microsoft Windows Server 2019 Base.
 
Step 6: Choose Instance Type
📝 Select the desired instance type (e.g., t2.micro for free tier eligible users).
 






Step 7: Create or Choose a Key Pair
📝 Create a new key pair or choose an existing one to securely access your instance later. Download the .pem file. 
 

 






Step 8: Configure Network Settings
📝 Set up your VPC and subnet or use the default settings. Ensure RDP (port 3389) is allowed for Windows access. 
 
Step 9: Configure Storage
📝 Choose the size of your root volume (e.g., 30 GiB for Windows) and type of storage (e.g., General Purpose SSD).
  




Step 10: Launch Instance
📝 Review all settings and click on Launch Instance to begin the provisioning process.
  
Step 11: Instance Launching
📝 You will see a confirmation screen. Click on “View Instances” to monitor your instance status.
  





Step 12: Wait for Instance to Run
📝 Wait until the instance status changes to “running” and passes all status checks. 
 
Step 13: Connect to Instance (RDP)
📝 Select the instance, click on Connect, choose the RDP client tab, and download the Remote Desktop file.
  





Step 14: Get Password
📝 Click on Get Password, upload your key pair .pem file, and decrypt the administrator password. 
  
 
Step 15: Remote Desktop Login
📝 Open the downloaded .rdp file and enter the administrator username and decrypted password to access your instance.
 

✅  Final Step: Successful EC2 Instance Launch
📝 The Windows EC2 instance has been successfully launched and accessed using Remote Desktop Protocol (RDP). 
🎉 Congratulations! Your Windows EC2 instance is up and running.
 

🔻 Step 16: Terminate the EC2 Windows Server
📝 Once your website testing or deployment is complete, and you no longer need the instance, you can terminate it to avoid charges.
✅ Steps:
1.	Select the instance you want to terminate (tick the checkbox).
2.	Click the “Instance State” dropdown at the top.
3.	Choose Terminate Instance.
4.	Confirm when prompted.
 
⚠️ Note: Termination will permanently delete the instance and any data stored on it (unless you created an AMI or Snapshot).


