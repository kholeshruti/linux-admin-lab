#SSH (Secure Shell)

## Objective
Learn the basics of SSH and how to verify that the SSH service is running.

## Check SSH Version
Command:
ssh -V
Displays the installed SSH client version.

## Install SSH Server
Command:
sudo apt install openssh-server -y
Installs the OpenSSH server.

## Check SSH Service
Command:
systemctl status ssh
Shows whether the SSH service is running.

## Enable SSH
Command:
sudo systemctl enable ssh
Ensures SSH starts automatically when the system boots.

## Find the IP Address
Command:
hostname -I
Displays the system's IP address.

## Connect Using SSH
Command:
ssh localhost
This connects to the local machine using SSH.

## What I Learned

- SSH stands for Secure Shell.
- SSH allows secure remote access to Linux systems.
- `systemctl status ssh` checks whether the SSH service is running.
- `hostname -I` shows the IP address.
- `ssh <host>` is used to connect to another Linux machine.