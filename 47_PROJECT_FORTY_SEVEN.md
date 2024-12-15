# Server Management for Web Application Firewall

---

### **Directory Creation & Organization:**

1. Create a directory named "waf_logs".
2. Inside "waf_logs", create 12 subdirectories, each named after a month (e.g., "January", "February", etc.).
3. Inside each month's directory, create files representing daily WAF logs (e.g., "log_day_1.txt", "log_day_2.txt").

---

### **Move and Rename Files:**

1. Move a log file (e.g., "log_day_1.txt") from one month's directory to another (e.g., from "January" to "February").
2. Rename a log file within a directory (e.g., rename "log_day_1.txt" to "log_day_1_final.txt") and verify the change by listing the contents of the directory.

---

### **Navigation & Listing Files:**

1. Navigate to the "waf_logs" directory.
2. List the contents of the directory and verify the presence of all subdirectories for each month (e.g., "January", "February") and the relevant log files created in the previous task.

---

### **File Permissions Management:**

1. Create a file named "waf_config.txt" in the "waf_logs" directory to store Web Application Firewall settings (e.g., blocked IPs, allowed user agents).
2. Change the permissions of the file so that only the user has read, write, and execute permissions.
3. Verify the permission changes by listing the file's details.

---

### **Backup Files:**

1. Create a backup of a log file (e.g., "log_day_1.txt") by copying it to another directory (e.g., "backup_waf_logs").
2. Verify the copy operation by listing the contents of the backup directory.

---

### **Removing Files & Directories:**

1. Delete an outdated log file (e.g., "log_day_1.txt") in the "waf_logs" directory that is no longer needed.
2. Remove an empty subdirectory from one of the months' directories (e.g., remove the "March" directory if it’s empty).

---

### **Creating a Script for File Generation:**

1. Write a script that creates 100 unique log files (e.g., "log_1.txt", "log_2.txt") in the "waf_logs" directory, simulating daily Web Application Firewall logs.

---

### **Exploring File History:**

1. View the command history to see the last 20 commands executed.
2. Search the history for any command related to file manipulation, WAF rule updates, or log file management.

---

### **System Monitoring:**

1. Check the system's uptime to ensure the WAF server is continuously available to monitor traffic and protect web applications.
2. View the system's load and resource usage statistics, especially CPU and RAM, to ensure the server is capable of handling heavy traffic and WAF operations.

---

### **Checking File Ownership and Permissions:**

1. Check the ownership and group of the "waf_config.txt" file and verify whether they are correct, ensuring that only authorized users can modify the firewall settings.

---

### **Ping Test & Network Verification:**

1. Verify network connectivity by pinging remote servers or external resources to check if the WAF is intercepting traffic correctly.
2. Record the response times and verify that the server can handle incoming traffic and block malicious requests effectively.

---

### **Search for Specific Files or Content:**

1. Search for a specific log file (e.g., "log_day_1.txt") within the "waf_logs" directory.
2. Search for a specific string of text (e.g., "blocked IP") inside one of the log files to identify potentially blocked malicious requests.

---

### **Create a Directory for Each User:**

1. Create a directory for each user or department (e.g., "user_1_logs", "user_2_logs") and assign appropriate permissions to store their respective WAF log files.

---

### **Creating a Script for Directory Cleanup:**

1. Write a script that deletes all empty subdirectories from the "waf_logs" directory, ensuring that unused or outdated directories are removed.

---

### **File Sorting & Management:**

1. Sort log files by size (e.g., large log files generated during a traffic spike) and then list the files based on their size, ensuring efficient storage management.
2. Create a report listing the largest and smallest log files in the directory to help in archiving or compressing large log files.

---

### **File Type Identification:**

1. Identify and list log files of a specific type (e.g., .txt, .json, .log) in the "waf_logs" directory, to manage log file formats and prepare them for further analysis.

---

### **File Compression and Archive:**

1. Compress the "waf_logs" directory into a single archive file to create a backup of all WAF logs and configurations.
2. Verify the contents of the archive without extracting it, ensuring that all necessary files are included in the backup.

---

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository