|Date:July 23, 2024| Entry: 1 |
|:------| :----------|
|Description| This incident occurred in the two phases;Detection and Analysis: The scenario outlines how the organization first detected the ransomware incident. For the analysis step, the organization contacted several organizations for technical assistance. Containment,Eradication, and Recovery: The scenario details some steps that the organization took to contain the incident. For example, the company shut down their computer systems. However, since they could not work to eradicate and recover from the incident alone, they contacted several other organizations for assistance.|
|Tool(s) used| None|
|The 5 W's| ### Who: An organized group of unethical hackers ### What: A ransomware security incident ### Where: At a health care company ### When: Tuesday 9:00 a.m ### Why: The incident happened because unethical hackers were able to access the company's systems using a phishing attack. After gaining access, the attackers launched their ransomware on the company's systems, encrypting critical files. The attackers' motivation appears to be financial because the ransom note they left demanded a large sum of money in exchange for the decryption key.|
|Additional notes| Prevention Strategy-The most critical lessons learned for preventing this type of targeted ransomware attack are 1)Immutable and Offline Backups: This is the most vital control. The clinic must ensure they have immutable backups that cannot be accessed or encrypted by the ransomware, guaranteeing recovery without paying the ransom. 2)Targeted User Training: Since the attack vector was a malicious attachment via phishing, mandatory, frequent, and high-quality phishing simulation training is essential for all staff. 3)Robust Endpoint Protection: Implement an Endpoint Detection and Response (EDR) solution to stop the behavior of the malware (mass file encryption) that traditional antivirus often misses. 4)Zero Trust Principles: Mandate Multi-Factor Authentication (MFA) on all remote and critical administrative access points to prevent lateral movement using stolen credentials, and implement strong network segmentation. ### Ransom Payment Decision-The company should generally NOT pay the ransom. 1)Rationale: Paying the ransom funds criminal enterprises, offers no guarantee of a working decryption key, and does not relieve the healthcare clinic of its legal and regulatory obligations (e.g., HIPAA compliance). 2)Primary Focus: The recovery strategy must rely entirely on secure, tested backups to restore the systems, followed complete forensic wiping and rebuilding of infected endpoints.| 


|Date: July 25,2024| Entry 2 |
| :------------| :--------------------|
|Description| Analyzing a packet capture file |
|Tool(s) used | For this activity, I used Wireshark to analyze a packet capture file. Wireshark is a network protocol analyzer that uses a graphical user interface. The value of Wireshark in cybersecurity is that it allows security analysts to capture and analyze network traffic. This can help in detecting and investigating malicious activity.|
| The 5 W's | #Who: N/A #What: N/A #Where: N/A #When: N/A #Why: N/A |
| Additional notes | I've never used Wireshark before, so I was excited to begin this exercise and analyze a packet capture file. At first glance, the interface was very overwhelming. I can see why it's such a powerful tool for understanding network traffic.|


|Date:  July 26,2024  | Entry 3|
| :------------------- | :--------------------- |
| Description | Capturing my first packet |
| Tool(s) used | For this activity, I used tcpdump to capture and analyze network traffic. Tcpdump is a network protocol analyzer that's accessed using the command-line interface. Similar to Wireshark, the value of tcpdump in cybersecurity is that it allows security analysts to capture, filter, and analyze network traffic. |
| The 5 W's | #Who: N/A #What: N/A #Where: N/A #When: N/A  #Why: N/A |
| Additional notes| I'm still new to using the command-line interface, so using it to capture and filter network traffic was a challenge. I got stuck a couple of times because I used the wrong commands. But after carefully following the instructions and redoing some steps, I was able to get through this activity and capture network traffic. |


|Date: July 27, 2024 | Entry 4 |
| :------------------- | :-------------------|
| Description | Investigate a suspicious file hash |
| Tool(s) used | For this activity, I used VirusTotal, which is an investigative tool that analyzes files and URLs for malicious content such as viruses, worms, trojans, and more.  It's a very helpful tool to use if you want to quickly check if an indicator of compromise like a website or file has been reported as malicious by others in the cybersecurity community. For this activity, I used VirusTotal to analyze a file hash, which was reported as malicious. This incident occurred in the Detection and Analysis phase. The scenario put me in the place of a security analyst at a SOC investigating a suspicious file hash. After the suspicious file was detected by the security systems in place, I had to perform deeper analysis and investigation to determine if the alert signified a real threat.|
| The 5 W's | #Who: An unknown malicious actor  #What: An email sent to an employee contained a malicious file attachment with the SHA-256 file hash of 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b  #Where: An employee's computer at a financial services company #When: At 1:20 p.m., an alert was sent to the organization's SOC after the intrusion detection system detected the file #Why: An employee was able to download and execute a malicious file attachment via e-mail.|
| Additonal Notes | To prevent against future incidents:Targeted Training:Implementing mandatory, frequent security awareness training. The training must specifically cover how to identify phishing emails, especially those with unusual or unexpected attachments, and teach employees to report suspicious mail instead of deleting it.  2) Simulated Phishing: Running regular, unannounced phishing simulations to test employee vigilance in a safe environment. Employees who click should receive immediate, personalized remedial training. 3)Email Filtering & Sandboxing: Deploying an advanced email security gateway. This tool should automatically sandbox (test in an isolated environment) all suspicious attachments and use File Hash Blacklisting to immediately quarantine emails containing known malicious hashes (like the SHA-256 hash you investigated). 4)Attachment Blocking: Configuring policies to block common risky file types (e.g., .exe, .zip, macro-enabled .docm) unless they are absolutely required for the employee's job function.|








































