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

---
## Day 2 

### 14. Kali Linux Overview

Explored Kali Linux, a Debian-based operating system designed for penetration testing, digital forensics, and security auditing. Learned about its desktop and command-line environments, preinstalled cybersecurity tools, and how it can be used in a virtual machine to build a controlled environment for learning security testing. Also explored the importance of using these tools only on systems for which permission has been granted.

### 15. Sudo Overview

Learned how `sudo` (superuser do) allows authorized users to execute commands with elevated privileges without necessarily logging in as the root user. Understood why some tasks, such as installing software or modifying system configuration, require administrative permissions. Also learned the importance of checking commands before running them with `sudo`, since elevated access can affect critical system files and settings.

### 16. Navigating the File System

Learned how to navigate the Linux directory structure through the terminal. Practiced commands such as `pwd` to display the current directory, `ls` to list files and directories, and `cd` to move between locations. Explored important directories, including `/home` for user files, `/etc` for system configuration, `/var` for changing data and logs, `/tmp` for temporary files, and `/root` for the root user's home directory. Also studied the difference between absolute and relative paths.

### 17. Users and Privileges

Explored how Linux uses users and groups to control access to files, directories, and system resources. Learned the three permission categories: owner, group, and others, alongside read (`r`), write (`w`), and execute (`x`) permissions. Reviewed commands such as `whoami` to identify the current user, `id` to display user and group IDs, `groups` to list group memberships, `chmod` to change permissions, and `chown` to change ownership. These concepts are important for understanding Linux security and preventing unauthorized access.

### 18. Common Network Commands

Learned how to use Linux networking commands to inspect network settings and troubleshoot connectivity problems. Explored `ip addr` for viewing network interfaces and IP addresses, `ip route` for examining routing information, `ping` for testing network reachability, and `ss` for inspecting network connections and listening ports. Understood how these commands help identify network configuration issues and provide useful information during authorized security assessments.

### 19. Viewing, Creating, and Editing Files

Practiced managing files and directories directly from the Linux terminal. Learned how `cat` displays file contents, `less` allows files to be viewed page by page, and `touch` creates empty files or updates timestamps. Explored `mkdir` for creating directories, `cp` for copying files, `mv` for moving or renaming files, and `rm` for removing files. Also reviewed using the Nano text editor to create and edit configuration files, notes, and scripts.

### 20. Starting and Stopping Services

Learned that Linux services are background processes that provide functions such as networking, time synchronization, and web hosting. Explored `systemctl` for managing services, including checking their status, starting or stopping them, and restarting them when necessary. Also learned the difference between starting a service temporarily and enabling it to launch automatically at boot. Understanding service management helps with system administration and identifying unnecessary services that could increase a system's attack surface.

### 21. Installing and Updating Tools

Explored the APT package manager used by Kali Linux to install, update, and remove software. Learned that `sudo apt update` refreshes the local package lists, while `sudo apt upgrade` upgrades installed packages when updates are available. Reviewed `sudo apt install` for installing tools and `sudo apt remove` for removing packages. Understood the importance of keeping the operating system and security tools updated to obtain bug fixes, security patches, and improved functionality.

### 22. Bash Scripting

Introduced Bash scripting as a way to combine Linux commands into reusable scripts and automate repetitive tasks. Learned about creating a script file, using the shebang `#!/bin/bash` to specify the interpreter, defining variables, displaying output with `echo`, and accepting user input with `read`. Also explored conditional statements, loops, and executable permissions, which form the foundation for building more useful automation scripts. In cybersecurity, Bash can help automate routine system checks, organize command output, and perform authorized administrative tasks.
