Linux Administration Lab

Project Overview

This project documents my hands-on Linux system administration practice using Ubuntu Server.

The lab focuses on managing users, groups, permissions, services, networking, SSH, software installation, web services, and troubleshooting.

Objectives

* Install and configure a Linux server
* Navigate and manage the Linux filesystem
* Create and manage users and groups
* Configure file and directory permissions
* Manage Linux services
* Configure SSH
* Install and configure Apache
* Monitor system resources
* Troubleshoot common Linux problems
* Document administrative procedures

Lab Environment

Component	Configuration
Operating System	Ubuntu Server
Virtualization	VirtualBox
Server Role	Linux Administration / Web Server
Web Server	Apache
Remote Access	SSH

Tasks

* [ ]	Install Ubuntu Server
* [ ]	Configure hostname
* [ ]	Configure networking
* [ ]	Create users
* [ ]	Create groups
* [ ]	Configure file permissions
* [ ]	Configure ownership
* [ ]	Install software using APT
* [ ]	Manage system services
* [ ]	Configure SSH
* [ ]	Install Apache
* [ ]	Test web server
* [ ]	Review system logs
* [ ]	Troubleshoot a service failure
* [ ]	Document troubleshooting process

Linux Commands Practiced

pwd
ls
cd
mkdir
touch
cp
mv
rm
cat
less
grep
find

User and Group Management

adduser
usermod
passwd
groupadd
groups

Permissions

chmod
chown
chgrp

System Administration

systemctl
journalctl
df
du
free
top
ps

Networking

ip
ping
ss
hostname

Web Server

Apache will be installed and configured as part of the lab.

Example installation:

sudo apt update
sudo apt install apache2

The Apache service will then be checked and tested.

Troubleshooting

Apache Service Failure

Problem:

To be documented after introducing or encountering a controlled service problem.

Symptoms:

To be documented.

Investigation:

I will check the service status and relevant logs.

Example commands:

systemctl status apache2
journalctl -u apache2

Root Cause:

To be documented.

Solution:

To be documented.

Verification:

The Apache service and website will be tested after the fix.

Skills Demonstrated

* Linux administration
* Ubuntu Server
* User management
* Group management
* File permissions
* Package management
* Service management
* SSH
* Apache
* Linux networking
* Troubleshooting
* Command-line administration

Evidence

Screenshots and configuration evidence will be added as the lab progresses.

Lessons Learned

This section will document the Linux administration concepts, commands, troubleshooting methods, and best practices learned during the project.
