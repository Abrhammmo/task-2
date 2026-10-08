# task-2

## Overview

Today, I started learning the fundamentals of ethical hacking, focusing on the role of an ethical hacker, essential security tools, networking concepts, and setting up a virtual environment for practical cybersecurity exercises.

## Topics Covered

### 1. Introduction to Ethical Hacking

Learned the meaning and purpose of ethical hacking, including how security professionals identify vulnerabilities and help organizations protect their systems. Also explored the importance of authorization, responsible disclosure, and working within a defined scope.

### 2. A Day in the Life of an Ethical Hacker

Explored the typical workflow of an ethical hacker, from gathering information and identifying potential vulnerabilities to testing security controls and documenting findings. Understood the importance of communicating risks and recommending appropriate fixes.

### 3. Effective Note-Taking

Learned why maintaining clear, organized notes is important during security assessments. Useful notes should include commands, tool configurations, observations, errors, findings, and possible solutions so that tests can be reproduced later.

### 4. Important Ethical Hacking Tools

Reviewed the role of commonly used cybersecurity tools for network discovery, traffic analysis, vulnerability assessment, and penetration testing. Understood that tools support the testing process, but interpreting their results requires technical knowledge.

### 5. Networking Fundamentals

Reviewed how computers and other devices communicate over networks. Covered concepts such as clients and servers, network communication, addressing, and data transfer, which form the foundation for understanding how systems interact and where security weaknesses may occur.

### 6. IP Addresses

Learned that an IP address identifies a network interface logically and enables data to be routed between networks. Explored IPv4 addresses, private and public IP addresses, and the difference between network and host portions of an address.

### 7. MAC Addresses

Studied MAC addresses, which are used to identify network interfaces at the Data Link layer for communication on a local network. Understood how MAC addresses differ from IP addresses and how devices use them when exchanging data within the same local network.

### 8. TCP, UDP, and the Three-Way Handshake

Learned the differences between TCP and UDP. TCP provides reliable, connection-oriented communication, while UDP sends data without establishing a connection first. Studied the TCP three-way handshake:

* **SYN:** The client requests to establish a connection.

* **SYN-ACK:** The server acknowledges the request and responds.

* **ACK:** The client acknowledges the response, completing the handshake.

These concepts help explain how network services communicate and how network traffic can be analyzed.

### 9. Common Ports and Protocols

Explored how port numbers help direct network traffic to the appropriate services and applications. Reviewed common ports and their associated protocols:

| Port | Protocol/Service | Purpose                     |
| ---- | ---------------- | --------------------------- |
| 21   | FTP              | File transfer               |
| 22   | SSH              | Secure remote access        |
| 25   | SMTP             | Email transmission          |
| 53   | DNS              | Domain name resolution      |
| 80   | HTTP             | Web communication           |
| 443  | HTTPS            | Encrypted web communication |

Understanding common ports helps identify network services during authorized security assessments.

### 10. The OSI Model

Studied the seven layers of the OSI model and how each represents a different part of network communication:

1. **Physical:** Transmits raw bits through physical media.

2. **Data Link:** Handles local network communication and frames.

3. **Network:** Manages logical addressing and routing.

4. **Transport:** Supports end-to-end communication using protocols such as TCP and UDP.

5. **Session:** Manages communication sessions.

6. **Presentation:** Deals with data representation, encoding, and related transformations.

7. **Application:** Supports network services used by applications.

The OSI model helps organize networking concepts and troubleshoot communication problems.

### 11. IP Subnetting

Learned how a large IP network can be divided into smaller subnetworks. Studied subnet masks, CIDR notation, network addresses, host addresses, and broadcast addresses. Also explored how subnetting helps organize networks, manage IP address allocation, and control network boundaries.

### 12. Installing VMware and VirtualBox

Explored virtualization platforms that allow multiple operating systems to run as virtual machines on a single computer. Learned how virtual machines can provide isolated environments for cybersecurity practice without requiring a separate physical computer for every operating system.

### 13. Installing Kali Linux

Learned about Kali Linux, a Debian-based Linux distribution designed for penetration testing and security auditing. Explored its role in cybersecurity labs and the importance of preparing a virtual machine for practicing security tools and techniques in a controlled environment.

## Key Takeaways

* Developed a stronger understanding of ethical hacking and the responsibilities of a security professional.

* Reviewed core networking concepts, including IP and MAC addresses, ports, protocols, and the OSI model.

* Learned the fundamentals of TCP connections and IP subnetting.

* Explored essential cybersecurity tools and virtualization platforms.

* Began preparing a Kali Linux environment for future hands-on security exercises.


**Next step:** Practice the networking concepts using simple commands and packet analysis, then begin exploring Kali Linux tools in an authorized lab environment.

