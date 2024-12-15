# Server Management for Content Management System

---

### **1. Directory Creation & Organization:**
   - Create a directory named "cms_server".
   - Inside "cms_server", create subdirectories for multiple CMS instances, such as "wordpress", "joomla", and "drupal".
   - Within each CMS instance directory, create subdirectories for "themes", "plugins", "uploads", and "logs".
   - Inside the "uploads" directory, create subdirectories for content types (e.g., "images", "videos", "documents").

---

### **2. Move and Rename Files:**
   - Move an image file (e.g., "logo.png") from the "uploads/images" directory of the WordPress instance to the Joomla instance.
   - Rename a plugin file in the "plugins" directory of Drupal (e.g., "plugin_old.zip" to "plugin_updated.zip"), and verify the changes by listing the directory contents.

---

### **3. Navigation & Listing Files:**
   - Navigate to the "cms_server" directory.
   - List all subdirectories and files to verify the presence of CMS instances and their associated directories.

---

### **4. File Permissions Management:**
   - Create a configuration file named "db_config.php" in the "cms_server" directory.
   - Restrict the permissions of "db_config.php" so that only the root user can read and write to it, ensuring database credentials are secure.
   - Verify the permissions using `ls -l`.

---

### **5. Backup Files:**
   - Create a backup of the "uploads" directory for the WordPress instance by copying it to a "backups" directory.
   - Verify the backup operation by listing the contents of the "backups" directory.

---

### **6. Removing Files & Directories:**
   - Delete a deprecated plugin file from the "plugins" directory of the Joomla instance.
   - Remove an empty "test" subdirectory from the "themes" directory of the Drupal instance that is no longer needed.

---

### **7. Creating a Script for File Generation:**
   - Write a script that generates 50 dummy image files (e.g., "image_1.jpg", "image_2.jpg", etc.) in the "uploads/images" directory of the WordPress instance to simulate user uploads.

---

### **8. Exploring File History:**
   - View the command history to see the last 20 commands executed on the CMS server.
   - Search the history for commands related to file manipulation, such as moving or renaming uploads.

---

### **9. System Monitoring:**
   - Check the server's uptime to ensure uninterrupted availability of the CMS platforms.
   - View system load and resource usage statistics, focusing on PHP and MySQL performance during peak traffic.

---

### **10. Checking File Ownership and Permissions:**
   - Check the ownership and group of the "index.php" file in the WordPress directory to ensure it belongs to the correct user and group for the web server.
   - Verify that the ownership aligns with the CMS installation requirements.

---

### **11. Ping Test & Network Verification:**
   - Verify network connectivity to the CMS server by pinging the domain name (e.g., `example.com`).
   - Record the response times to ensure the server is reachable and has minimal latency.

---

### **12. Search for Specific Files or Content:**
   - Search for a specific file, such as "wp-config.php", within the "cms_server" directory.
   - Search for a specific string, such as "define('DB_NAME')" in configuration files, to verify database settings.

---

### **13. Create a Directory for Each CMS Instance:**
   - Create a directory for each CMS instance (e.g., "cms_wordpress", "cms_joomla", "cms_drupal") in the "cms_server" directory.
   - Assign permissions so that each directory is accessible only by the respective CMS administrator.

---

### **14. Create a Script for Directory Cleanup:**
   - Write a script that deletes all empty directories in the "uploads" folder of the WordPress instance to remove unused content subdirectories.

---

### **15. File Sorting & Management:**
   - Sort files in the "uploads/images" directory by size to identify large image files.
   - Create a report listing the largest and smallest files, and decide which files can be optimized or removed.

---

### **16. File Type Identification:**
   - Identify and list files of specific types in the "uploads" directory, such as `.jpg` for images, `.mp4` for videos, and `.pdf` for documents.

---

### **17. File Compression and Archive:**
   - Compress the "themes" directory of the Joomla instance into a single archive file named "joomla_themes_backup.tar.gz".
   - Verify the contents of the archive without extracting it to ensure all theme files are included.

---

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository