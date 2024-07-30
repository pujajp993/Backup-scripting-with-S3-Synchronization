# Backup-scripting-with-S3-Synchronization
1. Create an IAM Role which allows access to S3, and attach with your aws instance
2. Login to the console (CLI) of the server and configure a MariaDB server.
3. Write a shell script for taking up the backups of databases to a directory
4. Configure aws-cli within the server and synchronize the backup directory with any of the
aws S3 buckets.
5. Verify the backups in S3
