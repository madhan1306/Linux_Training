# 🐧 Linux Junior Admin Training – Checklist & Roadmap

---

## ✅ Checklist

### 🔧 System Basics
- [ ] Create a new user and set a password  
- [ ] Add user to a group and create a shared directory  
- [ ] Use `chmod`, `chown`, `umask` to manage permissions  
- [ ] Monitor CPU/memory using `top`, `htop`, `free`, `vmstat`  

### 🗂️ File System & Disk
- [ ] Mount and unmount a USB drive  
- [ ] Use `df`, `du` to check disk usage  
- [ ] Create and extract `.tar.gz` archives  
- [ ] Create partitions with `fdisk` and format them  
- [ ] Set up LVM and mount a logical volume  

### 📦 Package Management
- [ ] Install, update, and remove packages with `apt` or `yum`  
- [ ] List installed packages  
- [ ] Add a new repository  

### 🖥️ Networking
- [ ] Check IP, routing, and DNS configuration  
- [ ] Test connectivity using `ping`, `traceroute`, `nc`  
- [ ] Use `curl` or `wget` to download a file  
- [ ] Use `ufw` or `firewalld` to open/close a port  

### 🔐 Security & Users
- [ ] Add user to `sudoers`  
- [ ] Change the SSH port and disable root login  
- [ ] Configure key-based SSH authentication  
- [ ] Set permissions on a sensitive file  

### 🛠️ Scripting & Automation
- [ ] Write a basic bash script (e.g., backup `/etc`)  
- [ ] Use `for` and `if` statements in a script  
- [ ] Schedule a cron job  
- [ ] Log script output to a file  

### 📋 Logs & Services
- [ ] Monitor logs in `/var/log/`  
- [ ] Use `journalctl` to view system logs  
- [ ] Enable/disable/start/stop services using `systemctl`  
- [ ] Configure a service to auto-restart  

---

## 📘 12-Week Structured Roadmap

### 🗓️ Week 1–2: Foundation
- Linux CLI navigation  
- File permissions and ownership  
- User and group management  
- Basic file editing (`nano`, `vim`)  

### 🗓️ Week 3–4: Filesystems & Disks
- Mounting drives  
- `df`, `du`, `lsblk`, `fdisk`  
- File archiving and compression  
- LVM basics  

### 🗓️ Week 5–6: Services & Packages
- `systemd`, service control  
- Installing/removing packages  
- Understanding dependencies  
- Managing repositories  

### 🗓️ Week 7–8: Networking & Security
- IP tools (`ip`, `netstat`, `ss`)  
- Firewalls (`ufw`, `iptables`, `firewalld`)  
- SSH security, key-based login  
- Basic scripting for automation  

### 🗓️ Week 9–10: Automation & Monitoring
- Shell scripting with variables, loops, conditions  
- Scheduling with `cron`  
- Monitoring CPU, memory, disk, services  
- Logging and alerting with simple scripts  

### 🗓️ Week 11–12: Mini Projects
- Setup a local web server (Apache/Nginx)  
- Create a disk monitor with email alert  
- Automate user creation with a script  
- Backup script with rotation  

---

## 🧪 Optional Mini Projects
- **User Report Script** – List all users with last login time  
- **Disk Space Checker** – Alert when usage exceeds 90%  
- **Log Watcher** – Monitor logs for specific keywords  
- **Auto Service Restarter** – Script to restart and alert if a service stops  
- **LAMP Stack Setup** – Install and configure Apache, MySQL, PHP  
- **SSH Hardening** – Secure an SSH server configuration  

---

> You can track your progress by checking tasks as you complete them ✅
