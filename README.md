# Wazuh SIEM Lab

Multi-scenario SIEM lab built with Wazuh for security event monitoring, detection, and analysis in a mixed Linux and Windows environment.

## Overview
I built this lab to get practical experience with log analysis, alert investigation, and general SIEM workflows in a realistic setup.


## Environment
- VirtualBox
- Wazuh server (Ubuntu)
- Windows machine (agent)
- Linux machine (agent)

Both endpoints are connected to Wazuh to forward logs and security events.


## What I tested
I generated different security events to see how they are collected and analyzed in Wazuh, including:

- Failed SSH login attempts (wrong password)
- Failed sudo authentication attempts
- General authentication errors on Linux and Windows

---

## What I learned
- How logs are generated and structured on Linux and Windows
- How Wazuh processes and categorizes security events
- How alerts are triggered and enriched with context
- How a basic SOC workflow looks in practice
- How to deploy and manage Wazuh agents across multiple systems

---

