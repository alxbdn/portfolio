# Portfolio

Welcome to my portfolio! This repository showcases a collection of Python projects and various Security Operations Center (SOC) analyst projects that demonstrate my skills and expertise in programming and cybersecurity.

## Table of Contents

1. [Introduction](#introduction)
2. [Python Projects](#python-projects)
3. [Contact](#contact)

## Introduction

This portfolio contains a range of projects that highlight my proficiency in Python programming and my work in the field of cybersecurity. The projects include scripts, tools, and analyses related to security operations and incident response.

## Python Projects

### Project 1: python-passgen.py
- **Description**: A simple password generator 
- **Features**:
  - Strong password using ASCII letters, digits, and punctuation.
  - 10 characters lenght

### Project 2: python-passman.py
- **Description**: A simple password manager
- **Features**:
  - Create account function
  - Login function
  - hashing feature to store passwords
  - Menu to choose between account creation and login
 
### Project 3: python-nmap.py
- **Description**: This Python code uses the Nmap tool (a network scanning utility) through its Python binding, python-nmap, to scan a target IP address for open ports, service versions, and possibly run default scripts (depending on the scan options).
- **Features**:
  - Importing Nmap library
  - Creating an Nmap Scanner instance
  - Defining the target and scan options
  - Executing the scan
  - Processing and printing the scan results
- **Use Case**: This script is designed to perform a network port scan on a specified IP address (45.33.32.156), gathering information about:
    - Which ports are open.
    - What services are running on these ports.
    - The versions of these services (via -sV option).
    - Running Nmap's default scripts for more information (via -sC).

### Project 4: python-cipher.py
- **Description**: This Python script implements a Caesar cipher, which is a simple encryption technique that shifts each letter of the message by a fixed number of positions in the alphabet. The script includes two main functions: one for encrypting a message and one for decrypting it.
- **Features**:
  - Importing the string module
  - Caesar Cipher Encryption
  - Caesar Cipher Decryption
  - Encrypting and Decrypting the Message
- **Use Case**: This script demonstrates how to implement a Caesar cipher, a classical cryptographic method. The encryption and decryption functions allow secure communication where the message can only be understood by someone who knows the key (in this case, 3).
 
### Project 5: python-whois.py
- **Description**: This Python script uses the socket module to perform a WHOIS lookup on a domain name. WHOIS is a protocol used to query information about domain name registrations, providing details such as the registrar, registration dates, and other information.
- **Features**:
  - Importing the socket module
  - WHOIS Lookup Function
  - Creating a TCP Socket
  - Connecting to the WHOIS Server
  - Sending the Domain Query
  - Receiving and Decoding the Response
  - Closing the Socket
  - Returning the Response
- **Use Case**: This script can be used to perform WHOIS lookups for domain names to retrieve information about the domain's registration, such as the registrar, creation date, and nameservers. It is often used by security researchers, network administrators, or anyone wanting to gather information about a domain.
- **Limitations**:
  - The script currently only connects to whois.iana.org, which provides basic information and may redirect you to a different WHOIS server for detailed information.
  - To get full details, you would need to connect to the correct WHOIS server specified by IANA, which would require additional logic.
 
### Project 6: python-pingsweep.py
- **Description**: This Python script performs a ping sweep on a given network. A ping sweep is a technique used to detect live hosts in a network by sending ICMP (ping) requests to all possible IP addresses in the given subnet and determining which ones respond.
- **Features**:
  - Importing necessary modules
  - Ping Sweep Function (ping_sweep)
  - Initializing variables
  - Creating the IP network
  - Counting total hosts
  - Performing the ping sweep
  - Returning live hosts
  - Main section
- **Use Case**: This script can be used by network administrators or penetration testers to identify live devices within a specific network. It helps in discovering which devices are active by sending ICMP ping requests to all the hosts in the subnet.
- **Notes**:
  - Scapy requires root/administrator privileges to send and receive raw packets.
  - If ICMP responses are blocked (by a firewall, for instance), hosts may appear offline even if they are active.
 
## Contact
  - Linkedin : https://www.linkedin.com/in/alexandreboudon/
  - mail : alx.boudon@gmail.com
  - tel : +33 7 60 63 90 86
