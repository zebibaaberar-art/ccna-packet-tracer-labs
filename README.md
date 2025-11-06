# ccna-packet-tracer-labs
I confirmed successful address assignment and connectivity across the network. This lab strengthened my skills in IPv4 subnetting, router configuration, DHCP services, and troubleshooting in a hands-on CCNA environment. I configured DHCP relay using the IP helper-address feature to forward client DHCP requests to R1.
# CCNA DHCPv4 Configuration Lab

This lab demonstrates how to configure DHCPv4 services on Cisco routers and implement a DHCP relay to support multiple subnets in a growing network. The objective is to automate IPv4 address assignment for devices and eliminate manual configuration challenges.

## Objectives
**Part 1:** Build the network and configure basic device settings  
**Part 2:** Configure and verify two DHCPv4 servers on R1  
**Part 3:** Configure and verify a DHCP relay on R2  

---

## Background / Scenario
As the company network grows, manually assigning IP addresses is no longer manageable. In this lab, you configure Router R1 to act as a DHCPv4 server for two subnets and configure Router R2 to forward DHCP requests as a relay. This allows hosts on different networks to receive IP configurations automatically.

DHCP (Dynamic Host Configuration Protocol) simplifies the assignment of:
- IPv4 addresses  
- Subnet masks  
- Default gateways  
- DNS server information  

This lab uses typical CCNA devices and Cisco IOS versions, but other hardware may also work with minor command differences.

---

## Required Resources
- 2 Routers (Cisco 4221 or similar)  
- 2 Switches (Cisco Catalyst 2960 or similar)  
- 2 PCs with terminal software  
- Console cables  
- Ethernet cables  
- Cisco Packet Tracer or physical equipment  

---

## Part 1: Build the Network and Configure Basic Device Settings
1. Create the network topology as shown in the instructions.  
2. Subnet **192.168.1.0/24** to support the required networks.  
3. Configure basic settings on routers and switches:
   - Hostnames  
   - IP addresses  
   - Interfaces  
   - No shutdown  
   - Default gateway  
   - Basic switch setup  

---

## Part 2: Configure the DHCPv4 Server on R1
- Configure two DHCP pools  
- Set default gateway and DNS for each pool  
- Exclude router interface IPs  
- Verify DHCP operation with:
