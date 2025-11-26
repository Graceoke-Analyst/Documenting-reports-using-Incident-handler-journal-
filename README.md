# Documenting-reports-using-Incident-handler-journal-
Documenting security incident and analysis using my incident handler journal 

## Summary
This document records key activities and investigations from a hands-on course covering the Incident Response Lifecycle, network traffic analysis, and threat intelligence tooling.

## Entry 1
Ransomware Incident Simulation (July 23, 2024)
This exercise simulated a major ransomware attack, forcing adherence to the NIST Incident Response Framework across the Detection, Analysis, Containment, Eradication, and Recovery phases.
* Action (Incident containment)
 Context:
A small U.S. health care clinic was under active ransomware encryption, threatening critical patient and operational data and requiring immediate isolation to limit lateral movement.
Action:
Executed the immediate containment step of shutting down all affected computer systems to quarantine the ransomware and stop the encryption process from spreading further across the network
Result:
Successfully contained the incident's scope, protecting remaining unencrypted files, and initiating external technical assistance for the complex eradication and recovery phases.

## Entry 2
 Network Traffic Analysis & Capture
These activities focused on using industry-standard tools for network protocol analysis, a core skill for threat hunting and detection.
* Tool
   Wireshark (Network Protocol Analyzer with a Graphical User Interface).
* Description
  The activity involved loading and navigating a pre-recorded packet capture file (.pcap).
  
## Entry 3
 Capturing My First Packet (July 25, 2024)
 * Tools
tcpdump (Network Protocol Analyzer accessed via the command-line interface).
* Description
 Used tcpdump to capture and filter live network traffic.

## Entry 4
Threat Intelligence Investigation (July 27, 2024)
* Tools
VirusTotal, an investigative tool that aggregates results from multiple antivirus engines and security tools to analyze files and URLs for malicious content.
* Incident
A critical alert was generated when an employee downloaded and executed a file attachment via email, triggering an IDS warning on a suspicious file hash.File hash (SHA-256: 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b)
* Action
Used VirusTotal to investigate the suspicious SHA-256 file hash and perform deeper analysis by leveraging community-reported intelligence and multiple vendor detections to confirm the threat.
* Result
Quickly confirmed the file as malicious and a real threat, enabling the security team to move immediately to containment and eradication based on validated external threat intelligence.

## Project artifact
see Incident handler file @ Incident_handler.md ( https://github.com/Graceoke-Analyst/Documenting-reports-using-Incident-handler-journal-/blob/main/Incident_handler.md)



  




