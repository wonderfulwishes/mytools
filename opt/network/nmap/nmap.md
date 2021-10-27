# nmap 

Nmap is a free and open-source network scanner &  Nmap is used to discover hosts and services on a computer network by sending packets and analyzing the responses.


[Nmap-cheat-sheet](https://www.stationx.net/nmap-cheat-sheet/)


**1. Target Specification**
**2. Scan Techniques**
**3. Host Discovery**
**4. Port Specification**
**5. Service and Version Detection**
**6. OS Detection**
**7. Timing and Performance**
**8. NSE Scripts**
**9. Firewall / IDS Evasion and Spoofing**
**10. Output**
**11. Miscellaneous Options**
**12. Other Useful Nmap Commands**




What are the techniques when using nmap?


**Target Specification**

1. Scan a single IP
2. Scan specific IPs
3. Scan a range
4. Scan using CIDR notation
5. Scan targets from a file
6. Scan 100 random hosts
7. Exclude listed hosts


**Scan Techniques**

1. TCP SYN port scan (Default)
2. TCP connect port scan (Default without root privilege)
3. UDP port scan
4. TCP ACK port scan
5. TCP Window port scan
6. TCP Maimon port scan


**Host Discovery**
1. No Scan. List targets only
2. Disable port scanning. Host discovery only.
3. Disable host discovery. Port scan only.
4. TCP SYN discovery on port x. (Port 80 by default)
5. TCP ACK discovery on port x. (Port 80 by default)
6. UDP discovery on port x. (Port 40125 by default)
7. ARP discovery on local network 
8. Never do DNS resolution


**Port Specification**
1. Port scan for port x
2. Port range
3. Port scan multiple TCP and UDP ports
4. Port scan all ports
5. Port scan from service name
6. Fast port scan (100 ports)
7. Port scan the top x ports
8. Leaving off initial port in range (makes the scan start at port 1)
9. Leaving off end port in range makes the scan go through to port 65535


**Service and Version Detection**
1. Attempts to determine the version of the service running on port
2. Intensity level 0 to 9. Higher number increases possibility of correctness
3. Enable light mode. Lower possibility of correctness. Faster
4. Enable intensity level 9. Higher possibility of correctness. Slower
5. Enables OS detection, version detection, script scanning, and traceroute


**OS Detection**

1. Remote OS detection using TCP/IP stack fingerprinting
2. If at least one open and one closed TCP port are not found it will not try OS detection against host
3. Makes Nmap guess more aggressively
4. Set the maximum number x of OS detection tries against a target
5. Enables OS detection, version detection, script scanning, and traceroute


**Timing and Performance**
1. Paranoid (0) Intrusion Detection System evasion
2. Sneaky (1) Intrusion Detection System evasion
3. Polite (2) slows down the scan to use less bandwidth and use less target machine resources
4. Normal (3) which is default speed
5. Aggressive (4) speeds scans; assumes you are on a reasonably fast and reliable network
6. Insane (5) speeds scan; assumes you are on an extraordinarily fast network
7. Give up on target after this long
8. Specifies probe round trip time
9. Parallel host scan group sizes
10. Probe parallelization
11. Adjust delay between probes
12. Specify the maximum number of port scan probe retransmissions
13. Send packets no slower than number per second
14. Send packets no faster than number per second


**NSE Scripts**

1. Scan with default NSE scripts. Considered useful for discovery and safe
2. Scan with default NSE scripts. Considered useful for discovery and safe
3. Scan with a single script. Example banner
4. Scan with a wildcard. Example http
5. Scan with two scripts. Example http and banner
6. Scan default, but remove intrusive scripts
7. NSE script with arguments


**Firewall / IDS Evasion and Spoofing**

1. 	Requested scan (including ping scans) use tiny fragmented IP packets. Harder for packet filters
2. 	Set your own offset size
3. 	Send scans from spoofed IPs
4. 	Above example explained
5. 	Scan Facebook from Microsoft (-e eth0 -Pn may be required)
6. 	Use given source port number
7. 	Relay connections through HTTP/SOCKS4 proxies
8. 	Appends random data to sent packet


**Output**
1. Normal output to the file normal.file
2. XML output to the file xml.file
3. Grepable output to the file grep.file
4. 	Output in the three major formats at once
5. 	Grepable output to screen. -oN -, -oX - also usable
6. 	Append a scan to a previous scan file
7. 	Increase the verbosity level (use -vv or more for greater effect)
8. 	Increase debugging level (use -dd or more for greater effect)
9. 	Display the reason a port is in a particular state, same output as -vv
10. Display the reason a port is in a particular state, same output as -vv
11. Only show open (or possibly open) ports
12. Show all packets sent and received
13. Shows the host interfaces and routes
14. Resume a scan

15. Scan for web servers and grep to show which IPs are running web servers
16. Generate a list of the IPs of live hosts
17. Append IP to the list of live hosts
18. Compare output from nmap using the ndif
19. Convert nmap xml files to html files
20. Reverse sorted list of how often ports turn up



**Miscellaneous Options**
1. Enable IPv6 scanning
2. nmap help screen



**Other Useful Nmap Commands**
1. Discovery only on ports x, no port scan
2. Arp discovery only on local network, no port scan
3. Traceroute to random targets, no port scan
4. Query the Internal DNS for hosts, list targets only

  

**Common Usage of nmap commands I used**

```
nmap <ip add>
```
