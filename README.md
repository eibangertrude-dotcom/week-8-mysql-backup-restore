
# Week 8 Assignment: MySQL Database Backup and Restore

## Description
This assignment demonstrates MySQL database backup operations using the mysqldump command-line utility.

## Tools Used
- MySQL Server 8.4.11
- MySQL Workbench 8.0
- Visual Studio Code
- PowerShell
- Git and GitHub

## Assignment Questions

### Question 1: Complete Database Backup
Command:
```bash
mysqldump -u root -p sales > sales_backup.sql
```

Creates a complete logical backup of the sales database, including its table structures and data.

### Question 2: Backup All Databases
Command:
```bash
mysqldump -u root -p --all-databases > all_databases_backup.sql
```

Creates a backup of the databases supported by mysqldump on the MySQL server.

## Backup Verification
Both backup commands were executed successfully and the generated files were verified.

- sales_backup.sql
- all_databases_backup.sql

## Learning Outcomes
- Creating individual database backups.
- Backing up multiple databases.
- Understanding database recovery.
- Understanding the importance of backups during migration.

## Author
GERTRUDE EIBAN
