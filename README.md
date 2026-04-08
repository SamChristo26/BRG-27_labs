# Server Environments & Architectures Lab [BRG-ISEA]

## Overview
This lab project focuses on setting up and managing a Linux-based server environment using cloud infrastructure. It includes practical tasks such as virtual machine deployment, system configuration, scripting, and automation.

## 1. Linux Environment Setup
Ubuntu Linux was installed and basic command-line operations were practiced. This includednavigation commands and file management. 
Commands explored: 
-pwd
-ls
-cd
-mkdir
-touch
These commands helped build familiarity with the Linux filesystem and terminal usage

![IMG_8434](https://github.com/user-attachments/assets/45f41dd5-0857-4dbe-a434-d577e058b090)

## Total Cost of Ownership (TCO)
A cost comparision was performed between on-premise infrastructure and cloud- based solutions over a 3 year period 
The analysis considered:
-initial hardware and setup costs
-Maintenance and Operational expenses
-cloud subscribtion pricing 
The results indicated that cloud services provide a more flexible and cost-effecient solution ,especially for small scale deployments 
![IMG_8462](https://github.com/user-attachments/assets/46f7e09c-6d4b-451d-b724-72c777d1d87f)
![IMG_8463](https://github.com/user-attachments/assets/82d33ad7-f4f5-46e8-9a78-a1696ab87339)

##3.Cloud Deployment using AWS EC2 
A virtual server instance was created using [Amazon Web Services ].The instance was configured with Ubuntu Server and accessed remotely via SSH.
Steps completed:
-Launched EC2 instance 
-Configured key pair for authentication
- Connected securely using SSH
- Updated system packages
![IMG_8440](https://github.com/user-attachments/assets/f401ce82-14ae-4ff7-b53c-b187d5ef9157)

  ##4.Web Server Configuration
  A web Server was set up using Nginx.
  After installation , the default webpage was successfully accessed via the instance's public IP address.
  This confirmed that the server was reachable over the network.
![IMG_8446](https://github.com/user-attachments/assets/49afdfd0-5e01-4816-901e-72a3dc40c223)
  ##5.Bash Scripting
  Basic shell scripts were created to automate simple tasks and demonstrate scripting concepts.
  Examples included:
  -Displaying system messages and date
  -Looping through values
  -Conditional checks for file existence
  Scripts were executed and permissions were modified using chmod.
![IMG_8445](https://github.com/user-attachments/assets/1feb687f-900c-47a5-9d21-efcc8e9ed7b9)

  ##6. Task Automation
  Automation was implemented using cron jobs.A script was scheduled to run automatically at a specified time.
  This demonstrates how routine administrative tasks can be automated on a Linux server
![IMG_8456](https://github.com/user-attachments/assets/aca3690d-2b22-46f7-b4ee-467b252cd249)

  ##7.DNS Testing
  DNS functionality was tested using command-line tools such as dig and nslookup.These tools confirmed that server could resolve domain names succesfully
![IMG_8458](https://github.com/user-attachments/assets/30b7a616-2c79-4cc2-b5d1-c1ad70848f41)

  ##8. SSL Tools (Certbot)
  Certbot was installed to manage SSL certificates.The installation was verified to ensure readiness for secure web configurations.
![IMG_8459](https://github.com/user-attachments/assets/9bf11bdc-ddcc-46bd-b90b-1f72940334a2)

  ##9.Additional Service -Docker
  Docker was installed as an additional server service. A test container was excuted to verify functionality .
  This demonstrates the use of containerisation in server enviroments.
![IMG_8460](https://github.com/user-attachments/assets/d8fd5bc0-0791-4533-b584-6b1f7006eda3)

  ## Reflection
This lab provided hands-on exprience in deploying and managing a cloud based server .Several challenges were encountered, particularly with SSH authentication and file permissions,which were resolved through trouble shooting.
Overall ,the lab enhanced my understanding of Linux systems ,cloud computing,and automation.These skills are directly applicable to role such as system adminstation and DevOps
  
