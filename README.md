# Linux-project
Autobackupfile.sh is a simple Bash script that automates the process of creating a compressed backup (.tar.gz) of recently modified files from a target directory, and stores it in a specified destination directory.
It’s designed to help automate daily backups in Unix/Linux environments.
#Features
Validates that the correct number of arguments is provided.
Checks that both source and destination directories exist.
Detects files modified within the last 24 hours.
Compresses selected files into a timestamped .tar.gz archive.
Moves the backup file to the specified destination directory.
