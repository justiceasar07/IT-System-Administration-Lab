Networking Lab

Project Overview

This project documents my hands-on networking practice using Cisco Packet Tracer.

The lab simulates a small business network and focuses on IP addressing, VLANs, switching, routing, DHCP, connectivity testing, and network troubleshooting.

Objectives

* Understand IPv4 addressing and subnetting
* Configure switches and routers
* Create and configure VLANs
* Configure access and trunk ports
* Configure inter-VLAN routing
* Configure DHCP
* Test network connectivity
* Troubleshoot network configuration problems
* Document network infrastructure

Lab Environment

Component	Configuration
Simulation Tool	Cisco Packet Tracer
Router	Cisco IOS Router
Switch	Cisco IOS Switch
Clients	Windows PCs
Network	IPv4
VLAN 10	IT
VLAN 20	HR

Network Design

                 Router
                    |
                 Switch
              ┌─────┴─────┐
              │           │
           VLAN 10      VLAN 20
             IT           HR
          ┌───┴───┐    ┌──┴───┐
         PC1     PC2   PC3    PC4

IP Addressing

VLAN 10 - IT

Network: 192.168.10.0/24
Gateway: 192.168.10.1

VLAN 20 - HR

Network: 192.168.20.0/24
Gateway: 192.168.20.1

The final IP configuration may be adjusted during the lab depending on the network design.

Tasks Completed

* [ ]	Designed the network topology
* [ ]	Configured router
* [ ]	Configured switch
* [ ]	Created VLAN 10
* [ ]	Created VLAN 20
* [ ]	Assigned switch ports to VLANs
* [ ]	Configured trunking
* [ ]	Configured inter-VLAN routing
* [ ]	Configured DHCP
* [ ]	Assigned IP addresses
* [ ]	Tested connectivity
* [ ]	Troubleshot a network failure
* [ ]	Documented the solution

Troubleshooting

Network Connectivity Problem

Problem:

To be documented after introducing a controlled configuration problem.

Symptoms:

To be documented.

Investigation:

The following tools and commands will be used where appropriate:

ping
ipconfig
tracert
show ip interface brief
show vlan brief
show interfaces

Root Cause:

To be documented.

Solution:

To be documented.

Verification:

Connectivity will be tested again after applying the fix.

Skills Demonstrated

* TCP/IP
* IPv4 addressing
* Subnetting
* VLANs
* Switching
* Routing
* DHCP
* Network troubleshooting
* Cisco IOS fundamentals
* Technical documentation

Evidence

Screenshots, network diagrams, Packet Tracer files, and troubleshooting evidence will be added as the project progresses.

Lessons Learned

This section will be updated with the key networking concepts and troubleshooting techniques learned during the project.
