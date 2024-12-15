# Server Management For E-commerce System

### 1. **Directory Creation & Organization:**
   - Create a directory named "ecommerce_app".
   - Inside "ecommerce_app", create 12 subdirectories, each named after a month (January to December).
   - Inside each month’s directory, create files named after daily logs or sales data, such as "sales_day_1.txt" to "sales_day_31.txt", based on the number of days in the month.

### 2. **Move and Rename Files:**
   - Move a log file from the "ecommerce_app" directory to a backup directory named "logs_backup".
   - Rename a sales data file in the "ecommerce_app" directory from "sales_day_1.txt" to "sales_2024-01-01.txt" and verify the change by listing the contents.

### 3. **Navigation & Listing Files:**
   - Navigate to the "ecommerce_app" directory.
   - List the contents of the directory to verify that all month subdirectories and sales files were created properly.

### 4. **File Permissions Management:**
   - Create a file named "config.txt" in the "ecommerce_app" directory to store configuration settings.
   - Change the file permissions so that only the system administrator can read, write, and execute the file, while others have no access.
   - Verify the permission changes by listing the file's details using `ls -l`.

### 5. **Backup Files:**
   - Create a backup of "config.txt" by copying it to a backup directory.
   - Verify the copy operation by listing the contents of the backup directory.

### 6. **Removing Files & Directories:**
   - Delete an old configuration file in the "ecommerce_app" directory.
   - Remove an empty directory from the "logs_backup" directory.

### 7. **Creating a Script for File Generation:**
   - Write a script that creates 100 files inside the "sales_data" directory, each file named uniquely (e.g., "order_1.txt", "order_2.txt", etc.).
   - These files will simulate customer orders.

### 8. **Exploring File History:**
   - View the command history to see the last 20 commands executed.
   - Search the history for any commands related to file operations, such as creating, moving, or deleting files.

### 9. **System Monitoring:**
   - Check the system's uptime to ensure the server is running smoothly.
   - View the system’s load and resource usage statistics, focusing on memory and CPU utilization, to determine the server's health and performance.

### 10. **Checking File Ownership and Permissions:**
   - Check the ownership and group of a file, such as a "database_backup.sql" file, and verify whether they are set correctly for the eCommerce application server's user group.

### 11. **Ping Test & Network Verification:**
   - Verify network connectivity by pinging a remote server, such as the external payment gateway or CDN (Content Delivery Network).
   - Record the response times to ensure the application can access the payment API and other external services.

### 12. **Search for Specific Files or Content:**
   - Search for a specific log file, such as "error_log.txt", in the "ecommerce_app" directory.
   - Search for a specific error message inside one of the log files, such as "500 Internal Server Error", to debug issues.

### 13. **Create a Directory for Each User:**
   - Create a directory for each user (e.g., "admin", "customer_service", "marketing") within the "ecommerce_app" directory and assign appropriate permissions based on the user's role.
   - Admin users might have full permissions, while others might only have read access.

### 14. **Create a Script for Directory Cleanup:**
   - Write a script that deletes all empty directories within the "ecommerce_app" directory to maintain a clean structure, ensuring that old or unused directories are removed.

### 15. **File Sorting & Management:**
   - Sort sales data files by size to identify large files that may need archiving or compression.
   - Create a report listing the largest and smallest sales data files, highlighting files that might require further processing or archiving.

### 16. **File Type Identification:**
   - Identify and list specific file types within the "ecommerce_app" directory, such as `.log`, `.txt`, and `.csv` files, to determine the type of data being stored.

### 17. **File Compression and Archive:**
   - Compress the entire "logs_backup" directory into a single archive file (e.g., "logs_backup.tar.gz").
   - Verify the contents of the archive without extracting it using commands like `tar -tvf logs_backup.tar.gz` to ensure that all logs are properly backed up.

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository