# NTLM Relay Attack Simulation & Log Analysis

This project demonstrates a simulated NTLM Relay attack in a virtual lab environment using Responder and Impacket's ntlmrelayx.py. 

## 🔧 Tools Used
- Kali Linux (VM)
- Responder
- Impacket Suite
- Windows Event Viewer
- XML & TXT Log Analysis via grep

## 🕵️‍♀️ Key Objectives
- Capture NTLM hashes from poisoned LLMNR/MDNS responses
- Relay credentials to a target SMB server
- Analyze `.evtx` logs for evidence of the attack
- Extract Source Port, Logon Type, and Logon ID from Event ID 4624
- Identify compromised account activity and accessed shares

## 📄 Report
The full PDF investigation report is available in the `report/` folder.
