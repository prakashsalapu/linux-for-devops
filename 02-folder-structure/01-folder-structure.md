
## Linux Folder Structure  

### 🔹 Understanding the Folder Structure  
Linux organizes everything in a **hierarchical directory tree**.  
Knowing the folder structure is **essential for navigation, file management, and DevOps tasks**.  


### 🔹 Symbolic Links (Less Significant)  

| Directory | Description |
|-----------|-------------|
| `/sbin -> /usr/sbin` | System binaries for administrative commands (linked to /usr/sbin) |
| `/bin -> /usr/bin`   | Essential user binaries (linked to /usr/bin) |
| `/lib -> /usr/lib`   | Shared libraries and kernel modules (linked to /usr/lib) |


### 🔹 Important System Directories  

| Directory | Description |
|-----------|-------------|
| `/boot`  | Stores files needed for booting the system (not relevant in containers) |
| `/usr`   | Contains most user-installed applications and libraries |
| `/var`   | Stores logs, caches, and temporary files that change frequently |
| `/etc`   | Stores system configuration files |


### 🔹 User & Application-Specific Directories  

| Directory | Description |
|-----------|-------------|
| `/home`  | Default location for user home directories |
| `/opt`   | Used for installing optional third-party software |
| `/srv`   | Holds data for services like web servers (rarely used in containers) |
| `/root`  | Home directory for the root user |


### 🔹 Temporary & Volatile Directories  

| Directory | Description |
|-----------|-------------|
| `/tmp`   | Temporary files (cleared on reboot) |
| `/run`   | Holds runtime data for processes |
| `/proc`  | Virtual filesystem for process and system information |
| `/sys`   | Virtual filesystem for hardware and kernel information |
| `/dev`   | Contains device files (e.g., `/dev/null`, `/dev/sda`) |


### 🔹 Mount Points  

| Directory | Description |
|-----------|-------------|
| `/mnt`    | Temporary mount point for external filesystems |
| `/media`  | Mount point for removable media (USB, CDs) |
| `/data`   | Likely your mounted volume from Windows (e.g., C:/ubuntu-data) |


### ✅ Key Takeaways  
- Linux folder structure is **organized in layers**: system files, user files, temporary files, and mount points.  
- Understanding this helps in **navigation, configuration, and DevOps tasks**.  
- Symbolic links are **shortcuts** to simplify access to important folders.  
