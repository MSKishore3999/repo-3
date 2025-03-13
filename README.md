#2025-03-13 10:15:32 INFO  [Main] Application started successfully.
2025-03-13 10:15:35 WARN  [Auth] Failed login attempt for user 'john_doe'.
2025-03-13 10:16:10 ERROR [DB] Connection to database failed: Timeout error.
2025-03-13 10:17:05 DEBUG [Cache] Cache refreshed for user ID: 12345.
2025-03-13 10:18:22 INFO  [Payment] Payment of $49.99 processed for order #9876.
192.168.1.10 - - [13/Mar/2025:10:12:45 +0000] "GET /index.html HTTP/1.1" 200 1024
192.168.1.11 - - [13/Mar/2025:10:12:47 +0000] "POST /login HTTP/1.1" 401 512
192.168.1.12 - - [13/Mar/2025:10:13:02 +0000] "GET /products HTTP/1.1" 200 2048
192.168.1.13 - - [13/Mar/2025:10:13:15 +0000] "POST /checkout HTTP/1.1" 500 128
Mar 13 10:14:02 server1 kernel: [152345.67] CPU usage exceeded threshold: 90%
Mar 13 10:14:15 server1 sshd[3456]: Failed password for root from 203.0.113.5 port 54321 ssh2
Mar 13 10:15:30 server1 cron[6789]: (root) CMD (/usr/bin/backup.sh)
Mar 13 10:16:45 server1 systemd[1]: Started Apache Web Server.
2025-03-13 10:10:32 INFO  [MySQL] Connection established with database 'shop_db'.
2025-03-13 10:11:15 ERROR [MySQL] Query failed: Duplicate entry '123' for key 'PRIMARY'.
2025-03-13 10:12:45 WARN  [MySQL] Slow query detected: SELECT * FROM orders WHERE user_id=999 (Execution Time: 5.2s).
2025-03-13 10:14:08 INFO  [MySQL] Transaction committed successfully.
