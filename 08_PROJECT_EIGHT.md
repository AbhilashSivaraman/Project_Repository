# Server Management for E-mail Server

---

### **1. Directory Creation & Organization:**
   - Create a directory named "mailserver".
   - Inside "mailserver", create subdirectories for email domains, such as "example.com" and "example.net".
   - Within each domain directory, create subdirectories for email users, such as "user1" and "user2".

---

### **2. Move and Rename Files:**
   - Move an email message file (e.g., "message1.eml") from "user1" to a backup directory named "mail_backup".
   - Rename the email file "message1.eml" to "message_important.eml" and verify the change by listing the directory contents.

---

### **3. Navigation & Listing Files:**
   - Navigate to the "mailserver" directory.
   - List all email domains and users to verify the directory structure.

---

### **4. File Permissions Management:**
   - Create a file named "mail_config.txt" in the "mailserver" directory to represent the email server's configuration file.
   - Change the permissions of "mail_config.txt" so only the email administrator has read and write access.
   - Verify the changes using `ls -l`.

---

### **5. Backup Files:**
   - Copy "mail_config.txt" to the "mail_backup" directory for safekeeping.
   - Verify the backup by listing the contents of the "mail_backup" directory.

---

### **6. Removing Files & Directories:**
   - Delete an outdated email message file from a user's directory (e.g., "old_message.eml").
   - Remove an empty directory for a deactivated user (e.g., "old_user") from the domain structure.

---

### **7. Creating a Script for File Generation:**
   - Write a script to create 50 placeholder email files for testing (e.g., "email_1.eml", "email_2.eml") in "user1's" directory.
   - Include placeholders for subject, sender, and recipient in each email file.

---

### **8. Exploring File History:**
   - View the command history to see the last 20 commands executed on the server.
   - Search the history for commands related to email configuration or log monitoring.

---

### **9. System Monitoring:**
   - Check the uptime of the email server to ensure continuous availability.
   - Monitor system resources (e.g., CPU, memory, and disk usage) to confirm the server can handle email traffic efficiently.

---

### **10. Checking File Ownership and Permissions:**
   - Verify the ownership and group of the "mail_config.txt" file to ensure it is correctly assigned to the email administrator.
   - Check that user directories (e.g., "user1", "user2") are accessible only by the respective users.

---

### **11. Ping Test & Network Verification:**
   - Verify network connectivity to a remote email server by pinging its IP address.
   - Use the `telnet` command to test SMTP connectivity to the server (e.g., `telnet mail.example.com 25`).

---

### **12. Search for Specific Files or Content:**
   - Search for a specific email message file (e.g., "important_message.eml") within the "mailserver" directory.
   - Search for specific text (e.g., "Subject: Important") within an email file.

---

### **13. Create a Directory for Each Email Domain:**
   - Create separate directories for each email domain managed by the server (e.g., "example.com", "example.net").
   - Organize user mailboxes and logs within these directories.

---

### **14. Create a Script for Directory Cleanup:**
   - Write a script to delete all empty user directories from the domain folders in the "mailserver" hierarchy.

---

### **15. File Sorting & Management:**
   - Sort email files in a user's directory by size.
   - Create a report listing the largest and smallest email files.

---

### **16. File Type Identification:**
   - Identify and list all `.eml` files in a user's directory.
   - Search for and list log files (e.g., "mail.log") in the "logs" directory.

---

### **17. File Compression and Archive:**
   - Compress the "mail_backup" directory into a single archive file named "backup.tar.gz".
   - Verify the archive contents without extracting it.

---
### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository