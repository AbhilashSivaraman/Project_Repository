# Server Management of BI Server

---

### **1. Directory Creation & Organization:**
   - Create a directory named "bi_server".
   - Inside "bi_server", create subdirectories named after different BI processes or reporting periods (e.g., "ETL", "Reports", "Data_Analysis", "Raw_Data").
   - Inside each directory, organize files for data extraction, transformation, loading (ETL) scripts, reports (e.g., "monthly_sales_report.pdf"), and raw data (e.g., "sales_data_jan.csv").

---

### **2. Move and Rename Files:**
   - Move a BI report file (e.g., "quarterly_report.pdf") from the "Reports" directory to "Archived_Reports".
   - Rename a data file (e.g., rename "raw_sales_data_jan.csv" to "raw_sales_data_2024_jan.csv") and verify the change by listing the contents of the directory.

---

### **3. Navigation & Listing Files:**
   - Navigate to the "bi_server" directory and list its contents.
   - Verify the presence of all BI directories and files, ensuring that BI processes like ETL, reporting, and analysis are properly organized by directories.

---

### **4. File Permissions Management:**
   - Create a file named "sensitive_data.xlsx" in the "bi_server" directory containing sensitive BI-related information (e.g., customer or financial data).
   - Change the permissions of the file so that only authorized BI analysts and admins have read, write, and execute permissions, while others have no access.
   - Verify the permission changes using `ls -l` to ensure that sensitive BI data is protected.

---

### **5. Backup Files:**
   - Create a backup of critical BI files (e.g., raw data files, reports, or analysis scripts) by copying them to a "backup" directory (e.g., "bi_server/backup").
   - Verify the backup operation by listing the contents of the backup directory to ensure all critical BI files are properly backed up.

---

### **6. Removing Files & Directories:**
   - Delete old or outdated BI reports that are no longer needed (e.g., reports that are replaced by newer versions).
   - Remove any empty directories from the "bi_server" directory to keep the storage clean and organized.

---

### **7. Creating a Script for File Generation:**
   - Write a script that generates 100 dummy data files (e.g., "sales_data_1.csv", "sales_data_2.csv") inside the "Raw_Data" directory, each containing different sales data.
   - Each file should contain dummy content such as customer IDs, sales amounts, and dates for analysis purposes.

---

### **8. Exploring File History:**
   - View the last 20 commands executed using `history`, especially those related to data manipulation (e.g., using `cp`, `mv`, `ls`, `rm`).
   - Search for any commands related to file operations in the context of BI data processing using `grep` (e.g., `history | grep report`).

---

### **9. System Monitoring:**
   - Check the system uptime to ensure the BI server is consistently running and processing BI workloads.
   - Monitor system resource usage (CPU, memory, disk space) to ensure the server can handle large data sets and intensive BI computations.

---

### **10. Checking File Ownership and Permissions:**
   - Verify the ownership and group of BI data files to ensure that only authorized users (e.g., BI analysts, data scientists) can modify or access the files.
   - Use `ls -l` to check file ownership and permissions to ensure proper access control.

---

### **11. Ping Test & Network Verification:**
   - Ping the BI server from a remote location to verify network connectivity and ensure analysts can access the server for querying and reporting.
   - Record the response times and verify that the server is accessible for BI operations.

---

### **12. Search for Specific Files or Content:**
   - Use `find` or `grep` to search for a specific BI report file (e.g., "quarterly_sales_report.pdf") in the BI server directory.
   - Search for a specific string within a BI report file (e.g., "revenue", "profit margin") to identify key metrics in the data analysis.

---

### **13. Create a Directory for Each User:**
   - Create a directory for each BI team member (e.g., "/home/bi_analyst1/data").
   - Assign appropriate permissions to each user's directory to ensure that they can only access the data files relevant to their tasks.

---

### **14. Create a Script for Directory Cleanup:**
   - Write a script that deletes all empty subdirectories from the BI server's main directory, especially after data processing or reporting.
   - Set up a cron job to run the cleanup script periodically, ensuring the system stays organized and free from unnecessary empty directories.

---

### **15. File Sorting & Management:**
   - Sort BI data files in the "Raw_Data" directory by size and list the files based on their size to identify large data files that may require more storage or processing time.
   - Generate a report listing the largest and smallest files in the directory, helping optimize disk space and processing.

---

### **16. File Type Identification:**
   - Identify and list files of a specific type (e.g., CSV, Excel, PDF, or SQL) in the "Reports" or "Raw_Data" directory.
   - Ensure that files are categorized based on type for better management and processing in BI workflows.

---

### **17. File Compression and Archive:**
   - Compress large datasets or reports into a single archive file (e.g., using `tar -cvf sales_reports.tar.gz`).
   - Verify the contents of the archive using `tar -tf sales_reports.tar.gz` to ensure that all relevant files are included for later extraction or sharing.

---

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository