# Secure-Multi-Branch-Enterprise-Network-Infrastructure
This project demonstrates a high-security enterprise network design using Cisco Packet Tracer. The main goal was to implement a "Zero Trust" approach at the infrastructure level.

Key Security Implementations:
1. Layer 2 Security: Mitigated common attacks using Port-Security (MAC filtering) and DHCP Snooping.

2. Traffic Control (ACLs): Restrictive access lists to permit only HTTP/S & Syslog to servers, and exclusive SSH access for the IT department.

3. Management Hardening: Secured VTY & Console lines with local authentication and encrypted passwords.

4. Trusted Monitoring: Centralized logging via Syslog and secure time synchronization using NTP with MD5 Authentication.

5. Routing Security: Secured OSPF routing with Passive Interfaces to prevent internal information leakage.

Network Technologies:
1. Routing: OSPF (Multi-Branch), Router-on-a-Stick (Inter-VLAN).
2. Services: DHCP, DNS, Web Server, Syslog, NTP.
