# Server Management for Log Aggregation

---

### **Directory Creation & Organization:**

1. Create a directory named "log_data".
2. Inside "log_data", create 12 subdirectories, each named after a month (e.g., "January", "February", etc.).
3. Inside each month’s directory, create log files to store aggregated logs, error logs, and system event logs (e.g., "log_day_1.json", "error_day_1.log", "event_day_1.txt").

---

### **Move and Rename Files:**

1. Move a log file (e.g., "log_day_1.json") from one month's directory to another (e.g., from "January" to "February").
2. Rename a file within a directory (e.g., rename "log_day_1.json" to "log_day_1_backup.json") and verify the change by listing the contents of the directory.

---

### **Navigation & Listing Files:**

1. Navigate to the "log_data" directory.
2. List the contents of the directory and verify the presence of all subdirectories for each month (e.g., "January", "February") and the relevant log files created in the previous task.

---

### **File Permissions Management:**

1. Create a file named "log_config.txt" in the "log_data" directory to store configuration settings for the log aggregation system.
2. Change the permissions of the file so that only the user has read, write, and execute permissions.
3. Verify the permission changes by listing the file's details.

---

### **Backup Files:**

1. Create a backup of a log file (e.g., "log_day_1.json") by copying it to another directory (e.g., "backup_logs").
2. Verify the copy operation by listing the contents of the backup directory.

---

### **Removing Files & Directories:**

1. Delete an outdated log file (e.g., "error_day_1.log") in the "log_data" directory that is no longer needed.
2. Remove an empty subdirectory from one of the months' directories (e.g., remove the "March" directory if it’s empty).

---

### **Creating a Script for File Generation:**

1. Write a script that creates 100 unique log files inside the "log_data" directory, each representing a day's logs (e.g., "log_day_1.json", "log_day_2.txt").

---

### **Exploring File History:**

1. View the command history to see the last 20 commands executed.
2. Search the history for any command related to log file manipulation, aggregation, or cleanup.

---

### **System Monitoring:**

1. Check the system's uptime to ensure the log aggregation server is functioning continuously.
2. View the system's load and resource usage statistics to ensure the server can handle high log volume from various sources.

---

### **Checking File Ownership and Permissions:**

1. Check the ownership and group of the "log_config.txt" file and verify whether they are correct, ensuring that only authorized personnel can modify log configurations.

---

### **Ping Test & Network Verification:**

1. Verify network connectivity by pinging external log sources (e.g., other servers, applications, or services that send logs to the aggregation server).
2. Record the response times and verify the connectivity between the server and remote systems for log aggregation.

---

### **Search for Specific Files or Content:**

1. Search for a specific log file (e.g., "log_day_15.json") within the "log_data" directory.
2. Search for a specific string of text (e.g., "ERROR") inside one of the log files to identify error messages within the aggregated logs.

---

### **Create a Directory for Each User:**

1. Create a directory for each user or service interacting with the log aggregation system (e.g., "user_1_logs", "app_2_logs") and assign appropriate permissions to store their logs.
   
---

### **Creating a Script for Directory Cleanup:**

1. Write a script that deletes all empty subdirectories from the "log_data" directory to keep the log storage organized and free of unused folders.

---

### **File Sorting & Management:**

1. Sort log files in the "log_data" directory by size and then list the files based on their size to identify any unusually large log files that may need to be archived.
2. Create a report listing the largest and smallest log files in the directory to assist in log management and storage optimization.

---

### **File Type Identification:**

1. Identify and list log files of a specific type (e.g., .json, .log, .txt) in the "log_data" directory, ensuring that the aggregation system is handling the appropriate formats.

---

### **File Compression and Archive:**

1. Compress the "log_data" directory into a single archive file to create a backup of aggregated logs.
2. Verify the contents of the archive without extracting it to ensure that all necessary log files are included in the backup.

---

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository