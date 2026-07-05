#Linux File permissions

##Objective
Learn how to view and change file permissions in linux using `ls -l` and `chmod`

## Step 1: Create a File 
Command:
touch notes.txt
This creates an empty file named `notes.txt`.

## Step 2: Check File Permissions
Command:
ls -l
Example Output:
-rw-r--r-- 1 root root 0 Jul 5 19:25 notes.txt

### Meaning of the Permission
-rw-r--r--
`-` = Regular file
`rw-` = Owner can read and write
`r--` = Group can only read
`r--` = Others can only read

## Step 3: Change File Permission to 777
Command:
chmod 777 notes.txt

Check again:
ls -l

Output:
-rwxrwxrwx

### What Happened?
Owner: Read, Write, Execute
Group: Read, Write, Execute
Others: Read, Write, Execute
This gives **eveyone full access** to the file

-> This permission is generally **not recommended** because it is not secure.

## Step 4: Change File Permission to 755
Command:
chmod 755 notes.txt

Check:
ls -l

Output:
-rwxr-xr-x

### What Happened?
Owner: Read, Write, Execute
Group: Read, Execute
Others: Read, Execute
This is commonly used for executable files and directories.

## Step 5: Change File Permission to 644
Command:
chmod 644 notes.txt

Check:
ls -l

Output:
-rw-r--r--

### What Happened?
Owner: Read and Write
Group: Read only
Others: Read only
This is one of the most common permission for text files.

## What I Learned
`ls -l`: display file permissions
`chmod`: changes file permissions
File permissions control who can read, write, or execute a file.
`777`: gives full access to everyone
`755`: is commonly used for executable files and directories
`644`: is commonly used for text files