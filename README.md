# IT Support and SOC Home Lab

## About Project
This project is a Home Lab designed to develop practical skills for IT Support and SOC Analyst roles, covering areas such as Windows Administration, Active Directory, and SIEM tools. The aim is to gain insights into how events are generated in Windows, ingested by SIEM tools, and how these events and logs are investigated for suspicious activities through Splunk.

## Project Objectives
- Virtual Machine creation and management using VirtualBox
- Windows Server Administration
- Active Directory user creation and management
- Splunk Enterprise (SPL Searches, Dashboards, and Reports)
- Splunk Universal Forwarder (Log forwarding)
- Network Troubleshooting
- Windows Services and Event Viewer

## Tools & Technologies
- VirtualBox
- Windows Server 2022
- Active Directory
- Splunk Enterprise
- Splunk Universal Forwarder
- Windows Network Configurations
- Windows Services and Event Viewer

## Project Implementation
The project encompassed the following stages:

- **Virtual Machine Setup:** Created the virtual lab environment using Oracle VirtualBox.
- **Windows Server Configuration:** Installed Windows Server 2022 and configured the basic network settings.
- **Active Directory Setup:** Configured Active Directory and created domain user accounts.
- **Windows Event Generation:** Generated Windows events to understand how system and security activities are recorded.
- **Splunk Installation:** Installed Splunk Enterprise and configured it.
- **Log Forwarding:** Configured Splunk Universal Forwarder to collect and forward Windows logs.
- **Security Monitoring:** Explored incoming events and practised using Splunk to search and review log data.
- **Failed Login Testing:** Performed controlled failed login attempts to generate Windows Security Event ID 4625 and examine failed authentication activity.

## Repository Contents
- `docs/` — supporting notes and technical explanations
- `diagrams/` — lab architecture diagram
- `splunk/` — example configuration and SPL searches
- `evidence/screenshots/` — location for original project screenshots

**Note:** Supporting documentation and SPL/configuration examples are reference material. Confirm any environment-specific values against your actual lab before presenting them as verified configurations. Add your original screenshots to `evidence/screenshots/`; no screenshots have been fabricated.
