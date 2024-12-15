# Server Management for Monitoring Server

---

### **1. Directory Creation & Organization:**
   - Create a directory named "monitoring_logs".
   - Inside "monitoring_logs", create subdirectories for logs from different services, such as "web_server", "db_server", and "auth_server".
   - Within each service's directory, create subdirectories for each day of the week (e.g., "Monday", "Tuesday").

---

### **2. Move and Rename Files:**
   - Move a log file (e.g., "access.log") from the "web_server" directory to a backup directory named "archived_logs".
   - Rename a log file in the "auth_server" directory from "error.log" to "auth_error.log" and verify the change.

---

### **3. Navigation & Listing Files:**
   - Navigate to the "monitoring_logs" directory.
   - List all log files and subdirectories to verify the directory structure.

---

### **4. File Permissions Management:**
   - Create a file named "monitoring_config.txt" in the "monitoring_logs" directory to represent the server configuration.
   - Set permissions on the file so only the monitoring admin can read and write to it.
   - Verify permissions using `ls -l`.

---

### **5. Backup Files:**
   - Copy the "monitoring_config.txt" file to the "archived_logs" directory for backup purposes.
   - Verify the backup by listing the contents of the "archived_logs" directory.

---

### **6. Removing Files & Directories:**
   - Delete an outdated log file (e.g., "old_logs.txt") from the "web_server" directory.
   - Remove an empty directory (e.g., "Friday") from the "db_server" logs.

---

### **7. Creating a Script for File Generation:**
   - Write a script that generates 50 simulated log files (e.g., "log_1.txt", "log_2.txt") in the "web_server" directory, each containing a timestamp and a sample log message.

---

### **8. Exploring File History:**
   - View the last 20 commands executed on the server to monitor changes made to the log management setup.
   - Search the history for commands related to file permissions or log file manipulation.

---

### **9. System Monitoring:**
   - Check the server uptime to ensure it has been running continuously.
   - Monitor the system's resource usage (CPU, memory, and disk) to ensure it can handle log processing efficiently.

---

### **10. Checking File Ownership and Permissions:**
   - Verify the ownership of the "auth_server" logs to ensure they are correctly assigned to the authentication team.
   - Confirm that sensitive logs (e.g., "error.log") are not accessible by unauthorized users.

---

### **11. Ping Test & Network Verification:**
   - Test connectivity to a remote monitoring endpoint by pinging its IP address.
   - Verify connectivity to an Elasticsearch or Prometheus instance using `curl` or similar tools.

---

### **12. Search for Specific Files or Content:**
   - Search for a specific log file (e.g., "critical_error.log") in the "auth_server" directory.
   - Search for a specific error message (e.g., "503 Service Unavailable") in the "web_server" logs.

---

### **13. Create a Directory for Each Monitored Service:**
   - Create directories for each monitored service (e.g., "application", "network", "database") under the "monitoring_logs" directory.
   - Organize logs into these directories by their source.

---

### **14. Create a Script for Directory Cleanup:**
   - Write a script that deletes all empty subdirectories from the "archived_logs" directory.

---

### **15. File Sorting & Management:**
   - Sort log files in the "web_server" directory by size.
   - Create a report listing the largest and smallest log files for the week.

---

### **16. File Type Identification:**
   - Identify and list log files that are in `.gz` (compressed) format in the "archived_logs" directory.
   - Find files containing JSON-formatted logs in the "db_server" directory.

---

### **17. File Compression and Archive:**
   - Compress the "auth_server" directory into an archive file named "auth_logs.tar.gz".
   - Verify the contents of the archive without extracting it.

---

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository