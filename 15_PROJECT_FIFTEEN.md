# Server Management for Game Server

---

### **1. Directory Creation & Organization:**
   - Create a directory named "game_servers".
   - Inside "game_servers", create 12 subdirectories, each representing a different game (e.g., "Minecraft", "CS:GO", "Fortnite", etc.).
   - Inside each game directory, create files representing different game configurations (e.g., "server.properties" for Minecraft, "autoexec.cfg" for CS:GO).

---

### **2. Move and Rename Files:**
   - Move a file from one game directory to another, such as moving a configuration file for "Minecraft" to "CS:GO".
   - Rename a file within a game directory, such as changing "old_config.txt" to "server_config.txt" in the "Minecraft" directory and verify the change by listing the contents of the directory.

---

### **3. Navigation & Listing Files:**
   - Navigate to the "game_servers" directory and list the contents.
   - Verify that all game subdirectories are present and contain necessary configuration files for each game server.

---

### **4. File Permissions Management:**
   - Create a file named "config.txt" in one of the game server directories.
   - Change the permissions so that only the game server administrator can read, write, and execute the file, while others can only read.
   - Verify the permission changes using `ls -l` to ensure security.

---

### **5. Backup Files:**
   - Create a backup of the game server configuration files by copying them to a backup directory (e.g., "game_servers/backup").
   - Verify the backup by listing the contents of the backup directory to ensure all game server configurations are backed up.

---

### **6. Removing Files & Directories:**
   - Delete an old configuration file, such as "old_map_config.txt", from the "Minecraft" server directory.
   - Remove an empty subdirectory from one of the game directories (e.g., "old_maps") using `rm -r`.

---

### **7. Creating a Script for File Generation:**
   - Write a script that generates 100 configuration files inside a game server directory, each with a unique name (e.g., "config_1.txt", "config_2.txt").
   - Add and commit the new configurations to the respective game server repository.

---

### **8. Exploring File History:**
   - View the last 20 commands executed on the server using `history` to check for server-related commands (e.g., "start server", "restart server").
   - Search for any commands related to game server file changes by using `grep` on the history (e.g., `history | grep config`).

---

### **9. System Monitoring:**
   - Check the system uptime to ensure the game server is running continuously without interruptions.
   - Monitor system resource usage (CPU, memory, disk space) during peak gaming hours to ensure the server is not overloaded or underperforming.

---

### **10. Checking File Ownership and Permissions:**
   - Verify the ownership and group of critical game server files (such as configuration files) to ensure that only authorized administrators have access.
   - Use `ls -l` to check the file ownership and permissions and confirm correct settings.

---

### **11. Ping Test & Network Verification:**
   - Test the network connectivity to the game server by pinging it from a remote player’s machine.
   - Record the response times and verify network stability to ensure players can connect to the server without issues.

---

### **12. Search for Specific Files or Content:**
   - Use `find` or `grep` to search for a specific configuration file (e.g., "server.properties" in the "Minecraft" directory).
   - Search for a specific string of text inside a game configuration file (e.g., searching for "max-players=20" in the "server.properties" file).

---

### **13. Create a Directory for Each User:**
   - Create a directory for each user who has administrator access to the game server (e.g., "/home/gameadmin1/.game_server_config").
   - Assign appropriate permissions to each user directory to restrict access to the game server configurations.

---

### **14. Create a Script for Directory Cleanup:**
   - Write a script that deletes all empty directories within the game server directories (e.g., empty "maps" or "logs" directories).
   - Ensure that the script runs periodically to keep the game server environment clean.

---

### **15. File Sorting & Management:**
   - Sort game server logs by size and list the largest files to identify possible issues or log bloat.
   - Create a report listing the largest and smallest log files generated by the server.

---

### **16. File Type Identification:**
   - Identify and list files of a specific type (e.g., `.log`, `.cfg`, `.dat`) within the game server directories.
   - Generate a list of all configuration files used by the game server.

---

### **17. File Compression and Archive:**
   - Compress the entire game server directory (e.g., "Minecraft" server directory) into a single archive file for backup or migration purposes.
   - Verify the contents of the archive file without extracting it using the `tar -tf` command.

---

### NOTE: Finally fetch all the project commands from history and create a detailed project report "your_name_rollname.md" and push it to git your git repository