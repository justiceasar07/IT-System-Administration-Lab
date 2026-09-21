Security Monitoring Lab

Project Overview

This project documents a hands-on security monitoring lab using Wazuh.

The environment is designed to demonstrate endpoint monitoring, security event collection, alert analysis, and basic security investigation.

Objectives

* Deploy a security monitoring environment
* Install and configure Wazuh
* Connect Windows and Linux endpoints
* Monitor endpoint activity
* Review security events
* Investigate alerts
* Practice basic incident analysis
* Document security findings

Lab Architecture

                 Wazuh Server
                      |
             ┌────────┴────────┐
             │                 │
        Windows Agent      Linux Agent
             │                 │
        Windows VM         Linux VM

Lab Environment

Component	Purpose
Wazuh	Security monitoring
Windows VM	Monitored endpoint
Linux VM	Monitored endpoint
Virtualization	Virtual lab environment

Tasks

* [ ]	Deploy Wazuh
* [ ]	Configure Wazuh dashboard
* [ ]	Configure Windows agent
* [ ]	Configure Linux agent
* [ ]	Verify agent connectivity
* [ ]	Generate safe test events
* [ ]	Review security alerts
* [ ]	Investigate an alert
* [ ]	Document findings
* [ ]	Document response actions

Security Events

The lab will be used to examine events such as:

* Failed authentication attempts
* File changes
* Configuration changes
* Service changes
* Other safe test events generated within the lab

Investigation Workflow

Security Event
      ↓
Alert Generated
      ↓
Review Alert
      ↓
Collect Evidence
      ↓
Identify Cause
      ↓
Determine Impact
      ↓
Take Appropriate Action
      ↓
Verify Resolution
      ↓
Document Findings

Example Investigation

Security Alert

Alert:

To be documented after generating and investigating an actual lab event.

Time:

To be documented.

Affected Endpoint:

To be documented.

Investigation:

To be documented.

Finding:

To be documented.

Response:

To be documented.

Verification:

To be documented.

Skills Demonstrated

* Security monitoring
* Wazuh
* Endpoint monitoring
* Log analysis
* Security alert investigation
* Basic incident response
* Linux
* Windows
* Cybersecurity documentation

Authorization

All security testing and monitoring activities in this project will be performed only on systems that I own or have explicit authorization to monitor or test.

Evidence

Screenshots of the Wazuh dashboard, connected agents, alerts, and investigation process will be added as the project progresses.

Lessons Learned

This section will document lessons learned about security monitoring, endpoint visibility, alert analysis, and incident investigation.
