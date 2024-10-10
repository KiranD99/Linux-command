Linux command(sysopctl)
sysopctl is a custom Linux command-line utility designed to help manage system resources, services, processes, and logs. It provides simple, intuitive commands to perform tasks such as listing running services, viewing system load, monitoring processes, and more.

Features
Service Management: Start, stop, and list running services.
System Monitoring: Check system load and monitor processes in real-time.
Disk Usage: Display disk usage by partition.
Log Analysis: Analyze recent critical system logs.
Backup: Backup directories to a specified path.

Installation
Clone the repository and navigate to the project directory:
        git clone <repository-url>
    cd sysopctl
Make the script executable:
        chmod +x sysopctl.sh
Optionally, move the script to a directory in your $PATH for easier access:
        sudo mv sysopctl.sh /usr/local/bin/sysopctl
        
To set up the manual page (optional):
Create a file called sysopctl.1 and place it in /usr/share/man/man1/, or use the included man page file.

Run
sudo mandb

Usage
Run sysopctl with the following commands and options: 
General Commands
Display help:
    sysopctl --help
Display version:
    sysopctl --version
    
Requirements:
Linux operating system
Bash shell (>= 4.0)
Utilities: systemctl, uptime, df, top, journalctl, rsync
