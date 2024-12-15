# Server Management for a Cloud Storage Server

---

### **1. Directory Creation & Organization:**
   - Create a directory named "cloud_storage".
   - Inside "cloud_storage", create subdirectories for various clients or departments (e.g., "client_A", "client_B", "HR", "Finance").
   - In each subdirectory, create folders for different file types, such as "images", "documents", and "archives".
   - Add placeholder files representing stored data, such as "invoice_01.pdf" in "Finance/documents".

---

### **2. Move and Rename Files:**
   - Move a file (e.g., "project_image.jpg") from "client_A/images" to "client_B/images".
   - Rename the file "project_image.jpg" to "final_project_image.jpg" and verify the change using `ls`.

---

### **3. Navigation & Listing Files:**
   - Navigate to the "cloud_storage" directory.
   - List all subdirectories and files, ensuring the folder structure matches the organization created earlier.

---

### **4. File Permissions Management:**
   - Create a file named "storage_config.txt" in the "cloud_storage" directory.
   - Set permissions so only the administrator (user) can read, write, and execute this file.
   - Verify the permissions using `ls -l`.

---

### **5. Backup Files:**
   - Copy a file (e.g., "invoice_01.pdf") from "Finance/documents" to a "backup" directory inside "cloud_storage".
   - Verify the backup by listing the contents of the "backup" directory.

---

### **6. Removing Files & Directories:**
   - Delete an outdated file (e.g., "old_policy.docx") from the "HR/documents" directory.
   - Remove an empty directory (e.g., "client_A/archives") from the "cloud_storage" folder.

---

### **7. Creating a Script for File Generation:**
   - Write a script to generate 50 dummy files with unique names (e.g., "file_1.txt", "file_2.txt") in the "client_A/documents" directory to simulate file uploads.

---

### **8. Exploring File History:**
   - View the command history to see the last 20 commands executed on the server.
   - Search the history for commands related to file creation or deletion.

---

### **9. System Monitoring:**
   - Check the server uptime to ensure availability for cloud storage operations.
   - Monitor system load and disk usage to ensure sufficient storage capacity for files.

---

### **10. Checking File Ownership and Permissions:**
   - Verify the ownership and group of a file (e.g., "storage_config.txt") to ensure it is managed by the correct user or group.
   - Check that permissions align with organizational security policies.

---

### **11. Ping Test & Network Verification:**
   - Test network connectivity to a remote cloud storage service by pinging its endpoint.
   - Record response times to ensure reliable access to external storage.

---

### **12. Search for Specific Files or Content:**
   - Search for a specific file (e.g., "project_plan.docx") within the "cloud_storage" directory.
   - Search for specific content (e.g., "confidential") inside files in the "HR/documents" folder.

---

### **13. Create a Directory for Each User:**
   - Create a directory for each user (e.g., "user1", "user2") in the "cloud_storage" directory.
   - Assign appropriate permissions so each user can only access their respective directory.

---

### **14. Create a Script for Directory Cleanup:**
   - Write a script to delete all empty directories from the "cloud_storage" hierarchy to maintain storage organization.

---

### **15. File Sorting & Management:**
   - Sort files in the "Finance/documents" directory by size.
   - Create a report listing the largest and smallest files and recommend storage optimization strategies.

---

### **16. File Type Identification:**
   - Identify and list all `.pdf` files in the "Finance/documents" directory.
   - Search for `.jpg` and `.png` files in "client_A/images" to verify the presence of image files.

---

### **17. File Compression and Archive:**
   - Compress the "HR" directory into an archive named "HR_backup.tar.gz".
   - Verify the contents of the archive without extracting it.

---
### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository