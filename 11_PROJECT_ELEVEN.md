# Server Management for File Sharing Server

---

### **1. Directory Creation & Organization:**
   - Create a directory named "shared_files".
   - Inside "shared_files", create subdirectories for different user groups, such as "employees", "managers", and "clients".
   - Within each subdirectory, create further directories for file categories like "reports", "invoices", and "documents".

---

### **2. Move and Rename Files:**
   - Move a file (e.g., "monthly_report.pdf") from the "reports" directory under "employees" to "managers".
   - Rename a file in the "clients" directory from "project_plan.docx" to "updated_project_plan.docx" and verify the change.

---

### **3. Navigation & Listing Files:**
   - Navigate to the "shared_files" directory.
   - List the contents of each group’s directory and verify the organization of files and subdirectories.

---

### **4. File Permissions Management:**
   - Create a file named "server_policy.txt" in the "shared_files" directory.
   - Set permissions so only the "managers" group can read and write to this file, while others have no access.
   - Verify the permissions using `ls -l`.

---

### **5. Backup Files:**
   - Copy the "invoices" directory under "employees" to a backup directory named "shared_files_backup".
   - Verify the backup by listing the contents of the backup directory.

---

### **6. Removing Files & Directories:**
   - Delete a file (e.g., "old_invoice.xlsx") from the "invoices" directory under "clients".
   - Remove an empty category directory (e.g., "drafts") from the "employees" section.

---

### **7. Creating a Script for File Generation:**
   - Write a script that generates 50 dummy files (e.g., "file_1.txt", "file_2.txt") in the "documents" directory under "employees" with placeholder content.

---

### **8. Exploring File History:**
   - View the last 20 commands executed to check changes made to the file-sharing structure.
   - Search the history for commands related to permission changes or file movements.

---

### **9. System Monitoring:**
   - Check the server uptime to ensure uninterrupted file sharing.
   - Monitor resource usage (CPU, disk I/O, and network) to identify potential bottlenecks in file transfer operations.

---

### **10. Checking File Ownership and Permissions:**
   - Verify the ownership and group of files in the "shared_files" directory to ensure proper user access.
   - Check that sensitive files like "server_policy.txt" are not accessible by unauthorized users.

---

### **11. Ping Test & Network Verification:**
   - Test connectivity to a remote file-sharing client by pinging their IP address.
   - Verify response times and identify potential network issues.

---

### **12. Search for Specific Files or Content:**
   - Search for a specific file (e.g., "annual_summary.pdf") in the "managers" directory.
   - Search for a specific term (e.g., "Confidential") inside files within the "employees" directory.

---

### **13. Create a Directory for Each User:**
   - Create personal directories for each user in the "shared_files" directory based on their username.
   - Assign appropriate read, write, or execute permissions based on their role.

---

### **14. Create a Script for Directory Cleanup:**
   - Write a script that deletes all empty directories under "shared_files".

---

### **15. File Sorting & Management:**
   - Sort files in the "reports" directory under "managers" by size.
   - Generate a report listing the largest and smallest files in each group’s directory.

---

### **16. File Type Identification:**
   - Identify and list all PDF files in the "shared_files" directory.
   - Find all spreadsheet files (e.g., `.xlsx`) in the "invoices" directories.

---

### **17. File Compression and Archive:**
   - Compress the "shared_files_backup" directory into a single archive file named "backup_shared_files.tar.gz".
   - Verify the contents of the archive without extracting it.

---

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository