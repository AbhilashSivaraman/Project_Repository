# Server Management for ETL jobs

---

### **Directory Creation & Organization:**

1. Create a directory named "data_etl".
2. Inside "data_etl", create 12 subdirectories, each named after a month (e.g., "January", "February", etc.).
3. Inside each month’s directory, create files for different ETL jobs or data transformation processes, such as "extract_sales_data.py", "transform_customer_data.sql", "load_orders_data.sh".

---

### **Move and Rename Files:**

1. Move a data transformation script (e.g., "customer_data_extract.py") from one month's directory (e.g., "January") to another (e.g., "February") to keep data processing tasks organized by time.
2. Rename a file (e.g., "old_transform.py" to "new_transform.py") and verify the change by listing the contents of the directory.

---

### **Navigation & Listing Files:**

1. Navigate to the "data_etl" directory.
2. List the contents of the directory and verify the presence of all subdirectories and files created in the previous task.

---

### **File Permissions Management:**

1. Create a file named "sensitive_data_load.sh" in the "data_etl" directory to store confidential ETL jobs related to secure data.
2. Change the permissions of the file so that only authorized users have read, write, and execute permissions.
3. Verify the permission changes by listing the file's details to ensure that only authorized personnel can modify or execute the ETL jobs.

---

### **Backup Files:**

1. Create a backup of an important ETL script (e.g., "data_load.sh") by copying it to a backup directory for disaster recovery.
2. Verify the backup operation by listing the contents of the backup directory to ensure that the file has been successfully copied.

---

### **Removing Files & Directories:**

1. Delete an outdated ETL script (e.g., "old_data_extract.py") in the "data_etl" directory to remove unnecessary jobs.
2. Remove an empty subdirectory from one of the months' directories (e.g., "March") if there are no new ETL tasks scheduled for that month.

---

### **Creating a Script for File Generation:**

1. Write a script that generates 100 sample ETL task files (e.g., "task_1_extraction.py", "task_2_transformation.sql") for different types of ETL processes like data extraction, transformation, and loading.

---

### **Exploring File History:**

1. View the command history to see the last 20 commands executed related to ETL processes and file management.
2. Search the history for any command related to data manipulation, extraction, or transformation within the "data_etl" directory.

---

### **System Monitoring:**

1. Check the system’s uptime to ensure the Data Transformation and ETL server has been running continuously to process and manage ETL jobs without interruption.
2. View the system’s load and resource usage statistics to ensure the server can handle multiple, simultaneous ETL tasks efficiently.

---

### **Checking File Ownership and Permissions:**

1. Check the ownership and group of an ETL job script (e.g., "data_transform.py") and verify whether they are correct to ensure proper access control for sensitive data processes.

---

### **Ping Test & Network Verification:**

1. Verify network connectivity by pinging a remote data source (e.g., cloud data storage or external APIs) that the ETL jobs rely on.
2. Record the response times and verify the connectivity to ensure smooth data extraction, transformation, and loading during scheduled jobs.

---

### **Search for Specific Files or Content:**

1. Search for a specific ETL script (e.g., "sales_data_extract.sh") within the "data_etl" directory to locate and review specific job files.
2. Search for a specific string of text (e.g., "SELECT * FROM") inside one of the SQL transformation scripts to identify the query structure.

---

### **Create a Directory for Each User:**

1. Create a directory for each user (e.g., "data_analyst", "etl_admin") working on data transformation and ETL jobs to store their personal job scripts and configuration files.
2. Assign appropriate permissions to ensure that only the respective user and authorized administrators can modify or access their personal ETL scripts.

---

### **Creating a Script for Directory Cleanup:**

1. Write a script that deletes all empty subdirectories from the "data_etl" directory after ETL tasks have been processed to maintain a clean file structure.

---

### **File Sorting & Management:**

1. Sort ETL job files in a directory by size or modification date and list the files based on the most recently updated or largest scripts.
2. Create a report listing the largest and smallest ETL scripts, identifying tasks that may need optimization or smaller scripts that can be merged.

---

### **File Type Identification:**

1. Identify and list files of specific types (e.g., Python scripts, SQL files) in the "data_etl" directory to help organize the types of transformations and extractions in use.
2. Filter and list only the files related to a specific ETL stage, such as "extraction_*.py", "transformation_*.sql", or "load_*.sh".

---

### **File Compression and Archive:**

1. Compress the "data_etl" directory into a single archive file to back up all the scripts, configurations, and logs related to the ETL jobs.
2. Verify the contents of the archive without extracting it to ensure that all relevant ETL scripts and transformation tasks are included.

---

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository