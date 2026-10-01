# cyber-task1
# Nmap Network Scanning and Wireshark Analysis

## Objective
Perform a TCP SYN scan and analyze the resulting network traffic.

## Tools Used

- Nmap
- Wireshark

## Procedure

### 1. Install Nmap
...

### 2. Find Local IP Range
...

### 3. Perform TCP SYN Scan

```bash
nmap -sS 192.168.29.20 -oN scan_results.txt

wireshark
tcp.flags.syn == 1 && tcp.flags.ack == 0

