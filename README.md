# SOC Automation Lab

## Objective

The Detection Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

## Skills Learned

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.
- Created automated alert system to evaluate threats using their MD5 Hash and comparing it to Virustotal API. 

### Tools Used
- Wazuh
- Virustotal
- DigitalOcean
- Shuffle
- Shuffler.io
- TheHive
- Sysmon
- VMware

## Steps

Drew out Lab Environment and Relationships between systems.

![Lab Environment drawio](https://github.com/user-attachments/assets/1b24ffe6-5463-42b1-b4db-b35545ca3af1)

Created Windows Environment and Installed Sysmon to keep track system activities.
![VMWareWindows](https://github.com/user-attachments/assets/280321ea-0daf-4055-bc93-62afb5208069)

Configuring Ubuntu in the Cloud w/ DigitialOcean
![SettingUpVirtualEnvironment](https://github.com/user-attachments/assets/b70273fe-1213-44ad-9fd2-529209d11880)

Creating Firewall Rules for SSH  into Cloud Envrionments for Wazuh/TheHive Installation & Configuration
![image](https://github.com/user-attachments/assets/0a791081-e6c9-4cfa-952c-229b2ad64c2f)

SSH into Ubuntu Server & Installation of Wazuh.
![image](https://github.com/user-attachments/assets/ea473770-089d-4cd4-b882-fafdb54980aa)

