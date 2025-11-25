---
already_read: false
link: https://github.com/imthenachoman/How-To-Secure-A-Linux-Server
read_priority: 2
relevance: 0
source: Alpha Signal
tags:
- Data_Engineering
type: Content
upload_date: '2025-11-26'
---

https://github.com/imthenachoman/How-To-Secure-A-Linux-Server
## Summary

The guide provides a comprehensive approach to securing a Linux server, covering various aspects of system hardening and security best practices. Here are the main technical points and key takeaways:

### **Introduction**
- **Objective**: Teach how to secure a Linux server.
- **Scope**: Covers many security aspects, with more topics/material to be added.
- **Ansible Playbooks**: Available for automation.

### **Guide Overview**
- **Distribution Agnostic**: Applicable to any Linux distribution.
- **Focus**: At-home Linux servers, but concepts apply to larger environments.
- **Order**: Intended to be followed in sequence but can be adapted.

### **Before You Start**
- **Identify Principles**: Understand your threat model and security needs.
- **Picking a Distribution**: Choose a stable, well-supported distribution.
- **Installing Linux**: Follow distribution-specific installation instructions.
- **Pre/Post Installation Requirements**: Disable port forwarding until the system is secured.

### **The SSH Server**
- **SSH Public/Private Keys**: More secure than passwords.
- **Secure /etc/ssh/sshd_config**: Configure SSH for security.
- **Remove Short Diffie-Hellman Keys**: Ensure strong encryption.
- **2FA/MFA for SSH**: Add an extra layer of security.

### **The Basics**
- **Limit Who Can Use sudo**: Restrict sudo privileges.
- **Limit Who Can Use su**: Restrict su privileges.
- **Run Applications in a Sandbox with FireJail**: Isolate applications.
- **NTP Client**: Keep system time synchronized.
- **Securing /proc**: Restrict access to process information.
- **Force Accounts To Use Secure Passwords**: Enforce strong passwords.
- **Automatic Security Updates and Alerts**: Keep the system updated.
- **More Secure Random Entropy Pool**: Improve randomness for encryption.
- **Add Panic/Secondary/Fake Password Login Security System**: Add an extra layer of security.

### **The Network**
- **Firewall With UFW**: Configure a firewall to control network traffic.
- **iptables Intrusion Detection And Prevention with PSAD**: Monitor and block suspicious network activity.
- **Application Intrusion Detection And Prevention With Fail2Ban**: Monitor and block suspicious application activity.
- **Application Intrusion Detection And Prevention With CrowdSec**: Monitor and block suspicious application activity with community threat intelligence.

### **The Auditing**
- **File/Folder Integrity Monitoring With AIDE**: Monitor file integrity.
- **Anti-Virus Scanning With ClamAV**: Scan for viruses.
- **Rootkit Detection With Rkhunter**: Detect rootkits.
- **Rootkit Detection With chrootkit**: Detect rootkits.
- **logwatch**: Analyze and report system logs.
- **ss**: See ports your server is listening on.
- **Lynis**: Perform security auditing.
- **OSSEC**: Host intrusion detection.

### **The Danger Zone**
- **Linux Kernel sysctl Hardening**: Secure kernel settings.
- **Password Protect GRUB**: Protect GRUB from unauthorized access.
- **Disable Root Login**: Prevent root login.
- **Change Default umask**: Set secure default file permissions.
- **Orphaned Software**: Remove unused software.

### **The Miscellaneous**
- **The Simple Way with MSMTP**: Configure MSMTP for sending emails.
- **Gmail and Exim4 As MTA With Implicit TLS**: Configure Exim4 to use Gmail for sending emails.
- **Separate iptables Log File**: Log iptables messages to a separate file.

### **Left Over**
- **Contacting Me**: Submit issues for questions or feedback.
- **Helpful Links**: Additional resources.
- **Acknowledgments**: Contributors and references.
- **License and Copyright**: License information.

This guide is a valuable resource for data scientists looking to enhance the security of their Linux servers, providing practical steps and best practices to follow.
## Links

- [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks/) : CIS Benchmarks provide industry-trusted, step-by-step instructions for securing various flavors of Linux.
- [Debian 9.3 Server Setup Guide](https://cloudpro.zone/index.php/2018/01/18/debian-9-3-server-setup-guide-part-1/) : A guide for setting up a Debian 9.3 server, covering various aspects of server configuration and security.
- [Ubuntu Server Initial Security Guide](https://blog.vigilcode.com/2011/04/ubuntu-server-initial-security-quick-secure-setup-part-i/) : A guide for securing an Ubuntu server, covering initial security setup and configuration.
- [Linux Server Hardening Checklist](https://securecompliance.co/linux-server-hardening-checklist/) : A comprehensive checklist for hardening a Linux server, covering various security measures and best practices.
- [How to Secure a Linux Server With Ansible](https://github.com/moltenbit/How-To-Secure-A-Linux-Server-With-Ansible) : An Ansible playbook for automating the security hardening of a Linux server.

## Topics

![[topics/Concept/SSH Public Private Keys]]

![[topics/Concept/SSH Group for AllowGroups]]

![[topics/Concept/Secure SSH Configuration]]

![[topics/Concept/Two Factor Authentication 2FA for SSH]]

![[topics/Concept/Limit Who Can Use sudo]]

![[topics/Concept/Limit Who Can Use su]]

![[topics/Concept/Run Applications in a Sandbox with FireJail]]

![[topics/Concept/NTP Client]]

![[topics/Concept/Securing proc]]

![[topics/Concept/Force Accounts To Use Secure Passwords]]