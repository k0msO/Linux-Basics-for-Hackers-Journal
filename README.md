# 🐧 Linux Basics for Hackers - Lab Journal

## Objective
Document hands-on Linux networking exercises to build foundational 
skills for SOC analysis and penetration testing.

## Chapter 3: Networking — Exercises & Solutions

### Exercise 1: Active Network Interfaces
Used `ifconfig` to identify active interfaces (eth0, eth1, lo) 
and analyze IP configurations, MAC addresses, and packet statistics.

### Exercise 2: IP Address Manipulation
Changed eth0 IP to 192.168.1.1 using `sudo ifconfig eth0 192.168.1.1`

### Exercise 3: MAC Address Spoofing
Brought interface down, changed hardware address with 
`ifconfig eth0 hw ether 00:11:22:33:44:55`, brought interface back up.

### Exercise 7: DNS Configuration
Edited `/etc/resolv.conf` to add Google's DNS server (8.8.8.8) 
as a fallback nameserver.

## Skills Demonstrated
- Linux command-line networking
- Interface configuration and troubleshooting
- MAC address manipulation
- DNS server management

## Tools Used
- Kali Linux, ifconfig, iwconfig, dig, nano
