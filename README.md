# Cisco-Switch-Security-Lab
Cisco Packet Tracer lab demonstrating switch hardening, AAA, SSH, and Layer 2 security.
Cisco Switch Security Hardening Lab
Project Overview

This project demonstrates hands-on Cisco IOS switch security configuration using Cisco Packet Tracer.

The objective was to harden an access switch (SW1), secure administrative access, implement Layer 2 security controls, and verify client connectivity.

Technologies Used
Cisco Packet Tracer
Cisco IOS
SSHv2
AAA Authentication
RADIUS and TACACS+
Access Control Lists (ACLs)
DHCP Snooping
Dynamic ARP Inspection (DAI)
Port Security
Security Implementations
Device and Administrative Security
Configured hostname and enable secret.
Enabled password encryption.
Secured console access.
Configured login and MOTD banners.
Generated 1024-bit RSA keys.
Enabled SSH version 2.
AAA and Remote Access
Created administrative and operator accounts.
Enabled AAA authentication.
Configured local VTY authentication.
Defined RADIUS and TACACS+ servers.
Restricted SSH access using ACL 20.
Configured login attempt blocking.
Layer 2 Security
Enabled port security with sticky MAC learning.
Configured maximum MAC addresses and restrict violation mode.
Enabled PortFast and BPDU Guard.
Configured errdisable recovery.
Enabled DHCP Snooping.
Enabled Dynamic ARP Inspection.
Configured trusted uplink interfaces.
Switching Security
Configured trunking.
Set native VLAN 999.
Disabled DTP negotiation.
Verification

Verified configurations using Cisco IOS commands, including:

show running-config
show port-security interface g0/2
show ip dhcp snooping
show interfaces trunk
show ip ssh

Successfully tested SSH administrative access from PC-A to SW1.

Corrected PC-B's default gateway to 192.168.10.1.

Skills Demonstrated
Cisco IOS configuration
Network device hardening
Secure remote administration
AAA authentication
Layer 2 security
Network troubleshooting
Configuration verification
Lab Environment

Cisco Packet Tracer

Note: This is a simulated lab environment. External AAA service traffic was not modeled.
