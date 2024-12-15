# Server Management for Backup Server

---

### **Directory Creation & Organization:**

1. Create a directory named "backups".
2. Inside "backups", create 12 subdirectories, each named after a month (e.g., "January", "February", etc.), for storing backups of data or applications throughout the year.
3. Inside each month’s directory, create files for different backup sets, such as "database_backup.tar.gz", "config_files_backup.zip", or "logs_backup.bz2".

---

### **Move and Rename Files:**

1. Move a backup file (e.g., "jan_database_backup.tar.gz") from one month’s directory (e.g., "January") to another (e.g., "February") to organize backups based on their execution dates.
2. Rename a backup file (e.g., "old_backup.zip" to "new_backup_2024.zip") and verify the change by listing the contents of the directory.

---

### **Navigation & Listing Files:**

1. Navigate to the "backups" directory.
2. List the contents of the directory and verify the presence of all subdirectories and backup files created in the previous task.

---

### **File Permissions Management:**

1. Create a file named "backup_config.json" in the "backups" directory to store configuration details for automated backup processes.
2. Change the permissions of the file so that only the system administrators or backup managers have read, write, and execute permissions.
3. Verify the permission changes by listing the file’s details to ensure that only authorized personnel can modify the backup settings.

---

### **Backup Files:**

1. Create a backup of a file (e.g., "important_data.txt") by copying it to a backup directory for safekeeping.
2. Verify the backup operation by listing the contents of the backup directory to ensure the file has been successfully copied.

---

### **Removing Files & Directories:**

1. Delete an outdated backup file (e.g., "old_backup_2023.zip") in the "backups" directory to avoid storage wastage.
2. Remove an empty subdirectory from one of the months' directories (e.g., "March") if no backups were performed during that period.

---

### **Creating a Script for File Generation:**

1. Write a script that generates 100 dummy files (e.g., "backup_file_1.txt", "backup_file_2.txt") in a directory to simulate backup operations and test the backup system’s capacity.

---

### **Exploring File History:**

1. View the command history to see the last 20 commands executed related to backup processes and file management.
2. Search the history for any command related to backup file creation, backup file deletion, or backup script execution.

---

### **System Monitoring:**

1. Check the system’s uptime to ensure the Backup Server has been running without interruption and is available for regular backups.
2. View the system’s load and resource usage statistics to monitor disk space and ensure sufficient resources for backup operations, especially during large backup processes.

---

### **Checking File Ownership and Permissions:**

1. Check the ownership and group of a backup file (e.g., "system_backup.tar.gz") and verify whether they are correct to ensure only the backup team can modify or access critical backup files.

---

### **Ping Test & Network Verification:**

1. Verify network connectivity by pinging a remote backup server or storage destination to ensure the Backup Server can transfer files to remote locations for off-site backups.
2. Record the response times and verify the network connectivity to ensure smooth operation of network-based backups.

---

### **Search for Specific Files or Content:**

1. Search for a specific backup file (e.g., "server_backup_2024.tar.gz") within the "backups" directory to locate and restore the necessary backup.
2. Search for a specific string of text (e.g., "Error log") inside a backup log file to identify any issues during the backup process.

---

### **Create a Directory for Each User:**

1. Create a directory for each user or department (e.g., "HR_department", "Finance_department") to store their respective backups, ensuring easy access and management.
2. Assign appropriate permissions to ensure only authorized personnel can access or restore their department’s backups.

---

### **Creating a Script for Directory Cleanup:**

1. Write a script that deletes all empty subdirectories from the "backups" directory after a set period, helping to keep the backup storage organized and clear of unnecessary directories.

---

### **File Sorting & Management:**

1. Sort backup files in a directory by size or modification date, and list the files based on the most recently created or the largest ones.
2. Create a report listing the largest and smallest backup files, helping to identify which files are consuming the most storage and may require optimization.

---

### **File Type Identification:**

1. Identify and list backup files of specific types (e.g., archive files such as `.tar.gz`, `.zip`, `.bak`) in the "backups" directory to help organize the backups based on their format.
2. Filter and list only files related to a specific backup type (e.g., "full_backup_*.tar.gz", "incremental_backup_*.zip") to focus on particular backup strategies.

---

### **File Compression and Archive:**

1. Compress the "backups" directory into a single archive file for easier storage or transfer to off-site locations.
2. Verify the contents of the archive without extracting it to ensure that all relevant backup files are included.

---

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository