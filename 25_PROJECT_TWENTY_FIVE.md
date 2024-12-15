# Server Management for Supply Chain Server

---

### **1. Directory Creation & Organization:**
   - Create a directory named "supply_chain_server".
   - Inside this directory, create subdirectories for different stages in the supply chain, such as "Procurement", "Warehousing", "Shipping", and "Inventory".
   - Within each stage’s directory, create files representing relevant records like orders, deliveries, and stock levels.

---

### **2. Move and Rename Files:**
   - Move a file (e.g., "order_001.csv") from the "Procurement" directory to "Warehousing" after an order has been processed for storage.
   - Rename a file in the "Shipping" directory (e.g., from "shipment_1234.csv" to "shipment_2024_1234.csv") to indicate the year of the shipment.

---

### **3. Navigation & Listing Files:**
   - Navigate to the "supply_chain_server" directory and list its contents.
   - Ensure that all supply chain stages have the appropriate subdirectories, and verify that files representing orders, shipments, and inventory are correctly placed.

---

### **4. File Permissions Management:**
   - Create a file named "supply_chain_report.csv" in the "supply_chain_server" directory containing critical data like inventory levels and order statuses.
   - Change the permissions of the file to limit access, allowing only supply chain managers to view and modify it.
   - Verify the permission changes to ensure that only authorized users have access.

---

### **5. Backup Files:**
   - Make a backup of critical supply chain data (e.g., current inventory or order reports) by copying it to a "backup" directory for recovery purposes.
   - Ensure the backup directory is regularly updated to reflect the latest data for disaster recovery.

---

### **6. Removing Files & Directories:**
   - Delete files that are no longer relevant, such as completed orders or outdated shipment logs.
   - Remove empty subdirectories from stages (e.g., "Shipping") that no longer contain any files or orders.

---

### **7. Creating a Script for File Generation:**
   - Write a script that generates mock supply chain files (e.g., "order_001.csv", "shipment_100.csv") containing sample data for orders, shipments, and inventory tracking.
   - The script can be used for testing purposes in supply chain operations.

---

### **8. Exploring File History:**
   - View the history of commands related to file management, particularly those used for moving or renaming supply chain-related files.
   - Search for any commands related to backup operations or file permissions to ensure they were executed correctly.

---

### **9. System Monitoring:**
   - Check the system's uptime to ensure that the server is continuously running and handling supply chain operations.
   - Monitor the system's resource usage (CPU, memory, disk space) to ensure smooth performance when processing supply chain data, especially during peak times like order processing or shipping.

---

### **10. Checking File Ownership and Permissions:**
   - Verify the ownership and group of critical files related to supply chain operations, such as inventory levels or order processing files.
   - Ensure that permissions are set correctly to avoid unauthorized access to sensitive supply chain data.

---

### **11. Ping Test & Network Verification:**
   - Perform a network ping test to verify the server’s connectivity with other systems involved in the supply chain, such as procurement systems or partner warehouses.
   - Check for any latency or downtime that could affect real-time order or shipment tracking.

---

### **12. Search for Specific Files or Content:**
   - Search for specific order files within the "Procurement" or "Warehousing" directories to verify the existence of orders or stock items.
   - Search within the files for a particular order ID or product name to ensure smooth retrieval of supply chain information.

---

### **13. Create a Directory for Each User:**
   - Create individual directories for supply chain team members, such as procurement managers, warehouse staff, and shipping coordinators, where they can store their relevant files and reports.
   - Assign appropriate permissions to each directory, ensuring that only authorized users can access the files.

---

### **14. Create a Script for Directory Cleanup:**
   - Write a script that removes empty directories or outdated files from the supply chain stages, such as when inventory data is no longer needed or orders have been shipped.
   - Set the script to run periodically to ensure a clean and organized server.

---

### **15. File Sorting & Management:**
   - Sort inventory files by product quantity to identify items that need restocking or are in excess.
   - Create a report listing the largest and smallest inventory files, which can indicate either a need for more storage or a large product range.

---

### **16. File Type Identification:**
   - Identify files related to specific types of supply chain data (e.g., CSV files for orders, TXT files for shipping logs) and organize them into directories based on file type.
   - Ensure that the server correctly handles file types that contain different supply chain-related information.

---

### **17. File Compression and Archive:**
   - Compress older supply chain files (e.g., completed orders, old shipment logs) into a single archive to save disk space and keep the system organized.
   - Verify the archive to ensure all relevant files are included, so they can be accessed if needed in the future.

---

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository