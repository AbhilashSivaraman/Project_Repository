# Server Management of Document Management System

---

### **1. Directory Creation & Organization:**
   - Create a directory named "document_management_system".
   - Inside "document_management_system", create 12 subdirectories, one for each month (e.g., "January", "February", "March", etc.).
   - Inside each month’s directory, create files representing different document categories (e.g., "invoice_01.pdf", "contract_02.docx", "report_03.txt").

---

### **2. Move and Rename Files:**
   - Move a document from one month's directory to another (e.g., move "invoice_05.pdf" from "May" to "June").
   - Rename a document file (e.g., "invoice_old_01.pdf" to "invoice_01.pdf") and verify the change by listing the contents of the directory.

---

### **3. Navigation & Listing Files:**
   - Navigate to the "document_management_system" directory and list its contents.
   - Verify the presence of all month directories and document files to ensure that the documents are organized by month and category.

---

### **4. File Permissions Management:**
   - Create a file named "confidential_report.pdf" in the "document_management_system" directory containing sensitive business documents.
   - Change the permissions of the file to ensure that only authorized users (e.g., admin or management) have read, write, and execute permissions, while others have no access.
   - Verify the permission changes using `ls -l` to ensure sensitive files are properly protected.

---

### **5. Backup Files:**
   - Create a backup of important documents (e.g., confidential reports, contracts) by copying them to a "backup" directory (e.g., "document_management_system/backup").
   - Verify the backup operation by listing the contents of the backup directory to ensure all important documents are backed up.

---

### **6. Removing Files & Directories:**
   - Delete old or irrelevant documents from the "document_management_system" directory (e.g., outdated invoices or drafts).
   - Remove any empty directories that are no longer needed from the system to keep the directory structure clean.

---

### **7. Creating a Script for File Generation:**
   - Write a script to generate 100 document files with unique names inside a directory (e.g., "doc_1.pdf", "doc_2.docx").
   - Each document file should contain dummy content or metadata like document title, date, and a brief description.

---

### **8. Exploring File History:**
   - View the last 20 commands executed using `history`, especially those related to managing document files.
   - Search for any commands related to document manipulation by using `grep` (e.g., `history | grep doc`).

---

### **9. System Monitoring:**
   - Check the system uptime to ensure the document management server is stable and operational.
   - Monitor system resource usage (CPU, memory, disk space) to ensure the server can handle document storage and retrieval efficiently.

---

### **10. Checking File Ownership and Permissions:**
   - Verify the ownership and group of sensitive files, like legal contracts and confidential documents, ensuring that only authorized users can access them.
   - Use `ls -l` to check file ownership and permissions, ensuring the correct access levels are in place.

---

### **11. Ping Test & Network Verification:**
   - Ping the document management server from a remote location to verify network connectivity.
   - Record the response times and ensure the server is accessible, as fast document retrieval requires stable network connectivity.

---

### **12. Search for Specific Files or Content:**
   - Use `find` or `grep` to search for specific document files (e.g., "invoice_05.pdf" in the "May" directory).
   - Search for specific text or keywords (e.g., "contract terms" or "payment agreement") within document files to verify content.

---

### **13. Create a Directory for Each User:**
   - Create a directory for each user or department in the document management system (e.g., "/home/HR_department/documents").
   - Assign appropriate permissions to each user's directory, ensuring that they can only access their department's documents.

---

### **14. Create a Script for Directory Cleanup:**
   - Write a script that deletes all empty subdirectories within the document management system, especially after old projects or document categories are archived.
   - Set the script to run periodically to ensure the system remains organized.

---

### **15. File Sorting & Management:**
   - Sort the document files in a directory by size, then list the files based on their size to identify large documents that may need to be archived or compressed.
   - Generate a report listing the largest and smallest documents in a directory for better document lifecycle management.

---

### **16. File Type Identification:**
   - Identify and list files of a specific type (e.g., PDF files, DOCX files) within the document management system.
   - Make sure sensitive files (e.g., financial reports or legal contracts) are categorized properly for access control.

---

### **17. File Compression and Archive:**
   - Compress a directory containing older or archived documents into a single archive file (e.g., `tar -cvf archived_documents.tar.gz`).
   - Verify the contents of the archive without extracting it by running `tar -tf archived_documents.tar.gz` to ensure all files are included.

---
### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository