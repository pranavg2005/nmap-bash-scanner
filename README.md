# Automated Network Reconnaissance using Nmap and Bash

## Overview
This beginner-friendly tool automates basic network scans using Nmap and Bash on Linux or WSL.

## Features
- Ping scan to check host availability
- Port scan to find open ports
- OS and service version detection
- Results saved to text files in a `results/` folder

## How to Use
1. Make the script executable:
   ```bash
   chmod +x scan.sh
   ```

2. Run the script:
   ```bash
   ./scan.sh
   ```

3. Enter a target IP or domain when prompted.
4. Find the results in the `results/` directory.
