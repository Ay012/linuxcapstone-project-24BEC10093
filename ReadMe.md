The Open Source Audit.

Open Source Software Capstone Project
Course: Open Source Software VITyarthi
Student Name: Ayan Tandon
Registration Number: 24BEC10093
Chosen Software: Python (Python Software Foundation License)

About This Project:
This repository is my submission for the Open Source Audit capstone project. 
I am doing an audit of Python, which is one of the most widely used open-source programming languages. 
I will cover its origin story, license, Linux footprint, FOSS ecosystem and comparison with alternatives.

The repository also contains five shell scripts that demonstrate my Linux and bash scripting skills, which are aligned with the course concepts.

Script Descriptions:

Script 1. System Identity Report
This script displays system information such as kernel version, user name, home directory, uptime and date. 
It also prints information about the open-source environment.
I used some concepts like variables echo command substitution and formatted output in this script.

Script 2. FOSS Package Inspector
This script checks if Python is installed on the system. 
If it is the script displays the Python version and prints a philosophy note about open-source software.
I used concepts like if-else case statement, command detection and conditional logic in this script.

Script 3. Disk and Permission Auditor
This script loops through system directories and displays their permissions, ownership and disk usage. It also checks Python-related directories.
I used concepts like for loop arrays and conditionals in this script.

Script 4. Log File Analyzer
This script reads a log file. Counts occurrences of a specified keyword. It displays the count and last five matching lines.
I used concepts like command-line arguments, grep and conditional checks in this script.

Script 5. Open Source Manifesto Generator
This script prompts the user for input. Generates a personalized open-source manifesto saved to a text file.
I used concepts like read, variables, file writing and output redirection, in this script.

Dependencies:

All scripts are written in bash. Designed for Linux environments.
To install Python you can use these commands:

sudo update

sudo apt install python3

How to Run the Scripts:

Step 1. Clone the repository
git clone https://github.com/yourusername/oss-audit-24BEC10093.git
cd oss-audit-24BEC10093

Step 2. Make scripts executable
chmod +x script1.sh
chmod +x script2.sh
chmod +x script3.sh
chmod +x script4.sh
chmod +x script5.sh

Step 3. Run scripts

Script 1:
./script1.sh

Script 2:
./script2.sh

Script 3:
./script3.sh

Script 4:
./script4.sh

Script 5:
./script5.sh

Notes:

I tested the scripts using Git Bash and Linux shell.
They work best on Ubuntu or WSL.
Some directories may differ on Windows environments.

References:

Python Official Website: https://www.python.org
Python Documentation: https://docs.python.org/3/
Python Software Foundation: https://www.python.org/psf/
GNU Bash Manual:Linux Command Line Guide: https://linuxcommand.
