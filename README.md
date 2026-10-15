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

   <img width="644" height="337" alt="image" src="https://github.com/user-attachments/assets/cd8c09cd-22b5-47b6-ad91-c882e1147988" />

   # Add Permission

   Click on add permission and select the attach perfect policy the click on add policy box and type Administrator.
   Below it  shows the list select the 3rd option Administrator access and then next. Click add permission the user creation
   tab is shown. 

   <img width="680" height="366" alt="image" src="https://github.com/user-attachments/assets/b7fbf051-f995-4519-ae6e-c74fa133bb3f" />

    <img width="700" height="345" alt="image" src="https://github.com/user-attachments/assets/8cb36b89-7e97-4902-a24a-a435698ee2f6" />

    <img width="602" height="323" alt="image" src="https://github.com/user-attachments/assets/fd66f5d0-d9e8-4175-a523-c5ecb6995a8b" />

    # Step 7 : Open the new incognito window by selecting Ctrl + N 

    <img width="602" height="323" alt="image" src="https://github.com/user-attachments/assets/5895f986-80e7-4aae-9923-841ebf9fb55c" />

    In the address bat type https://1669044935737.singin.aws.amazon.com/console

    <img width="712" height="430" alt="image" src="https://github.com/user-attachments/assets/6dcf8781-e8de-4342-bf2d-e7d8b828e9a2" />

    # Step 8 : Set the new password
    
    Password dialog box is open. Type first old password then type new password and confirm password. After click continue and password change.
    Password successfully changed and the new window is open.

    <img width="732" height="446" alt="image" src="https://github.com/user-attachments/assets/141b9ef3-b20b-413b-9aad-648851dcbdb1" />

    <img width="702" height="424" alt="image" src="https://github.com/user-attachments/assets/59863614-c85a-4807-af00-75299c575518" />

   #  Step 9: Confirm MFA Status
   
    You will see a success message confirming that the MFA device has been assigned.

    Under the Security credentials tab of the IAM user, check that Multi-factor authentication (MFA) status shows Assigned.

    <img width="738" height="430" alt="image" src="https://github.com/user-attachments/assets/c069b524-2747-4ee4-b2f0-e727c518845b" />

   # Conclusion

    Enabling Multi-Factor Authentication (MFA) adds an essential layer of security to your AWS IAM user accounts. By requiring a secondary authentication code 
    generated from an Authenticator app alongside standard login credentials, you significantly reduce the risk of unauthorized access, account takeover, and 
    identity misuse. Implementing MFA is a fundamental best practice for securing cloud infrastructure and maintaining robust AWS identity governance.
   


    

     






   

   


  







