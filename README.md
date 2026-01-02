# Bash Network Scanner (Ping Sweeper)

## Overview
This is a Bash script designed for network reconnaissance. It automates the process of discovering active hosts on a network by iterating through IP addresses and analyzing ICMP (Ping) responses.

## Features
- **Range Scanning:** Scans a user-defined subnet (e.g., `192.168.1.x`) from host 1 to 254.
- **Input Handling:** Accepts user input to define the target network.
- **Traffic Logic:** Uses `ping` with specific timeouts (`-W`) to prevent hanging on dead hosts.
- **Exit Code Analysis:** Uses `$?` to determine if a host is reachable (0) or offline (1).

## How to Use
1. Make the script executable:
   ```bash
   chmod +x netsweep.sh

 A Bash script for automated network reconnaissance and active host discovery using ICMP (Ping)
