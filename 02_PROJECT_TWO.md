# Server Management for CRM Server

### **1. Directory Creation & Organization:**
   - Create a directory named "crm_system".
   - Inside "crm_system", create subdirectories for each department interacting with the CRM, such as "sales", "support", "marketing", and "admin".
   - Inside the "sales" directory, create 12 subdirectories named after months (January to December) to store monthly sales reports.
   - Inside each month’s directory, create files representing daily customer interactions, such as "interaction_day_1.txt" to "interaction_day_31.txt", depending on the month.

---

### **2. Move and Rename Files:**
   - Move a sales report file (e.g., "interaction_day_1.txt") from the "sales" directory to the "admin" directory for review.
   - Rename a file in the "support" directory, such as changing "ticket_123.txt" to "ticket_resolved_123.txt", and verify the change by listing the directory contents.

---

### **3. Navigation & Listing Files:**
   - Navigate to the "crm_system" directory.
   - List the contents of all subdirectories to verify the presence of department-specific folders and files.

---

### **4. File Permissions Management:**
   - Create a file named "config.json" in the "crm_system" directory to store CRM system configurations.
   - Restrict access to "config.json" so that only the admin user can read, write, and execute it, ensuring sensitive settings are secure.
   - Verify the permissions using `ls -l`.

---

### **5. Backup Files:**
   - Create a backup of the "config.json" file by copying it to a directory named "backups".
   - Verify the backup by listing the contents of the "backups" directory.

---

### **6. Removing Files & Directories:**
   - Delete an outdated customer interaction file from the "support" directory.
   - Remove an empty folder from the "marketing" directory that was created for an unused campaign.

---

### **7. Creating a Script for File Generation:**
   - Write a script that generates 100 customer interaction files in the "support" directory, each named uniquely (e.g., "ticket_1.txt", "ticket_2.txt", etc.).
   - These files will simulate customer support tickets.

---

### **8. Exploring File History:**
   - View the command history to see the last 20 commands executed on the CRM server.
   - Search the history for commands related to file manipulation, such as creating or deleting customer interaction files.

---

### **9. System Monitoring:**
   - Check the server’s uptime to ensure continuous availability of the CRM application.
   - View the system’s load and resource usage statistics, focusing on memory and CPU, to ensure smooth handling of user requests and customer data processing.

---

### **10. Checking File Ownership and Permissions:**
   - Check the ownership and group of a file such as "customer_db_backup.sql" to ensure it is correctly assigned to the admin group.
   - Verify the ownership matches the expected user and group settings.

---

### **11. Ping Test & Network Verification:**
   - Verify network connectivity by pinging the database server used by the CRM application.
   - Record the response times to ensure stable connectivity between the application and its backend.

---

### **12. Search for Specific Files or Content:**
   - Search for a specific ticket file, such as "ticket_45.txt", in the "support" directory.
   - Search for a specific string, such as "High Priority", within all files in the "support" directory to identify critical tickets.

---

### **13. Create a Directory for Each User:**
   - Create a directory for each CRM user (e.g., "sales_manager", "support_lead", "admin") within the "crm_system" directory.
   - Assign permissions based on roles: admin users should have full permissions, while others have restricted access.

---

### **14. Create a Script for Directory Cleanup:**
   - Write a script that deletes all empty directories within the "crm_system" directory, ensuring the file structure remains organized.

---

### **15. File Sorting & Management:**
   - Sort customer interaction files in the "support" directory by size to identify large files that may indicate extensive ticket details or attachments.
   - Create a report listing the largest and smallest files, such as "largest_ticket.txt" and "smallest_ticket.txt".

---

### **16. File Type Identification:**
   - Identify and list specific file types in the "crm_system" directory, such as `.json` files for configurations, `.log` files for system logs, and `.txt` files for customer interactions.

---

### **17. File Compression and Archive:**
   - Compress the "support" directory into a single archive file named "support_logs.tar.gz" to backup resolved tickets.
   - Verify the contents of the archive without extracting it to ensure all ticket files are included.

---

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to your git repository