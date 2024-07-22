# SOC Automation Lab

## Objective

Objective: Deploy and manage a honeypot in Tokyo to detect, analyze, and understand cyber threats.

Scope: Implement a decoy system to attract cyber attackers, capturing data on their methods and techniques.

## Skills Learned

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Honeypot Design and Implementation:

- Developed expertise in setting up and configuring honeypot systems.
- Simulated realistic and attractive targets to lure cyber attackers.

### Cyber Threat Analysis:

- Analyzed attack data to identify patterns, techniques, and tactics used by cybercriminals.
- Threat intelligence.
  
### Network Security:

- Monitored network traffic to detect and respond to potential threats.
- Strengthened skills in network security protocols and intrusion detection systems.

### Data Collection and Analysis:

- Collected, managed, and interpreted large volumes of security data.
- Employed data analysis tools to extract actionable insights.

### Incident Response:

- Developed a response strategies based on honeypot findings.
- Enhanced skills in incident detection, investigation, and mitigation.

### Cybersecurity Strategy Development:

- Contributed to the organization's cybersecurity strategy by integrating findings from honeypot data.
- Improved understanding of proactive and reactive security measures.

### Technical Documentation:

- Documented honeypot setup, configuration, and analysis processes.

## Tools Used

- Elastic Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Wireshark for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.
- T-Pot Online Interface for visual representation of data.
- Amazon Web Services EC2 instances for scalability and reliability.

## Steps

Create a AWS EC2 Cloud Server w/ Ubuntu OS.
![image](https://github.com/NotArtwork/TokyoHoneyPot/assets/105832230/4d4a5360-89c3-43b9-8694-ed47ac75b6ec)

Select t2.Large + 128 GB of Space. We need this so that our system is laggy and can run our T-Pot Program.
![image](https://github.com/NotArtwork/TokyoHoneyPot/assets/105832230/494a9b7c-6146-43f7-ac0f-3aa98651d071)

SSH into machine
![image](https://github.com/NotArtwork/TokyoHoneyPot/assets/105832230/96f8be44-23b6-4345-b735-719d7f88fedd)

Git Clone T-Pot and Install the on to system.
![image](https://github.com/NotArtwork/TokyoHoneyPot/assets/105832230/ef1de388-5185-4564-a769-2980a86980dd)

Sign into your machine's Web Portal with credentials you've chosen during setup. 
![image](https://github.com/NotArtwork/TokyoHoneyPot/assets/105832230/c62a41a2-a855-42e5-bece-64ed0044a2b3)

Attack Map for Live Attacks on HoneyPot
![image](https://github.com/NotArtwork/TokyoHoneyPot/assets/105832230/50facd35-ccf6-42bf-9cc5-5d6e84ac6dd5)

SIEM + Heat Map
![image](https://github.com/NotArtwork/TokyoHoneyPot/assets/105832230/4c78c9f9-2fd0-4305-a1ce-707249b51267)
