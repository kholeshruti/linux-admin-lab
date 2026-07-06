#Nginx Installation and Service Management

## Objective 
Learn how to install, start, and verify the Nginx web server.

## Update Packages
Command:
sudo apt update
Updates the pacakage list.

## Install Nginx
Command:
sudo apt install nginx -y
Installs the Nginx web server.

## Check Service Status
Command:
systemctl status nginx

Result;
Nginx service is active.
Status: running.

## Test the Web Server
Command:
curl localhost

Output:
The HTML of default **Welcome to nginx!** page is displayed.
This confirms that the web server is running successfully.

## What I Learned?
- How to install software using `apt`.
- How to check service status using `systemctl`.
- How to  verify a web server using `curl localhost`.