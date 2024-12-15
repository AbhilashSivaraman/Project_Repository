# Server Management for Web Server

---

### **1. Directory Creation & Organization:**
   - Create a directory named "web_server".
   - Inside "web_server", create subdirectories for hosted websites (e.g., "site1", "site2", "site3").
   - Within each site’s directory, create subdirectories for "html", "css", "js", and "logs".
   - In the "html" subdirectory of each site, create files named "index.html" and "about.html" as placeholder web pages.

---

### **2. Move and Rename Files:**
   - Move a CSS file (e.g., "style.css") from the "site1/css" directory to "site2/css" for reuse.
   - Rename "index.html" in "site3/html" to "home.html" to align with site requirements, and verify the change by listing the directory contents.

---

### **3. Navigation & Listing Files:**
   - Navigate to the "web_server" directory.
   - List all subdirectories and files to ensure proper organization and verify the presence of required website files.

---

### **4. File Permissions Management:**
   - Create a configuration file named "server.conf" in the "web_server" directory.
   - Set permissions on "server.conf" so that only the root user can read, write, and execute it, ensuring server configurations are protected.
   - Verify the permissions using `ls -l`.

---

### **5. Backup Files:**
   - Create a backup of the "site1" directory by copying it to a "backups" directory.
   - Verify the backup by listing the contents of the "backups" directory and ensuring all files are present.

---

### **6. Removing Files & Directories:**
   - Delete an outdated log file from the "logs" directory of "site2".
   - Remove an empty "test" subdirectory from "site3" that was created during development but is no longer needed.

---

### **7. Creating a Script for File Generation:**
   - Write a script that generates 100 log files in the "logs" directory of "site1". Each file should have a unique name (e.g., "log_1.txt", "log_2.txt", etc.) to simulate access logs.

---

### **8. Exploring File History:**
   - View the command history to see the last 20 commands executed on the web hosting server.
   - Search the history for commands related to file manipulation, such as creating or deleting website files.

---

### **9. System Monitoring:**
   - Check the server's uptime to ensure the web hosting server is continuously available for users.
   - View system load and resource usage statistics, focusing on CPU and memory usage during peak traffic periods.

---

### **10. Checking File Ownership and Permissions:**
   - Check the ownership and group of the "index.html" file in the "site1/html" directory to ensure it belongs to the correct user and group.
   - Verify that ownership aligns with the hosting account's permissions.

---

### **11. Ping Test & Network Verification:**
   - Verify connectivity to the web server by pinging its public IP address or domain name.
   - Record the response times to ensure low latency and consistent connectivity.

---

### **12. Search for Specific Files or Content:**
   - Search for a specific file, such as "home.html", within the "web_server" directory.
   - Search for a specific string, such as "<title>", in all HTML files to verify proper title tags in web pages.

---

### **13. Create a Directory for Each Website:**
   - Create a directory for each hosted website in the "web_server" directory, and name them according to the domain names (e.g., "example.com", "mysite.org").
   - Assign permissions so that only the respective site owner can access their files.

---

### **14. Create a Script for Directory Cleanup:**
   - Write a script that deletes all empty directories within the "web_server/logs" directory to remove unused log folders.

---

### **15. File Sorting & Management:**
   - Sort the log files in the "site2/logs" directory by size to identify large files that may need archiving or compression.
   - Create a report listing the largest and smallest log files for each site.

---

### **16. File Type Identification:**
   - Identify and list files of specific types in the "web_server" directory, such as `.html` for web pages, `.css` for stylesheets, and `.log` for access logs.

---

### **17. File Compression and Archive:**
   - Compress the "site3/logs" directory into a single archive file named "site3_logs.tar.gz" to save space.
   - Verify the archive’s contents without extracting it to ensure all log files are included.

---

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to your git repository