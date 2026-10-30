Site-to-Site IPsec VPNA 
comprehensive implementation guide and technical report for a Site-to-Site IPsec Virtual Private Network (VPN) using Cisco routers, developed as part of a CCNA Security oriented project.


📋 Project OverviewModule:
Network FoundationAcademic Year: 2025–2026
Institution: National School of Cyber Security (NSCS)


🛠️ Theoretical Framework & Objectives:
This project demonstrates how to securely interconnect two remote Local Area Networks (LANs) over an untrusted ISP infrastructure.Key Services Provided: Confidentiality (AES encryption), Integrity (SHA hashing), Peer Authentication, and Anti-Replay protection.

Operating Mode: IPsec Tunnel Mode (standard for site-to-site deployments).

🌐 Network Addressing 

   TableDeviceInterfaceIP
 
      AddressSubnet

MaskRouter 1    (WAN)Gi0/0209.165.100.1255.255.255.252
Router     1    (LAN)Gi0/1192.168.1.1255.255.255.0
Router     3    (WAN)Gi0/0209.165.200.1255.255.255.252
Router     3    (LAN)Gi0/1192.168.3.1255.255.255.0
