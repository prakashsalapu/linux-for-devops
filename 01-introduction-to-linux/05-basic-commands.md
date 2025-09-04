## 5. Basic Linux Commands  

### 🔹 File & Directory Commands  

| Command | Description | Example |
|---------|-------------|---------|
| `pwd`  | Show current directory | `$ pwd` → `/home/user` |
| `ls`   | List files & folders | `$ ls -l` → shows details |
| `cd`   | Change directory | `$ cd Documents` |
| `mkdir` | Create a new folder | `$ mkdir myfolder` |
| `rmdir` | Remove an empty folder | `$ rmdir myfolder` |
| `rm`   | Remove files or folders | `$ rm file.txt` |

### 🔹 File Viewing & Editing  

| Command | Description | Example |
|---------|-------------|---------|
| `cat`  | View file content | `$ cat file.txt` |
| `less` | Scroll through large files | `$ less file.txt` |
| `nano` | Edit files in terminal | `$ nano file.txt` |
| `vim`  | Advanced editor | `$ vim file.txt` |
| `touch` | Create empty file | `$ touch newfile.txt` |

### 🔹 File & Folder Operations  

| Command | Description | Example |
|---------|-------------|---------|
| `cp`    | Copy files/folders | `$ cp file.txt /home/user/` |
| `mv`    | Move or rename | `$ mv file.txt newfile.txt` |
| `chmod` | Change permissions | `$ chmod 755 script.sh` |
| `chown` | Change file owner | `$ chown user:group file.txt` |

### 🔹 System Info & Process Commands  

| Command | Description | Example |
|---------|-------------|---------|
| `top`   | Show running processes | `$ top` |
| `ps`    | List processes | `$ ps aux` |
| `df`    | Disk space usage | `$ df -h` |
| `free`  | Memory usage | `$ free -h` |
| `uptime` | System uptime | `$ uptime` |

### 🔹 Flow: How Commands Work  
```
User types command → Shell interprets → Kernel executes → Output shown to user

```

### 🔹 Quick Tips  
- Use `Tab` for **auto-completion** of commands & file names.  
- Use `Ctrl + C` to **stop a running command**.  
- Use `man <command>` to see **manual/help page** of any command.  

### 🔹 Key Takeaways  
- Basic Linux commands are **building blocks** for DevOps.  
- Practice them daily → navigation, editing, and managing files becomes **second nature**.  
