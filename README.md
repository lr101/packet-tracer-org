# Packet Tracer Org Example

This project was an assignment in university to create a real-life organization structure and network security implementation in packet tracer. 
It focuses on implementing network security policies for a Small-to-Medium Business (SMB) operating in a hybrid cloud environment

This includes:
 - Different deparments, a DMZ, remote workers and server running in the cloud
 - The network is split into Internal, DMZ and external zones, were all public facing services are in the DMZ and all departments are on seperate VLANs in the internal zone
 - ACLs are implemented between the VLANs to limit access
 - IDS and IPS are used to detect and prevent common attack patterns
 - Routing and fallback routers are setup (Routers, Firewalls, MLPS, Switches)
 - RADIUS is used to implement AAA on all network devices
 - A site-to-site VPN is used to connect the internal zone with the cloud
 - Device hardening is performed on all network devices (turn off unused ports, restrict access, use spanning-tree guards, ...)

