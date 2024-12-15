# Server Management for Distributed File System

---

### **Directory Creation & Organization:**

1. Create a directory named "dfs_data".
2. Inside "dfs_data", create 12 subdirectories, each named after a month (e.g., "January", "February", etc.).
3. Inside each month’s directory, create files representing daily data chunks (e.g., "data_day_1.txt", "data_day_2.txt").

---

### **Move and Rename Files:**

1. Move a data file (e.g., "data_day_1.txt") from one month's directory to another (e.g., from "January" to "February") across the distributed file system.
2. Rename a file within a directory (e.g., rename "data_day_1.txt" to "data_day_1_final.txt") and verify the change by listing the contents of the directory.

---

### **Navigation & Listing Files:**

1. Navigate to the "dfs_data" directory.
2. List the contents of the directory and verify the presence of all subdirectories for each month (e.g., "January", "February") and the relevant data files created in the previous task across the distributed system.

---

### **File Permissions Management:**

1. Create a file named "dfs_config.txt" in the "dfs_data" directory to store distributed file system settings (e.g., replication levels, storage locations).
2. Change the permissions of the file so that only the user has read, write, and execute permissions.
3. Verify the permission changes by listing the file's details.

---

### **Backup Files:**

1. Create a backup of a data file (e.g., "data_day_1.txt") by copying it to another node or directory in the DFS.
2. Verify the copy operation by listing the contents of the backup directory across the distributed system.

---

### **Removing Files & Directories:**

1. Delete an outdated data file (e.g., "data_day_1.txt") in the "dfs_data" directory that is no longer needed.
2. Remove an empty subdirectory from one of the months' directories (e.g., remove the "March" directory if it’s empty across the DFS).

---

### **Creating a Script for File Generation:**

1. Write a script that creates 100 unique data files (e.g., "data_1.txt", "data_2.txt") in the "dfs_data" directory, simulating daily data chunks across the distributed file system.

---

### **Exploring File History:**

1. View the command history to see the last 20 commands executed related to file management across the DFS.
2. Search the history for any command related to file manipulation, replication, or movement within the DFS.

---

### **System Monitoring:**

1. Check the system’s uptime to ensure the DFS is continuously available for file retrieval and storage.
2. View the system’s load and resource usage statistics, especially CPU, memory, and disk usage, to ensure the DFS nodes are functioning optimally.

---

### **Checking File Ownership and Permissions:**

1. Check the ownership and group of the "dfs_config.txt" file and verify whether they are correct, ensuring that only authorized users can modify the DFS settings.

---

### **Ping Test & Network Verification:**

1. Verify network connectivity by pinging remote nodes in the DFS cluster to ensure all nodes are accessible.
2. Record the response times and verify that all DFS nodes can communicate effectively for file storage and retrieval.

---

### **Search for Specific Files or Content:**

1. Search for a specific data file (e.g., "data_day_1.txt") within the "dfs_data" directory on the DFS system.
2. Search for a specific string of text (e.g., "replication_failed") inside one of the files in the directory to identify any replication issues within the DFS.

---

### **Create a Directory for Each User:**

1. Create a directory for each user or department (e.g., "user_1_data", "user_2_data") and assign appropriate permissions to store their respective DFS files.

---

### **Creating a Script for Directory Cleanup:**

1. Write a script that deletes all empty subdirectories from the "dfs_data" directory across the DFS, ensuring that unused or outdated directories are removed.

---

### **File Sorting & Management:**

1. Sort data files by size (e.g., large files that take up more space in the DFS) and then list the files based on their size, ensuring efficient storage management.
2. Create a report listing the largest and smallest files in the directory to help in archiving or compressing large data files.

---

### **File Type Identification:**

1. Identify and list data files of a specific type (e.g., text files, CSV files, log files) in the "dfs_data" directory across the DFS to manage file formats and prepare them for analysis or processing.

---

### **File Compression and Archive:**

1. Compress the "dfs_data" directory into a single archive file to create a backup of all distributed data and configurations.
2. Verify the contents of the archive without extracting it, ensuring that all necessary files are included in the backup.

---

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository