Web Vulnguard:-

Overview:-

Web Vulnguard is a comprehensive toolkit designed to perform web security audits. It leverages various industry-standard tools and techniques to identify, analyze, and mitigate vulnerabilities in web applications. This repository is ideal for cybersecurity professionals, researchers, and enthusiasts who aim to enhance the security posture of their web applications.

Features:-

Automated Scanning:
Utilize tools like Nikto, Amass, Whois, OWASP ZAP, and Arachni to perform thorough security scans.

Vulnerability Assessment:
Identify and document potential vulnerabilities in web applications.

Detailed Reporting:
Generate comprehensive reports that include findings and recommendations for improvement.
Command-Line Interface: Easy-to-use commands for quick and efficient security assessments.
Tools Included

Nikto:
A web server scanner that performs comprehensive tests against web servers for multiple items, including over 6700 potentially dangerous files/CGIs, versions on over 1250 servers, and version-specific problems on over 270 servers.

Amass:
A tool for in-depth DNS enumeration and network mapping.

Whois:
A query and response protocol that is widely used for querying databases that store registered users or assignees of an Internet resource.

OWASP ZAP:
An open-source web application security scanner. It helps find security vulnerabilities in web applications during the development and testing phase.

Arachni:
A feature-full, modular, high-performance Ruby framework aimed towards helping penetration testers and administrators evaluate the security of web applications.

Installation:-

Prerequisites:-

Ensure you have Kali Linux installed on your system.
Root privileges for certain commands.

Steps:-

Clone the Repository:

git clone https://github.com/yourusername/web-vulnguard.git
cd web-vulnguard

Install Nikto:

sudo apt-get install nikto
Install Amass:

sudo apt-get install amass

Install Whois:

sudo apt-get install whois

Install OWASP ZAP:

sudo apt-get install zaproxy

Install Arachni:

wget https://github.com/Arachni/arachni/releases/download/v1.5.1/arachni-1.5.1-0.5.12-linux-x86_64.tar.gz
tar -zxvf arachni-1.5.1-0.5.12-linux-x86_64.tar.gz

Usage:-

Nikto
Perform a basic scan:

sudo nikto -host http://example.com

Amass

Perform an active enumeration:

amass enum -active -d example.com -o ~/example_active_subdomains.txt

Whois

Retrieve domain information:

whois example.com

OWASP ZAP

Start the OWASP ZAP GUI:

zap.sh

Arachni

Perform a web scan:

./arachni/bin/arachni http://example.com
