# soc-automation-homelab

# soc-automation-lab
Building a full SOC Automation Lab using Wazuh (SIEM/XDR), TheHive (case management), and Shuffle (SOAR automation).


# SOC Automation Lab

This project demonstrates how to build a **fully automated Security Operations Center (SOC) lab** using open-source security tools.

The goal of this lab is to simulate a real SOC environment where alerts are generated, analyzed, and automatically processed through SOAR workflows.

---

## Tools Used

| Tool | Purpose |
|-----|------|
| Wazuh | SIEM and XDR platform |
| TheHive | Incident response case management |
| Shuffle | SOAR automation platform |
| Mimikatz | Attack simulation |
| Python | Security automation scripts |

---

## Lab Architecture

The SOC environment consists of:

- Wazuh SIEM for detection
- Endpoint telemetry generation
- Alert forwarding
- Shuffle SOAR automation
- TheHive case management
- Email alerting to analysts

---

## Project Stages

### Day 1
Design SOC architecture diagram.

## SOC Architecture

The SOC Automation Lab simulates a real-world security operations workflow.

The architecture includes:

- Windows 10 endpoint running Wazuh agent
- Wazuh SIEM for detection
- Shuffle SOAR for automation
- TheHive for case management
- SOC analyst investigation workflow

![SOC Architecture](Architecture/soc-architechure.png)

### Day 2
Deploy SOC infrastructure in the cloud.

### Day 3
Configure servers and endpoint telemetry.

### Day 4
Generate attack telemetry (Mimikatz simulation).

### Day 5
Automate incident response using SOAR.

---

## Example Detection Workflow

1. Endpoint executes suspicious activity
2. Wazuh generates alert
3. Alert sent to Shuffle
4. Shuffle creates case in TheHive
5. Email notification sent to SOC analyst

---

## Screenshots

*(Screenshots of dashboards, alerts, and automation will be added here.)*

---

## Skills Demonstrated

- SIEM configuration
- Threat detection engineering
- SOAR automation
- Incident response workflows
- Cloud security lab deployment

---

## Author

San Saad

Cybersecurity Student
