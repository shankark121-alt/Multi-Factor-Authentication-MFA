# AWS Cloud Security: Root Account MFA Hardening & Identity Assurance

# Table of Contents

Overview

Prerequisites

Step-by-Step MFA User Creation & Setup Guide

Step 1: Log in to the AWS Management Console

Step 2: Navigate to IAM Users

Step 3: Select the Target User

Step 4: Access Security Credentials

Step 5: Assign an MFA Device

Step 6: Configure Virtual or Hardware MFA

Step 7: Scan QR Code and Verify Codes

Verification and Testing Login

# 1. Overview

Multi-Factor Authentication (MFA) adds an extra layer of protection on top of your username and password credentials. When MFA is enabled, 
an IAM user must provide their standard credentials (something they know) and a code from their MFA device (something they have) to log in to 
the AWS Management Console.

# 2. Prerequisites

An active AWS Account.

Administrator access or permissions to manage IAM users and security credentials.

A compatible authenticator app installed on a smartphone or computer (e.g., Google Authenticator, Microsoft Authenticator, Authy) if using a virtual MFA device.

# 3. Step-by-Step MFA User Creation & Setup Guide

# Step 1: Log in to the AWS Management Console
  Open your browser and navigate to the AWS Management Console[cite: 1].

  Sign in using your administrator credentials.

# Step 2: Navigate to IAM Users
  In the search bar at the top of the console, type iam and select IAM (Manage access to AWS resources).

  From the left navigation menu under Access management, click on Users.

 <img width="709" height="425" alt="image" src="https://github.com/user-attachments/assets/e4ecbbd8-5ab1-4755-8f17-ae8622bb3526" />

<img width="761" height="418" alt="image" src="https://github.com/user-attachments/assets/d57d4412-eb2e-4ce5-918f-eeb4f177fab0" />

<img width="693" height="359" alt="image" src="https://github.com/user-attachments/assets/0484350b-5929-41e1-8a4d-e49de7e394fa" />


# Step 3: Select the Target User

  Locate and click on the name of the specific IAM user (e.g., shankar) for whom you want to configure MFA.

  <img width="707" height="373" alt="image" src="https://github.com/user-attachments/assets/2a7f9739-fbcf-447a-819f-b9d9a2ff8dfd" />

  <img width="698" height="363" alt="image" src="https://github.com/user-attachments/assets/f13d005c-ca7a-4dfa-8826-6f3c61071e30" />

# Step 4: Access Security Credentials

  Once you are on the user's details page, click on the Security credentials tab.

  <img width="711" height="368" alt="image" src="https://github.com/user-attachments/assets/20197bd3-b05c-4dd0-a6c4-e16043e16816" />

# Step 5: Assign an MFA Device

 Scroll down to the Multi-factor authentication (MFA) section.

  Click the Assign MFA device button.

  <img width="701" height="353" alt="image" src="https://github.com/user-attachments/assets/26fd30bf-e37f-4d04-af12-177173463f9b" />

  # Step 6: Select MFA Device Type
  
   After clicking Assign MFA device, enter a Device name (e.g., Authenticator-App or Mobile-MFA).

   Select Authenticator app (e.g., Google Authenticator, Microsoft Authenticator, or Authy) as the MFA method.

    Click Next.


  







