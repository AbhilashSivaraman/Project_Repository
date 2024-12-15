# Server Management for FTP Server

---

### **1. Directory Creation & Organization:**
   - Create a directory named "ftp_data".
   - Inside "ftp_data", create subdirectories for different user groups, such as "admin", "users", and "guests".
   - In each subdirectory, place sample files representing different types of data, such as "documents", "images", and "backups".

---

### **2. Move and Rename Files:**
   - Move a file from one user directory to another, for example, moving "data.txt" from the "users" directory to "admin".
   - Rename a file in the "guests" directory from "temp_file.txt" to "guest_data.txt" and verify the change.

---

### **3. Navigation & Listing Files:**
   - Navigate to the "ftp_data" directory.
   - List the contents of the "admin", "users", and "guests" directories and verify that all files and subdirectories are present.

---

### **4. File Permissions Management:**
   - Create a file named "ftp_config.txt" in the "ftp_data" directory.
   - Change the permissions so that only the admin user has read and write access, while the others can only read the file.
   - Verify the permission changes using `ls -l`.

---

### **5. Backup Files:**
   - Create a backup of the "users" directory by copying it to a backup directory named "ftp_backup".
   - Verify the backup by listing the contents of the "ftp_backup" directory.

---

### **6. Removing Files & Directories:**
   - Delete an old file, such as "old_file.txt", from the "users" directory.
   - Remove an empty subdirectory, like "old_data", from the "guests" directory.

---

### **7. Creating a Script for File Generation:**
   - Write a script that generates 100 sample files inside the "users" directory, each with unique names like "file_1.txt", "file_2.txt", and so on.

---

### **8. Exploring File History:**
   - View the last 20 commands executed to check changes made to the FTP server configuration.
   - Search the history for commands related to file transfers or FTP server restarts.

---

### **9. System Monitoring:**
   - Check the server uptime to ensure continuous FTP service availability.
   - Monitor system resource usage (CPU, memory, and disk space) to identify any bottlenecks or performance issues affecting FTP transfers.

---

### **10. Checking File Ownership and Permissions:**
   - Verify the ownership and group of files in the "ftp_data" directory, ensuring that the correct users and groups have the appropriate permissions.
   - Check that files such as "ftp_config.txt" are only accessible by the admin user and FTP service.

---

### **11. Ping Test & Network Verification:**
   - Test the network connectivity of the FTP server by pinging a remote server or client machine.
   - Record the response times and verify the network's stability for FTP operations.

---

### **12. Search for Specific Files or Content:**
   - Search for specific FTP configuration files, such as "vsftpd.conf" or "proftpd.conf", within the "ftp_data" directory.
   - Search for a specific string, such as "anonymous_enable", inside FTP configuration files to verify settings.

---

### **13. Create a Directory for Each User:**
   - Create individual directories for FTP users within the "ftp_data" directory, such as "user1_files", "user2_files".
   - Assign appropriate read and write permissions for each user directory based on their access requirements.

---

### **14. Create a Script for Directory Cleanup:**
   - Write a script that deletes all empty directories from the "ftp_data" directory, which are no longer required after file transfers.

---

### **15. File Sorting & Management:**
   - Sort files in the "ftp_data" directory by size and list the files based on their size.
   - Create a report listing the largest and smallest files in the "admin", "users", and "guests" directories.

---

### **16. File Type Identification:**
   - Identify and list files of a specific type (e.g., `.txt`, `.jpg`, `.pdf`) in the "ftp_data" directory.
   - List all text files in the "users" directory to ensure appropriate file management.

---

### **17. File Compression and Archive:**
   - Compress the "ftp_backup" directory into a single archive file named "ftp_backup.tar.gz" for future use.
   - Verify the contents of the archive without extracting it using `tar -tf ftp_backup.tar.gz`.

---

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository