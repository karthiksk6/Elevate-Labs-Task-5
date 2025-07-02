# Elevate-Labs-Task-5
Analyzing Network Traffic Using Wireshark
This repository contains my work for Task 1 of the Cyber Security Internship: Capturing and Analyzing Network Traffic using Wireshark.

Objective
To capture live network packets using Wireshark and analyze them by applying protocol filters to identify basic protocols and traffic types.

Tools Used
Wireshark

Steps Performed
Start Packet Capture

Opened Wireshark and started capturing on the active network interface (Wi-Fi/Ethernet).

Verified the interface by checking for live traffic.

Generate Network Traffic

Visited websites such as facebook.com and google.com to create HTTP and DNS traffic.

Pinging servers to generate ICMP packets.

Stop Capture

After about 1 minute, stopped the packet capture.

Apply Protocol Filters

Applied filters in Wireshark to isolate and analyze specific protocols:

http – HTTP requests/responses

dns – DNS name resolution lookups

icmp – Ping/echo traffic

tcp – TCP transport layer

udp – UDP transport layer

ipv6 – IPv6 traffic

Export Capture

Saved the captured data as a .pcap file for further analysis or documentation.

Findings

Observed detailed packet information and protocol behavior.

Documented key packet attributes and traffic patterns based on applied filters.

File Contents
capture.pcap – The exported Wireshark capture file (if added).

README.md – This file, describing the task process and findings.

License
This project is part of an internship exercise and is intended for educational purposes.
