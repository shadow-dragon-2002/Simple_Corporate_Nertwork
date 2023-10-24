# [Simplified_Corporate_Nertwork](https://github.com/shadow-dragon-2002/Simple_Corporate_Nertwork/blob/7c4176b85e91547de423befea71c194400a3c390/Corp_Network_with_DMZ.pkt "Simplified_Corporate_Nertwork")

I started this project to learn more about network hardening techniques and improve my networking abilities. It functions as a simplified version of a safe corporate network, complete with subnetworks for internal and external use and a demilitarized area for hosting servers and services that need to be connected to the internet. These network parts are effectively segregated by a specialized firewall. Cisco Packet Tracer was used to develop the full setup, which includes real-world networking and network hardening techniques.

### Network:

![Corp_Network_With_DMZ](https://github.com/shadow-dragon-2002/Simple_Corporate_Nertwork/assets/73079262/d86c3c44-0946-472e-9ecd-c0dbc4f98781)


## Contents:
The network contains the following:-

#### Internal Zone:
This zone contains the main working parts of the network with the internal architecture like the end users and internal network servers are located here. In the network I created the internal network contains the following elements :
* Technician VLAN
* End-User Workstations VLAN
* Syslog Server
* NTP Server
* Internal FTP Server
* DHCP Server
* Internal Zone Switch

#### Demilitarized Zone:
This is an intermediary zone between the external network and the internal network to work as an intermediary to protect the internal network from the external facing network. The DMZ contains the following :
* Email Server
* HTTP Server
* External FTP Server
* DMZ Switch

#### External Zone:
This is the network that is exposed to the internet directly and contains some corporate infrastructure but not much confidential or important data. The External Zone contains the following :
* External Technician VLAN
* External End-User Workstations VLAN
* External Zone Switch

#### Firewall:
This is the segregation factor, the firewall separates the internal network and DMZ from the external network. 

#### Implemented Network Security Practices:
* Switchport assignment hardening
* DHCP Snooping
* ARP Inspection
* Secure Firewall Configuration
* Access Control List's
* Port Security and VLAN Segregation
* Secure Switch Setup
