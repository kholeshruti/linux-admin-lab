#Process Management

## Objective 
Learn how to view and manage running processes in Linux.

## View Running Processes
Command:
ps aux 
- It displays all running processes.

## Find the Nginx Process
Command:
ps aux | grep nginx
- Displays only the Nginx processes.

## Monitor Processes
Command:
top
- It shows live CPU, memory, and running processes.

Press **q** to exit.

## Stop a Service
Command:
sudo systemctl stop nginx
- It stops the Nginx service.

## Start the Service Again
Command:
sudo systemctl start nginx
- It starts the Nginx service.

## What I Learned 
- Every running program is a process.
- `ps aux` lists all processes.
- `grep` filters the output.
-`top` shows processes in real time.
- `systemctl` is used to manage services like Nginx.