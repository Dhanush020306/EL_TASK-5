# EL_TASK-5

# MALWARE TYPES AND BEHAVIOR ANALYSIS
This task focuses on the fundamental analysis of different malware types and their behaviors. The objective is to identify how various malicious programs function, spread, and interact with a host system using industry-standard analysis tools.

**Tools Used**
- VirusTotal
- MalwareBazaar (for hash)

**Malware Types Analyzed**
In this task, I researched and analyzed the following classifications:
- *Virus*: Requires a host file and human interaction to spread.
- *Worm*: A standalone program that self-replicates across networks.
- *Trojan*: Disguises itself as legitimate software to gain unauthorized access.
- *Ransomware*: Encrypts user data and demands a ransom for the decryption key.

**Analysis Process**
- *Identification*: Obtained known malware hashes for analysis.
- *Detection*: Uploaded hashes to VirusTotal to observe detection rates across multiple antivirus engines.
- *Behavioral Observation*: Analyzed the "Behavior" tab to identify file system changes, registry modifications, and network communications.
- *Lifecycle Study*: Documented the malware's path from initial delivery to execution and persistence.

**Key Findings and Prevention**
Through this analysis, I identified several methods to prevent malware infections:
- Keep software and operating systems updated (Patching).
- Use Endpoint Detection and Response (EDR) tools.
- Implement regular data backups to mitigate ransomware risks.
- Exercise caution with email attachments and suspicious links.
