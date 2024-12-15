# Server Management for HRMS Server

---

### **1. Directory Creation & Organization:**
   - Create a directory named "hrms_server".
   - Inside "hrms_server", create subdirectories for different HR functions like "Employee_Records", "Payroll", "Leave_Management", and "Training".
   - Inside each directory, store employee data, payroll files (e.g., "employee_salary_jan.xlsx"), leave records, and training schedules.

---

### **2. Move and Rename Files:**
   - Move a file (e.g., "employee_payslip_jan.pdf") from the "Payroll" directory to the "Archived_Payslips" directory.
   - Rename an employee data file (e.g., rename "employee_12345.csv" to "employee_2024_12345.csv") and verify the change by listing the directory contents.

---

### **3. Navigation & Listing Files:**
   - Navigate to the "hrms_server" directory and list its contents.
   - Verify the presence of subdirectories like "Employee_Records", "Payroll", and others, ensuring that all HR-related documents and data are properly organized.

---

### **4. File Permissions Management:**
   - Create a file named "sensitive_employee_data.xlsx" in the "hrms_server" directory containing personal employee information (e.g., social security numbers, salary details).
   - Change the permissions of the file so that only authorized HR personnel can read, write, and execute the file.
   - Verify the permission changes using `ls -l` to ensure sensitive employee data is protected.

---

### **5. Backup Files:**
   - Create a backup of critical HR files (e.g., employee records, payroll) by copying them to a "backup" directory (e.g., "hrms_server/backup").
   - Verify the backup operation by listing the contents of the backup directory to ensure all critical files are backed up.

---

### **6. Removing Files & Directories:**
   - Delete outdated employee records or payroll files that are no longer required, following company data retention policies.
   - Remove empty subdirectories from the "hrms_server" directory to maintain a clean environment.

---

### **7. Creating a Script for File Generation:**
   - Write a script that creates 100 dummy employee records files (e.g., "employee_1.csv", "employee_2.csv") inside the "Employee_Records" directory, each containing dummy data (e.g., name, ID, department).
   - Each file should represent a new employee’s record for testing purposes.

---

### **8. Exploring File History:**
   - View the last 20 commands executed using `history`, especially those related to HR data manipulation (e.g., `mv`, `cp`, `ls`, `rm`).
   - Search for any commands related to sensitive HR data management using `grep` (e.g., `history | grep payroll`).

---

### **9. System Monitoring:**
   - Check the system uptime to ensure the HRMS server is operational and running smoothly for HR activities.
   - Monitor system resource usage (CPU, memory, disk space) to ensure the server can handle the HRMS workload, especially during payroll periods or when running reports.

---

### **10. Checking File Ownership and Permissions:**
   - Verify the ownership and group of sensitive HR data files to ensure that only authorized HR personnel have access.
   - Use `ls -l` to check file ownership and permissions for employee records and payroll data, ensuring proper access control.

---

### **11. Ping Test & Network Verification:**
   - Ping the HRMS server from a remote location to verify network connectivity, ensuring that HR personnel can access the server for employee management.
   - Record the response times and verify connectivity to ensure HR systems are functioning properly.

---

### **12. Search for Specific Files or Content:**
   - Use `find` or `grep` to search for a specific employee file (e.g., "employee_12345.csv") in the HRMS directory.
   - Search for specific data within an employee record file (e.g., employee names, job titles) to verify data accuracy and consistency.

---

### **13. Create a Directory for Each User:**
   - Create a directory for each HR team member (e.g., "/home/hr_manager1/records") to store relevant files.
   - Assign appropriate permissions to each directory to ensure HR personnel can only access data necessary for their roles.

---

### **14. Create a Script for Directory Cleanup:**
   - Write a script that deletes all empty subdirectories from the "hrms_server" directory, which may occur after data processing or employee data archiving.
   - Set up a cron job to automatically run the cleanup script at regular intervals to maintain the server’s organization.

---

### **15. File Sorting & Management:**
   - Sort HR files in the "Employee_Records" directory by size to identify larger files, such as long payroll spreadsheets or extensive training records.
   - Generate a report listing the largest and smallest files in the directory, helping optimize disk space and processing time.

---

### **16. File Type Identification:**
   - Identify and list files of specific types (e.g., CSV, Excel, PDF) in the "Employee_Records" or "Payroll" directory.
   - Ensure files are categorized based on their type for better management and processing within the HRMS.

---

### **17. File Compression and Archive:**
   - Compress employee records or archived payroll data into a single archive file (e.g., using `tar -cvf employee_records.tar.gz`).
   - Verify the contents of the archive using `tar -tf employee_records.tar.gz` to ensure that all relevant files are included.

---

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository