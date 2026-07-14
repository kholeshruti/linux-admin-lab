#Bash Scripting

## Objective
Learn how to create and run a simple Bash script.

## Script
#!/bin/bash
echo "Backup Started"
date
cp /root/linux-admin-lab/notes.txt /root/linux-admin-lab/backups/
echo "Backup Completed"

## Purpose
This script creates a backup of `notes.txt` by copying it to the `backups` folder.

## Commands Learned
- nano
- chmod +x
- cp
- echo
- date

## What I Learned
- How to create a Bash script.
- How to make a script executable.
- How to run a script.
- How to automate simple tasks in Linux.