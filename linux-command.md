# Linux Command Cheatsheet

## File and Directory Management

- `ls`: List files and directories.
- `pwd`: Print the current working directory.
- `cd <directory>`: Change the current directory.
- `mkdir <directory>`: Create a new directory.
- `rmdir <directory>`: Remove an empty directory.
- `rm <file>`: Remove a file.
- `rm -r <directory>`: Remove a directory and its contents.
- `touch <file>`: Create an empty file.
- `cp <source> <destination>`: Copy files and directories.
- `mv <source> <destination>`: Move or rename files and directories.
- `find <directory> -name <filename>`: Search for files in a directory.

## File Viewing and Editing

- `cat <file>`: Display the contents of a file.
- `less <file>`: View a file one page at a time.
- `nano <file>`: Edit a file using the Nano text editor.
- `vim <file>`: Edit a file using the Vim text editor.
- `head <file>`: Display the first lines of a file.
- `tail <file>`: Display the last lines of a file.

## File Permissions

- `chmod <permissions> <file>`: Change file permissions.
- `chown <user> <file>`: Change the owner of a file.
- `chgrp <group> <file>`: Change the group of a file.
- `umask`: Display or set the default file permissions.

## Process Management

- `ps`: List running processes.
- `top`: Display a dynamic view of system processes.
- `kill <PID>`: Terminate a process by its Process ID.
- `killall <process_name>`: Terminate processes by their names.
- `nice`: Set process priority.
- `jobs`: List background jobs.
- `fg`: Bring a background job to the foreground.

## System Information

- `uname -a`: Display system information.
- `lsb_release -a`: Display Linux distribution information.
- `df -h`: Show disk space usage.
- `free -h`: Display memory usage.
- `ifconfig`: Show network interfaces and IP addresses.
- `netstat`: Display network statistics.

## Package Management

- `apt update`: Update the package list (Debian/Ubuntu).
- `apt upgrade`: Upgrade installed packages (Debian/Ubuntu).
- `yum update`: Update the package list (Red Hat/CentOS).
- `yum upgrade`: Upgrade installed packages (Red Hat/CentOS).
- `dnf update`: Update the package list (Fedora).

## File Compression and Archiving

- `tar -cvf <archive.tar> <files>`: Create a Tar archive.
- `tar -xvf <archive.tar>`: Extract files from a Tar archive.
- `gzip <file>`: Compress a file with Gzip.
- `gunzip <file.gz>`: Decompress a Gzipped file.
- `zip -r <archive.zip> <directory>`: Create a Zip archive.
- `unzip <archive.zip>`: Extract files from a Zip archive.

## User and Group Management

- `useradd <username>`: Add a new user.
- `userdel <username>`: Delete a user.
- `passwd <username>`: Change a user's password.
- `groupadd <groupname>`: Create a new group.
- `groupdel <groupname>`: Delete a group.
- `adduser <username> <groupname>`: Add a user to a group.
- `deluser <username> <groupname>`: Remove a user from a group.

## Miscellaneous

- `date`: Display the current date and time.
- `who`: Show who is logged in.
- `shutdown`: Shut down or restart the system.
- `reboot`: Reboot the system.

Remember to use these commands with caution, especially when dealing with system files and configurations. Always refer to the documentation and man pages for more detailed information on each command.

