# Server Management for Customer Support System

---

### **1. Directory Creation & Organization:**
   - Create a directory named "customer_support_system".
   - Inside "customer_support_system", create 12 subdirectories, each named after a month (e.g., "January", "February", "March", etc.).
   - Inside each month’s directory, create files corresponding to customer support tickets (e.g., "ticket_001.txt", "ticket_002.csv", "ticket_003.md") for each issue raised during that month.

---

### **2. Move and Rename Files:**
   - Move a customer support ticket file from one month’s directory to another (e.g., move "ticket_045.txt" from "February" to "March").
   - Rename a ticket file (e.g., rename "ticket_001_old.txt" to "ticket_001_resolved.txt") and verify the change by listing the contents of the directory.

---

### **3. Navigation & Listing Files:**
   - Navigate to the "customer_support_system" directory and list its contents.
   - Verify the presence of all month directories and customer support ticket files to ensure proper organization by month and issue category.

---

### **4. File Permissions Management:**
   - Create a file named "confidential_ticket.txt" in the "customer_support_system" directory containing sensitive customer information.
   - Change the permissions of the file so that only support agents or admins can read, write, and execute the file, while others have no access.
   - Verify the permission changes using `ls -l` to ensure sensitive ticket data is protected.

---

### **5. Backup Files:**
   - Create a backup of important support ticket files by copying them to a "backup" directory (e.g., "customer_support_system/backup").
   - Verify the backup operation by listing the contents of the backup directory to ensure all critical support tickets are backed up.

---

### **6. Removing Files & Directories:**
   - Delete resolved or closed support tickets from the "customer_support_system" directory (e.g., tickets that have been resolved or archived).
   - Remove any empty directories from the system to keep the ticket storage organized.

---

### **7. Creating a Script for File Generation:**
   - Write a script that generates 100 customer support ticket files with unique names (e.g., "ticket_1.txt", "ticket_2.csv") inside a directory.
   - Each ticket file should contain dummy content such as ticket ID, customer details, issue description, and priority.

---

### **8. Exploring File History:**
   - View the last 20 commands executed using `history`, especially those related to file manipulations of customer support tickets.
   - Search for any commands related to file operations using `grep` (e.g., `history | grep ticket`).

---

### **9. System Monitoring:**
   - Check the system uptime to ensure the ticketing system is running continuously for ticket creation and updates.
   - Monitor system resource usage (CPU, memory, disk space) to ensure the server can handle multiple customer support tickets, especially during peak times.

---

### **10. Checking File Ownership and Permissions:**
   - Verify the ownership and group of ticket files to ensure that only authorized users (e.g., support agents, team leads) can modify the tickets.
   - Use `ls -l` to check file ownership and permissions and ensure proper access control.

---

### **11. Ping Test & Network Verification:**
   - Ping the customer support server from a remote location to verify network connectivity.
   - Record the response times and ensure the server is accessible to customer service agents for timely ticket updates.

---

### **12. Search for Specific Files or Content:**
   - Use `find` or `grep` to search for specific customer support tickets (e.g., "ticket_35.txt") in the system directory.
   - Search for specific keywords within ticket files (e.g., "priority", "resolved") to verify ticket details.

---

### **13. Create a Directory for Each User:**
   - Create a directory for each support agent or department in the system (e.g., "/home/agent1/tickets").
   - Assign appropriate permissions to each user's directory to ensure that they can only access tickets assigned to them or their department.

---

### **14. Create a Script for Directory Cleanup:**
   - Write a script that deletes all empty subdirectories from the ticketing system, especially after ticket resolution.
   - Set up a cron job to run the cleanup script periodically to ensure the ticket system stays organized.

---

### **15. File Sorting & Management:**
   - Sort customer support ticket files in a directory by size and list the files based on their size to identify larger files (e.g., tickets with attachments).
   - Generate a report listing the largest and smallest ticket files for better resource management.

---

### **16. File Type Identification:**
   - Identify and list files of a specific type (e.g., text files, CSV files, logs) within the ticket management directory.
   - Ensure that tickets are categorized properly based on file type for easy retrieval.

---

### **17. File Compression and Archive:**
   - Compress a directory containing resolved or archived tickets into a single archive file (e.g., `tar -cvf resolved_tickets.tar.gz`).
   - Verify the contents of the archive without extracting it by running `tar -tf resolved_tickets.tar.gz` to ensure that all resolved ticket files are included.

---

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository