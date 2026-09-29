Activity # 7: adoVM CTM Terminal Simulator (Linux Networking Commands)

Repository: GitHub https://github.com/MasterMind8307/CTM_Activity_7

Overview

The adoVM CTM Terminal Simulator is a Python-based terminal simulation designed to replicate basic Linux networking commands in a controlled environment.

This project is created for CTM Simulation students to practice:

Networking fundamentals

Command-line usage

Cybersecurity concepts (SOC basics)

Objectives Simulate real-world Linux networking tools

Interpret command outputs

Understand network diagnostics

Develop foundational cybersecurity skills

Features

Simulated Linux terminal interface

Predefined DNS and IP mappings

Randomized outputs for realism

Activity logging system

File system simulation (ls, cat, wget)

Admin vs non-admin command behavior

How to Download & Run (from GitHub)

Repository:

https://github.com/MasterMind8307/CTM_Activity_7

Option 1: Download as ZIP (Easiest)

1. Go to the repository link above

2. Click the green “Code” button

3. Select “Download ZIP”

4. Extract the ZIP file on your computer

5. Open the folder

6. Double-click the .exe file to run

Option 2: Clone using Git (Optional)

1. Open Command Prompt / Terminal

2. Run:

https://github.com/MasterMind8307/CTM_Activity_7

3. Open the downloaded folder

4. Run the .exe file

Running the Program

Simply double-click the .exe file

A terminal window will appear

Follow the setup instructions (hostname, IP, etc.)

Initial Setup

When the program starts:

1. Enter a Hostname

2. Choose connection:

Ethernet

WLAN

3. Enter a Class A IP Address (1–126 range)

Example: 10.0.0.1

4. Subnet mask is automatically:

255.0.0.0

[Commands Overview]

Basic Commands

help

ip a

ip route

hostname -I

Network Tools

ping

traceroute

netstat -tulnp

DNS Tools

nslookup

dig

Scanning

nmap

nmap -sV

nmap -A

Monitoring

arp-scan --localnet

sudo arp-scan --localnet

tcpdump -i

Web Tools

curl

nc

whois

File System

ls

cat

wget

System

shutdown

[Major Tasks]

Activity 1: Network Info

ip a

hostname -I

Activity 2: Connectivity Test

ping

traceroute

Activity 3: DNS Analysis

nslookup

dig

Activity 4: Port Scanning

nmap

nmap -sV

nmap -A

Task 5: Traffic Monitoring

tcpdump -i Ethernet

Task 6: Device Discovery

arp-scan --localnet

sudo arp-scan --localnet

Task 7: Logs & Files

ls

cat

wget
