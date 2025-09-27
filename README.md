# Cloud-Network-Monitoring-Azure
Built a cloud-based monitoring system for Azure VMs using Python and Azure Monitor API. Automated alerts for CPU/memory thresholds and visualized performance metrics, reducing manual troubleshooting and improving reliability.

# Cloud-Based Network Monitoring & Automation (Azure)

## Overview
This project monitors Azure VM metrics (CPU, Memory) and generates alerts when thresholds are exceeded. It also visualizes metrics and automates notifications.

## Features
- Real-time CPU & Memory monitoring of Azure VMs
- Automated alerts via email
- Visualization of metrics using Matplotlib
- Expandable to multi-VM monitoring with Azure Log Analytics

## Tech Stack
- Python, psutil
- Azure Monitor API
- Matplotlib
- Automation (SMTP for alerts)<


## How to Run
1. Clone repo and install requirements: `pip install -r requirements.txt`
2. Update Azure subscription and VM details in code.
3. Run the notebook or script.

## Example Output
- CPU Usage: 75%

- Memory Usage: 82%
- ALERT: CPU usage high!
<img width="559" height="440" alt="Screenshot 2025-09-27 at 21 35 21" src="https://github.com/user-attachments/assets/b895ca61-7ac3-4ac6-b208-5f3f7b95d59b" />


