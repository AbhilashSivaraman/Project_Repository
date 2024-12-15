# Server Management for Payment Gateway

---

### **1. Directory Creation & Organization:**
   - Create a directory named "payment_gateway".
   - Inside "payment_gateway", create 12 subdirectories, one for each month (e.g., "January", "February", "March", etc.).
   - Inside each month’s directory, create files that correspond to transaction logs for each day of the month (e.g., "transaction_log_01.txt", "transaction_log_02.txt").

---

### **2. Move and Rename Files:**
   - Move transaction log files from one month's directory to another (e.g., move "transaction_log_05.txt" from "May" to "June").
   - Rename a transaction log file (e.g., "transaction_log_old_05.txt" to "transaction_log_05.txt") and verify the change by listing the contents of the directory.

---

### **3. Navigation & Listing Files:**
   - Navigate to the "payment_gateway" directory and list its contents.
   - Verify the presence of all month directories and transaction log files, ensuring that transaction records are organized by month and day.

---

### **4. File Permissions Management:**
   - Create a file named "config.json" in the "payment_gateway" directory containing API keys, database connection details, and other sensitive configuration data.
   - Change the permissions of the file to ensure only administrators have read, write, and execute permissions, and that others have no access.
   - Verify the permission changes using `ls -l` to ensure sensitive configuration files are secure.

---

### **5. Backup Files:**
   - Create a backup of critical files, such as transaction logs, configuration files, and payment-related data, by copying them to a "backup" directory (e.g., "payment_gateway/backup").
   - Verify the backup operation by listing the contents of the backup directory to ensure all important files are included.

---

### **6. Removing Files & Directories:**
   - Delete old or irrelevant transaction log files from the "payment_gateway" directory (e.g., "transaction_log_01.txt").
   - Remove any empty directories from the system that are no longer needed, ensuring a clean server environment.

---

### **7. Creating a Script for File Generation:**
   - Write a script to generate 100 transaction log files with unique names inside a directory (e.g., "transaction_log_1.txt", "transaction_log_2.txt").
   - Ensure that each log file contains dummy payment transaction data, including a timestamp, transaction ID, and payment status.

---

### **8. Exploring File History:**
   - View the last 20 commands executed using `history`, especially those related to managing sensitive payment files and logs.
   - Search for any commands related to the handling of transaction logs or sensitive data by using `grep` (e.g., `history | grep transaction`).

---

### **9. System Monitoring:**
   - Check the system uptime to ensure the payment gateway server has not been unexpectedly restarted.
   - Monitor system resource usage (CPU, memory, disk space) during peak transaction periods to ensure the server can handle a large number of simultaneous transactions efficiently.

---

### **10. Checking File Ownership and Permissions:**
   - Verify the ownership and group of payment-related files and configuration files to ensure that only authorized personnel have access.
   - Use `ls -l` to check file ownership and permissions, confirming the correct access levels for sensitive files like configuration files and transaction logs.

---

### **11. Ping Test & Network Verification:**
   - Ping the payment gateway server from a remote location to verify network connectivity.
   - Record the response times and ensure network stability, as quick and reliable network connectivity is critical for processing transactions in real time.

---

### **12. Search for Specific Files or Content:**
   - Use `find` or `grep` to search for specific transaction log files (e.g., "transaction_log_05.txt" in the "May" directory).
   - Search for specific transaction data (e.g., "transaction_id=12345") within the log files to verify specific payment activity.

---

### **13. Create a Directory for Each User:**
   - Create a directory for each user or merchant account in the payment system (e.g., "/home/merchant1/payment_data").
   - Assign appropriate permissions to each user's directory, ensuring that only authorized personnel can access their payment data.

---

### **14. Create a Script for Directory Cleanup:**
   - Write a script that deletes all empty directories within the payment gateway system (e.g., unused directories for old merchants or customers).
   - Set the script to run periodically to ensure the system remains organized.

---

### **15. File Sorting & Management:**
   - Sort the transaction log files by size and list the largest files to identify logs that may need to be archived or cleaned up.
   - Generate a report listing the largest and smallest transaction log files and verify that they meet retention policies.

---

### **16. File Type Identification:**
   - Identify and list files of a specific type (e.g., `.log`, `.txt`) within the payment gateway directories.
   - Identify any files that may contain sensitive payment data, ensuring they are properly secured.

---

### **17. File Compression and Archive:**
   - Compress the entire "payment_gateway" directory into a single archive file (e.g., `tar -cvf payment_gateway_backup.tar.gz`).
   - Verify the contents of the archive without extracting it by running `tar -tf payment_gateway_backup.tar.gz`.

---
### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository