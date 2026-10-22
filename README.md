 # Design and Implementation of a Centralized User and Permission Management System for Linux

**Name:** Ashin Lucky Thomas
**Course Title:** Linux Server
**Topic:** Design and Implementation of a Centralized User and Permission Management System for Linux

### Abstract
This project implements a centralized system to organize users, groups, and file permissions on Linux servers to improve security and accountability.

### Objectives
- Centralize user and group creation
- Implement Role-Based Access Control (RBAC)
- Enforce 90-day password policy
- Organize directories with proper chmod/chown/ACL
- Generate audit logs

### Tools Used
- Ubuntu Server 22.04 LTS
- Bash Shell Scripting
- Linux commands: useradd, groupadd, chpasswd, chmod, chown, setfacl, getfacl
- Git & GitHub

### Folder Structure
/scripts - Automation scripts
/config - users_list.csv and groups
/docs - Permission matrix and screenshots

### How to Run
chmod +x scripts/*.sh
sudo ./scripts/create_users.sh
sudo ./scripts/set_permissions.sh
./scripts/audit_users.sh

### Author
Ashin Lucky Thomas - Linux Server Project 2026
