# File Management (Day 2)

## Commands Learned

- touch → create file
- mkdir → create directory
- rm → delete file
- rmdir → delete empty directory
- cp → copy files
- mv → move/rename files

## Practice

touch file1.txt
mkdir test-folder
cp file1.txt test-folder/
mv file1.txt file2.txt
rm file2.txt

## My Understanding

Linux allows full control over files using commands. 
File operations are fast and efficient compared to GUI.

## SRE Insight

File management is important for:
- handling logs
- managing configs
- cleaning disk space


---

# File Permissions (Day 3)

## Commands Learned

- ls -l → view permissions
- chmod → change permissions

## Permission Format

-rwxr-xr-x

- r → read
- w → write
- x → execute

## Practice

ls -l
chmod 755 file.sh
chmod +x script.sh

## My Understanding

Permissions control who can access or modify files.

## SRE Insight

Critical for:
- securing servers
- controlling access
- avoiding security risks