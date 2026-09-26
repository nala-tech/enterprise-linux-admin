# An enterprise linux admin cyber range simulation. 

XP Cyber Range Challenge Summary

In this challenge, I was tasked with improving the security and administration of a production web server as well as providing elevated privileges to a specific user. I first investigated the environment to identify the correct systems and services involved. While troubleshooting, I discovered that the web server was running Apache as the httpd service on a Linux-based system rather than the Ubuntu-style apache2 service.

I performed package management and update operations, including refreshing the system repositories and upgrading the Apache web server software from an older version to a current release. During the process, I diagnosed update failures by testing network connectivity and repository access, confirming that the server could reach external package sources.

I also reviewed user and privilege management on the server. After determining that the environment used the wheel group for administrative access, I verified the correct method for granting elevated privileges to users rather than relying on the Ubuntu-specific sudo group.

Key tasks completed:

Investigated the server environment and identified the correct Apache service implementation (httpd).
Troubleshot package update issues by validating network and repository connectivity.
Updated the Apache web server software to the latest available version.
Reviewed Linux user account and privilege management practices.
Verified that administrative privileges were managed through the wheel group.
Distinguished between development and production systems while validating challenge requirements.

Skills demonstrated:

Linux system administration
User and group management
Privilege escalation configuration
Apache (httpd) administration
Package management (APT/YUM/DNF)
Network and DNS troubleshooting
Server update and maintenance procedures
Cybersecurity operations and system hardening fundamentals

<img width="1026" height="235" alt="Screenshot 2026-09-26 172334" src="https://github.com/user-attachments/assets/a484178c-1aa1-43ab-a937-cc11cce114a9" />

<img width="1025" height="287" alt="Screenshot 2026-09-26 172348" src="https://github.com/user-attachments/assets/1be999f2-0d6a-4434-b27d-2fee4a2d01aa" />

<img width="1022" height="442" alt="Screenshot 2026-09-26 172359" src="https://github.com/user-attachments/assets/dd57abe6-4a28-4d58-b4d1-eef329006b19" />

<img width="1021" height="590" alt="Screenshot 2026-09-26 172416" src="https://github.com/user-attachments/assets/ce04f60b-5b4c-405b-8e14-fbbca9284ff8" />

<img width="1102" height="431" alt="Screenshot 2026-09-26 172435" src="https://github.com/user-attachments/assets/848e89fd-547e-41d9-a903-94452c876449" />
