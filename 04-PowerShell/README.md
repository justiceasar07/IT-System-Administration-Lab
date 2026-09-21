PowerShell IT Administration & Automation

Project Overview

This project demonstrates how I use PowerShell to perform common Windows administration, system information gathering, diagnostics, and automation tasks.

The goal is to reduce repetitive manual work and create reusable tools for IT support and system administration.

Objectives

* Learn PowerShell fundamentals
* Query Windows system information
* Manage processes and services
* Collect network information
* Monitor disk space
* Work with local users
* Automate common IT support tasks
* Create troubleshooting scripts
* Document scripts and their purpose

Environment

Component	Configuration
Operating System	Windows 10/11
Shell	PowerShell
Use Case	IT Support / System Administration

PowerShell Commands Practiced

Get-Process
Get-Service
Get-ComputerInfo
Get-NetIPConfiguration
Get-Disk
Get-LocalUser
Get-LocalGroup

Scripts

The scripts folder contains PowerShell scripts developed during this project.

1. System Information Script

File:

scripts/system-info.ps1

Purpose:

Collect important information about the Windows computer, including system details, operating system information, networking information, and storage.

2. Network Diagnostic Script

File:

scripts/network-diagnostic.ps1

Purpose:

Collect network configuration information and perform basic connectivity checks.

3. IT Support Diagnostic Script

File:

scripts/IT-support-diagnostic.ps1

Purpose:

Automate common information-gathering tasks that an IT Support Specialist may perform when diagnosing a user’s computer.

Tasks

* [ ]	Learn PowerShell syntax
* [ ]	Work with variables
* [ ]	Use PowerShell cmdlets
* [ ]	Work with objects and pipelines
* [ ]	Query system information
* [ ]	Query Windows services
* [ ]	Query network configuration
* [ ]	Check disk space
* [ ]	Create system information script
* [ ]	Create network diagnostic script
* [ ]	Create IT support diagnostic script
* [ ]	Test scripts
* [ ]	Document script outputs

Example Workflow

User reports computer problem
          ↓
Run diagnostic script
          ↓
Collect system information
          ↓
Check network configuration
          ↓
Check services
          ↓
Check disk/system resources
          ↓
Analyze results
          ↓
Troubleshoot problem

Security Considerations

Scripts will not contain passwords, API keys, authentication tokens, private keys, or other sensitive information.

Scripts will be tested only on systems I own or have authorization to administer.

Skills Demonstrated

* PowerShell
* Windows administration
* IT automation
* System diagnostics
* Network diagnostics
* Scripting
* Troubleshooting
* Technical documentation

Lessons Learned

This section will be updated with lessons learned while developing and testing PowerShell automation scripts.
