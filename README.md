# Network Security & Socket Programming Assignment

## Overview

This repository contains the work for an assignment involving two tasks: identifying a network security breach and practicing network socket programming.

### Task 1: Identify a Network Security Breach
In this task, a webserver was installed and an insecure website was examined for potential vulnerabilities. Using **Wireshark**, network traffic was captured to identify security flaws, specifically focusing on extracting sensitive information such as usernames and passwords.

### Task 2: Socket Programming
In the second task, socket programming was practiced by establishing a TCP connection with a specified server. **Wireshark** was used to capture and analyze network traffic, focusing on application transactions, TCP handshake, and local subnet broadcasting.

## Installation

### Webserver Setup:
1. Install your preferred webserver (Apache, Nginx, IIS).
2. Configure the server to host the website content, including your hobbies, interests, and student ID picture.
3. Access the insecure website (`http://zero.webappsecurity.com/index.html`) to capture network traffic and analyze it for security breaches.

### Wireshark Setup:
1. Install **Wireshark** to monitor the network traffic during the execution of both tasks.

### Socket Programming:
1. Complete the socket programming as per Lab 7 instructions, but replace the server with `netlab.cs.herts.ac.uk`.
2. Modify the displayed message to include your student ID when the connection is made.
3. Monitor and analyze the traffic using **Wireshark**.

## Task Breakdown

### Task 1: Identify a Network Security Breach
- **Objective**: Install a webserver, access an insecure website, capture network traffic, and extract sensitive data (username/password).
- **Tools Used**: Apache Webserver, Wireshark
- **Key Findings**: Captured network traffic revealed the transmission of plain text username and password, highlighting a security vulnerability.

### Task 2: Socket Programming
- **Objective**: Perform socket programming to establish a TCP connection, modify the connection message, and analyze the traffic using Wireshark.
- **Tools Used**: Python (socket library), Wireshark
- **Key Findings**: Captured socket communication and examined TCP handshake and application-level transactions.

## Screenshots

### Task 1:
- **Webserver Screenshot**: A screenshot of the installed webserver and website.
- **Captured Traffic**: Evidence of extracted username/password from Wireshark.
- **Security Breach Discussion**: Details of the security breach and recommendations for preventing similar incidents.

### Task 2:
- **Socket Programming Output**: Screenshot of the Python socket programming output with the modified message.
- **Wireshark Traffic Capture**: Screenshots of the network traffic captured during the socket connection process.

## Report

The full report on both tasks can be found in the `report.md` file, detailing the analysis of security flaws, Linux security evaluation, and network communication analysis.

## Directory Structure

