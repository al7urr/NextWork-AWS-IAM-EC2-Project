# NextWork AWS IAM & EC2 Project

## ✅ Project Overview
In this project, I learned to **launch EC2 instances** and **manage access using IAM**. I created separate **production and development environments**, set up **users, groups, and policies**, and tested permissions to ensure secure access.

![Step 1: Launch EC2 & Tags](NextWork-AWS-IAM-EC2-Project/images/01-ec2-launch-tags.png)

## 🛠 Key Services and Concepts
- **EC2** – Launching and managing virtual servers.  
- **IAM** – Creating users, groups, and permission policies.  
- **Tags** – Organizing resources by environment (production vs development).  
- **Account Alias** – Simplifying console login URLs.  
- **Access Control** – Restricting user actions based on policies.

![Step 2: IAM Policy](NextWork-AWS-IAM-EC2-Project/images/02-iam-policy.png)

## 🔧 Steps Completed
1. Launched **two EC2 instances**: production and development.  
2. Tagged instances with **Env = production/development**.  
3. Created a **JSON IAM policy** to restrict access.  

![Step 3: Account Alias](NextWork-AWS-IAM-EC2-Project/images/03-account-alias.png)

4. Created **IAM user and group** for the intern.  
5. Shared **intern sign-in details** (username & password) for testing.  

![Step 4: Intern Login Details](NextWork-AWS-IAM-EC2-Project/images/04-intern-login-details.png)

6. Tested access:
   - Tried stopping the **production instance** → got **access denied**.  
   - Stopped the **development instance successfully**.  

![Step 5: Production Access Denied](NextWork-AWS-IAM-EC2-Project/images/05-production-error.png)  
![Step 6: Development Stop Success](NextWork-AWS-IAM-EC2-Project/images/06-dev-stop-success.png)

## 📌 Key Learnings
- How to **safely separate development and production environments**.  
- How **IAM policies, groups, and users work together** to control access.  
- Practical experience with **EC2 instance management**.

## ⏱ Time Taken
This project took approximately **1 hour**.  
The most challenging part was **setting up the IAM policy correctly**, and the most rewarding part was **testing the intern's access successfully**.

## 💡 Reflection
I chose this project to **gain hands-on experience with AWS access management and EC2 instances**.  
It helped me understand **secure cloud practices** and gave me confidence to manage real AWS environments.

## 📂 Project Files
- PDF of the project guide: [NextWork-AWS-Project.pdf](NextWork-AWS-Project.pdf)  
- All screenshots are in the `images` folder.
