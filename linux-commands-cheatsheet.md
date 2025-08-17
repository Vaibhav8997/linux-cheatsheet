#  Linux Commands Cheat Sheet

A curated list of Linux commands I frequently use in my daily workflow, with practical examples

---

##  File & Directory Management
- `ls -lh` → List files with human-readable sizes  
- `cd /path/to/dir` → Change directory  
- `pwd` → Show current directory  
- `mkdir dir_name` → Create new directory  
- `rm -rf folder/` → Remove folder and contents  

---

##  Process Management
- `ps aux` → Show running processes  
- `top` or `htop` → Monitor processes in real-time  
- `kill -9 <pid>` → Kill a process by PID  
- `systemctl restart pkg_name` → Restart a service  

---

##  Networking
- `ifconfig` or `ip a` → Show IP addresses  
- `ping google.com` → Test network connection  
- `netstat -tulnp` → Show open ports  
- `curl -I https://example.com` → Check HTTP headers  

---

##  Package Management (Debian/Ubuntu)
- `apt update` → Update package lists  
- `apt upgrade` → Upgrade installed packages  
- `apt install pkg_name` → Install a package  
- `apt remove pkg_name` → Remove a package  

---

##  Search & Find
- `grep "text" file.txt` → Search inside file  
- `find / -name file.txt` → Find a file by name  
- `locate filename` → Quickly locate a file  

---

##  Permissions
- `chmod 755 script.sh` → Change file permissions  
- `chown user:group file` → Change ownership  
- `sudo su` → Switch to root  

---

##  Disk & System Info
- `df -h` → Show disk usage  
- `du -sh *` → Show folder sizes  
- `free -h` → Show memory usage  
- `uname -a` → Show system info  

---

##  Useful Shortcuts
- `!!` → Run last command  
- `!<command>` → Run last command starting with word  
- `Ctrl + C` → Kill running process  
- `Ctrl + R` → Search command history  

---

✍️ **Note:** This list will be updated regularly with commands I use in my daily workflow 
