# CS491-Automated-Cisco-Config-with-Ansible\

# Automated Cisco Configuration with Python & Ansible

## Project Overview
This project automates the configuration of Cisco network devices using Python, Ansible, and Cisco Modeling Labs CML. It focuses on implementing VLANs, ACLs, and user/group permissions across virtualized environments, streamlining tasks that would otherwise require manual CLI interaction.

## Objectives
- Automate VLAN and ACL configurations on Cisco switches using Ansible Playbooks.
- Integrate a Linux based Ansible control node with Cisco Modeling Labs.
- Test and validate configurations through SSH and Telnet.
- Improve network reproducibility, scalability, and security using automation best practices.

## Technologies Used
- Ansible
- Python
- Cisco Modeling Labs (CML)
- GNS3 (second exploration)
- Linux
- Cisco IOS/ASA devices
- Markdown / PowerPoint for Documentation

## System Topology
The project was tested using a simulated lab environment with the following device IPs and credentials:

todo:

## Testing & Validation
- Configuration playbooks were tested by connecting to devices via SSH/Telnet from the control node.
- VLANs were verified using show vlan and interface status.
- ACL behavior was validated by simulating access attempts between PCs.
- User/group configurations were verified on Linux machines using permission-based file creation and access.

##  Team Members
- Stephen Ordway– Project Manager  
- Andres Garcia– DevOps Engineer  
- Yumi Song – DevOps Engineer  

## Stakeholders
- Network Engineers  
- System Architects  
- Security Analysts  
- Cisco Systems  
- Ansible (Red Hat)  
- IT Admins and End Users
