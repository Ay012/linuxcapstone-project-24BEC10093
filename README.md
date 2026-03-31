The Open Source Audit — Python
Open Source Software (OSS) Capstone Project

Course: Open Source Software | VITyarthi
Student Name: Ayan Tandon
Registration Number: 24BEC10093
Chosen Software: Python (Python Software Foundation License)

>> About This Project

This repository is the submission for the Open Source Audit capstone project. The project involves a structured audit of Python, one of the most widely used open-source programming languages, covering its origin story, license, Linux footprint, FOSS ecosystem, and comparison with proprietary alternatives.
The repository also contains five shell scripts demonstrating practical Linux and bash scripting skills aligned with course concepts.

>> Script Descriptions
Script 1 — System Identity Report

Displays key system information such as kernel version, user name, home directory, uptime, and date. Also prints information about the open-source environment.

Concepts used: variables, echo, command substitution $(), formatted output

Script 2 — FOSS Package Inspector

Checks whether Python is installed on the system. If found, it displays the Python version and prints a short philosophy note about open-source software.

Concepts used: if-then-else, case statement, command detection, conditional logic

Script 3 — Disk and Permission Auditor

Loops through important system directories and displays their permissions, ownership, and disk usage. Also checks Python-related directories.

Concepts used: for loop, arrays, ls -ld, du, awk, conditionals

Script 4 — Log File Analyzer

Reads a log file and counts occurrences of a specified keyword. Displays the total count and last five matching lines.

Concepts used: command-line arguments, grep, wc, tail, conditional checks

Script 5 — Open Source Manifesto Generator

Prompts the user for input and generates a personalized open-source manifesto saved to a text file.

Concepts used: read, variables, file writing, date command, output redirection

>> Dependencies

All scripts are written in bash and designed for Linux environments.

To install Python:
sudo apt update
sudo apt install python3

>> How to Run the Scripts

Step 1 — Clone repository
git clone https://github.com/yourusername/oss-audit-24BEC10093.git
cd oss-audit-24BEC10093

Step 2 — Make scripts executable
chmod +x script1.sh
chmod +x script2.sh
chmod +x script3.sh
chmod +x script4.sh
chmod +x script5.sh

Step 3 — Run scripts

Script 1:
./script1.sh

Script 2:
./script2.sh

Script 3:
./script3.sh

Script 4
./script4.sh

Script 5:
./script5.sh

>> Notes
Scripts tested using Git Bash / Linux shell
Works best on Ubuntu or WSL
Some directories may differ on Windows environments

📚 References
Python Official Website: https://www.python.org
Python Documentation: https://docs.python.org/3/
Python Software Foundation: https://www.python.org/psf/
GNU Bash Manual: https://www.gnu.org/software/bash/manual
Linux Command Line Guide: https://linuxcommand.org

