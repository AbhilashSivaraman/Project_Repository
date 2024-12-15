# Server Management for VCS Server

---

### **1. Directory Creation & Organization:**
   - Create a directory named "git_repos".
   - Inside "git_repos", create 12 subdirectories, each representing a different project (e.g., "project_1", "project_2", etc.).
   - Initialize a Git repository in each project directory (`git init`), and create some sample files representing project code, such as "index.py", "README.md", and "config.json".

---

### **2. Move and Rename Files:**
   - Move a file from one repository to another, for example, moving "old_config.json" from "project_1" to "project_2".
   - Rename a file within the repository, such as changing "app.py" to "main.py" in "project_1", and verify the change by listing the contents of the repository (`git status`).

---

### **3. Navigation & Listing Files:**
   - Navigate to the "git_repos" directory and list the contents.
   - Verify that all project subdirectories (repositories) are present and contain Git-managed files (e.g., `.git` folder).

---

### **4. File Permissions Management:**
   - Create a file named "config.txt" in one of the project directories.
   - Change the permissions so that only the repository administrator has read, write, and execute permissions, while others can only read the file.
   - Verify the permission changes using `ls -l`.

---

### **5. Backup Files:**
   - Create a backup of one project repository by copying the entire repository directory to "git_repos/backup".
   - Verify the backup by listing the contents of the "git_repos/backup" directory.

---

### **6. Removing Files & Directories:**
   - Delete an old file, such as "old_documentation.md", from the "project_1" repository.
   - Remove an empty subdirectory from one of the project directories using `git rm` (e.g., `git rm -r old_data`).

---

### **7. Creating a Script for File Generation:**
   - Write a script that generates 100 files inside one of the project directories, each with a unique name (e.g., "file_1.txt", "file_2.txt", etc.).
   - Add and commit all the new files to the Git repository.

---

### **8. Exploring File History:**
   - View the last 20 Git commands executed using `history` or `git reflog`.
   - Search the Git history for any commit related to a specific file or change, for example, `git log -- <file_name>`.

---

### **9. System Monitoring:**
   - Check the system uptime to ensure the Git server is running continuously without interruptions.
   - Monitor system resource usage (CPU, memory, disk space) to ensure Git operations are not being hindered by resource constraints.

---

### **10. Checking File Ownership and Permissions:**
   - Verify the ownership and group of files in the project repositories to ensure that the correct users have appropriate access.
   - Use `git ls-tree HEAD` to check if files and directories in the repository have the correct permissions.

---

### **11. Ping Test & Network Verification:**
   - Test the network connectivity to the Git server from a remote client machine by pinging the server.
   - Record the response times and verify the connection’s stability, ensuring that developers can push and pull from the repositories.

---

### **12. Search for Specific Files or Content:**
   - Use `git ls-files` to search for specific files within a Git repository.
   - Search for a specific string of text inside one of the project files using `git grep`, such as `git grep "config"` to find configuration references.

---

### **13. Create a Directory for Each User:**
   - Create individual user directories for storing user-specific Git configuration and SSH keys, such as "/home/gituser/.ssh" for access management.
   - Assign appropriate permissions for each user directory, ensuring that only the owner has access.

---

### **14. Create a Script for Directory Cleanup:**
   - Write a script that deletes all empty directories from the Git repositories, ensuring that repository management remains clean and efficient.

---

### **15. File Sorting & Management:**
   - Sort files in a repository by size and list the files based on their size using `git ls-tree`.
   - Generate a report listing the largest and smallest files in the repository by checking file sizes with `git cat-file commit <commit_id>`.

---

### **16. File Type Identification:**
   - Identify and list files of a specific type (e.g., `.py`, `.html`, `.md`) in a repository by using `git ls-files` or `find` commands.
   - Generate a list of text files or source code files within a project directory.

---

### **17. File Compression and Archive:**
   - Compress a project repository into a tarball or zip file (`tar -czvf project_1.tar.gz project_1`).
   - Verify the contents of the archive without extracting it using `tar -tf project_1.tar.gz`.

---

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository