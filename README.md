# MFA-Implementation-For-Active-Directory

#Objective


This project demonstrates the implementation of Two-Factor Authentication (2FA) using Duo Security for Active Directory users to enhance endpoint security. It also includes the configuration of a Network Time Protocol (NTP) server to resolve time drift issues (which I did not document but read more here https://learn.microsoft.com/en-us/troubleshoot/windows-server/active-directory/configure-authoritative-time-server), ensuring reliable authentication. This project showcases skills in system administration, identity and access management, and security best practices for enterprise environments.

#Skills Learned

Two-Factor Authentication (2FA) Implementation – Configuring and enforcing 2FA using Duo Security.


Active Directory Management – Managing user accounts and security policies in AD.

Identity and Access Management (IAM) – Enhancing security through user authentication and access controls.

Endpoint Security – Securing endpoints by integrating multi-factor authentication.

Duo Security Configuration – Setting up Duo for domain users, including enrollment and policy management.

Group Policy (GPO) Configuration – Enforcing authentication settings through Active Directory policies.

Windows Server Administration – Managing security configurations on a Windows Server environment.

Network Time Protocol (NTP) Configuration – Setting up an NTP server to synchronize system time and prevent authentication failures.

#Tools Used

Windows Server - Used to configure the domain controller and manage Active Directory (AD) settings.

Duo Security – Configured two-factor authentication (2FA) for Active Directory users..


Steps

1.signing up for free trial of duo on windows server 

![image](https://github.com/user-attachments/assets/ea222cce-b3e8-4d77-acb2-d1d22cab42ad)



2. Adding Group To Duo For AD Lab Users

![image](https://github.com/user-attachments/assets/8222a039-dac7-46fe-9d42-596785eda1de)
![image](https://github.com/user-attachments/assets/50703eed-73ca-40ea-a4a5-50f51691fb2c)




3. Next Step we are going to Add the user Jenny Smith (Make sure the user login matches the name you add in duo)





![image](https://github.com/user-attachments/assets/bf7cca73-45eb-4006-b003-1c14a3b8147c)
![image](https://github.com/user-attachments/assets/eb3a0ddf-8a63-495f-9150-4a8d70838cbd)
![image](https://github.com/user-attachments/assets/7b42499d-4c46-44f5-a7e6-f786d040aab7)



4. Adding user to AD Lab Group  in DUO




![image](https://github.com/user-attachments/assets/1f89e28d-799f-467c-ae13-79b847f11199)



5. Receiving Enrollment Email For “jsmith”





![Image_thumbnail - Copy](https://github.com/user-attachments/assets/a2fcbba1-0273-40a3-abbe-f36bc9ba1b3e)




7. Sending An Duo Push For Testing Purposes For “jsmith”





![AD LAB Duo Test - Made with Clipchamp](https://github.com/user-attachments/assets/e51aef63-ba44-4563-899e-d5480e93c181)



8. Protecting Application In DUO (Select Microsoft RDP)





   ![image](https://github.com/user-attachments/assets/47c2409d-de28-4360-b86e-2efe6b0a227c)



9.Configuring Duo Security Module On Windows Server






![image](https://github.com/user-attachments/assets/05ca3706-a933-412b-b603-868ca1149653)
![image](https://github.com/user-attachments/assets/26be9001-374c-4a92-b0cf-5fbe13882847)



10.Testing Duo Push On User "jsmith" Device






![Untitled video - Made with Clipchamp (1)](https://github.com/user-attachments/assets/c1984d9e-8005-44f3-ba77-57df740d2bd1)






