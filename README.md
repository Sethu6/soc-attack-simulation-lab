# SOC Attack Simulation Lab

# Overview
This project simulates a real-world cyber attack and demonstrates detection and investigation using Splunk and Sysmon.

# Lab Setup
- Windows 10 (Victim)
- Kali Linux (Attacker)
- Splunk SIEM
- Sysmon Logging

# Attack Chain
Phishing → PowerShell Execution → Payload Download → Command & Control → Persistence → Credential Access → Lateral Movement

# Detection Techniques
- PowerShell command-line analysis (IEX, DownloadString)
- Process chain analysis
- Network connection monitoring (C2)
- Registry persistence detection
- Credential access detection (cmdkey)
- Lateral movement detection (net use)

# Skills Demonstrated
- Log Analysis
- Incident Investigation
- SIEM (Splunk)
- Threat Detection
- MITRE ATT&CK Mapping

# Project Files
- SOC_Attack_Simulation.pdf (Full report)
- Screenshots (Detection evidence)

# Author
Sethupathi
