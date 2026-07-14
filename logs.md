#Linux Logs

## Objective
Learn how to view system and Nginx logs.

## View Nginx Service Logs
Command:
sudo journalctl -u nginx
- This displays logs related to the Nginx service, such as when it starts or stops.

## View Access Log
Command:
cat /var/log/nginx/access.log
- The access log records requests made to the web server.

Example:
- `127.0.0.1` → Local computer
- `GET /` → Home page requested
- `200` → Request completed successfully

## View Error Log
Command:
cat /var/log/nginx/error.log
The error log records problems or errors related to Nginx.
If the file is empty, it usually means there are no errors.

## What I Learned

- Logs help troubleshoot problems.
- `journalctl` shows service logs.
- `access.log` records successful requests.
- `error.log` records errors.