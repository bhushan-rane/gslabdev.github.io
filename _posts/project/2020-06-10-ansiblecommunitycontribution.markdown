---
layout: project
title:  "Ansible community contribution"
date:   2020-06-10 16:54:46
author: Masarrat Mahedvi, Pallavi Joshi, Sakar Mehra, Suyeb Ansari, Pallavi Chaudhari, Shwetali Berad
categories:
- project
img: ansible-community-contribution.png
thumb: thumb02.jpg
carousel:
- ansible-community-contribution.png
client: https://github.com/ansible-collections/community.windows Pull requests - 90, 112, 127, 131, 136 and https://github.com/ansible-collections/azure Pull request - 243, 248, 254, 264, 271, 286
---

#### Ansible Community Contribution
Ansible is an open-source software provisioning, configuration management, and application-deployment tool. It has different modules for integration. Following are the features that we have developed in different ansible module.

Windows Ansible Collection:
1. winZip Module: Added a new feature of password parameter which unarchive password protected zip files.
2. win_dns_record Module: Added a new feature of SRV dns record to an existing win_dns_record module.
3. win_firewall_rule Module: Added a new feature that allows the user to enable or disable all the firewall rules in a particular group.
4. win_dns_record Module: Added a new feature of NS DNS record to an existing win_dns_record module.
5. win_firewall Module: Added a new feature of inbound, outbound connections that allow the user to either block or allow the connection in windows firewall. 

Azure Ansible Collection:
1. azure_rm_backupazurevm and azure_rm_backupazurevm_info Module: Added a new features of backup Azure VM for enabling protection, trigger on-demand backup, modify backup, top protection but retain existing data, Stop protection, delete data and get detail information about Azure VM backups.
2. azure_rm_recoveryservicesvault and azure_rm_recoveryservicesvault_info Module: Added a new features of Azure Recovery Services Vault with operations create, update, delete and get detail information about Azure Recovery Services Vault.
3. azure_rm Module: Added a new feature to fetch availability zone info into hostvars via Azure Inventory Script.
4. azure_rm_vmbackuppolicy azure_rm_vmbackuppolicy_info Module: Added a new features of Azure VM Backup Policy with oprations create, delete and get detail of VM Backup policy.
5. azure_rm_privatednsrecordset Module: Added a new features of DNS record set in a Private DNS zone with operations create, update, deleta and get details of DNS record set from Private DNS zone.
6. azure_rm_subnet Module: Added a new feature to delegation capabilities in azure_rm_subnet module.

#### Our Contributions
Feature implementation in different Ansible Collections and Ansible Module.