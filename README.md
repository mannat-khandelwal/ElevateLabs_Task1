# ElevateLabs_Task1

Network Scanning Task – Nmap | Target: 192.168.88.0/24

Overview:

This project demonstrates a basic network scanning task performed using Nmap on Kali Linux. The goal was to identify live hosts, open ports, running services, and evaluate any potential security risks in a local subnet.

Tools Used:

Kali Linux (Operating System) Nmap (Network Mapper)

Steps Performed:

Host Discovery
To identify live hosts within the target network:
nmap -sn 192.168.88.0/24

-sn = Performs a host discovery only, without scanning any ports.

Once the active hosts were identified, a full TCP scan was performed:
nmap -sS 192.168.88.0/24

-sS = Performs a stealthy scan by sending SYN packets to detect open ports. To find which TCP ports are open, without completing the TCP handshake.

Conclusion:
This exercise helped us understand:

The use of Nmap for active host and port discovery
Identifying services and understanding their function
Evaluating basic network security risks.
