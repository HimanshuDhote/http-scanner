# HTTP-Scanner
The HTTP Scanner is a tool designed to scan for common vulnerabilities.  The tools is helpful to find below listed common vulnerability:
* It helps identify web applications or pages that are susceptible to clickjacking attacks, where an attacker tricks users into interacting with malicious elements unknowingly.
* It helps identify web applications that may have misconfigured or missing HTTP headers,cookies, which can lead to security risks or improper behavior.

# Requirements:
To run this script, Curl need to be there in your system.

# Install
Curl is a widely used command-line tool for making HTTP requests and transferring data. It is available for various Linux distributions, and the installation process may vary slightly depending on the package manager used by each distribution. Here are the installation instructions for some popular Linux distributions:

# Debian-based distributions (e.g., Ubuntu, Debian)
Open a terminal and run the following command to install curl:

`sudo apt-get install curl`

# Red Hat-based distributions (e.g., CentOS, Fedora)
Open a terminal and run the following command to install curl:

`sudo dnf install curl`

or

`sudo yum install curl`

# Arch-based distributions (e.g., Arch Linux)
Open a terminal and run the following command to install curl:

`sudo pacman -Sy curl`

# SUSE-based distributions (e.g., openSUSE)
Open a terminal and run the following command to install curl:

`sudo zypper install curl`

# Useage

Follow these steps to run the shell scripts from this repository:

* Clone the repository to your local machine using the following command:

`git clone https://github.com/HimanshuDhote/http-scanner`

* Change into the cloned repository's directory:

`cd http-scanner`

* Make the shell script executable by running the following command:

`chmod +x http-scanner.sh`

* Run the shell script using the following command:

`./http-scanner.sh`


