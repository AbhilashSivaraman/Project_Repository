# Server Management for Inventory Server

---

### **1. Directory Creation & Organization:**
   - Create a directory named "inventory_server".
   - Inside "inventory_server", create subdirectories for different product categories, such as "Electronics", "Furniture", "Clothing", etc.
   - Inside each category directory, organize product records by creating files named after individual products, including details like product IDs, names, and stock levels.

---

### **2. Move and Rename Files:**
   - Move a file (e.g., "electronics_product_001.csv") from the "Electronics" category to the "Archived_Products" directory for discontinued items.
   - Rename a file within the "Clothing" directory (e.g., from "clothing_item_100.csv" to "clothing_item_2024_100.csv") to reflect the year or season of the product.

---

### **3. Navigation & Listing Files:**
   - Navigate to the "inventory_server" directory and list its contents.
   - Verify the presence of all product category subdirectories and ensure that the inventory files for each product are correctly organized.

---

### **4. File Permissions Management:**
   - Create a file named "inventory_report.csv" in the "inventory_server" directory, containing sensitive stock data (e.g., product quantities and pricing).
   - Change the permissions of the file to restrict access, ensuring that only authorized staff members can view and modify the file.
   - Verify the changes by listing the file’s details and checking the permissions.

---

### **5. Backup Files:**
   - Create a backup of important product data (e.g., product inventory reports, stock levels) by copying them to a "backup" directory.
   - Ensure that backups are regularly made to avoid data loss, especially for critical information like stock levels and sales data.

---

### **6. Removing Files & Directories:**
   - Delete obsolete inventory files, such as product records for discontinued items or outdated reports.
   - Remove empty subdirectories from product categories that no longer contain inventory files or records.

---

### **7. Creating a Script for File Generation:**
   - Write a script that generates 100 dummy product files (e.g., "product_001.csv", "product_002.csv") with mock product data, including name, description, price, and stock.
   - These files can serve as placeholders for testing inventory management processes.

---

### **8. Exploring File History:**
   - View the command history to see the last 20 commands executed, particularly those related to file management in the "inventory_server" directory (e.g., `mv`, `cp`, `ls`, `rm`).
   - Search for any commands related to inventory file handling and make sure they were executed as intended.

---

### **9. System Monitoring:**
   - Check the server’s uptime to verify that the inventory management system is operating continuously.
   - Monitor system resource usage (CPU, memory, disk space) to ensure that the server can handle the growing inventory data and product records.

---

### **10. Checking File Ownership and Permissions:**
   - Verify the ownership and group of inventory-related files to ensure that the right personnel have the appropriate access.
   - Check if permissions are set correctly for sensitive files, like inventory reports, so that only authorized users can access them.

---

### **11. Ping Test & Network Verification:**
   - Perform a ping test to verify the server's network connectivity, ensuring that it can communicate with remote systems for inventory updates or data synchronization.
   - Record the response times to ensure the network is performing optimally for data transfer and communication.

---

### **12. Search for Specific Files or Content:**
   - Use search commands to locate specific product files (e.g., "product_101.csv") within the "inventory_server" directory.
   - Search for a particular item or keyword within product files (e.g., "laptop" or "chair") to find relevant inventory records quickly.

---

### **13. Create a Directory for Each User:**
   - Set up individual directories for each inventory manager or team member to store data relevant to their area (e.g., product management, reporting, logistics).
   - Assign appropriate permissions to each directory to ensure secure and role-based access.

---

### **14. Create a Script for Directory Cleanup:**
   - Write a script to automatically remove empty or outdated product directories (e.g., for products that have been discontinued or out of stock).
   - Set up a scheduled task to run this cleanup script periodically to maintain an organized and efficient inventory server.

---

### **15. File Sorting & Management:**
   - Sort the inventory files in the "Electronics" directory by file size to identify which product records are larger and may need more storage or optimization.
   - Create a report listing the largest and smallest product files to monitor inventory growth and identify inefficiencies in data storage.

---

### **16. File Type Identification:**
   - Identify and list specific types of files (e.g., CSV, Excel) that contain inventory data.
   - Categorize files based on their types, helping to ensure that product data is stored in the most appropriate format for inventory analysis and reporting.

---

### **17. File Compression and Archive:**
   - Compress product data or inventory reports into a single archive file for long-term storage or transfer (e.g., compress old product records).
   - Verify the contents of the archive to ensure all necessary files are included without extraction.

---

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository