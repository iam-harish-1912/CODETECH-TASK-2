NAME : HARISH K

COMPANY : CODTECH IT SOLUTIONS

ID : CT08DS4488

DOMAIN : CYBER SECURITY AND ETHICAL HACKING

DURATION : 4 WEEKS

MENTOR : MUZAMMIL AHMED

OVERVIEW OF THE PROJECT

Project : Simple Network Vulnerability Scanner

Objective

The Simple Vulnerability Scanning Tool project is designed to assess the security of a network or website by scanning for common vulnerabilities. The tool focuses on identifying open ports, detecting outdated software versions, and checking for basic misconfigurations. This project aims to provide a basic yet functional security assessment tool that helps users identify potential security weaknesses and take necessary actions to mitigate them.

Key Features

Open Port Scanning:

The tool scans a predefined list of common ports on the target IP address or hostname to identify which ports are open. Open ports can potentially be exploited by attackers if the services running on them have vulnerabilities.

Outdated Software Detection:

The tool checks the versions of commonly used software (e.g., Apache, Nginx, MySQL) installed on the target system and compares them against the latest known versions. This helps identify outdated software that may contain known vulnerabilities.

Basic Misconfiguration Checks:

Although the current implementation is simplified and doesn't include comprehensive misconfiguration checks, it provides a foundation for extending the tool to include more sophisticated configuration auditing.

Code Explanation

Main Method:

The main method is the entry point of the application. It prompts the user to enter the IP address or hostname to scan, then calls the methods for port scanning and software version checking.

Port Scanning (scanPorts method):

This method iterates over a list of common ports (e.g., 21, 22, 80, 443) and attempts to establish a connection to each port on the target. If the connection is successful, the port is open; otherwise, it is closed.

Software Version Checking (checkSoftwareVersions method):

This method compares the installed versions of specific software (hardcoded for demonstration) against the latest known versions stored in a map. It reports whether the installed software is up-to-date or outdated.

Sample Output

When the tool is run, it might produce output similar to the following:
(https://github.com/user-attachments/assets/0dd72d1c-63b3-4113-aa70-d7bff9276063)

Usage

User Input:

The user is prompted to enter the target IP address or hostname to scan.

Port Scanning:

The tool scans a set of common ports on the target to identify which ones are open.

Software Version Checking:

The tool checks the versions of predefined software on the target and reports whether they are up-to-date.

Benefits

Security Awareness:

Helps users identify open ports and outdated software that could be potential security risks.

Proactive Measures:

Encourages users to update their software and close unnecessary open ports to improve security.

Foundational Tool:

Provides a basis for further development and extension to include more comprehensive vulnerability checks.

Conclusion

The Simple Vulnerability Scanning Tool project provides a basic yet functional utility for assessing the security of networks and websites. By identifying open ports and outdated software, it helps users take proactive steps to secure their systems. This project serves as an introductory example of vulnerability scanning and can be expanded to include more advanced features and checks.
