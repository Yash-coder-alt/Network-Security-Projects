# Basic Firewall Configuration & Traffic Control

## Project Overview
This project demonstrates the implementation of basic firewall rules
to control inbound and outbound network traffic. The objective is to
understand how firewall rules work and how traffic can be allowed or
blocked based on ports, protocols, and IP rules.

---

## Objectives
- Learn basic firewall rule configuration
- Control network traffic using security rules
- Verify firewall behavior using testing tools

---

## Tools & Technologies
- Windows Defender Firewall
- Wireshark
- Command Prompt
- Web Browser
- Nmap (optional)

---

## Implementation Details
- Configured inbound firewall rules to block ICMP (ping) requests.
- Created port-based rules to block HTTP traffic (Port 80).
- Tested firewall rules using ping commands and browser traffic.
- Performed port scanning to verify blocked ports.
- Verified allowed and blocked packets using Wireshark packet capture.

---

## Testing & Validation
- Ping requests were blocked after applying ICMP rules.
- Web traffic failed when HTTP port was blocked.
- Packet capture confirmed blocked packets at firewall level.

---

## Key Learnings
- Understanding of inbound and outbound firewall rules
- Practical exposure to traffic filtering
- Real-time firewall verification using packet analysis

---

## Outcome
Successfully implemented and tested firewall rules to control network
traffic and validated security behavior through packet analysis.
