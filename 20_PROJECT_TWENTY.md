# Server Management for Task Management System

---

### **1. Directory Creation & Organization:**
   - Create a directory named "task_management_system".
   - Inside "task_management_system", create 12 subdirectories, each named after a month (e.g., "January", "February", "March", etc.).
   - Inside each month's directory, create files representing different task categories (e.g., "task_01.txt", "task_02.csv", "task_03.md").

---

### **2. Move and Rename Files:**
   - Move a task file from one month’s directory to another (e.g., move "task_15.txt" from "March" to "April").
   - Rename a task file (e.g., "task_old_01.txt" to "task_01.txt") and verify the change by listing the contents of the directory.

---

### **3. Navigation & Listing Files:**
   - Navigate to the "task_management_system" directory and list its contents.
   - Verify the presence of all month directories and task files to ensure that tasks are properly organized by month and category.

---

### **4. File Permissions Management:**
   - Create a file named "private_task.txt" in the "task_management_system" directory containing sensitive task details.
   - Change the permissions of the file to ensure that only authorized users (e.g., admin or team lead) can read, write, and execute the file, while others have no access.
   - Verify the permission changes using `ls -l` to ensure sensitive task data is protected.

---

### **5. Backup Files:**
   - Create a backup of important task files (e.g., critical project tasks) by copying them to a "backup" directory (e.g., "task_management_system/backup").
   - Verify the backup operation by listing the contents of the backup directory to ensure all important tasks are backed up.

---

### **6. Removing Files & Directories:**
   - Delete completed or outdated task files from the "task_management_system" directory (e.g., tasks that have been completed or canceled).
   - Remove any empty directories that are no longer needed from the system to keep the directory structure clean.

---

### **7. Creating a Script for File Generation:**
   - Write a script to generate 100 task files with unique names (e.g., "task_1.txt", "task_2.csv") inside a directory.
   - Each task file should contain dummy content like task descriptions, due dates, and assignees.

---

### **8. Exploring File History:**
   - View the last 20 commands executed using `history`, especially those related to task file manipulation.
   - Search for any commands related to file operations using `grep` (e.g., `history | grep task`).

---

### **9. System Monitoring:**
   - Check the system uptime to ensure the task management server is running continuously.
   - Monitor system resource usage (CPU, memory, disk space) to ensure the server can handle multiple tasks, especially as the database of tasks grows.

---

### **10. Checking File Ownership and Permissions:**
   - Verify the ownership and group of task files, ensuring that only the correct user (e.g., project manager) has write access.
   - Use `ls -l` to check file ownership and permissions to ensure correct access levels for team members.

---

### **11. Ping Test & Network Verification:**
   - Ping the task management server from a remote location to verify network connectivity.
   - Record the response times and ensure the server is accessible to all team members for task creation and updates.

---

### **12. Search for Specific Files or Content:**
   - Use `find` or `grep` to search for specific task files (e.g., "task_10.txt") in the task management system directory.
   - Search for specific keywords within task files (e.g., "due date", "assigned to") to verify task details.

---

### **13. Create a Directory for Each User:**
   - Create a directory for each user or team in the task management system (e.g., "/home/JohnDoe/tasks").
   - Assign appropriate permissions to each user’s directory to ensure they can only access their own tasks and not those of other users.

---

### **14. Create a Script for Directory Cleanup:**
   - Write a script that deletes all empty subdirectories from the task management system, especially after task completion.
   - Set up a cron job to run the cleanup script periodically to keep the system organized.

---

### **15. File Sorting & Management:**
   - Sort task files in a directory by size, then list the files based on their size to identify large task documents that may need to be archived or compressed.
   - Generate a report listing the largest and smallest task files to understand task data usage.

---

### **16. File Type Identification:**
   - Identify and list files of a specific type (e.g., text files, CSV files) within the task management system directory.
   - Make sure all task files are categorized properly for easy retrieval (e.g., project tasks in CSV format, documentation in text files).

---

### **17. File Compression and Archive:**
   - Compress a directory containing completed or archived tasks into a single archive file (e.g., `tar -cvf completed_tasks.tar.gz`).
   - Verify the contents of the archive without extracting it by running `tar -tf completed_tasks.tar.gz` to ensure all archived task files are included.

---

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository