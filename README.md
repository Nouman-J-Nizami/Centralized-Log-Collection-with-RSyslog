## Centralized Log Collection with RSyslog

## Overview
This project demonstrates the implementation of a centralized logging solution using **RSyslog**. A **Kali Linux** machine was configured as a Syslog server, while a **Windows 11** machine was configured to forward Windows Event Logs using the **RSyslog Windows Agent**.

## Objectives
- Configure Kali Linux as a centralized Syslog server.
- Enable TCP log reception on port 514.
- Install and configure the RSyslog Windows Agent.
- Forward Windows Event Logs to Kali Linux.
- Verify successful log collection and monitoring.

## Technologies Used
- Kali Linux
- Windows 11 Pro
- RSyslog
- RSyslog Windows Agent
- UTM Virtualization

## Key Activities
1. Installed and configured RSyslog on Kali Linux.
2. Enabled remote Syslog reception over TCP (port 514).
3. Created a dedicated directory for remote logs.
4. Installed the RSyslog Windows Agent.
5. Configured Windows Event Log forwarding.
6. Verified network connectivity and service status.
7. Validated real-time log reception on the Kali server.

## Results
The centralized logging infrastructure was successfully deployed. Windows Event Logs were transmitted and collected on the Kali Linux Syslog server, demonstrating effective log aggregation and monitoring capabilities.

## Author
Nouman J. Nizami
