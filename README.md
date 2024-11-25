# Linux For DevOps

Welcome to the **Linux for DevOps** course! This course is designed to equip you with the essential Linux skills that are critical for a successful DevOps career. You will learn how to work with Linux systems, manage servers, and automate tasks effectively in a DevOps environment.

## Course Prerequisites
- Basic understanding of computers and operating systems.
- Familiarity with cloud platforms (AWS, Azure, GCP) is a plus, but not required.
- No prior Linux knowledge is required, but some familiarity with programming/scripting languages (Bash, Python, etc.) can be helpful.

## Course Outline

### Module 1: Introduction to Linux
- Overview of Operating system and Kernel
- Open source vs proprietary and Linux distributions (Ubuntu, CentOS, RedHat, etc.)
- Overview of Vertulizations
- Installing Linux (VirtualBox, Cloud environments)
- Navigating the desktop environment and Terminal
- Basic Linux Commands:
  - `ls`, `cd`, `pwd`, `cp`, `mv`, `rm`, `mkdir`
- Understanding files vs. directories
  - Directory structure (`/home`, `/etc`, `/var`, etc.)
  - Absolute vs Relative Path & Hard Link vs Soft Link
- File and directory permissions (`chmod`, `chown`)
  - Symbolic Permissions and Numeric Permissions
    
### Module 2: Working with Users, Groups, Adavance Permissions and File Manipulation
- Understanding users and groups in Linux
  - Managing users (`useradd`, `adduser`, `usermod`, `userdel`)
  - Understanding Types of Accounts
  - Managing groups (`groupadd`, `groupdel`, `gpasswd`)
- Advance File permissions:
  - SGID, SUID, Stiky Bit
  - Access Control Lists (ACLs, `setfacl`, `getfacl`)
  -  File Attributes (`chattr`, `lsattr` etc.)
- User authentication (Password management, `passwd`, SSH key management)
- File Manipulation
  - Input, Output Redirection and Piping
  - View Files ( `echo`, `cat`, `tac`, `tail`, `more`, `less`, `head`)
  - Search Files and Content ( `locate`, `grep`)
  - Search and replace patterns (`sed`)
  - Cut, Sort and Compare the content ( `cut`, `sort`, `uniq`, `diff`) 

### Module 3: System Administration
- Package Management
  - Software installation and package management (APT, YUM, DNF)
  - Managing Repositories and authentication
  - Troubleshooting Package Issues, Backup and Restore Packages
- Service Management
  - Understanding Systemd and Types of Units
  - Managing Service with Systemd (`systemd`, `service`, `systemctl`)
  - Creating custom service unit
- Process Management
  - Key concept of process (`PID`, `PPID`, `States`)
  - Process Prioritization
- Storage Management
  - Overview of File System
  - Disk management and partitioning (`gdisk`, `automounting`, `parted`)
  - File systems and mounting (`ext4`, `xfs`, etc.)
  - Logical Volume Management (`pvcreate`, `vgcreate`, `lvcreate`, etc.)
  - Overview of RAID (Redundant Array of Independent Disks)
- System logging and monitoring (`syslog`, `journalctl`, `dmesg`)
- Cron jobs and scheduling tasks (`crontab`)

### Module 4: Networking and Security
- Basic networking concepts:
  - IP addressing, subnetting, and network interfaces
  - `ifconfig`, `ip`, `ping`, `netstat`, `ss`
- Firewalls and security:
  - Configuring `iptables` and `firewalld`
  - Understanding SELinux or AppArmor
  - Introduction to SSH (Secure Shell) and SSH key-based authentication
- User and system security best practices
  - Securing Linux servers (updates, patches, configurations)
  - Introduction to `fail2ban`, `ufw`, and `SELinux`

### Module 5: Automation and Configuration Management
- Introduction to automation in DevOps
- Git Basics (Versioning Control tool Basics)
- Bash scripting for task automation
- Configuration management with **Ansible**:
  - Ansible installation and setup
  - Writing Ansible playbooks
  - Managing remote servers with Ansible
- Introduction to **Docker** and containerization on Linux
  - Installing Docker
  - Basic Docker commands (`docker run`, `docker ps`, `docker build`, `docker-compose`)

### Module 6: DevOps Tools and Linux in the Cloud
- Introduction to DevOps and Continuous Integration/Continuous Deployment (CI/CD)
- Linux in the cloud (AWS, Azure, GCP)
- Introduction to Infrastructure as Code with **Terraform**
- Introduction to **Kubernetes** and container orchestration
 
## Operational Excellence
- Understand and Deploy your first application on apache web server
- Understand Nginx Reverse proxy and securely host webserver
- Create Docker containers for a simple web application and deploy it to Kubernetes.

## Recommended Resources
- **Books**: 
  - "Linux Basics for Hackers" by OccupyTheWeb
  - "The Linux Command Line" by William E. Shotts
- **Websites**:
  - [Linux Command](https://linuxcommand.org/)
  - [What is Operating System](https://en.wikipedia.org/wiki/Operating_system)
  - [What is Linux Operating Systems](https://en.wikipedia.org/wiki/Linux)
  - [What is Kernel](https://en.wikipedia.org/wiki/Kernel_(operating_system))
  - [Linux Kernel](https://en.wikipedia.org/wiki/Linux_kernel)
  - [DigitalOcean Tutorials](https://www.digitalocean.com/community/tutorials)
  - [Ansible Documentation](https://docs.ansible.com/)

## Conclusion
By the end of this course, you will be able to manage Linux servers, automate administration tasks, and use essential DevOps tools to build and deploy applications in a cloud environment. This course will set you up for success in your DevOps journey.

