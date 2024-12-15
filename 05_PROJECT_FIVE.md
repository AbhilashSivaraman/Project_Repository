# Server Management for a DB Server

---

### **1. Directory Creation & Organization:**
   - Create a directory named "db_backup_server".
   - Inside "db_backup_server", create subdirectories for different database types (e.g., "mysql", "postgresql", "mongodb").
   - Within each database type directory, create subdirectories for "daily", "weekly", and "monthly" backups.
   - In the "mysql/daily" directory, create files named after each day of the week (e.g., "Monday.sql", "Tuesday.sql").

---

### **2. Move and Rename Files:**
   - Move a backup file (e.g., "backup.sql") from the "daily" directory to the "weekly" directory under the MySQL backups.
   - Rename the file "backup.sql" in the "weekly" directory to "week1_backup.sql", and verify the change by listing the directory contents.

---

### **3. Navigation & Listing Files:**
   - Navigate to the "db_backup_server" directory.
   - List all subdirectories and verify the presence of daily, weekly, and monthly backup folders for each database type.

---

### **4. File Permissions Management:**
   - Create a file named "config_backup.txt" in the "db_backup_server" directory.
   - Set permissions so that only the root user has read, write, and execute access to the file to secure sensitive backup configurations.
   - Verify the changes using `ls -l`.

---

### **5. Backup Files:**
   - Copy the "Monday.sql" file from the "mysql/daily" directory to a "temp_backup" directory as a temporary backup.
   - Verify the copy operation by listing the contents of the "temp_backup" directory.

---

### **6. Removing Files & Directories:**
   - Delete an outdated backup file (e.g., "old_backup.sql") from the "postgresql/weekly" directory.
   - Remove an empty subdirectory from the "mongodb/monthly" directory that is no longer used.

---

### **7. Creating a Script for File Generation:**
   - Write a script that generates 30 dummy SQL backup files (e.g., "backup_1.sql", "backup_2.sql", etc.) in the "mysql/daily" directory to simulate daily backups.

---

### **8. Exploring File History:**
   - View the command history to see the last 20 operations performed on the backup server.
   - Search the history for any commands related to copying or deleting SQL files.

---

### **9. System Monitoring:**
   - Check the server uptime to ensure uninterrupted availability of the database backup server.
   - View system load and disk usage to monitor storage capacity for backups.

---

### **10. Checking File Ownership and Permissions:**
   - Check the ownership and group of a backup file (e.g., "backup.sql") in the MySQL daily backups directory to ensure it is owned by the database administrator.
   - Verify the permissions align with the server’s security policies.

---

### **11. Ping Test & Network Verification:**
   - Test network connectivity by pinging a remote database server to ensure backups can be transferred remotely.
   - Record response times and verify connectivity.

---

### **12. Search for Specific Files or Content:**
   - Search for a specific backup file (e.g., "Friday.sql") in the "mysql" directory.
   - Search for a specific keyword (e.g., "CREATE TABLE") inside a backup file to verify the content of the SQL dump.

---

### **13. Create a Directory for Each Database Instance:**
   - Create a directory for each database instance (e.g., "db_instance1", "db_instance2") under the "mysql" folder.
   - Assign permissions so that each directory is accessible only by the database administrator responsible for that instance.

---

### **14. Create a Script for Directory Cleanup:**
   - Write a script that deletes all empty directories in the "postgresql" backup hierarchy to keep the server organized.

---

### **15. File Sorting & Management:**
   - Sort backup files in the "mongodb/monthly" directory by size to identify the largest and smallest backups.
   - Create a report listing the largest and smallest files, and recommend storage optimization strategies.

---

### **16. File Type Identification:**
   - Identify and list all `.sql` files in the "db_backup_server" directory to verify backup consistency.
   - Search for `.gz` files to ensure compressed backups are in place.

---

### **17. File Compression and Archive:**
   - Compress the "weekly" backups directory under MySQL into a single archive named "weekly_backup.tar.gz".
   - Verify the contents of the archive without extracting it to ensure all files are included.

---

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository