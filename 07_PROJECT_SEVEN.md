# Server Management for a DNS server 

---

### **1. Directory Creation & Organization:**
   - Create a directory named "dns_config".
   - Inside "dns_config", create subdirectories for managing zone files: "forward_zones" and "reverse_zones".
   - In "forward_zones", create files representing domain zone configurations, such as "example.com.zone".
   - In "reverse_zones", create files for reverse DNS lookups, such as "192.168.1.zone".

---

### **2. Move and Rename Files:**
   - Move a zone file (e.g., "example.com.zone") from "forward_zones" to a backup directory named "zone_backup".
   - Rename the zone file "example.com.zone" to "example.net.zone" and verify the change by listing the contents of the directory.

---

### **3. Navigation & Listing Files:**
   - Navigate to the "dns_config" directory.
   - List all zone files and verify that they are present in their respective directories.

---

### **4. File Permissions Management:**
   - Create a file named "named.conf" in the "dns_config" directory to represent the main DNS configuration file.
   - Change the permissions of "named.conf" so only the DNS administrator (user) has read and write access.
   - Verify the permission changes using `ls -l`.

---

### **5. Backup Files:**
   - Copy the "named.conf" file to the "zone_backup" directory.
   - Verify the backup by listing the contents of "zone_backup".

---

### **6. Removing Files & Directories:**
   - Delete an outdated zone file (e.g., "old_zone.zone") from the "forward_zones" directory.
   - Remove an empty directory (e.g., "unused_zones") from the "dns_config" folder.

---

### **7. Creating a Script for File Generation:**
   - Write a script to generate 50 placeholder zone files with unique names (e.g., "zone_1", "zone_2") in the "forward_zones" directory.
   - Ensure each file contains basic DNS zone structure placeholders.

---

### **8. Exploring File History:**
   - View the command history to see the last 20 commands executed on the server.
   - Search the history for commands related to DNS file edits or configuration changes.

---

### **9. System Monitoring:**
   - Check the DNS server's uptime to ensure continuous service availability.
   - Monitor system load and memory usage to confirm the DNS server can handle query traffic efficiently.

---

### **10. Checking File Ownership and Permissions:**
   - Verify the ownership and group of the "named.conf" file to ensure it is correctly assigned to the DNS server user.
   - Check zone file permissions to confirm they are only editable by the administrator.

---

### **11. Ping Test & Network Verification:**
   - Test network connectivity to a remote DNS server by pinging its IP address.
   - Use the `dig` or `nslookup` command to verify DNS resolution for a domain (e.g., "example.com").

---

### **12. Search for Specific Files or Content:**
   - Search for a specific zone file (e.g., "example.com.zone") within the "dns_config" directory.
   - Search for specific configurations (e.g., "TTL") inside the "named.conf" file or zone files.

---

### **13. Create a Directory for Each Domain:**
   - Create a subdirectory for each managed domain (e.g., "example.com", "example.net") within "dns_config".
   - Organize zone files and logs for each domain in their respective subdirectories.

---

### **14. Create a Script for Directory Cleanup:**
   - Write a script to delete all empty directories from the "dns_config" hierarchy to maintain a clean configuration structure.

---

### **15. File Sorting & Management:**
   - Sort zone files in the "forward_zones" directory by size.
   - Create a report listing the largest and smallest zone files and suggest cleanup or optimization.

---

### **16. File Type Identification:**
   - Identify and list all `.zone` files in the "dns_config" directory.
   - Search for `.log` files in a "logs" directory to review DNS query logs.

---

### **17. File Compression and Archive:**
   - Compress the "forward_zones" directory into a single archive file named "zones_backup.tar.gz".
   - Verify the contents of the archive without extracting it.

---
### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository